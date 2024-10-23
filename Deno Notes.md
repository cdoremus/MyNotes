## Running system commands
To migrate from `Deno.run` to `Deno.Command` and use `readLines` with the new API, you'll need to adjust your code to work with the `Deno.Command` class and its method for spawning a subprocess. The `Deno.Command` class provides a `spawn` method that returns a `Deno.Process` object, which you can use to interact with the subprocess's input and output streams.

Here's how you can use `Deno.Command` to spawn a long-running subprocess and read lines from its standard error stream:

```ts
import { readLines } from "https://deno.land/std/io/mod.ts";

const command = new Deno.Command("your-command", {
  args: ["your", "args", "here"],
  stderr: "piped", // Ensure that stderr is piped
});

const process = command.spawn();

// Assuming you want to read from stderr
for await (const line of readLines(process.stderr)) {
  console.log(line);
  // ... your logic here
}

// Continue using the subprocess
// ...
```

In this example, replace `"your-command"` and `["your", "args", "here"]` with the actual command and arguments you want to run. The `readLines` function is used to asynchronously iterate over the lines of the subprocess's standard error stream.

Remember that since the subprocess is long-running and doesn't exit on its own, you'll need to manage the lifecycle of the subprocess yourself. This includes potentially killing the subprocess when it's no longer needed or handling any cleanup logic.

The documentation mentions that if you want to communicate with a started subprocess, you must use the "piped" option for `stdin`, `stdout`, and `stderr` as needed. This allows you to read from or write to the subprocess's streams.

If you encounter any issues with the `readLines` function or the `Deno.Command` class, please make sure you are using the latest version of Deno

---