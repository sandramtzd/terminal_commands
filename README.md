# Make a Command-Line Cheat Sheat

Both Terminal and Git are important tools in my career as software engineer, so understanding them and practicing with them is vital. In this lab I'm writing a cheat-sheet to summarise the most useful commands for future reference.

## MVP (Minimum Viable Product)

- Create a Markdown file to record the research about commands:
`touch terminal_cheatsheet.md`. (Note, the `.md` file extension, which denotes this as a Markdown file.)
- Open the `terminal_cheatsheet.md` using VSCode.
- Use markdown to create a Terminal commands cheatsheet. There are many resources on the web to help me get to know Markdown.
- Here is a Markdown cheatsheet to get started: [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/). 

## Using Git in Terminal

- Initialise the folder as a Git project (remember, Git is local - i.e. on your laptop).

- Ensuring I have navigated to my `terminal_commands` folder.

- Type `git init` in order to create a `.git` folder (the `.` indicates it is a hidden file). You should now see `git:(main)` after your folder name. Try typing `ls -a` and you should now see `.git` listed.

### Tracking changes in our code
I can now stage my work and make a commit.

- `git add .` will add all changes (in this case everything, as the whole project is new) to be tracked in our `.git` file.
- `git commit -m"first commit"` confirms to Git that we want to save this work (take a snapshot) at this stage.

## GitHub

In order to push the project to GitHub I created a remote repository first - a place for the code to sit in GitHub. I followed the next steps:

- Go to the browser and navigate to GitHub
- Create a new repository. Please remember that this repo must be public in order for everyone to see it! 
- Copy the three lines of code from the middle block that looks like this:

```
...or push an existing repository from the command line
git remote add origin git@github.com:<your_github_name>/<your_repo>.git
git branch -M main
git push -u origin main
```

## Terminal

I can now push the code to GitHub. 
- Pasting the code I copied into the terminal and hit `enter`. This code tells Git where to push the work to on GitHub, and then pushes it up.
- Check if it worked! 
Heading back to the browser and GitHub, refresh the page and I should now see the file on GitHub.


## Extensions

- Investigated `.gitignore` files and what they are used for. Tried adding one to my repository.
