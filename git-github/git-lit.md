# Git / GitHub

#### Workflow Diagram
![git workflow diagram](/imgs/git-workflow.png)

#### git init
This command turns the folder your code is in into a local git repository.

```
$: cd project-folder
$: git init
```
#### git status
This command prints out the current state of your local repository. It will show you the files git is tracking or not, what changes have been made, and what changes are staged for commit. This is a command developers run frequently and inbetween different stages.

```
$: git status
```
#### git add .
When you are happy with a change (or changes) you need to move them to the staging area. Files in the staging are in green when you run the ```git status``` command. All staged changes will be included in your next commit.

```
$: git add .
```

#### git commit -m
Like mentioned earlier, a commit a snapshot of the code at that time. This command takes the staged changes and makes that snapshot. The command also takes a message that describes the changes being committed.

```
$: git commit -m "useful message describing the change"
```
#### create a remote and link to remote repository
Instructions for how to do this can be found [here](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/). Github will give us some additional commands to link the local with the remote repository. For now copy and paste these to set up tracking.

#### git push
Now the changes are in the local repository, it is time to put them on the remote repository to share the code you wrote (with a friend!). This command will do that!

```
$: git push
```

## More Resources
- [git documentation](https://git-scm.com/doc)
- [Github Cheat Sheet](https://services.github.com/kit/downloads/github-git-cheat-sheet.pdf)
- [Visual Git Cheat Sheet](http://ndpsoftware.com/git-cheatsheet.html)
