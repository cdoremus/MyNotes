
Deno Blog Ideas 

# JSR
- browser support
  - tool to create import maps: https://github.com/denoland/deno/issues/22439#issuecomment-1950970619
- URL imports are undecided (Luca on 2/19/24)
- GitHub action integration
- Convert deno.land/x to jsr by @ry
Very early conversion tool from deno.land/x modules to jsr modules: https://jsr.io/@deno/x-to-jsr

please report bugs when you hit them


# Upgrading a node project to Demo
- see https://youtu.be/eCbiywoDORw?si=IdSWeqPNME7PaAlo
- Use npm: prefix in import map
- caveat
  - web framework doesn't work mostly


# UI Libraries and Fresh
## shadcn-ui
- Netzo
https://netzo.io/docs/framework/components
source
https://github.com/netzo/netzo/blob/main/lib/components/ui
- also https://github.com/nikogoli/testing-shadcn-ui-in-fresh
  - see https://discord.com/channels/684898665143206084/991511118524715139/1194019321568039032

## Daisy UI
- see: https://discord.com/channels/684898665143206084/991511118524715139/1194005323925692417


# Hono with Deno

# Kitson Kelly KV Toolbox
https://github.com/kitsonk/kv-toolbox

# Using Jupyter notebooks for code explorations outside of data science 

# Server communication via Websocket, SSE & Broadcast Channel 
- websocket: https://showcase-chat.deno.dev/

# Using esbuild with Deno

# fresh-testing-library

# esm.sh

# Deno.serve()

# Using Deno on Docker

# DYO Authentication/Authorization with KV
- see Lucia
  - https://lucia-auth.com/
  - Deno adapter: https://deno.land/x/lucia_kv@0.1.3
- see onyx: https://github.com/oslabs-beta/onyx
- see auth_middleware: https://github.com/httpland/auth-middleware
*Concepts to cover*
- SessionId stored in context state 
- Remember Me
- Authorization Groups with URLs
- username, password, email
- password hashing
see https://examples.deno.land/hashing
- redirect URL
- password reset 

# e-commerce with Stripe and Shopify 

# deno-tauri
https://github.com/marc2332/tauri-deno-starter
Astrodon: https://github.com/astrodon/astrodon

#Using Lit with SSR


#SaasKit - how to use it


# Using BroadcastChannel to notify all Deno Deploy instances (or WebRTC)
https://github.com/nhrones/FreshDiceRTC

# Creating a Deno CLI app


# Deno SASS Compilation 


# Deno Security 

Avoiding the traps of Deno's security system

- the -A or --allow-all security flag should not be used in production
  - many Deno libraries do not point that out in the documentation

- most security flags allow you to constrain the security access in a comma-separated list
  - go through each one to show how it's used 

- adding security flags when using the MPM prefix if difficult unless you carefully examine the source code of the dependencies of an NPM library




What are 10 ideas for a blog article on the JavaScript runtime Deno?

1. "Getting Started with Deno: A Beginner's Guide to the JavaScript Runtime"
2. "Deno vs Node.js: Which is the Better JavaScript Runtime for Your Project?"
3. "Secure Coding with Deno: Best Practices for Writing Safe JavaScript Applications"
4. "How to Use Deno's Built-in Testing Framework for Unit Testing Your Code"
5. "Deno for Web Development: Building Server-Side Applications with JavaScript"
6. "Exploring Deno's Standard Library: A Comprehensive Guide to Built-in Modules"
7. "Migrating from Node.js to Deno: Tips and Tricks for a Smooth Transition"
8. "Debugging JavaScript Applications with Deno: A Step-by-Step Guide"
9. "Deno for Machine Learning: Building AI Applications with JavaScript"
10. "Deploying Deno Applications: Best Practices for Hosting and Scaling Your Code"


Sure, here are 5 ideas for advanced developers who are already familiar with Deno:

"Creating Custom Deno Modules: How to Build and Share Your Own Libraries"
"Advanced TypeScript Features in Deno: Using Generics, Decorators, and More"
"Optimizing Deno Performance: Tips and Tricks for Faster JavaScript Applications"
"Deno and Docker: Building Lightweight and Portable Containers for Your Applications"
"Managing Dependencies in Deno: Strategies for Versioning, Locking, and Resolving Conflicts"


Deno Blog Ideas.


cdoremus@gmail.com
What are 10 ideas for a blog article on the JavaScript runtime Deno?


"Getting Started with Deno: A Beginner's Guide to the JavaScript Runtime"
"Deno vs Node.js: Which is the Better JavaScript Runtime for Your Project?"
"Secure Coding with Deno: Best Practices for Writing Safe JavaScript Applications"
"How to Use Deno's Built-in Testing Framework for Unit Testing Your Code"
"Deno for Web Development: Building Server-Side Applications with JavaScript"
"Exploring Deno's Standard Library: A Comprehensive Guide to Built-in Modules"
"Migrating from Node.js to Deno: Tips and Tricks for a Smooth Transition"
"Debugging JavaScript Applications with Deno: A Step-by-Step Guide"
"Deno for Machine Learning: Building AI Applications with JavaScript"
"Deploying Deno Applications: Best Practices for Hosting and Scaling Your Code"



cdoremus@gmail.com
How about 5 ideas for advanced developers that already know Deno

Sure, here are 5 ideas for advanced developers who are already familiar with Deno:

"Creating Custom Deno Modules: How to Build and Share Your Own Libraries"
"Advanced TypeScript Features in Deno: Using Generics, Decorators, and More"
"Optimizing Deno Performance: Tips and Tricks for Faster JavaScript Applications"
"Deno and Docker: Building Lightweight and Portable Containers for Your Applications"
"Managing Dependencies in Deno: Strategies for Versioning, Locking, and Resolving Conflicts"



cdoremus@gmail.com
How about five ideas for a blog article on Deno web development?

Sure! Here are 5 ideas for a blog article on Deno web development:

"Building a RESTful API with Deno: A Step-by-Step Guide": This article could cover the basics of building a RESTful API with Deno, including how to use Deno's built-in web server and how to handle HTTP requests and responses.

"Real-time Web Applications with Deno and WebSockets": This article could cover how to use Deno and WebSockets to build real-time web applications, including chat applications, real-time data visualization, and more.

"Building a Full-Stack Deno Application with React and MongoDB": This article could cover how to build a full-stack application with Deno, including how to use Deno as the backend server, how to use React for the frontend, and how to connect to a MongoDB database.

"Building Serverless Web Applications with Deno and AWS Lambda": This article could cover how to use Deno with AWS Lambda to build serverless web applications, including how to set up a Lambda function, how to use Deno modules with Lambda, and how to deploy your application.

"Testing Deno Web Applications with Jest": This article could cover how to use Jest to test your Deno web applications, including how to set up Jest with Deno, how to write unit tests for your code, and how to run your tests as part of your build process.



Deno Blog Ideas.


cdoremus@gmail.com
What are 10 ideas for a blog article on the JavaScript runtime Deno?


"Getting Started with Deno: A Beginner's Guide to the JavaScript Runtime"
"Deno vs Node.js: Which is the Better JavaScript Runtime for Your Project?"
"Secure Coding with Deno: Best Practices for Writing Safe JavaScript Applications"
"How to Use Deno's Built-in Testing Framework for Unit Testing Your Code"
"Deno for Web Development: Building Server-Side Applications with JavaScript"
"Exploring Deno's Standard Library: A Comprehensive Guide to Built-in Modules"
"Migrating from Node.js to Deno: Tips and Tricks for a Smooth Transition"
"Debugging JavaScript Applications with Deno: A Step-by-Step Guide"
"Deno for Machine Learning: Building AI Applications with JavaScript"
"Deploying Deno Applications: Best Practices for Hosting and Scaling Your Code"



cdoremus@gmail.com
How about 5 ideas for advanced developers that already know Deno

Sure, here are 5 ideas for advanced developers who are already familiar with Deno:

"Creating Custom Deno Modules: How to Build and Share Your Own Libraries"
"Advanced TypeScript Features in Deno: Using Generics, Decorators, and More"
"Optimizing Deno Performance: Tips and Tricks for Faster JavaScript Applications"
"Deno and Docker: Building Lightweight and Portable Containers for Your Applications"
"Managing Dependencies in Deno: Strategies for Versioning, Locking, and Resolving Conflicts"



cdoremus@gmail.com
How about five ideas for a blog article on Deno web development?

Sure! Here are 5 ideas for a blog article on Deno web development:

"Building a RESTful API with Deno: A Step-by-Step Guide": This article could cover the basics of building a RESTful API with Deno, including how to use Deno's built-in web server and how to handle HTTP requests and responses.

"Real-time Web Applications with Deno and WebSockets": This article could cover how to use Deno and WebSockets to build real-time web applications, including chat applications, real-time data visualization, and more.

"Building a Full-Stack Deno Application with React and MongoDB": This article could cover how to build a full-stack application with Deno, including how to use Deno as the backend server, how to use React for the frontend, and how to connect to a MongoDB database.

"Building Serverless Web Applications with Deno and AWS Lambda": This article could cover how to use Deno with AWS Lambda to build serverless web applications, including how to set up a Lambda function, how to use Deno modules with Lambda, and how to deploy your application.

"Testing Deno Web Applications with Jest": This article could cover how to use Jest to test your Deno web applications, including how to set up Jest with Deno, how to write unit tests for your code, and how to run your tests as part of your build process.




cdoremus@gmail.com
Ok. How about 5 more Deno web development articles?

Sure, here are 5 more Deno web development article ideas:

"Secure Web Development with Deno: Best Practices for Avoiding Common Web Vulnerabilities": This article could cover how to write secure web applications with Deno, including how to prevent common web vulnerabilities such as cross-site scripting (XSS) and SQL injection.

"Building Progressive Web Apps (PWAs) with Deno": This article could cover how to use Deno to build progressive web apps, including how to implement service workers, offline caching, and other PWA features.

"Building a GraphQL API with Deno and Oak": This article could cover how to use Deno with the Oak middleware to build a GraphQL API, including how to define your GraphQL schema, how to handle GraphQL queries and mutations, and how to use Apollo Server with Deno.

"Scaling Deno Web Applications with Kubernetes": This article could cover how to use Kubernetes to scale Deno web applications, including how to containerize your Deno application, how to deploy it to a Kubernetes cluster, and how to set up horizontal scaling.

"Building Serverless Functions with Deno and Google Cloud Functions": This article could cover how to use Deno with Google Cloud Functions to build serverless functions, including how to write functions with Deno, how to deploy them to Google Cloud Functions, and how to trigger them with events.



Deno Blog Ideas.


cdoremus@gmail.com
What are 10 ideas for a blog article on the JavaScript runtime Deno?


"Getting Started with Deno: A Beginner's Guide to the JavaScript Runtime"
"Deno vs Node.js: Which is the Better JavaScript Runtime for Your Project?"
"Secure Coding with Deno: Best Practices for Writing Safe JavaScript Applications"
"How to Use Deno's Built-in Testing Framework for Unit Testing Your Code"
"Deno for Web Development: Building Server-Side Applications with JavaScript"
"Exploring Deno's Standard Library: A Comprehensive Guide to Built-in Modules"
"Migrating from Node.js to Deno: Tips and Tricks for a Smooth Transition"
"Debugging JavaScript Applications with Deno: A Step-by-Step Guide"
"Deno for Machine Learning: Building AI Applications with JavaScript"
"Deploying Deno Applications: Best Practices for Hosting and Scaling Your Code"



cdoremus@gmail.com
How about 5 ideas for advanced developers that already know Deno

Sure, here are 5 ideas for advanced developers who are already familiar with Deno:

"Creating Custom Deno Modules: How to Build and Share Your Own Libraries"
"Advanced TypeScript Features in Deno: Using Generics, Decorators, and More"
"Optimizing Deno Performance: Tips and Tricks for Faster JavaScript Applications"
"Deno and Docker: Building Lightweight and Portable Containers for Your Applications"
"Managing Dependencies in Deno: Strategies for Versioning, Locking, and Resolving Conflicts"



cdoremus@gmail.com
How about five ideas for a blog article on Deno web development?

Sure! Here are 5 ideas for a blog article on Deno web development:

"Building a RESTful API with Deno: A Step-by-Step Guide": This article could cover the basics of building a RESTful API with Deno, including how to use Deno's built-in web server and how to handle HTTP requests and responses.

"Real-time Web Applications with Deno and WebSockets": This article could cover how to use Deno and WebSockets to build real-time web applications, including chat applications, real-time data visualization, and more.

"Building a Full-Stack Deno Application with React and MongoDB": This article could cover how to build a full-stack application with Deno, including how to use Deno as the backend server, how to use React for the frontend, and how to connect to a MongoDB database.

"Building Serverless Web Applications with Deno and AWS Lambda": This article could cover how to use Deno with AWS Lambda to build serverless web applications, including how to set up a Lambda function, how to use Deno modules with Lambda, and how to deploy your application.

"Testing Deno Web Applications with Jest": This article could cover how to use Jest to test your Deno web applications, including how to set up Jest with Deno, how to write unit tests for your code, and how to run your tests as part of your build process.




cdoremus@gmail.com
Ok. How about 5 more Deno web development articles?

Sure, here are 5 more Deno web development article ideas:

"Secure Web Development with Deno: Best Practices for Avoiding Common Web Vulnerabilities": This article could cover how to write secure web applications with Deno, including how to prevent common web vulnerabilities such as cross-site scripting (XSS) and SQL injection.

"Building Progressive Web Apps (PWAs) with Deno": This article could cover how to use Deno to build progressive web apps, including how to implement service workers, offline caching, and other PWA features.

"Building a GraphQL API with Deno and Oak": This article could cover how to use Deno with the Oak middleware to build a GraphQL API, including how to define your GraphQL schema, how to handle GraphQL queries and mutations, and how to use Apollo Server with Deno.

"Scaling Deno Web Applications with Kubernetes": This article could cover how to use Kubernetes to scale Deno web applications, including how to containerize your Deno application, how to deploy it to a Kubernetes cluster, and how to set up horizontal scaling.

"Building Serverless Functions with Deno and Google Cloud Functions": This article could cover how to use Deno with Google Cloud Functions to build serverless functions, including how to write functions with Deno, how to deploy them to Google Cloud Functions, and how to trigger them with events.




cdoremus@gmail.com
How about 5 articles that focus on the Deno Fresh web framework?

Sure, here are 5 article ideas that focus on the Deno Fresh web framework:

"Getting Started with Deno Fresh: A Beginner's Guide to Building Web Applications": This article could cover the basics of Deno Fresh, including how to install it, how to create a new project, and how to build a simple web application.

"Working with Templates in Deno Fresh: How to Build Dynamic Web Pages": This article could cover how to use templates in Deno Fresh to build dynamic web pages, including how to define templates, how to pass data to templates, and how to use template inheritance.

"Building APIs with Deno Fresh: How to Create a RESTful API": This article could cover how to use Deno Fresh to build a RESTful API, including how to define routes, how to handle HTTP requests and responses, and how to use middleware to add functionality to your API.

"Using WebSockets with Deno Fresh: Building Real-Time Web Applications": This article could cover how to use Deno Fresh and WebSockets to build real-time web applications, including how to define WebSocket routes, how to handle WebSocket messages, and how to use WebSockets with templates.

"Deploying Deno Fresh Applications with Docker and Kubernetes": This article could cover how to use Docker and Kubernetes to deploy Deno Fresh applications, including how to containerize your Deno Fresh application, how to deploy it to a Kubernetes cluster, and how to set up scaling and load balancing.


