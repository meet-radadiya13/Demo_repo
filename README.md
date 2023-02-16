# Demo_repo
Demo Repository for practical exam

Made New Branch


------------------------------------------------------------------------------------
Steps done for assignments

1)  Make example of pull request and two branch merge event.
git checkout -b new-feature
git commit -m "Add new feature
git push -u origin new-feature
(Web-ui - make pull request)
git merge new-feature
git branch -d new-feature

2) Try to rebase feature branch with master branch 
git checkout feature-branch
git fetch
git checkout main
git pull
git rebase main
git push  —force

3) Commit push on commit in feature branch and then change commit message
git checkout feature-branch
git commit -m "Initial commit”
git push origin feature-branch
git commit --amend -m "New commit message"
git push --force origin feature-branch

4) Pick some commits from feature branch to master branch
git checkout main
git fetch
git checkout -b pick-branch
git log --oneline (for viewing hash value)
git cherry-pick <commit-hash>
git merge pick-branch
git push

5) Remove some commit from feature branch.
git checkout -b new-feature-branch
git log --oneline (for viewing hash value)
git reset --hard <commit-hash>
git push --force origin new-feature-branch

------------------------------------------------------------------------------------
