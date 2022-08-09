git diff
 git merge branch
git status
// git branch kim
// git checkout kim
// git add .
// git commit -m 'first'

// "Make repository on github namd length"
// git remote add origin https://github/wolfgangbergin/length.git
// git push -u origin kim

// git clone https://github.com/wolfgangbergin/length.git
// ls
// cd length
// git add .
// git commit -m 'first'
// git push
// git fetch
// git merge
// OR git pull!

// Extra commands
// git branch -r // git remote branch
// git remote
// git remote rm origin
//git branch -d <branch> // Delete branch

// git branch -r // git remote branch !!!

// Where business is a new branch someone else created off the master
// git checkout origin/business
// \* (HEAD detached at origin/business)
// git checkout -b business

// or ShortHand where dummy is the new Local branch branch name
// or git checkout -b dummy origin/business

// If you wish to set tracking information for this branch you can do so with:

// origin = remote
//git pull <remote> <branch>
// git remote add integer https://github.com/wolfgangbergin/though.git
//git pull integer delete

******\_\_******!!!
// git branch --set-upstream-to=<remote>/<branch> company

// >> git branch -u integer/delete company
// Branch 'company' set up to track remote branch 'delete' from 'integer'.
******\_\_******!!!

// git push integer HEAD:delete

******\_\_******!!!

// Generate SSH key
// ssh-keygen -o -t rsa -C "wolfgangbergin@gmail.com"
// cat id_rsa.pub

******\_\_******!!!

git config --global alias.add-commit '!git add -A && git commit'



git reset --hard 691a78500

******\_\_******!!!

git commit -a --allow-empty-message -m ''
******\_\_******!!!

git config --global alias.add-commit '!git add -A && git commit -m "commit"'
git config --global alias.wolf '!git add -A && git commit -m "commit" && git push'
******\_\_******!!!

git checkout -- .