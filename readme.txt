该CAS项目仅仅只是起到演示的作用，项目中只有class文件，并没有源代码
使用的tomcat版本：tomcat 6.0.43
使用的jdk版本：1.6.0
使用的MyEclipse版本：MyEclipse 10
使用方法：
1.首先需要修改hosts配置文件：添加上一下的两行信息：
127.0.0.1	www.bbs.com
127.0.0.1	www.news.com
2.将server.xml配置文件覆盖掉%Tomcat_Home%/conf/server.xml配置文件。
然后将server文件夹、news1文件夹、bbs1文件夹全部拷贝到%Tomcat_Home%目录中。
最后启动服务器。
3.首先访问：www.bbs.com，现实需要登陆信息。
4.然后访问：www.news.com，如果需要登录信息，则表示演示失败；
如果不需要登录信息就直接登陆成功了，则表示演示成功。