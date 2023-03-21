# Terminal Notes

To see what directory we are currently in using the following command: `pwd`

To get a list of files and folders that are in the current directory use the following command: `ls`

To change to a new directory use the following command: `cd [name of folder]`

To move back a directory (folder) use the following command: `cd ..`

To move back to main top folder: `cd ~`

To create a folder use the following command: `mkdir [name of folder]`

To return to last directory: `cd -`

To see hidden files in a directory use the following command: `ls-la`


## Create an initial repository
Use the command in the terminal `git init` YOU MUST BE IN THE DIRECTORY YOU ARE WANTING TO TRACK

- In VS Code you can right click the folder you want to start tracking and choose `Open in Integrated Terminal`

## List all the changes that Git is tracking

Use the command in the terminal of `git status`

## Adding files to the Staging Area

Use the command in the terminal: `git add .`

## Commiting our changes and adding a message

Use the command in the terminal `git commit -m "YOUR MESSAGE HERE"

## Setting username and email in git

`git config --global user.name "Mona Lisa"` sets the username
`git config --global user.email "MY_NAME@example.com"` sets the user email
`git config --list` will allow you to verify your git settings


# Github
1. Create a repository and give it a unique name. Ex. sdb-mar-2023-unit-1
2. Copy and paster the last option and paste it into the terminal

# Already have a repo or a github repo and you want to update with changes.

1. `git add .`
2. `git status` - to verify (optional)
3. `git commit -m "ADD NEW MESSAGE HERE"` - EX 'added styling" or "fixed bug"
4. `git puch origin main`