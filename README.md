# Notes on How to Use Git and Interact with Github

## Notes were derived from the Codacademy module on Git


### Git projects have three parts:

1.  A working directory: where you will be doing al lteh work: creating, editing, and organzing files.

2.  A staging area:  lists changes you make to the working directory.

3.  A repository:  Git permanently stores those changes as different versions of the project.

---
```
$ git init
```
...Initializes the project and sets up the tools to begin tracking changes on a project.
---
```
$ git status
```
... Checks and reports the status of changes.
... Files in *Red* are untracked and git 
---
```
$ git add <filename>
```
...To start tracking changes, files need to be first added to the staging area.
...Use *git add* to add to the staging area.
...Text in green is in the staging area.
---