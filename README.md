# git-commands
list of git commands

# check the git user name and set new user name
git config --global user.name // 'user name'

# check the git user email set new user email
git config --global user.email // user email

# remove the current user name 
git config --global --unset user.name

# remove the current user email
git config --global --unset user.email


# remote repo location 
git remote -v

# remove the origin
git remote remove origin

# change to another origin 
git remote add origin "url"

# Prettier settings
esbenp.prettier-vscode

# delete remote branch
git push -d origin <branch_name>

# delete local branch
git branch -d branch_name
