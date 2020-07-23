this is git  

ssh-keygen 创建公钥

cat  ~/.ssh/id_rsa.pub  查看公钥

https://github.com   settings    SSH and GPG keys   new sshKey

本地项目到远程仓库  git init

关联到远程仓库   git remoyte add origin    如:  git remote add origin https://github.com/mas0918/gittest.git

添加版本库  git add .

提交文件  git commit -m “conntent”

提交到远程 git push      更新  git pull 

获取远程仓库和本地同步合并 （如果远程仓库不为空 必须做这一步，否则后面提交会失败） git pull --rebase origin maseter

把本地库的内容推送到远程，使用 git push命令，实际上是把当前分支master推送到远程。执行此命令后会要求输入用户名、密码，验证通过后即开始上传。
git push - u origin master

查看在你上次提交之后是否有修改 git status 

执行 git diff 来查看执行 git status 的结果的详细信息

项目clone   git clone  url 

 本地添加ssh信任      ssh -T git@github.com     ssh -T git@gitee.com
   








 



