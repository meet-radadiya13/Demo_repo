# Demo_repo
Demo Repository for practical exam

Made New Branch


------------------------------------------------------------------------------------
Steps done for assignments

1)  Make example of pull request and two branch merge event.<br>
git checkout -b new-feature<br>
git commit -m "Add new feature<br>
git push -u origin new-feature<br>
(Web-ui - make pull request)<br>
git merge new-feature<br>
git branch -d new-feature<br>

2) Try to rebase feature branch with master branch.<br>
git checkout feature-branch<br>
git fetch<br>
git checkout main<br>
git pull<br>
git rebase main<br>
git push  —force<br>

3) Commit push on commit in feature branch and then change commit message.<br>
git checkout feature-branch<br>
git commit -m "Initial commit”<br>
git push origin feature-branch<br>
git commit --amend -m "New commit message"<br>
git push --force origin feature-branch<br>

4) Pick some commits from feature branch to master branch.<br>
git checkout main<br>
git fetch<br>
git checkout -b pick-branch<br>
git log --oneline (for viewing hash value)<br>
git cherry-pick <commit-hash><br>
git merge pick-branch<br>
git push<br>

5) Remove some commit from feature branch.<br>
git checkout -b new-feature-branch<br>
git log --oneline (for viewing hash value)<br>
git reset --hard <commit-hash><br>
git push --force origin new-feature-branch<br>

------------------------------------------------------------------------------------
