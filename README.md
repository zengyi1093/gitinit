ȫ������:

git config --global user.name "ASxx" 
git config --global user.email "123456789@qq.com"

���� git �ֿ�:

mkdir wap
cd wap
git init
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin https://git.oschina.net/name/package.git
git push -u origin master
������Ŀ?

cd existing_git_repo
git remote add origin https://git.oschina.net/name/package.git
git push -u origin master
