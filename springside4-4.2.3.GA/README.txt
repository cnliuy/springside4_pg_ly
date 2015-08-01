

  SpringSide is a Spring Framework based JavaEE application reference architecture. 
  
  It shows the mainstream technologies and pragmatic practice in JavaEE world.  
  
  It has 2 major examples:
  
  1. Quickstart -- a minimal CRUD Todo-List web application.
  2. Showcase -- demonstrate many other interesting technologies.
 
-------------------------------
Offical Site: http://springside.github.io
Document: https://github.com/springside/springside4/wiki
CI Status: [![Build Status](https://travis-ci.org/springside/springside4.svg?branch=master)](https://travis-ci.org/springside/springside4)



==========================================================================


基于springside4-4.2.3.GA。感谢江南白衣和他的团队！





1.修改完 {springside4-4.2.3.GA_mc_pg}\springside4-4.2.3.GA\support\maven-archetype\src\main\resources\archetype-resources 下的相应模板文件

2.运行 {springside4-4.2.3.GA_mc_pg}\springside4-4.2.3.GA\support\maven-archetype下的install.bat文件，出现 {springside4-4.2.3.GA_mc_pg}\springside4-4.2.3.GA\support\maven-archetype\target对应的quickstart-archetype-4.2.3-GA.jar等文件

3.运行 {springside4-4.2.3.GA_mc_pg}\springside4-4.2.3.GA\generate-project.bat 就能生成项目了 



备注：

1.此目录下，已完成上述操作，可以直接生成项目了

2.{springside4-4.2.3.GA_mc_pg}\springside4-4.2.3.GA\installmvnjar_ly.bat安装相应的mvn jar包用

3.生成项目时，数据表的前缀可以使用"_"这个符号,如 lr_ 

4.生成项目后，修改 application.properties 下的数据库文件相应信息

 #postgresql
 jdbc.driver=org.postgresql.Driver
 #先创建你的数据库
 jdbc.url=jdbc:postgresql://localhost:5432/你的数据库名
 jdbc.username=postgres
 jdbc.password=********




--EOF--