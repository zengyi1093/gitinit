全局设置:

git config --global user.name "ASxx" 
git config --global user.email "123456789@qq.com"

创建 git 仓库:
mkdir wap
cd wap
git init
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin https://git.oschina.net/name/package.git
git push -u origin master
已有项目?

cd existing_git_repo
git remote add origin https://git.oschina.net/name/package.git
git push -u origin master

git 免密码
1、cd ~/

2、touch .git-credentials   (注意文件名前面有个  ”点”)

3、打开刚刚创建的文件，写入 https://username:password@github.com，username、password 对应 bitbucket 用户名密码

4、任意目录下 git config --global credential.helper store 

5、完事之后，新生成一个叫做 .gitconfig 的文件，该文件你的git配置文件

6、接下来的操作你就熟悉了，什么pull、push、branch都不需要密码 （注意：设置好这些之后，首次执行git的时候是要输入密码的，仅此一次，以后就不需要了）