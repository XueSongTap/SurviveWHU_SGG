# 叶小川

yxc2020@whu.edu.cn

180-3695-3166 (微信同号)

## 教育背景

武汉大学（985）– 资源与环境（测绘工程）  硕士

高精度位置感知研究中心

研究方向：点云处理、三维感知

河海大学（211）- 计算机科学与技术（辅修）/ 水利类强化班 学士


## 实习经历

### 后摩智能 AI解决方案研发中心 自动驾驶算法工程化实习生
apollo7.0 protobuf bazel

### 武汉众向科技--研发中心--C++开发实习生

ros melodic ubuntu18.04 cmake 
基于ROS/CMake的IMU姿态解算模块的开发

实现了IMU板卡的UART串口非阻塞的序列化读写驱动

完成了基于加速计、陀螺仪数据的实时卡尔曼滤波,互补滤波算法的四元数姿态解算节点

在激光SLAM方案下通过ROS topic同步位姿信息，与激光里程计等模块进行耦合，取得较好的定位效果

## 项目经历


### cpp项目

#### 基于pdal库大规模点云层次化索引的高性能服务器
利用Octree将大规模离散点云数据进行层次化索引，发布成为http文件服务


使用cjson进行点云索引的存储和解析

利用IO复用技术Epoll与线程池实现多线程的Reactor高并发模型，可以发布上亿点云数据

使用状态机解析http请求报文，支持解析GET/POST请求

通过potree等前端服务的接口可以很好完成web端的点云层次化渲染任务


#### 基于C++17的TCP协议的实现

实现程序模块化,实现TCP发送方和接送方之间之间间进行数据通信、连接建立

编写有序字节流类,模拟通信双方发送的字节流内容,具有容量上限，支持读写和容量控制

实现基于滑动窗口协议的TCP接收端, 能够实现可靠有序的接收

实现基于滑动窗口协议的TCP发送端类, 能根据接收端发送来的报文限制窗口大小实现流量控制

实现TCPConnection类,结合了TCPSender和TCPReceiver,与其他TCP实现对话

实现Router路由器类,他能够跟踪路由表(转发规则或路由列表) ,并转发它收到的每个数据报

#### c++高性能分布式服务器框架

sylar

https://github.com/sylar-yin/sylar

webserver,websocket server,自定义tcp_server（包含日志模块，配置模块，线程模块，协程模块，协程调度模块，io协程调度模块，hook模块，socket模块，bytearray序列化，http模块，TcpServer模块，Websocket模块，Https模块等, Smtp邮件模块, MySQL, SQLite3, ORM,Redis,Zookeeper)


#### 基于fastdfs的分布式云盘

fastdfs  nginx mysql redis qt

上传 下载 秒传

https://github.com/foshougua/network-dash

一、实现安全登录 二、实现大文件的快速上传和下载 三、实现大文件的秒传功能 四、实现文件的增量上传 五、实现文件时光机功能

#### 基于drogon框架的xxx应用


https://github.com/drogonframework/drogon/blob/master/README.zh-CN.md

https://github.com/drogonframework/drogon-website

https://github.com/0rangeFox/Drogon-JWT-Filter-example

#### 简单的关系型数据库

https://github.com/cmu-db/bustub


#### 基于c++的分布式文件系统
https://github.com/foreverhy/yfs


#### 基于protobuf的轻量化rpc
https://github.com/baidu/sofa-pbrpc/wiki

https://github.com/chenyahui/AnnotatedCode/tree/master/sofa-pbrpc

#### 基于c++11的STL实现
mytinystl
#### 优化/定制c++ stirng

例如folly库的fbstring

https://zhuanlan.zhihu.com/p/348614098

#### jieba分词的cpp实现

https://github.com/yanyiwu/cppjieba


#### 基于文本检索的轻量级搜索引擎
https://github.com/stdbilly/SearchEnigine


### 基于c++的模型部署平台

https://github.com/gdyshi/model_deployment

### java项目

#### 基于 Netty 的简易 RPC 框架实现

 实现轻量级 RPC 框架，使得客户端可以通过网络从远程服务端程序上请求服务

 在客户端实现了基于一致性哈希算法的负载均衡

 动态代理部分使用 JDK 动态代理

 网络传输部分使用 http 协议进行传输


#### 基于monogodb的地图数据存储与高并发地图找房
kafka netty mongodb docker

完成地图数据收集和存储

mongodb分布式存储 实现地图数据存储

高并发netty接受用户请求，发到kafka集群


#### 基于springboot外卖平台
sprintboot mysql mybatis maven lombok spring session redis

本项目（瑞吉外卖）是专门为餐饮企业（餐厅、饭店）定制的一款软件产品，包括系统管理后台和移动端应用两部分。其中系统管理后台主要提供给餐饮企业内部员工使用，可以对餐厅的分类、菜品、套餐、订单、员工等进行管理维护。移动端应用主要提供给消费者使用，可以在线浏览菜品、添加购物车、下单等。

乐观锁 


https://gitee.com/itxinfei/reggie




### python项目

#### 基于主动学习的点云语义标注

#### 基于seggroup的点云语义分割


#### 基于open3d的点云八叉树索引


#### 基于Django的博客系统

https://github.com/liangliangyy/DjangoBlog


https://github.com/wsvincent/awesome-django



#### 基于django的谷里学院 

https://www.bilibili.com/video/BV1qb411P7XQ/?vd_source=7371452b85fe4d187885825b04f8393a
#### 基于Django的地理信息系统

能更容易与地理信息系统项目协作的包。

django-geoposition, star:261 - 一个数据模型项，可用来保存地理信息(经度/纬度)，并提供相应的后台管理/表单组件。
django-location-field, star:266 - 一个位置项及其组件，并与 google 地图集成。
django-spillway, star:42 - Django REST 框架的 Geodata 扩展。
djangorestframework-gis, star:372 - Django REST 框架的地理信息扩展。

#### 基于flask的个人博客系统
https://github.com/longzx-9527/flask_spider


https://github.com/happyte/flask-blog

https://github.com/CoreyMSchafer/code_snippets/tree/master/Python/Flask_Blog



#### 基于flask的深度学习图像识别部署系统

https://github.com/jiajunhua/StevenLei2017-AI_projects

https://www.bilibili.com/video/BV1M4411n789/?vd_source=7371452b85fe4d187885825b04f8393a


https://leovan.me/cn/2018/10/serving-models-with-flask-and-gae/

### 基于flask vue的Yolov5模型部署系统

https://github.com/liuxiaoxiao666/Yolov5-Flask-VUE

### 嵌入式项目

## IT 技能

### cpp版本

熟悉C++语言，具有良好的编码规范，掌握多态的实现、智能指针的使用、重载与覆写问题等

掌握linux, Docker常用命令, 会使用vim, 握gdb调试技能，能够编写makefile，cmake编译指令

熟悉HTTP,DNS,TCP,UDP等协议，掌握TCP/UDP套接字编程

掌握基础的数据结构算法及STL容器，能够在项目中使用deque、vector、map等进行开发

了解Git使用，可以很好完成协同开发工作

了解常见的SQL查询语言，数据库索引，事务原理和锁机制


### java版本

 熟练掌握 Java 基础，集合等相关知识，了解常见设计模式，熟悉 Spring，SpringBoot 等常用框架

 了解 C++继承、封装、多态三大特征

 熟悉 OSI 层模型和 TCP/IP 四层体系分层结构，掌握常见网络协议，如 HTTP、TCP 等

 熟悉操作系统的进程通信、死锁、内存管理等知识

 掌握 linux、Docker 常用命令，如 netstat、grep、top、chmod、find 等

 掌握基础的数据结构算法，能够在项目中使用栈、队列、map、堆等数据结构进行开发

 了解 Git 使用，可以很好完成开发工作

 了解 Mysql 索引、事务、锁

## 获奖/证书等

CET-6 649，托福 97 
全国大学生数学建模大学国家级二等奖
蓝桥杯省级Java程序设计A组三等奖
国家奖学金