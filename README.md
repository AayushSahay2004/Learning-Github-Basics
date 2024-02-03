# Learning-Github-Basics
-For Aayush To learn Github Fundamentals for Working

when we want the status , we use the git status
to clone the repositry git clone "https://github.com/AayushSahay2004/Learning-Github-Basics.git" then to press enter to go to the folder

then cd to change to that directory
The computer you are working is the local computer
Always add then do commit , and then push that to the Remote Computer(That is the Github page)

git add README.md
git commit -m "Message : 1st time commiting Changes in the readme file of this repo"
then to reflect it on the github do 
git push origin main

if error like:
Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.
PS C:\Users\Dell\Desktop\hello\Learning-Github-Basics> git add README.md
fatal: Unable to create 'C:/Users/Dell/Desktop/hello/Learning-Github-Basics/.git/index.lock': File exists.

Solution:
do it
PS C:\Users\Dell\Desktop\hello\Learning-Github-Basics> rm .git/index.lock
PS C:\Users\Dell\Desktop\hello\Learning-Github-Basics> git add README.md
PS C:\Users\Dell\Desktop\hello\Learning-Github-Basics> git status