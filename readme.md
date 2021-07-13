#Task 1.2. Decentralized VCS practice with Git

###Using Terminal
1: Install Git (if you dont have it): https://git-scm.com/downloads

2: Create a repository on github.com

[1.2a, 1.2b]

3: Open your explorer, Go to the folder you want to start your tracking in github. Left click and click on Git Bash Here.
[1.2c]

You can also manually  enter to the location going to your command prompt and navigating to the your target folder, for example:
    cd E:\wangn\Downloads\BrooklynCollege\assigments\GitTutorial
[1.2d]

4: Create the files you want to start tracking:
[1.2e]

5: On your git bash, or terminal enter:
5.1
`git init` - To initialize git [1.2f]
5.2
`git add [filename]` - to add file to the staging area 
-> for example `git add readme.md`
You can also add all the in the folders using: `git add -A` or `git add --all`
5.3
now commit your files addition using `git commit -m "[your message]"` 
-> for example `git commit -m "first commit"`

5.4 Create your branch
`git branch -M main`

5.5 Add your origin:
`git remote add origin https://github.com/NeneWang/CISC3140-Task-1.2.git`

5.6 push to the origin
`git push -u origin main`

### Make your changes and update your repo
Make your changes
[1.2g]

Commit your changes
`git commit -m "gitTutorial | descriptions changed" -a`
`git push origin main`
[1.2h]












