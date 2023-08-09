# Git-A5

-->
Create a Git Flow workflow architecture on Git -->
Create all the required branches -->
 Starting from the feature branch, push the branch to the master, following the architecture -->
 Push a urgent.txt on master using hotfix










  mkdir assignment5
  181  cd assignment5
  182  git init 
  183  touch master.txt
  184  git add master.txt
  185  git branch
  186  git branch master
  187  git commit -m "commiting master.txt
  188  git commit -m "commiting master.txt"
  189  git branch develop
  190  git checkout develop
  191  touch develop.txt
  192  git add develop.txt
  193  git commit -m "commiting develop.txt"
  194  git branch feature
  195  git checkout develop
  196  git merge feature
  197  git checkout
  198  git checkout master
  199  git merge develop
  200  git branch hotfix
  201  touch urgent.txt
  202  git add urgent.txt
  203  git commit -m "commiting urgent.txt"
  204  git checkout master
  205  git merge hotflix
  206  git merge hotfix
  207  git add remote https://github.com/dirun11/Git-A5.git
  208  git remote add origin https://github.com/dirun11/Git-A5.git
  209  git push origin --all
  210  history
