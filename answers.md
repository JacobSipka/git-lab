git version 2.34.1
user.name=JacobSipka; user.email=js503422@ohio.edu
When I typed git --help, it displayed a lot of common Git commands. It also told me a bunch of differnt things that I can do on git, for example, "start a working area (see also: git help tutorial)"
On branch master; No commits yet; Untracked files: (use "git add <file>..." to include in what will be committed), README.md, answers.md; nothing added to commit but untracked files present (use "git add" to track)
The README.md file was moved from the Untracked files section to the Changes to be committed section and was also turned green.
Now the README.md file and the answers.md file are both green and in the Changes to be committed section
After issuing git status again it says, "On branch master" and "nothing to commit, working tree clean"
commit 67a4b04c854b1c02214882b097d98a898f25dceb (HEAD -> master); Author: JacobSipka<js503422@ohio.edu>; Date:   Fri Jan 26 14:20:36 2024 -0500
The status is currently On branch main; Your branch is up to date with 'origin/main'; nothing to commit, working tree clean
The changes I made online were not reflected in the local copy
When I tried to use git push again I got an error message
After using git pull my changes were on my local respository
After using ls -a it said I had .  ..  .git  .gitignore  README.md
