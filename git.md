# Terminal, GIT, and GITHUB

### Key Terms 03JUN2020 

#### [Syntax Blog for GIT](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7_3)

<img src ="images/lillies.jpg" height="300px" align = "right">

### Getting Help with in Ubuntu
When using any commmand in Ubuntu - you can type the command `cmd --help` works and gives you a copy of the syntax for the command

### **Moving around directories**

`cd ..` 
> change one directory upward

`ls` and `ls -a`
> lists out the current directly files. "-a" shows everything.

`mkdir [directory name]`
> makes a directory

`cdwr`
> change directory to windowns root

`pwd`
> present working directory


`rm -r` or `rm- -rf`
> removes eith a recursion - deletes from the ground up. BECAREFUL when using RF - F is force to delete all hidden files as well

`touch`
> make a new file

`xdg-open index.html`
Open up your default browser with the file name index.html



### **ACP - Add / Commit / Push**

`git status ` 
> allows you to see what files have changed


`git add [filename] ` 
> add the files names that you want to push up to the repository  

`git add *`
> another command to add all files. Use a filename instead of this "catchall" as you need to know which files you are committing to the repository

`git commit -m "Your Messsage " ` 
 >adds a comment to the files that are updated to the repository on the version control. Message should be something everyone can understand

`git push origin master`
> pushes all files that have been added up to the repository


` git clone [https://your repository file]`
> clones the file directory/repository from github. Copy/Paste
> copy the address from github
> paste into Ubuntu

**Remove File from local**

`git rm [filename]`
> removes the file from the local directory






**VCS**

Version control - there is version control in Local, Central and Distributed

**Git vs Github**

Git is the code to manipulate the files and repository. Contorls the versions or snapshots of the repository
Github is where the repository is maintained and lives

**Local vs Remote**

Local is on your current machine and GIT controls versions of the file
Remote is on the GITHUB

**Clone**

Cloning is creating a copy of the repository into a test directory of the URL
> By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.


**Commit**
commit command will commit the changes you have made.  there are other commands that allow you to hide your changes until your're ready to commit them for real  'get stash' will hide your changes

**ACP**

Add commit and Push (ACP)
get add filename - to add a file
get commit -m " message"  will commit the file
get push will push the files




**Deployment**


## **Here are some sample codes to try**
Check Settings
To check settings, use the git config --list command.

Example:

$ git config --list

>user.name=Jane Smith

>user.email=example@email.com

>color.status=auto

>color.branch=auto

>color.interactive=auto



## Getting Help
There are three ways to get more information on a particular command, by accessing the manual:

git help command

git command --help

man git-command


[go back](README.md)


