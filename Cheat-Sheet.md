# Commands to create new repository for any project

1. Step 1: Go to project path from cmd prompt

2. Remove previous git repositories by the following cmd

   ```
   C:\"Project_Path"> rd .git /S/Q 	
   ```

3. Initialize a new git repository to our local environment

4. ```
   C:\"Project_Path"> git init
   ```

   Adding all the files

   ```
   C:\"Project_Path"> git add .
   ```

5. Commit the changes

6. ```
   C:\"Project_Path"> git commit -m "Initial commit"
   ```

   Create a new empty repository in git

7. Follow this command to add GitHub setup in desktop

```
   C:\"Project_Path"> "repository https link from github"
```

8. Push all the changes
9. ```
   git push -u origin master
   ```
10. If not logged in already, a popup would show, enter your credentials.
11. Refresh the GitHub page to view your project file s in repo
