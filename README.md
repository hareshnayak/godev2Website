# newWebsite
website 


to use git bash - https://git-scm.org/

Create a new folder
commands

```
git init  //.git file is created
//files edit/create
git add <filename>   // only one file is added
git add .           // all the files in the folder are added
git commit -m "Commit done"
git remote add origin master <link>      // https://github.com/HimeshNayak/godev2Website.git to be done only first time
git push -u origin master
```

### OR

1. to get the gtihub repo on your local git :-
    - ```$ git clone <ssh link>```
2. to check for all the files that are tracked/untracked and changes that are to be commited:-
    - ```$ git status```
3. to add files to the staging area 
   - for some perticular files -> ```$ git add <filename>  ```
   - for some all the files -> ```$ git add .  ``` or ```$ git add -A```
4. to commit the changes
   - ```$ git commit -m"meaningfull commit message"```
5. to push the changes to the remote repository (the one on github)
   - ```$ git push```
6. to get any changes from the remote repository
   - ```$ git fetch```
7. to **mrege** the changes fetched from the remote repo
   - ```$ git mrege```

8. if you want to do both *step 6* and *step 7* in one go ( that is **fetch + merge** )
   - ```$ git pull```
