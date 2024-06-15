# Important git Commands

### Beginner level Commands

-`git init`-> It initializes a new git repository.What is a git repository?it is a folder managed by git where we can track all the changes we are making in the project.

-`git status`->This shows the current state of your working directory and staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.

-`git log` -> This displays the commit history for the repository. It shows a list of all the commits, along with details such as the commit hash, author, date, and commit message.


-`git add <filename>`-> Starts tracking your new changes for the next commit.

-`git commit -m "<message>"`-> This creates a new version based on your prev changes.

-`git remote add origin <repository-link>` -> This links the remote repository to our local folder.

-`git push origin <branch>` -> This pushes the new and latest changes to the remote repository's specified branch.

### Advanced Commands

-`git cat-file -t <hash first 5-6 characters> ` -> This commands shows the type of the file stored in  .git/objects/

-`git cat-file -t <hash first 5-6 characters> ` -> This commands shows the content of the file stored in  .git/objects/

-`git rm --cached <filename>`->This deletes the complete file from the staging area and brings it back to the working area.

-`git restore --staged <filename>`-> This restores only the current staged change from the file not complete file.

-`git log --oneline` -> This provides a condensed version of the commit history, showing each commit on a single line. It displays the commit hash and the commit message in a simplified format, making it easier to scan through the history quickly.






