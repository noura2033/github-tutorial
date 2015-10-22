# GitHub Tutorial

_by Nour Abid_

---
## Git vs. GitHub
The difference between **Git** and **GitHub** is that Git is a version control of the code which takes   
vitrul snapshots. This means that when you edit a chunk of code, you   
  git commit it to save and push it to send to GitHub. This doesn't require GitHub though. Now GitHub on the other  
  hand requires Git. GitHub store code in the cloud which means you can perceptibly track your changes.
      


---
## Initial Setup
**Initial Setup** is the the quick, one-time setup you do when first starting your github account. 



Go to [GitHub](github.com)  

1. Go to profile
2. G to settings
3. Go to SSH keys and click on it
4. Give it a title
5. Paste key
6. Open IDE  

Now start coding on your command line  
```ssh -T git@github.com``` , type 'yes'  

```git config```  

Make a directory  
```mkdir first-repo```  
```cd first-repo```    
``` pwd ```  

Now you're home  


``` git init ```  
``` git config --global user.name 'First Name Last Name' ```    
``` git config --global user.name 'First Name Last Name' ```









---
## Repository Setup  


 ``` pwd ```  to see where you are  
 Master shown which means you are using Git   
 ```git add READMME.md```  
 ```git commit -m "Message"```  
 
 Go to [GitHub](github.com)  
 1. Top right go to *New Repository*  
 2. Add a name  
 3. Create the Repository  
 4. Click *SSH*  
 5. Copy the ```git push```  
 
 From now on you can edit your work but remember to  
- **Add** and **Commit**   
- ```git push```  


---

## Workflow & Commands
* Check which files need to be **saved **and **comitted **
 * ```git status```
 
* **Add files** to stage to get committed later
 * ```git add FILENAME```   
  *   ```git add .``` to add all the files that haven't been added yet 
  *   when you add a file, you're getting ready to commit it so it can be sent it GitHub
 
 _Hint_: Multiple files can be added by putting a space between the file names  

* To **commit** a file  
 * ```git commit -m 'message' ```  
   * -m means that the next text will be your message
   * your message should be explaining the changes made in the commit 
   * Committing is taking a virtual snapshot and being able to view it later  
   
* To **send** your code and commits to GitHub  
  * ```git push```      
  
---
##**Error Handling**  
If you ```git init``` in the wrong repository:  
To remove a local/remote repository,    
all you have to do is ```rm -rf .git ```   

---  

##**Collaboration**  
_Fork_ and _Cloning_  

Forking someone else's repo  
-You maintain a _remote_ copy of _their remote_ repo  
-Then _clone_ your _remote_ to your _local_ 
-You have permission to _push_ to your _remote_  

Cloning someone else's repo
-You maintain a _local copy_ of _their remote_ repo  
-You **DON'T** have permission to _push_ to their _remote_ 
  



