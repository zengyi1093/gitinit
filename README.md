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

git ������
1��cd ~/

2��touch .git-credentials   (ע���ļ���ǰ���и�  ���㡱)

3���򿪸ոմ������ļ���д�� https://username:password@github.com��username��password ��Ӧ bitbucket �û�������

4������Ŀ¼�� git config --global credential.helper store 

5������֮��������һ������ .gitconfig ���ļ������ļ����git�����ļ�

6���������Ĳ��������Ϥ�ˣ�ʲôpull��push��branch������Ҫ���� ��ע�⣺���ú���Щ֮���״�ִ��git��ʱ����Ҫ��������ģ�����һ�Σ��Ժ�Ͳ���Ҫ�ˣ�