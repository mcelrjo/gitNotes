# Notes on How to Use Git and Interact with Github

## Notes were derived from the Codacademy module on Git


### Git projects have three parts:

1.  A working directory: where you will be doing al lteh work: creating, editing, and organzing files.

2.  A staging area:  lists changes you make to the working directory.

3.  A repository:  Git permanently stores those changes as different versions of the project.


```
$ git init
```
   Initializes the project and sets up the tools to begin tracking changes on a project.

```
$ git status
```
   Checks and reports the status of changes.
   Files in *Red* are untracked and git 


```
$ git add <filename>
```
>>To start tracking changes, files need to be first added to the staging area.
>>Use *git add* to add to the staging area.
>>Text in green is in the staging area.

```
$ git diff <filename>
```
	Checks the difference between the working directory and the staging area.

```
$ git commit -m "enter your message here"
```
	The last step in the Git workflow
	Commits permanently.  Stores changes from the staging area in side repository.
	Standard conventions of a commit message:
		1.  Must be in quotation marks.
		2.  Written in present tense.
		3.  50 characters or less

```
$ git log
```
	Lists commits to repository chronologically.

###In Git, the commit you are on is *HEAD* known as the head commit.  In most cases the most recently made commit is the head commit.

```
$ git show HEAD
```
	Shows you the head commit.
	Output shows everthing the git log command displays for the HEAD commit, plus all the files changes that were committed. 

