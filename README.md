# cc
cd C:\
git clone https://github.com/your-username/git-demo.git
cd git-demo

echo "This is a sample file" > sample.txt
git status
git add sample.txt

git commit -m "Added sample.txt file"

git push origin main



git fetch origin
git pull origin main

git branch new_feature
git checkout new_feature

echo "New branch content" > branch.txt
git add branch.txt
git commit -m "Added branch.txt in new_feature branch"

git checkout main

git reset --soft HEAD

git reset --hard HEAD

git rm sample.txt
git commit -m "Deleted sample.txt"
git push origin main




git init
git add .
git commit -m "first"

git add .
git commit -m "second"
