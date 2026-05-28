# is218-cheatsheet
first assignment for IS218

# commands
1. git checkout \<branch\>
- Used to change to a different branch. Add -b before the branch name to create a new branch with that name.
2. git commit -m "\<message\>"
- Used to commit a change to a branch with a message.
3. git add \<file\>
- Used to add a file to currently staged changes. Can use a . in place of the file name to include everything in the current directory.
4. git push \<remote\> \<branch\>
- Used to push a given branch to a given remote repository. Common useage with github is "git push origin \<current branch\>"
5. cd \<new directory\>
- Used to change the current active directory to a new one.
6. mv \<old path\> \<new path\>
- Used to move a file from one path to another. Can also be used to rename paths.
7. ls
- Used to list the files in a directory
8. vi \<filename\>
- Opens the provided file into the Vi text editor
9. git diff \<a\> \<b\>
- Checks the differences between two branches or two commits. Can also look at differences between staged commits with --staged
10. cp \<existing file\> \<new path\>
- Copies a file to a given path. Can copy directories with -r
11. rmdir \<directory\>
- Removes empty directories
