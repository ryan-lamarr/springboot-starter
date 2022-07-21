# springboot-starter
快速完成springboot项目搭建

1. 安装jdk
2. 安装maven
3. 安装mysql
4. 初始化springboot项目



### Maven安装与配置（Windows环境）
- 解压maven到自定义目录
- 配置环境变量  
  添加环境变量MAVEN_HOME: D:\Toolkit\apache-maven-3.8.6  
  在系统Path中配置maven的bin文件夹路径：%MAVEN_HOME%\bin
### 附：linux环境maven安装
解压maven的.tar文件  
```
# tar -xvf  apache-maven-3.8.6-bin.tar.gz
# sudo mv -f apache-maven-3.8.6 /usr/local/
```
设置linux环境变量，编辑 /etc/profile 文件  
```
# sudo vim /etc/profile
```  
在文件末尾添加如下代码：  
```
export MAVEN_HOME=/usr/local/apache-maven-3.8.6  
export PATH=${PATH}:${MAVEN_HOME}/bin
```
