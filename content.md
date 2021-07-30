* First Time setup(On installing Git)
* git config --global user.email johndoe@example.com
* git config --global user.name "John Doe"
* to verify -> git config --list

# (You need to do it always) When you create repo
 git init
 create a file .gitignore=> add node_modules to it
 git add .
 git commit -m "commit message"
 create a repo on github
 git remote add origin Your Repo Name
 git push -u origin master