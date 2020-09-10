# GIt commands cheat-sheet: the most useful 
## 1.Navigate to your git project folder

Use `cd` to move between folders. E.g:
```
cd workspace
cd bdl02_FlorinFiath_git_cheatsheet

## 2.Check the status of the project

- `git status`

    With `git status` I can see some changes have happened and if some files are ready to be committed .
    It gives me an overview of the project at the specific moment in time.
- `git log`
- `git diff`

## 3. Initialize a git project 
If any `git` command that we run gives the following output:
> fatal: not a git repository (or any of the parent directories): .git
it means that we are not inside a git project.
In this case we can:
1. Make sure that we are inside the right folder (and navigate to it, if necessary)
2. Initialize a git project
To initialize git run `git init`. This command creates an empty Git repository.From now on , we can make changes to our files and permanently save those changes.