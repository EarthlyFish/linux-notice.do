获取进程信息，通过ps命令：
1.	获取所有进程信息
   命令：ps aux
2.	获取某一个名称为tomcat的进程
  命令：ps aux |grep tomcat
给某个文件夹加权限：
1.给/tmp/inspur文件夹加admin用户：chown admin /tmp/inspur
2.给/tmp下所有文件夹加admin用户：chown  -R  admin /tmp/inspur
