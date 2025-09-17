#Setting Up a Git Repository

1. mkdir git-for-devops: Creates a new directory named git-for-devops.

2. cd git-for-devops: Navigates into the newly created directory.

3. pwd: Prints the current working directory to confirm the location.

4. git init: Initializes a new Git repository in the current directory.

5. ls -a: Lists all files, including hidden ones, to show the .git directory.

6. git config --global user.name "anshulrautela": Sets your name globally for Git commits.

7. git config --global user.email "anshulrautela@gmail.com": Sets your email globally for Git commits.

#Basic File Management and Staging

1. touch nibba.txt nibbi.txt: Creates two new, empty files.

2. vim hello-dosto.txt: Opens a file in the Vim editor to add or modify its content.

3. ls: Lists the files in the current directory.

4. git status: Shows the current state of the working directory and the staging area.

5. git add nibba.txt nibbi.txt: Stages the specified files, adding them to the staging area.

6. rm hello-dosto.txt: Deletes a file.

7. git rm --cached nibba.txt: Unstages a file without deleting it from your working directory.

8. git restore nibbi.txt: Discards unstaged changes to a file, restoring it to its state from the last commit.

#Committing Changes

1. git commit -m "adding nibba nibbi": Creates a new commit with the staged files and includes a descriptive message.

2. git commit: Opens an editor to allow you to write a more detailed commit message.

#Viewing History and Branching

1. git log: Displays the commit history.

2. git log --oneline: Shows a condensed, single-line version of the commit history.

3. git branch: Lists all branches in the repository and indicates the current one.

4. git checkout -b dev: Creates a new branch named dev and switches to it.

5. git checkout master: Switches to the master branch.

6. git switch master: A newer, more intuitive command to switch to an existing branch.
