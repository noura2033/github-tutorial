# GitHub Tutorial

_by Nour Abid_

---
## Git vs. GitHub
The difference between Git and GitHub is that Git is a version control of the code which takes   
vitrul snapshots. This means that when you edit a chunk of code, you   
  git commit it to save and push it to send to GitHub. This doesn't require GitHub though. Now GitHub on the other  
  hand requires Git. GitHub store code in the cloud which means you can perceptibly track your changes.
      


---
## Initial Setup
Initial Setup is the the quick, one-time setup you do when first starting your github account. Starting your github by   
doing git config (user.name & user.email)is the initial setup.   
```
git config [
user.name
user.email
]
```
This tells Git the username and email associated with  
your Git commits. Next step is to connect with SSH whenever making a repository. To use SSH, you need to get the SSH keys from GitHub. This is to push or pull from GitHub. 





---
## Repository Setup

Steps:  

 1. Make a new repo from the top right   
 2. Select the account to create the repo 
 3. Give your repo a name (Make it make sense!) 
 4. Choose wether you want your repo to be publically viewable or private 
 5. Edit your repo! You're set

Whenever making a new repository in Git, you have to add a few commands:
```
git init git add
```
```
git commit
```

---

## Workflow & Commands
* Check which files need to be saved and comitted 
 * ```git status```
 
* Add files to stage to get committed later
 * ```git add FILENAME```   
  *   ```git add .``` to add all the files that haven't been added yet 
 
 _Hint_: Multiple files can be added by putting a space between the file names  

* To commit a file  
 * ```git commit -m 'message' ```  
   * -m means that the next text will be your message
   * your message should be explaining the changes made in the commit 
   * Committing is taking a virtual snapshot and being able to view it later  
   
* To send you code and commits to GitHub  
 * ```git push```  



