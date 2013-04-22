vwnav
=====
$ mkdir ~/vwnav
# Creates a directory for your project called "Vwnav" in your user directory

$ cd ~/vwnav
# Changes the current working directory to your newly created directory.

$ git init
# Sets up the necessary Git files

# Initialized empty Git repository 

$ touch README
# Creates a file called "README" in your Vmnav directory

$ git add README
# Stages your README file, adding it to the list of files to be committed

$ git commit -m 'first commit'
# Commits your files, adding the message "first commit"

$ git remote add origin https://github.com/nguptag/vwnav.git
# Creates a remote named "origin" pointing at your GitHub repository


$ git push origin master
# Sends your commits in the "master" branch to GitHub
