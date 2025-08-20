<p><h1 align="center"> 基于Java+SpringBoot及thymeleaf的疫情信息管理系统</h1></p>

- <b>完整代码获取地址：从戎源码网 ([https://armycodes.com/](https://armycodes.com/))</b>
- <b>技术探讨、资料分享，请加QQ群：692619798</b> 
- <b>作者微信：19941326836  QQ：952045282</b> 
- <b>承接计算机毕业设计、Java毕业设计、Python毕业设计、深度学习、机器学习</b>
- <b>选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 一条龙服务</b>
- <b>所有选题地址 ([https://github.com/YuLin-Coder/AllProjectCatalog](https://github.com/YuLin-Coder/AllProjectCatalog)) </b>

## 一、系统介绍

疫情信息管理系统应当具备两种对象，疫情管理员对象可以对确诊患者、密切接触者、死亡患者、治愈患者的信息进行管理操作，

系统管理员对象在疫情管理员对象的功能基础上可以对系统登录用户进行增删改查。针对需求分析设计了具体模块，系统功能模块图如下图所示。

![contents](./picture/picture12.png)


抗疫管理员登录后可以进行确诊患者管理、密切接触者管理、死亡管理、治愈管理，同时可以看到数据面板的数据变化与动态图。系统管理员除了拥有抗疫管理者的权限，还可以对抗疫管理员进行管理。

密切接触者可以转换成确诊患者；确诊患者可以转换成死亡患者或者治愈患者，业务流程图如下图2-1。

![contents](./picture/picture13.png)

## 二、所用技术

SpringSecurity SpringBoot Mysql Mybatis Thymeleaf  echarts


## 三、环境介绍

基础环境 :IDEA/eclipse, JDK 1.8 , Mysql,

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图

![contents](./picture/picture1.png)

![contents](./picture/picture2.png)

![contents](./picture/picture3.png)

![contents](./picture/picture4.png)

![contents](./picture/picture5.png)

![contents](./picture/picture6.png)

![contents](./picture/picture7.png)

![contents](./picture/picture8.png)

![contents](./picture/picture9.png)

![contents](./picture/picture10.png)

![contents](./picture/picture11.png)

## 五、浏览地址

前端访问地址：http://localhost:8002/indexpage

管理员账号/密码：Admin/123456  

## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
   若为maven项目，导入成功后请执行maven clean;maven install命令，然后运行；
   



