# git-cafe-exercise

## Bundle 5
### Exercise 2
```bash
  cd ..
  git clone https://github.com/irumvag/git-cafe-exercise.git
  cd .\git-cafe-exercise\
  git add -A
  git commit -m "feat: index welcome changed"
  git push origin main
  git push --set-upstream origin main
  git status
```
## Bundle 6
### Exercise 1,2,3 & 4
```bash
 git checkout -b new-feature
 git add -A
 git  commit -m "feat: service menu added"
 git push origin main
 git add .
 git commit -m "feat: new menu html file added"
 git push origin new-feature
 git status
 git checkout -b bug-fix
 git add .\Contact.html
 git add .\index-4.html
 git commit -m "feat: Contact page created"
 git push --set-upstream origin bug-fix
 git add -A
 git commit -m "The hot fix on phone number"
 git push origin bug-fix
 git checkout main
```