# Where the repo is called "NODE-WEB" and the branch "feature-to-be-added":
 
### Downloads only the 'feature-to-be-added' branch from the remote repository
``` 
git clone --branch feature-to-be-added --single-branch <remote-repo-url> NODE-WEB
```
 
### The last part of the previous command downloaded the files to a new directory called NODE-WEB
``` 
cd NODE-WEB
```
 
### Check you are on the 'feature-to-be-added' branch
```
git checkout feature-to-be-added
```
 
### To commit and push changes to the 'feature-to-be-added' branch
``` 
git add .
```
```  
git commit -m "descr" -m "longer description"
```
``` 
git push origin feature-to-be-added
``` 

### To force pull (will overwrite your local repo in case of emergency)
```
git fetch origin feature-to-be-added
```
``` 
git reset --hard origin/feature-to-be-added
```
