## main

---

\_**\_\_\_\_**/
branch to do some work

how do I create a branch?
checkout tells us to go to a different place
-b is saying create a new branch

`git checkout -b <name of your branch>`

To combine add and commit use

`git commit -am 'relevant message'`

to see all branches

`git branch `
hit Q when you are done viewing the branches

to push to a branch

`git push origin <branch name>`

git checkout <branch name> without the b allows you to look at a branch & check it out

`git pull origin main`

do this after you merge on GitHub and before you add anything else to your main branch

to locally delete branch

`git branch -d branch-name`

if you get a message that it won't delete use

`git branch -D branch-name `

I am creating a Contact component. I want to then push it it to Github without my netlify updating

1. create a local branch
2. create a Components folder
3. create a Contact.js
4. git status to look at updates
5. git add .
6. git commit -m "message"
7. add Component (Contact) to App.js
8. npm start to make sure changes are working
9. git status check everything is staged
10. git push to local branch
11.
