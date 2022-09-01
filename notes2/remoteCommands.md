git merge --abort 
ctrl + z
Q
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




git reset --hard 691a78500

******\_\_******!!!

git commit -a --allow-empty-message -m ''
******\_\_******!!!

git config --global alias.add-commit '!git add -A && git commit -m "commit"'
git config --global alias.wolf '!git add -A && git commit -m "commit" && git push'
******\_\_******!!!

git checkout -- . // checkout Head
git branch -D branchName // delete branch
******\_\_******!!!
git stash
git stash -m 'message'
git stash apply
git stash list
git stash apply 2
git stash push -m 'massage'
git stash drop 2
git stash pop 1
git stash clear


git stash store $(git stash create) -m "Stash commit message" // stash something without reverting to head to the head

This can be saved to a Git alias to make it more convenient:

git config --global alias.stash-keep '!git stash store $(git stash create)'

git stash-keep -m "Stash commit message"

git config --global alias.sta '!git stash  && git stash apply'

----------------------
 git config --global alias.test '!git wolf && git stash apply'

 ----------------------
 git merge --
  branchName
 git rebase breanchName

 ----------------------
  git config --global alias.stm 'stash -m'
----------------------

git revert 89fbb2c
  git reflog
  git log --graph --decorate --oneline
  git config --global alias.l 'log --graph --decorate --oneline'
  git log -S 'wolfMan' // search
  git push origin --delete wolfMan // delete remote branch
  git branch -vv
  git remote update --prune
  git --help
  git branch -vv | awk '/: gone]/{print $1}'
  git branch -vv | awk '/: gone]/{print $1}' | xargs git branch -d
   git bisect start
   git bisect bad
   git bisect good 9f708bc
   git reset --hard origin/wolfMan   // hard Reset  to origin/branchName
  ----------------------
Press Esc to enter Command mode, and then type :wq to write and quit the file. The other, quicker option is to use the keyboard shortcut ZZ to write and quit. To the non-vi initiated, write means save, and quit means exit vi.


git config --global alias.ss "stash save"



 git config --global alias.sa 'stash apply'
git ss test33 && git sa