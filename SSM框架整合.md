# SSM框架整合

### Maven

##### 1.安装Maven

1. 下载解压
2. 更改配置
   - 更改配置文件，设置本地仓库路径存储jar包
   - 设置镜像，提高下载速度
   - 指定jdk版本
3. 将maven添加到eclipse

##### 2.新建maven工程

![image-20200606155123276](../WorkRecord/学习区/SSM框架整合——图片集/image-20200606155123276.png)

##### 3.poom.xml配置文件

![image-20200606163111672](../WorkRecord/学习区/SSM框架整合——图片集/image-20200606163111672.png)

##### 4.maven仓库

https://mvnrepository.com/

### TomCat

##### 1.下载解压

##### 2.在eclipse上配置

### 新建web项目

##### 开始

1. 生成web.xml文件
2. 添加tomcat运行环境

##### 导入依赖

- Spring
- SpringMVC
- mybatis
- mysql
- c3p0连接池
- spring-jdbc
- junit
- log4j
- …

##### 编写配置文件

###### spring配置文件

bean.xml配置文件

​	-需要在启动项目时，解析配置文件

​	所以需要在web.xml文件中，添加启动配置

###### springMVC配置文件

###### mybatis配置文件



