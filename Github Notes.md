
# Github Commands for the MyNotes Repo

`cd storage/downloads/Obsidian/MyNotes`
`git add .`
`git commit . -m ""`

  Use cdoremus as the username and the MyNotes access token for the pwd after runnings a push (or any operation on a remote repo)

commit-notes.sh

`#!/bin/bash`
`if [ $1 != ""]; then
  `cd ~/storage/downloads/Obsidian/MyNotes`
  `git commit . -am "$1"`
`else`
  `echo 'Include commit message'`
`fi`

sh commit-notes.sh 'Commit Message'

`git push origin main`






