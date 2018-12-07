# GitProjects
GitProjects项目，所有GitProjects提交目录。<br /><br />
### 日常建立git基线脚本如下：<br /><br />
1、配置用户名<br /><br />
   &ensp;&ensp;&ensp;`git config --global user.name "xx";` <br /><br />
2、配置邮箱<br /><br />
   &ensp;&ensp;&ensp;`git config --global user.email "xx.com"; ` <br /><br />
3、生成SSH<br /><br />
   &ensp;&ensp;&ensp;`ssh-keygen –t rsa –C xx.com; ` <br /><br />
4、测试连通性<br /><br />
   &ensp;&ensp;&ensp;`ssh –T git@github.com; ` <br /><br />
5、初始化项目<br /><br />
   &ensp;&ensp;&ensp;`git init; ` <br /><br />
6、增加注释<br /><br />
   &ensp;&ensp;&ensp;`git commit –m “注释内容”; ` <br /><br />
7、本地项目远程关联<br /><br />
   &ensp;&ensp;&ensp;`git remote add 别名 git@github.com:xxx.git; ` <br /><br />
8、本地项目发布到远程<br /><br />
   &ensp;&ensp;&ensp;`git push –u 别名 master; ` <br /><br />
9、远程项目下载到本地<br /><br />
   &ensp;&ensp;&ensp;`git clone git@github.com:xxx.git; ` <br /><br />
10、更新项目<br /><br />
   &ensp;&ensp;&ensp;`git pull; ` <br /><br />
