https://github.com/vcjain/git
## Revert Commonad 
 git version
  209  mkdir demo  -->Repository created on Local repository
  210  cd demo/
  211  ls
  212  history
  213  cd Git
  214  ssh-keygen -t rsa -b 4096 -C "rohinicse1999@gmail.com"
  215  git clone git@github.com:rohinivempa/Git.git  --> Cloning the git hub repository (remote repository)
  216  get status
  217  git status
  218  cd Git/
  219  get status
  220  git status
  221  git checkout -b feature
  222  git status
  223  git add .
  224  git commit -m "First commit"
  225  git status
  226  git add .
  227  git commit -m "2nd commit"
  228  git push
  229  git push --set-upstream origin feature
  230  git revert e198d0d097cbd3eb6e55c6c55ed2c589a1e91b06
  231  git status
  232  git push
## Revert command ended
## Merage cOmmand start
git checkout main
  187  git commit -a -m "1st commit to main"
  188  git commit -am "1st commit to main"
  189  git add .
  190  got commit -m "1st commit to main"
  191  git commit -m "1st commit to main"
  192  git push
  193  clear
  194  git checkout main
  195  git merge feature/test
  196  git push
## Merge command ended
## Rebase Command 
git checkout -b feature/dev1

  203  git add .
  204  git commit -m  "2nd commit in dev1 branch"
  205  git push
  206  git push --set-upstream origin feature/dev1
  207  clear
  208  git checkout main
  209  git add .
  210  git commit -m "2nd commit in main"
  211  git push
  212  git checkout feature/dev1
13  git rebase main
  214  clear
  215  git checkout main
  216  git merge feature/dev1
  217  git push
