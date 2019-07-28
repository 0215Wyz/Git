如果是要上传文件到一个新的仓库：  

1. 先把路径制定到对应的本地文件夹

2. git init

3. git add .  

    默认把该文件夹里的所有文件上传

4.  git commit -m "loading first time"

    双引号里的可以自己随意修改

5.  git remote add origin (可以在github中的Clone with SSH)找到

    例如我的就是：git remote add origin git@github.com:0215Wyz/my-pictures.git

6. git push -u origin master

    之后刷新页面就可以看到上传成功了

如果是上传到已有的仓库：  

直接执行3，4，5，6就可以