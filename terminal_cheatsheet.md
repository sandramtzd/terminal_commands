# Commands cheatsheet for the terminal
Below you will find some core commands is necessary to know for navigating around the terminal proficiently.

## Terminal Commands to navigate the file system
| Command     | Description | Example
| ----------- | ----------- | -----------
| `➜  ~`        | It is not a command but indicates home directory | ```/Users/sandra```|
| `pwd`         | To see the actual directory | ```/Users/sandra/Documents``` |
|`cd`          | Change Directory| ```➜  ~  cd D``` If you push shift, you will see the available folders. We selected Documents in this case |
|`cd .. `  | With this you will navigate to the parent directory **NOTE: The space between cd and the dots is important**   | After doing that you on Documents you will come back to ```/Users/Sandra``` |
| `ls`   | Shows a list of the folders and files that are already in the folder you are navigating | **ls** in Documents will show me bnta_work and c11_coursenotes |
| `ls -a` | Shows a list of the files or folders that are hidden for the best, so as users will not mess around them **NOTE: The space between cd and the dots is important**   | *.DS_Store , .localized*  **NOTE: It has a point precedent, indicating a hidden document and maybe forbidden** |
| `ls -l `| Shows details about the **visible** folders or files like, owner, team and date | ```drwxr-xr-x  15 sandra  staff  480  4 Jul 18:09 bnta_work```
| `history` | Outputs the entire command history inputted into the terminal | No example
| `ctrl + k`| Clears the terminal | You will have a fresh terminal window. You can also use the command `clear`|
| `ctrl + l` | Moves the current line to the top of the screen | The cursor will be on the top of the screen





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