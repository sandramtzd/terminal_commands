# Commands cheatsheet for the terminal
Below you will find some core commands is necessary to know for navigating around the terminal proficiently.

## Terminal Commands to navigate the file system
| Command     | Description | Example
| ----------- | ----------- | -----------
| `➜  ~`        | It is not a command but indicates home directory | ```/Users/sandra```|
| `pwd`         | To see the actual directory | ```/Users/sandra/Documents``` |
|`cd`          | Change Directory| ```➜  ~  cd D``` If you push shift, you will see the available folders. We selected Documents in this case |
|`cd .. `  | With this you will navigate to the parent directory **NOTE: The space between cd and the dots is important**   | After doing that you on Documents you will come back to ```/Users/Sandra``` |
| `ls`   | Shows a list of the folders and files that are already in the folder you are navigating | This will show a list of theavailable folders in the home directory |
| `ls -a` | Shows a list of the files or folders that are hidden for the best, so as users will not mess around them **NOTE: The space between cd and the dots is important**   | *.DS_Store , .localized*  **NOTE: It has a point precedent, indicating a hidden document and maybe forbidden** |
| `ls -l `| Shows details about the **visible** folders or files like, owner, team and date | ```drwxr-xr-x  15 sandra  staff  480  4 Jul 18:09 bnta_work```
| `history` | Outputs the entire command history inputted into the terminal | No example
| `ctrl + k`| Clears the terminal | You will have a fresh terminal window. You can also use the command `clear`|
| `ctrl + l` | Moves the current line to the top of the screen | The cursor will be on the top of the screen

<br>

## Terminal Commands to manipulate directories and files
| Command     | Description | Example
| ----------- | ----------- | -----------
| `rm `| Used to delete files | ```rm my_file.txt``` |
|`rm -r `| Deletes the folder recursively, even the empty folder | ```rm -r my_folder``` |
| `rm -rf` | ***CAUTION!*** removes recursively and forcefully the specified file** | `rm -rf my_file.png`|
| `rm -rf ~/` | **Don't use it NEVER in your life unless you want to broke and unrecover your beautiful computer** | ==No example, just know that exists== |
| `touch` | Create files | ```touch my_file.txt``` Just be sure about where you are creating the file |
| `open .` | This will open the file that we just create like my_file.txt | ```open .``` And this will open the text editor with our file on it **NOTE: The space between open and the dot is important** |
| `code .` | This will open the Visual Studio Code app and the file related | ```code .``` And the app will be opened with the the file and the folder tree **NOTE: Remember the space** | 
| `mv` | This command is for move files | ```mv example.txt /Users/Sandra``` This will move the file *example.txt* to the folder *Sandra*. Remember the space between the file and the directory. | 
| `mv` | This command is also for rename files | ```mv example.txt exm.txt``` This will rename the file *example.txt* for *exm.txt* |

## Terminal Commands for Git
| Command     | Description | Example
| ----------- | ----------- | -----------
| `git init`      | Initialises a git repository in the current directory | ```git init```|
| `git status`  | Gives the status of the current working tree | ```git status```|
| `git add .`  | Used before committing after making changes to the working tree. Stages the content by updating the index in the working tree | ```git add .```|
| `git commit -m"message here"`  | Commits the change to the repository with a message | ```git commit -m"added readme file"```|
| `git status`      | Gives the status of the current working tree | ```git status```|
| `git log`      | Displays the git commit history | ```git log```|
| `git push`      | Pushes the content of the main branch to the remote repository | ```git push origin main``` In this case the content is pushed to origin main |
| `git pull`      | Pull the content from the remote repository to the main branch | ```git pull origin main``` In this case the content is pulled to origin main |
| `git clone`      | Creates a clone of a repository or branch into a newly created directory on the local machine | ```git clone git@github.com:sandramtzd/terminal_commands.git ``` Here, we are cloning a repository using a ssh link |
| `git branch`      | Creates a new branch on the repository | ```git branch my_new_branch ``` Created a branch called `my_new_branch`. To delete a branch we can run `git branch -d my_new_branch` |
| `git checkout`      | To switch the branch you are currently working on. | ```git checkout my_new_branch ``` Switched to a branch called `my_new_branch`. To create a new branch and switch to it we can run `git checkout -b my_new_branch` |

<br><br>

# Git Ignore

When sharing your code with others, there are often files or parts of your project, you do not want to share.

Examples

- log files
- temporary files
- hidden files
- personal files

Git can specify which files or parts of your project should be ignored by Git using a `.gitignore` file.

Git will not track files and folders specified in `.gitignore`. However, the `.gitignore` file itself **IS** tracked by Git

To create a `.gitignore` file we can simply run in the root of the local Git:
```
touch .gitinore
```
Opening the file using a text editor we can two simple rules:

- Ignore any files with the `.log` extension
- Ignore everything in any directory named `temp`

```
# ignore ALL .log files
*.log

# ignore ALL files in ANY directory named temp

temp/
```

