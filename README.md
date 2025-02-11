# Video-blogger-recommendation-system
这是一个基于朴素贝叶斯的视频博主推荐系统，数据是从bilibili抓取的，相关数据集来自模拟生成。
一.开发工具

IDEA版本: IntelliJ IDEA 2023.2.1

pythram:  PyCharm Community Edition 2023.3.4

Vue版本: 2.6.14

vue/cli 版本: 5.0.8

npm版本: 10.5.2

node.js版本: 21.6.0

JDK版本: jdk17

MySQL版本: 8.3.0

理数据库管理工具:  Navicat Premium 16

二.部署过程
1.	可以打开navicat创建好数据库,然后执行sql文件将相关表导入数据库中
操作步骤如下:
  ![image](https://github.com/user-attachments/assets/8d81cb9a-8bf2-4358-b114-2bf42d548bad)
![image](https://github.com/user-attachments/assets/a7e6851c-6853-4c93-be7c-9835e49c361a)


2.打开python脚本,导入所需的包

(1)	使用到的关键第三方库为bilibili_api,导入指令为:$ pip3 install bilibili-api-python

所需的包如下所示:
   ![image](https://github.com/user-attachments/assets/0367e4af-c927-457e-bd92-356bdfbc1032)


 (2)相关开发文档地址:[bilibili-api 开发文档 (nemo2011.github.io)](https://nemo2011.github.io/bilibili-api/#/)

2.	使用idea打开后端项目文件,点击pom.xml文件夹更新相关的依赖.需要注意的是记得在application.yml更新自己的数据库配置.


3.	可以使用idea打开前端项目文件

首次运行时,除了使用命令行运行之外,可以直接点击此处运行前端服务.
 ![image](https://github.com/user-attachments/assets/b41d862b-ef00-4bca-b55f-259cfceacd34)


5.先启动后端项目,在启动前端项目,这样可以避免你的电脑端口默认设置导致的端口冲突.

三.相关功能使用介绍

用户端使用方式:
![image](https://github.com/user-attachments/assets/5c415bc0-0d67-4420-aef2-1c4fbcbfd26b)

  ![image](https://github.com/user-attachments/assets/713f662d-678b-432f-a010-7c061f0ff699)


管理员使用方式:
 ![image](https://github.com/user-attachments/assets/7dabc15a-2c0e-46e5-b0cf-b5fd5a96116b)

