# POD-3-activity

#Create branch based on Features follow the below structure
## feature/yourname-login-api   

## Example
feature/rupesh-login

## How to create your own branch
git checkout -b feature/login-api

## How to push your branch 
git push -u origin feature/login-api

After this pull requested will be generated to main branch

## IMPORTANT
feature/ → indicates this branch is for a new feature.
login → short description of what the feature is about.




## Morning Routine
1 - Update your local main branch:
  
  git checkout main
  git pull origin main

2 - Update your feature branch with latest main:
  
  git checkout feature/<your-feature>
  git merge origin/main

3 - Push updated feature branch:
  git push



# Merge Strategy
Always create a Pull Request from your feature branch → main.
