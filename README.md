# day1_ Hello CLI is a command line program that accepts text input to execute operating system functions.
Command	Description
ls	List the directory (folder) system.
cd pathname	Change directory (folder) in the file system.
cd ..	Move one level up (one folder) in the file system.
cp	Copy a file to another folder.
mv	Move a file to another folder.
mkdir	Creates a new directory (folder).
rmdir	Remove a directory (folder).
clear	Clears the CLI window.
exit	Closes the CLI window.
man command	Shows the manual for a given command.
# this is how we tell GIT 'please use CONNECT TO THIS folder on github'
yavuzbingol@yavuzs-MacBook-Pro day1_ % git
Reinitialized existing Git repository in /Users/yavuzbingol/Desktop/Git1/day1_/.git/

# TELL ME what folder it is connected to
yavuzbingol@yavuzs-MacBook-Pro day1_ % yavuzbingol@yavuzs-MacBook-Pro day1_ % git remote -v
origin  https://github.com/AysebATGI/day1_.git (fetch)
origin  https://github.com/AysebATGI/day1_.git (push)

'dash'

# git remove rm origin
remove the repo it is currently connected to

# git remote add origin  https://github.com/AysebATGI/javaprojects.git
this links the REMOTE repo (github project) to your LOCAL repo (your laptop)

# git add .
THIS STAGES ALL THE FILES THAT YOU WILL COMMIT

# GIT COMMIT -M "insert comment here"

yavuzbingol@yavuzs-MacBook-Pro day1_ % git commit -m "Babi"
[main 7ee5669] Babi
 1 file changed, 26 insertions(+), 1 deletion(-)
 rewrite README.md (100%)


# git status
checks if it was sent to the STAGING AREA correctly

yavuzbingol@yavuzs-MacBook-Pro day1_ % git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

# git push
yavuzbingol@yavuzs-MacBook-Pro day1_ % git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 746 bytes | 746.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/AysebATGI/day1_.git
   5c3e5f6..7ee5669  main -> main
   one two three
