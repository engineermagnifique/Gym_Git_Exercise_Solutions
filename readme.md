## Git Exercises

### Bundle1

#### Exercise 1:

```bash
mkdir GitLearning
cd GitLearning
git init
git branch -m master main
git add --all
git commit -m "first commit"
git branch -M main
git remote add  origin https://github.com/engineermagnifique/Gym_Git_Exercise_Solutions
git push -u origin main
git branch dev
git checkout dev
git push -u origin dev
git checkout -b test
git checkout dev
git branch -d test
git push origin --delete test
git stash -u //for stashing untracked files
touch about.html
git add about.html
git stash
touch team.html
git add team.html
git stash
git stash apply "stash@{1}"
git stash apply "stash@{2}"
git reset
git checkout main
git pull origin main
git commit -m "Added new things to service"
git add services.html
git commit -m "Added new things to service"
git push origin main
//creating pull request
```
