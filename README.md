# Intro to GIT
- Helps us to track changes
- Helps us to collaborate on the same project through branches
- Helps us to push our project(codes) to a cloud repository (github, gitlab, gitbucket)

## Using git
- `git init` : initializes a git repository
- `git add`: adds all your changes to track area
e.g git add . : this will stage to track all your folder files
- git commit -m "whatever your message is": This will save a version of your changes
- git remote add origin url: You do not need to know this because github will always provide this instruction. But this is basically to just connect your local repo to the cloud repo
- git push: Will push your local changes to the cloud repo
- git log: Will print all your commits
- git status: prints the status

## Setup git before using
- git config --global user.name "John Niyontwali"
- git config --global user.email nijohn@gmail.com
**NB** : This is only done once