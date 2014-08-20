###SVN的安装与使用
1.安装好SVN server打开Repositories创建一个CloudAtlas
![CL][1]
2.新建Folder下面，个人建议新建分组和组员信息及个人代码库
![Folder][2]
3.1在Users下面Create New User 输出name建立一个个人Password
![User][3]
3.2在Groups下Create New Group ，Group name（one）然后Add User xinjiahong进去。服务器搭建基本完毕，
4.创建代码库
安装TortoiseSVN，创建一个代码库
![tortoiseSVn][4]
进入此文件夹，鼠标右键，点击SVN update
![SVNupdate][5]然后可以把服务器中的创建好的类下载到本地
5.代码库和服务器的初使用
5.1在本地刚刚从服务器下载好的文件中创建一个日志文件 20140819工作日志.TXT
![TXT][6]
5.2打开Commit-TortoiseSVN上传写好的工作日志20140819工作日志.TXT
![Commit][7]
上传完毕![ADDED][8]
5.3修改日志文件，上传已修改的文件，下载代码库中修改好的日志。检查前后是否一致
修改日志文件![xg][9]
上传修改后的文件并删除本地的日志![sc][10]
下载修改后上传的那个文件查看与删除前的文件是否一致![yz][11]
5.4比较前后上传2次文件的不同
![version][12]
5.5同时删除服务器代码库中自己的文件和本地文件
点击自己本地的文件右键打开TortoiseSVN的Delete，然后就可以删除掉服务器和本地的文件了



[1]:1.png
[2]:2.png
[3]:3.png
[4]:4.png
[5]:5.png
[6]:6.png
[7]:7.png
[8]:8.png
[9]:9.png
[10]:10.png
[11]:11.png
[12]:12.png





