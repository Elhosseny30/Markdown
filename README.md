# Explain how make Local repository

1. **Intialize** it by using command `git init`

2. If we have files we should tracked it by using `git add <file_name>`

    > if we want tracked all files once we use **`git add . `**
3. After that any changes in files will tracked to see there is any changes or not using `git status`

4. After any changes we should make two thing 
    - First add it convert from WT to stagging area by using `git add . `

    - second commit it and convert from stagging area to history by using `git commit -m "description of commit `   

    - ***NOTE*** 
        - We can add and commit changes by using one command it is ` git commit -am "description of commit`

----
## To push changes to repo on GIT-HUB

- Make a remote repo on **GIT-HUB**
- We should link between local repo and remote repo by using command that is 
    - `git remote add origin <URL>`
- change name of branch in local repo from **master** to **main** to be like the remote repo if you don't that is no errors appear. 
    - `git branch -m main`
- After that should the content in local repo to remote repo on **GIT-HUB** 
    - `git push origin main `

----
# To sum up 
| Command | Explain |
| --- | --- |
| git init | Make local repo |
| git status | reflect the changes |
| git add . | To Tracked All files |
| git commit -m "Description of commit | To commit the changes |
| git log | to see the commits | 
| git remote add **`URL`** | to connect between local repo and remote repo
| git branch -m *new_name* | change branch name |
| git push origin main | to push changes and files to remote repo |
