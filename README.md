# Git lesson

This lesson covers the basics of git for version control.

To make a commit ("version" or "checkpoint") of your files, follow this procedure:

1. Make changes to your project 
2. When you have your chagnes, tell `git` you are ready with `git add FILENAME`
3. Create a checkpoint of your file with `git commit -m "COMMENTS"` 

## Adding features
Features shoudl be developed on branches
To create branch use:

`git switch -c NEW_BRANCH_NAME`

To switch to an existing one, don't include `-c`