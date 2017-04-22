## Shortcuts  

**Create bare remote repo**  
`ssh user@host git init --bare /path/to/repo.git`  

**List local branches **  
`git branch`  

**Checkout a local branch**  
`git checkout branch_name`  

**Create new branch**  
`git checkout -b myNewBranch branchingFrom`

**Push branch to remote**   
`git push -u origin branch_name`  

**D elete local branch**  
`git branch -d branch_name`  

**Delete remote branch**  
`git push origin --delete branch_name`  

**Diff two branches**  
`git diff master..test-dev`  

**Rebase from remote**  
```
git fetch origin            # Updates origin/master  
git rebase origin/master    # Rebases current branch onto origin/master`
```

<!-- ***************************************************************** -->

## Other info

**Global git ignore file**    
located in `~/.gitignore_global`

<!-- ***************************************************************** -->

## Links

 - [Setting up a new remote git repository](https://gist.github.com/toolmantim/569530)

- [Add existing project from CLI](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/)
