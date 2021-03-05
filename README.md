> # **M300**  - Cheat sheet

**Author**: Juan Cardoso

---

This cheat sheet will prove itself useful to remember the different commands I will have to use along the M300

# Commands

## Basics

- Git Innit < directory >
  - Create empty Git repo in specified directory. Run with no arguments to initialize the current directory as a git repository.
- Git clone < repo >
  - Clone repo located at < repo > onto local machine. Original repo can be located on the local filesystem or on a remote machine via HTTP or SSH.
- git config user.name < name >
  - Define author name to be used for all commits in current repo. Devs commonly use --global flag to set config options for current user.
- git add < directory >
  - Stage all changes in < directory > for the next commit. Replace < directory > with a < file > to change a specific file.
- git commit -m"< message >"
  - Commit the staged snapshot, but instead of launching a text editor, use < message > as the commit message.
- git status
  - List which files are staged, unstaged, and untracked
- git log
  - Display the entire commit history using the default format. For customization see additional options.
- git diff
  - Show unstaged changes between your index and working directory

## Aditional commands

- git log -< limit >
  - Limit number of commits by < limit > E.g. ”git log -5” will limit to 5 commits
- git log --oneline
  - Condense each commit to a single line.
- git log -p
  - Display the full diff of each commit.
- git log --stat    
  - Include which files were altered and the relative number of lines that were added or deleted from each of them.
- git log --author=”< pattern >”
  - Search for commits by a particular author
- git log --grep=”< pattern >”
  - Search for commits with a commit message that matches < pattern >.
- git log < since >..< until >
  - Show commits that occur between < since > and < until >. Args can be a commit ID, branch name, HEAD, or any other kind of revision reference.

## **This file is still a work in progress, more will be added in the future** - V1
  
