git clone https://github.com/ **YourGithubAccount** /c2022-challenge
cd c2022-challenge
ls

git config user.name "李雨斌"
git config user.email "323910043@qq.com"

git remote -v
git remote add upstream https://github.com/luckymark/c2022-challenge
git status
git add .
git commit -m "完成了running letter"
git push
git fetch upstream
git merge upstream/master
