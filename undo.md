Sometimes people make mistakes. If you made a mistake but didn't push it to the online git repository yet, you can undo with:

```git commit --amend```
That may be like this:

```git commit -m 'Initial commit'```
```git add forgotten_file```
```git commit --amend```
If you already put your mistakes online in the remote git repository, you can roll back using the next video (you will lose all changes)
