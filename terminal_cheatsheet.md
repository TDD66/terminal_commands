# Terminal Cheatsheet

## Overview
Terminal cheatsheet gives a simple overview on navigating and doing actions on file systems on terminal, and also includes a few basic git commands.

### Terminal

#### Navigation and Directories

|Command |Action |
|:------|:-------|
|`cd DIRECTORY`| Changes directory to **DIRECTORY** e.g `cd Downloads`|
|`cd ..`| Navigates up one directory|
|`cd`| Navigates to the home directory|
|`cd -`| Navigates to the previous working directory|
|`cd DIRECTORY/SUB_DIRECTORY`| Changes directory to **DIRECTORY/SUB_DIRECTORY**|
|`ls`| List all of the directory's contents|
|`ls -a`| List all of the directory's contents including hidden files|
|`ls -l`| List all of the directory's contents as well has additional information|
|`ls -al`| Combination of the previous 2 commands|
|`pwd`| Prints working directory to the terminal|

#### File and Directory Actions

|Command |Action |
|:------|:-------|
|`mkdir DIRECTORY`| Creates a directory called **DIRECTORY** in the working directory|
|`touch FILE`| Creates a file named **FILE**|
|`rm FILE`| Deletes a file named **FILE**|
|`rm -r DIRECTORY`| Deletes a directory named **DIRECTORY**|
|`rm -f FILE`| Forces the deletion of a file named **FILE**|
|`mv OLD_FILE_NAME NEW_FILE_NAME`| Renames the file called OLD_FILE_NAME to NEW_FILE_NAME|
|`mv FILE DIRECTORY`| Move **FILE** from it's current directory to **DIRECTORY**|
|`cp FILE DIRECTORY`| Copy **FILE** to **DIRECTORY**|
|`cp -r DIRECTORY NEW_DIRECTORY`| Copy **DIRECTORY** to **NEW_DIRECTORY**|

### Basic Git Commands

|Command |Action |
|:------|:-------|
|`git init`| Initialises current directory as a Git directory|
|`git clone URL`| Retrieve Git repository from remote repo using **URL**|
|`git status` or `gst`| Shows information whether anything in the repo has been modified|
|`git add FILE`| Tells Git to begin tracking **FILE**|
|`git add --all`| Add all of the files in local directory to the repo|
|`git add .`| Stage all of the changes in the current directory|
|`git commit -m "MESSAGE"`| Creates a new commit with the changes that were added to the staging area, with the commit message **MESSAGE**|
|`git revert COMMIT_ID`| Creates a new commit that reverts a previous commit with the commit ID **COMMIT_ID**|
