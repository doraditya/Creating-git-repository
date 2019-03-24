# Resolving error: ! [rejected\] master -> master (fetch first)

1. We have to fetch first before pushing any new changes. 

2. ```
   git fetch origin master
   git merge origin master
   ```

   If you get an error: rejected to push . Try the following (this creates a temporary branch does the magic and removes the branch)

   ```
   git fetch origin master:temp-branch
   git rebase temp-branch
   git push origin HEAD:master
   git branch -D temp-branch
   ```

3. Try this git command. **This overrides git push restriction.**

   ```
   git push origin master --force
   ```

   or

   ```
   git push origin master -f
   ```
