# MacSetUp -

If you are new to programming and want to get started, it's best to know how to use your laptop (Mac) to speed up opening files, making files, downloading dependencies and running code. I will be covering a few basics here to help you get started

## Using Terminal

*Terminal* is the command prompt that is native to a Mac. You can access your terminal by pressing *Command + Space*, typing in terminal in the search bar and clicking enter. It should resemble like the image below

<img width="524" alt="Screen Shot 2022-05-15 at 5 45 58 PM" src="https://user-images.githubusercontent.com/45598727/168497169-4f525c6e-7782-42be-8053-ab06c302d083.png">


Terminal is useful for several things. 

- The first is navigating and opening files. We are all use to opening files by opening folders, going through them and clicking on them to open. With terminal you can navigate through your laptop and see the files that have.
- The second is to download and import dependencies. As you begin to code, you will need to import frameworks, tools and libraries and running the download commands via your terminal is the best way to do that
- Other reasons to use terminal is that it provides you the interface to run CURL commands, use git for managing your projects and for troubleshooting your servers if they are deployed. For now though, do not worry about this.

### Basic Written Commands for terminal
A few terminal commands that you want to get use to include
1) *ls* - this lets your see all the files/folders in the directory that you are currently in
2) *cd folder_name* - this lets you nagivate into a folder that is held in the directory you are in
3) *cd ..*  -  this lets you jump back one folder back 
4) *cd* - this lets you jump back to your root folder
5) *touch my_file_name* - this lets you create a file in your current directory

### Basic Mac Commands for Terminal
1) *Control + c* - This lets you start a new line on your terminal interface
2) *Command + k* - This cleans your terminal interface in case you can a fresh screen
3) *Command + t* - This lets you open a new tab in your terminal. This can be useful if you want to run different programs simultaneously or have different projects opened
4) *Comman + w* - This let's you close the current tab you are in
5) *Comman + q* - This let's you close your entire terminal
6) *Up key* -  This lets you scroll through the previous commands that you ran on your terminal.
 

There are many other commands that you can research but for now, these should suffice. We will cover a few more once we introduce git, node and IDEs

## Installing some dependencies

As you continue in your journey, know that you will start to leverage dependencies and it's great to install them into your system via your terminal. If you run into issues downloading these dependencies, google the error message and see how to resolve. Once successfully installed, use the *verification command* to ensure that you have the dependency and its version number.

*NOTE: After downloading these softwares, you may run into issues where expected commands aren't working. If this is the case, try closing your terminal and opening it again*

### Homebrew
First, lets install Homebrew: https://brew.sh/. Copy the command into your terminal and watch it install

Homebrew is a package management system that helps you install other dependencies onto your system. Essentially, it helps download the stuff you need with its comamnds. 

Verification Command: `brew -v`

### Node
Let's install Node. Node is a back-end JavaScript runtime environment that is needed to help run your code bases. We will be using homebrew here to install node.

In downloading Node, we also downloaded `npm`. Npm is a package manager for JavaScript. You will be using npm commands such as `npm install` and `npm run` down the road

Installation Command:  `brew install node` 
Verification: `node -v`, `npm -v`


## Installing an IDE

An IDE is simply an interface that let's you open your files/folders and see/write your code. Examples of this would include `Eclipse`, `Intellij`, `Atom` and `Visual Studios`

For now let's just install Atom and Visual Studio

### Atom
- Download Atom (https://atom.io/)
- Next, open the IDE and follow the tutorial on how to use it
- Finally, follow the directions listed here so that you can open atom via terminal (https://stackoverflow.com/questions/43013195/how-to-open-the-terminal-in-atom)
- Follow a similar process for Visual Studios( https://code.visualstudio.com/) ( https://www.freecodecamp.org/news/how-to-open-visual-studio-code-from-your-terminal/)


Once downloaded, you can open either of these IDEs through your terminal. Simply type in `atom .` or `code .` With this you can now go to any project you want and open it on your IDE and start coding!

## Git and GitHub

One final thing to do is to great a GitHub Account. GitHub is a version manager platform that helps in tracking, updating and keeping your code base. Essentailly, it's place where you can `push` up your code and keep track of the changes.

The way you can push up your changes is by using Git. You can download this by running `brew install git`. 


### BreakDown on GitHub

Github stores your projects in what we call `repositories`. This is simply the place/folder where yous have your files of code and other resources stored in. You can make private and public repositories and maange them via different setttings. You can download repositories by copying the git url homepage and use `git clone repository_url`

The way GitHub manages your code changes is through `commits`. A commit is simply a chunk of changes that you want to make. For example, lets you you change the name of your file, change a line of code, add a file or delete a file. What you need to do is create a commit that show cases the changes.

The process of make a commit is straight forward. First, lets assume you have some repository and make a new file called `test.js` that you want to add. You should run these commands via your terminal 

1) `git status` -  This lets you see changes made to your project. Typically any changes whill be highlited in red for unstaged changes and green for staged
2) `git add my_file_name` - This lets you `stage` your file. Essentially, you are marking this file as the one you want yo push up to your github repository. Once ou stage your file or files you can can check the status of them and see that they are now highlighted green
3) `git commit -m "Some descriptive message of your change"` - This is `commiting` the changes. Here, you commit your files and provide it a message for the changes you are making. This is crucial for version control since this you will be able to see this commit/message if you ever want to see the history of your project
4) `git push` - Once you committed your files,  you will see that if you run the `git status`, those are no longer shown. Don't worry that's normal since git status only shows files that have changes and are not commited. But just becasue they are committed, it doens't mean that they ahve been pushed up into GitHub. So run `git push` in order to finally push up the changes and see it being reflected in your repository


## Final Note

It's crucial to note that this is only a basic set up. There's a lot more features to terminal, git, GitHub, node, npm and IDEs that this is not covering
I would recommend targeting the following things. As always, read as much as you can and use google to find the answers to any issues you have.

Git - How to revert commits, how to reset chnages
Giub -  What is a branch? what is a pull request?
NPM - What is a .gitignore file? how do I download dependencies (npm i)? What are script comamnds?
Terminal - More basic commands
IDEss - How to install terminals in IDEs, git versioning via IDEs, Package management

