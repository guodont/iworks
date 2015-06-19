# iWorks

##简介
>iWorks面向大学师生，提供收发电子作业的服务。

>在这里，你可以注册成为学生用户，注册并审核成功后可以关注自己的教师，收取教师发的教学动态或者布置的电子作业，和教师进行互动，以化简以往交电子作业的方法，还可以加强自己的课程学习。
  
>当然，如果你是教师，你也可以注册成为教师用户，审核成功后，你可以在iworks向学生发布作业、分享资源、解答学生提问、收取作业等等，总之，一切为了学生，简化您的工作，让您更高效地工作，提升在学生中的热度。

##项目开发文档
  见[/doc](https://github.com/guodont/iworks/tree/master/doc) 
  
### android client [iworks-android](https://github.com/guodont/iworks-android)
### web [iworks-web](https://github.com/guodont/iworks-web)

##项目架构与规范
###server：
  
  + 开发：
    ruby on rails (api/back-end) + mysql(database) 
  
  + 测试及文档生成：
    rails api docs[swagger-docs](https://github.com/richhollis/swagger-docs)

  + 代码规范(未完成)

###web-front-end

  + 开发：  
    angularjs+html+css+js(front-end)

  + 框架：
    angularjs+bootstrap
  
  + 开发工具：
    + 前端包管理工具[bower](http://bower.io/)
    + 前端自动化工具[grunt](http://www.gruntjs.net/)

###android-client

  + 开发：
    android4.2+ + java 
  
  + 开发工具：
    android studio 

  + 代码规范(未完成)

###第三方服务

  + [七牛云存储QINIU](http://www.qiniu.com/) 
    + android-sdk [link](https://github.com/qiniu/android-sdk)
    + javascript-sdk [link](https://github.com/qiniu/js-sdk)
    + ruby-sdk [link](https://github.com/qiniu/ruby-sdk)
  
