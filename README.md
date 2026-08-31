# SharedTestRepo
In this Repo I NWDau and AdamB will use this Repo to further our knowledge in repository instruction.
we are retards

# Bash worksheet (44-550: Operating Systems)

## Name: `Adam Bartout`

Answer the following questions; provide your answer in the code tags next to the questions, where appropriate.
Unless otherwise specified, you may assume that your current working directory is your home directory.

### Directories
1. What bash command prints your current working directory? 
pwd
1. What directory is `~` a shortcut for?  What does it mean?
Shortcut for home directory. Shows the directory that's assigned to your username.
1. Write a bash command that creates the directory `assignments` in your home directory.
mkdir  ~/assignments
1. Write one or more commands that creates the directory `projects/p01` in your home directory.  Do not assume the projects directory exists.
mkdir -p ~/projects/p01

### Navigating Directories

1. Write a bash command that changes your current working directory to `/usr/local/bin`.  You may not assume your current working directory is `/`.
cd ~/usr/local/bin
1. Write a bash command that changes your current working directory to `~/assignments/ws-01`.  You may assume that your current working directory is your home directory. 
cd ~/assignments/ws-01
1. Write a bash command that changes your working directory to your home directory. 
cd ~
1. Write a different bash command that changes your working directory to your home directory. 
cd

### Files

1. Write a bash command that lists all of the files in the current directory.  You do not need to print hidden directories or extra information. 
ls
1. Write a bash command that lists all of the files in the `/usr/local/bin` directory.  You do not need to print hidden directories or extra information. 
ls /usr/local/bin
1. Write a bash command that copies `file1.txt` to `file2.txt` in the current working directory. 
cp file1.txt file2.txt
1. Write a bash command that moves `tpo_file_name.txt` to `typo_file_name.txt` in the current working directory. 
mv tpo_file_name.txt typo_file_name.txt
1. Write a bash command that removes `~/files/file2.txt`. 
rm ~/files/file2.txt
1. True or False: files removed with the command above can be restored (similar to the Recycle Bin in Windows). 
NO


### Git-CLI

1. Write the bash command that clones your repository for this worksheet into the current working directory. git clone repo-URL
1. Write a bash command to change your current working directory into the repository cloned in the question above. 
cd nameOfRepo
1. Write a bash command that opens the file `README.md` in the text editor of your choice. code README.md
1. Write a bash command that adds the changes to the file `README.md`. 
git add "README.md"
1. Write a bash command that commits your changes to this repository.  You may either use the `-m` flag to specify the message here at the command line or use a text editor. 
git commit -m "Modified the file README.md"
1. Write a bash command that pushes your changes to this repository to the origin repository. 
git push
