# Commands cheatsheet for terminal
Below you will find some core commands is necessary to know for navigating around the terminal proficiently.

## Terminal Commands for navigate the file system
| Command     | Description | Example
| ----------- | ----------- | -----------
| `➜  ~`        | It is not a command but indicates home directory | /Users/sandra|
| `pwd`         | To see the actual directory | /Users/sandra/Documents |
|`cd`          | Change Directory| ➜  ~  cd D and you push shift, so you can see the available folders. We selected Documents in this case |
|`cd .. `  | With this you will navigate to the parent directory **NOTE: The space between cd and the dots is important**   | After doing that you on Documents you will come back to /Users/Sandra |
| `ls`   | Shows a list of the folders and files that are already in the folder you are navigating | **ls** in Documents will show me bnta_work and c11_coursenotes |
| `ls -a` | Shows a list of the files or folders that are hidden for the best, so as users will not mess around them **NOTE: The space between cd and the dots is important**   | *.DS_Store , .localized*  **NOTE: It has a point precedent, indicating a hidden document and maybe forbidden** |
| `ls -l `| Shows details about the **visible** folders or files like, owner, team and date | drwxr-xr-x  15 sandra  staff  480  4 Jul 18:09 bnta_work
| `history` | Outputs the entire command history inputted into the terminal | No example
| `ctrl + k`| Clears the terminal | You will have a fresh terminal window
| `ctrl + l` | Moves the current line to the top of the screen | The cursor will be on the top of the screen








| `rm `| Used to delete files | rm my_file.txt |
|`rm -r `| Deletes the folder recursively, even the empty folder | rm -r my_folder |
| rm -rf | **Don't use it NEVER in your life unless you want to broke and unrecover your beautiful MAC** | ==No example, just know that exists== |
| `rm -rf` | **Don't use it NEVER in your life unless you want to broke and unrecover your beautiful MAC** | ==No example, just know that exists== |
| touch | Create files | touch my_file.txt Just be sure about where you are creating the file |
| open . | This will open the file that we just create like my_file.txt | open . And this will open the text editor with our file on it <span style="color: #ffa7a6">**NOTE: The space between open and the dot is important** </span>
| code . | This will open the Visual Studio Code app and the file related | code . And the app will be opened with the the file and the folder tree <span style="color: #ffa7a6">**NOTE: Remember the space** </span>| 
| mv | This command is for move files or rename it | - Move files   <span style="color: #f25477">mv example.txt /Users/Sandra</span> This will move the file *example.txt* to the folder Sandra. - Rename files  <span style="color: #f25477">mv example.txt exm.txt</span> This will change the name for exm.txt |
| clear | Will give you an empty space but you can scroll up to see what was before | NA |
|

