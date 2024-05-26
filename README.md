# My list of most used git commands. 
Created as a checklist whenever the commands are forgotten 

### Often used:
<ol>
  <li>Creating JSON package:</li>

   ```HTML
  npm init
  ```

  <li>Stage changes:</li>
  
  ```HTML
  git add . 
  ```
  
  <li>commit changes (with message):</li>

  ```HTML
  git commit -m "<"message">"
  ```
</ol>


### GIT branches:
<ol>
  <li>Create branch:</li>

   ```HTML
  git branch <"branch name">
  ```

  <li>Change branch:</li>

   ```HTML
  git checkout <branch name">
  ```

  <li>Create new branch and move to that branch:</li>

   ```HTML
  git checkout -b <branch name">
  ```

  <li>View all branches (local and remote):</li>

   ```HTML
  git branch -a
  ```

  <li>Delete local branch</li>
  
  ```HTML
  git branch -d <branch name"> 
  ```
  
  <li>Delete branch(es) that's already deleted on Github, but still appears as remote in editor(repo)</li>

  ```HTML
  git fetch --prune
  ```
</ol>
