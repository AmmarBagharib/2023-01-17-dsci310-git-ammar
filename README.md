# 2023-01-17: DSCI 310 Git Demo
Intro Git Demo

- `git clone <URL>`: clones the repo from github to local computer
- `git status`: tells you what's going on in the repo
- `git add <FILE>`: add the <FILE> to the staging area
-  `git commit`: create the commit AKA snapshot
- `git commmit - m "MESSAGE"`: create the git commit message directly in terminal instead of opening code editor
- `git push <where> <what>`: take local commits on `<what>` and send them into `<where>`
    - e.g., `git push origin main`
- `git pull <where> <what>`: take remote commits on `<what>` and pull from `<where>`
    - e.g., `git pull origin main`

- `git add -f <FILE>`: force add a file, even if it is within a directory that you've specified in your .gitignore file

## branches
- `git branch`: creates a git branch named <branch> wherever you are (`HEAD`)
- `git switch <branch name>`: switch to that branch
    - `git checkout <branch name>`: old method of switching to branch
