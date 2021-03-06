# 计算机网络

本内容整理自计算机学科专业基础综合考试大纲中的 **计算机网络** 部分。

### 目标

- 掌握计算机网络的基本概念、基本原理和基本方法。
- 掌握计算机网络的体系结构和典型网络协议，了解典型网络设备的组成和特点，理解典型网络设备的工作原理。
- 能够运用计算机网络的基本概念、基本原理和基本方法进行网络系统的分析、设计和应用。

### 计算机网络体系结构

- 计算机网络概述
  - 计算机网络的概念、组成与功能
  - 计算机网络的分类
  - 计算机网络主要性能指标
- 计算机网络体系结构与参考模型
  - 计算机网络分层结构
  - 计算机网络协议、接口、服务等概念
  - ISO/OSI 参考模型和 TCP/IP 模型

### 物理层

- 通信基础
  - 信道、信号、宽带、码元、波特、速率、信源与信宿等基本概念
  - 奈奎斯特定理与香农定理
  - 编码与调制
  - 电路交换、报文交换与分组交换
  - 数据报与虚电路
- 传输介质
  - 双绞线、同轴电缆、光纤与无线传输介质
  - 物理层接口的特性
- 物理层设备
  - 中继器
  - 集线器

### 三、数据链路层

- 数据链路层的功能
- 组帧
- 差错控制
  - 检错编码
  - 纠错编码
- 流量控制与可靠传输机制
  - 流量控制、可靠传输与滑轮窗口机制
  - 停止-等待协议
  - 后退 N 帧协议（GBN）
  - 选择重传协议（SR）
- 介质访问控制
  - 信道划分
    - 频分多路复用
    - 时分多路复用
    - 波分多路复用
    - 码分多路复用
  - 随即访问
    - ALOHA 协议
    - CSMA 协议
    - CSMA/CD 协议 CSMA/CA 协议
  - 轮询访问
    - 令牌传递协议
- 局域网
  - 局域网的基本概念与体系结构
  - 以太网与 IEEE 802.3
  - IEEE 802.11
  - 令牌环网的基本原理
- 广域网
  - 广域网的基本概念
  - PPP 协议
  - HDLC 协议
- 数据链路层设备
  - 网桥的概念和基本原理
  - 局域网交换机及其工作原理。

### 网络层

- 网络层的功能
  - 异构网络互联
  - 路由与转发
  - 拥塞控制
- 路由算法
  - 静态路由与动态路由
  - 距离-向量路由算法
  - 链路状态路由算法
  - 层次路由
- IPv4
  - IPv4 分组
  - IPv4 地址与 NAT
  - 子网划分与子网掩码、CIDR
  - ARP 协议、DHCP 协议与 ICMP 协议
- IPv6
  - IPv6 的主要特点
  - IPv6 地址
- 路由协议
  - 自治系统
  - 域内路由与域间路由
  - RIP 路由协议
  - OSPF 路由协议
  - BGP 路由协议
- IP 组播
  - 组播的概念
  - IP 组播地址
- 移动IP
  - 移动 IP 的概念
  - 移动 IP 的通信过程
- 网络层设备
  - 路由器的组成和功能
  - 路由表与路由转发

### 传输层

- 传输层提供的服务
  - 传输层的功能
  - 传输层寻址与端口
  - 无连接服务与面向连接服务
- UDP 协议
  - UDP 数据报
  - UDP 校验
- TCP 协议
  - TCP 段
  - TCP 连接管理
  - TCP 可靠传输
  - TCP 流量控制与拥塞控制

### 六、应用层

- 网络应用模型
  - 客户/服务器模型
  - P2P 模型
- DNS 系统
  - 层次域名空间
  - 域名服务器
  - 域名解析过程
- FTP
  - FTP 协议的工作原理
  - 控制连接与数据连接
- 电子邮件
  - 电子邮件系统的组成结构
  - 电子邮件格式与 MIME
  - SMTP 协议与 POP3 协议
- WWW
  - WWW 的概念与组成结构
  - HTTP 协议
