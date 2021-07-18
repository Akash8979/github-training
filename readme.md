# Github Training


check status of the different files
````
git status
````

add files to git to commit change 
````
git add <filepath>
git add --add
````

Commit your changes
````
git commit -m "message"
````

if commiting first time you need to add the user name and the email in config
````
git config user.name "<name>"
git config user.email "<email>"
````
To check the userName and email
````
git config user.name
git config user.file
````
push change to git gub
````
git push -u origin <branch>
````

To checkout existing branch
````
git checkout <branch>
````
To checkout new branch
````
git checkout -b <new_branch_name>
````

List brach on local
````
git branch <branch>
````
pull new code in a brach from origin
````
git pull origin <branch>
````
reset all change from previous commit
````
git reset --hard
````
check difference from the previous commit
````
git diff
```` 