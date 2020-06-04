** VCS **
Version control - there is version control in Local, Central and Distributed

** Git vs Github **
Git is the code to manipulate the files and repository. Contorls the versions or snapshots of the repository
Github is where the repository is maintained

** Local vs Remote **
Local is on your current machine and GIT controls versions of the file
Remote is on the GITHUB

** Clone **
Cloning is creating a copy of the repository into a test directory of the URL
By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

To clone a repository into a directory with another name of your choosing, use the following command format:


Commit

ACP


Deployment


Check Settings
To check settings, use the git config --list command.

Example:

$ git config --list

user.name=Jane Smith

user.email=example@email.com

color.status=auto

color.branch=auto

color.interactive=auto


Getting Help
There are three ways to get more information on a particular command, by accessing the manual:

git help command

git command --help

man git-command
