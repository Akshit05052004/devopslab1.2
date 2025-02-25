# devopslab1.2
this repo is for the devops lab 2

git clone https://github.com/Akshit05052004/devopslab1.2.git
cd devopslab1.2
git branch feature-branch
git switch feature-branch
echo "New feature added" > feature.txt
git add feature.txt
git commit -m "Added feature.txt in feature-branch"
git switch main
git merge feature-branch
git reset HEAD~  # Undo last commit
git rebase main  # Rebase feature-branch onto main
git push origin main
git branch -d feature-branch  # Delete branch
