# MacSetUp -

If you are new to programming and want to get started, it's best to know how to use your laptop (Mac) to speed up opening files, making files, downloading dependencies and running code. I will be covering a few basics here to help you get started

## Using Terminal

*Terminal* is the command prompt that is native to a Mac. You can access your terminal by pressing *Command + Space*, typing in terminal in the search bar and clicking enter. It should resemble like the image below

<img width="524" alt="Screen Shot 2022-05-15 at 5 45 58 PM" src="https://user-images.githubusercontent.com/45598727/168497169-4f525c6e-7782-42be-8053-ab06c302d083.png">


Terminal is useful for several things. 

- The first is navigating and opening files. We are all use to opening files by opening folders, going through them and clicking on them to open. With terminal you can navigate through your laptop and see the files that have.
- The second is to download and import dependencies. As you begin to code, you will need to import frameworks, tools and libraries and running the download commands via your terminal is the best way to do that
- Other reasons to use terminal is that it provides you the interface to run CURL commands, use git for managing your projects and for troubleshooting your servers if they are deployed. For now though, do not worry about this.

*Basic commands*
A few terminal commands that you want to get use to include
1) *ls* - this lets your see all the files/folders in the directory that you are currently in
2) *cd folder_name* - this lets you nagivate into a folder that is held in the directory you are in
3) *cd ..*  -  this lets you jump back one folder back 
4) *cd* - this lets you jump back to your root folder
5) *touch my_file_name* - this lets you create a file in your current directory


There are many other commands that you can research but for now, these should suffice. We will cover a few more once we introduce git, node and IDEs

## Installing some dependencies

As you continue in your journey, know that you will start to leverage dependencies and it's great to install them into your system. If you run into issues downloading these dependencies, google the error message and see how to resolve. Once successfully installed, use the *verification command* to ensure that you have the dependency and its version number

###Homebrew
First, lets install Homebrew: https://brew.sh/. Copy the command into your terminal and watch it install

Homebrew is a package management system that helps you install other dependencies onto your system. Essentially, it helps download the stuff you need with its comamnds. 

Verification Command: brew -v

### Node

