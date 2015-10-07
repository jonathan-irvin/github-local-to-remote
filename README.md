# Create a New Github Repo from a new Local Repo on the Windows Commandline
1. Go to **http://github.com**.  Login and create a new repository on the right (Green button).
2. ***DO NOT INITIALIZE WITH A README***
3. Change to the directory you wish to make a project from. *This can be a folder under your eclipse workspace which will contain all the code for a single java program.*
4. **git config user.name** "Firstname Lastname"
5. **git config user.email** "email@example.com"
6. **git echo** # nameofproject >> README.md
7. **git init**
8. **git add README.md** *This will only add the single README.md file to the staging area*
9. **git commit -m** "first commit"
10. **git remote add origin** https://github.com/*username*/nameofproject.git
11. **git push -u origin master**
