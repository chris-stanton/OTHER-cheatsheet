
# Working with git individually

##### `` git init ``
This command turns the folder your code is in into a local git repository.


##### `` git status ``
This command prints out the current state of your local repository. It will show you the files git is tracking or not, what changes have been made, and what changes are staged for commit. This is a command developers run frequently and inbetween different stages.


##### `` git add . ``
When you are happy with a change (or changes) you need to move them to the staging area. Files in the staging are in green when you run the ```git status``` command. All staged changes will be included in your next commit.


##### `` git commit -m "useful message describing the change" ``
Like mentioned earlier, a commit a snapshot of the code at that time. This command takes the staged changes and makes that snapshot. The command also takes a message that describes the changes being committed.


##### create a remote and link to remote repository
Instructions for how to do this can be found [here](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/). Github will give us some additional commands to link the local with the remote repository. For now copy and paste these to set up tracking.


##### ``` git push ```
Now the changes are in the local repository, it is time to put them on the remote repository to share the code you wrote (with a friend!). This command will do that!





## Working with git in groups

#### Create develop and feature branches
1. pull master ``` git pull ```
2. create develop branch ``` git checkout -b develop ```
3. create a feature branch ``` git checkout -b feature-<branch name>```
4. make feature commits on feature branch

#### merge feature to another branch
1. update branch that you will be merging content into ``` git pull ```
2. merge feature branch into current branch ``` git merge --no-ff <branch name> ```
3. Resolve any conflicts and commit the merge
4. if no conflicts ``` :wq ``` exits in terminal
5. push master to the remote as soon as possible ``` git push ```
6. copy and paste the set path given in the terminal.
