# Git Command
## After creating new project
Note: all content with [] should be replaced

1. Git Initialization
```
git init
```

2. Adding files and folders to git for tracking Note: For specific files
```
git add [file_name]
eg: git add index.html
```
To add all *files* and ***folders*** (follow this)
```
git add .
```

3. Git verson save or `commit`
```
git commit -m "[your_commit_message]"
eg: git commit -m "auth feature done"
```

4. change main branch [optional step]
```
git branch -M [your_new_branch_name]
```

5. Add remote Url (link remote repository url)
```
git remote add origin [remote_repo_url]
```

6. Push the commited code to the remote repo
At Initial (-u: upstream)
```
git push -u origin [your_branch_name]
```
After first push
```
git push
```

7. To check the status of git (vcs)
```
git status
```

8. To update the remote repo url
```
git remote set-url origin [your_repo_url]

To verify/Display added remote url:

git remote -v 
```
