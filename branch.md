## Branches let you work on features isolated from each other. You can think of a branch as a copy of the entire project, but changes don't affect what the other programmers are doing.

The master branch is the default branch. Git lets you switch between branches and you can mix branches together (called merging).

Consider the image below, where:

- master branch is the default branch

- a branch named "your work" is created

- a branch named "someone else's work" is created

The two people work on the branches individually. And changes are merged into the master project.



Commands:

To create a branch named feature_x

```git checkout -b feature_x```



To switch branch to the master branch

```git checkout master```



To delete a branch

```git branch -d feature_x```



To put your branch online

```git push origin <branch>```



To merge a branch

```git merge <branch>```
