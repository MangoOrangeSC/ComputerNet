# 计算机网络

## 第一章 计算机网络体系结构

### 1.1 计算机网络的概念

![image1](pic/pic1.png)

![image1](pic/pic2.png)

### 1.2 计算机网络的组成


![image1](pic/pic3.png)
![image1](pic/pic4.png)
![image1](pic/pic5.png)

### 1.3 计算机网络的分类

![image1](pic/pic6.png)



![image1](pic/pic7.png)

### 1.4 标准化

![image1](pic/pic8.png)

### 1.5 性能指标

#### 1 速率
![image1](pic/pic9.png)

#### 2 带宽

![image1](pic/pic10.png)

#### 3 吞吐量

![image1](pic/pic11.png)

#### 4 时延

发送时延

![image1](pic/pic12.png)
![image1](pic/pic13.png)

传播时延

排队时延、处理时延：路由器

![image1](pic/pic14.png)
高速链路：提高发送速率，提高带宽，传播速率不变



#### 5 时延带宽积

![image1](pic/pic15.png)
描述信息量的属性



#### 6 往返时延RTT

![image1](pic/pic16.png)

#### 7 利用率
![image1](pic/pic17.png)
![image1](pic/pic18.png)

### 1.6 分层结构、协议、接口、服务

![image1](pic/pic19.png)
![image1](pic/pic20.png)

- 协议：水平方向，对等实体间有协议
- 接口：两层之间
- 服务：上层使用下层服务



![image1](pic/pic21.png)

服务是单向的

![image1](pic/pic22.png)
![image1](pic/pic23.png)


### 1.7 OSI参考模型



![image1](pic/pic24.png)
![image1](pic/pic25.png)
![image1](pic/pic26.png)
![image1](pic/pic27.png)

中间系统：路由器

中间系统没有上面4层，好像是直接通信，所以是端到端

下面三层只管与下一个中间系统，所以是点对点

![image1](pic/pic28.png)

数据链路层加了首部和尾部

因为同层协议相同，所以可以去掉首部



#### 应用层

![image1](pic/pic29.png)

联网才能用的东西

文件传输：FTP

电子邮件：SMTP

万维网：HTTP

#### 表示层

![image1](pic/pic30.png)

显示

JPEG ASCII

#### 会话层

![image1](pic/pic31.png)

#### 传输层

![image1](pic/pic32.png)

每个进程都有一个端口号，端到端

可靠传输：建立链接，确认机制；接收方需要返回确认信息

不可靠传输：

TCP UDP

#### 网络层

![image1](pic/pic33.png)

网际互联

#### 数据链路层

![image1](pic/pic34.png)

#### 物理层

![image1](pic/pic35.png)
![image1](pic/pic36.png)


### 1.8 TCP、IP参考模型

![image1](pic/pic37.png)
![image1](pic/pic38.png)

![image1](pic/pic39.png)
![image1](pic/pic40.png)
![image1](pic/pic41.png)
![image1](pic/pic42.png)

## 第二章 物理层

![image1](pic/pic43.png)

### 2.1 物理层概念

![image1](pic/pic44.png)
![image1](pic/pic45.png)

### 2.2 数据通信基础知识

![image1](pic/pic46.png)
![image1](pic/pic47.png)
![image1](pic/pic48.png)
![image1](pic/pic49.png)
![image1](pic/pic50.png)

通信方式是在确定谁为发送方，谁为接受方

![image1](pic/pic51.png)

数据在信道上的传输方式

![image1](pic/pic52.png)
![image1](pic/pic53.png)

### 2.3 码元、速度、波特、带宽

![image1](pic/pic54.png)
![image1](pic/pic55.png)

1 Baud = 1码元/s

![image1](pic/pic56.png)
![image1](pic/pic57.png)
![image1](pic/pic58.png)


### 2.4 奈氏准则、香农定理

### 2.5 编码、调制

### 2.6 物理层传输介质

### 2.7 物理层设备

#### 中继器

![image1](pic/pic59.png)

衰减信号再生放大

两端是网段、不是子网

不超过5个网段、最多有4个物理层设备、只有三个段可以链接计算机

#### 集线器

![image1](pic/pic60.png)

集线器：广播

## 第三章 数据链路层
![image1](pic/pic61.png)
### 3.1 概述

![image1](pic/pic62.png)

水平发送

![image1](pic/pic63.png)
![image1](pic/pic64.png)
![image1](pic/pic65.png)

### 3.2 封装成帧、透明传输



### 3.3 差错控制



### 3.4 流量控制



### 3.5 介质访问控制



### 3.6 局域网


![image1](pic/pic66.png)
![image1](pic/pic67.png)
![image1](pic/pic68.png)
![image1](pic/pic69.png)
![image1](pic/pic70.png)

wifi是wlan的一种



![image1](pic/pic71.png)
![image1](pic/pic72.png)
![image1](pic/pic73.png)

#### 以太网

![image1](pic/pic74.png)
![image1](pic/pic75.png)
![image1](pic/pic76.png)
![image1](pic/pic77.png)
![image1](pic/pic78.png)

MAC地址，随着网卡

![image1](pic/pic79.png)
![image1](pic/pic80.png)
![image1](pic/pic81.png)
![image1](pic/pic82.png)

#### 无线局域网

![image1](pic/pic83.png)
![image1](pic/pic84.png)
![image1](pic/pic85.png)
![image1](pic/pic86.png)
![image1](pic/pic87.png)
![image1](pic/pic88.png)

### 3.7 广域网

### 3.8 链路层设备

#### 网桥、交换机

![image1](pic/pic89.png)

冲突域：同一区域同一时刻只能一个设备通信

![image1](pic/pic90.png)
![image1](pic/pic91.png)
![image1](pic/pic92.png)
![image1](pic/pic93.png)
![image1](pic/pic94.png)
![image1](pic/pic95.png)
![image1](pic/pic96.png)
![image1](pic/pic97.png)



## 第四章 网络层

### 4.1 网络层功能

![image1](pic/pic98.png)

异构网络互联：路由器

### 4.2 数据交换方式



### 4.3 IP

#### 431 IP数据报格式
![image1](pic/pic99.png)
![image1](pic/pic100.png)

数据部分是传输层的

![image1](pic/pic101.png)

#### 432 IP数据报分片

![image1](pic/pic102.png)
![image1](pic/pic103.png)
![image1](pic/pic104.png)
![image1](pic/pic105.png)

#### 4.3.3 IPv4

![image1](pic/pic106.png)

标识主机或路由器

![image1](pic/pic107.png)
![image1](pic/pic108.png)

网络号：

主机号：

![image1](pic/pic109.png)

网络号：222.1.3.0

222.1.1.0

222.1.2.0

一个路由器有多个IP地址，每个接口都有一个IP地址

绿色区域为无编号网络

![image1](pic/pic110.png)
![image1](pic/pic111.png)
![image1](pic/pic112.png)
![image1](pic/pic113.png)


#### 434 网络地址转换（NAT）

![image1](pic/pic114.png)
![image1](pic/pic115.png)

端口号：传输层，标识进程

#### 435 子网划分、子网掩码

![image1](pic/pic116.png)
![image1](pic/pic117.png)
![image1](pic/pic118.png)

所有的145.13.x.x的数据报都会先到达路由器，然后在向下发送，具体发送方法，需要了解子网掩码

![image1](pic/pic119.png)

子网掩码：网络号1 主机号0

![image1](pic/pic120.png)
![image1](pic/pic121.png)
![image1](pic/pic122.png)

#### 436 五分类编制CIDR

#### 437ARP

#### 438 DHCP

#### 4.3.9 ICMP

### 4.4 IPv6



### 4.5 路由算法与路由协议

![image1](pic/pic123.png)
![image1](pic/pic124.png)
![image1](pic/pic125.png)

### 4.6 ip组播

### 4.7 移动ip

### 4.8 网络层设备



## 第五章 传输层



### 5.1 传输层概述
![image1](pic/pic126.png)

传输层：进程与进程

网络层：主机与主机

![image1](pic/pic127.png)

微信聊天一般都是UDP

![image1](pic/pic128.png)

端口：唯一标识主机中的进程，逻辑端口、软件端口

端口号：动态选择

![image1](pic/pic129.png)

套接字：主机+进程

### 5.2 UDP



### 5.3 TCP

