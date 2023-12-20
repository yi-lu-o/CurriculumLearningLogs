# 计算机网络考前学习

## 学习时间记录：

1. 11月30日 17：00-18：00，近1h
1. 12月1日 10：00-12：00，近2h,进度：看完速成课p1-p10
1. 12月1日 13：30-15：00，近1.5h,进度：看完速成课p11-p14
1. 12月1日 21：35-23：05，近1.5h,进度：看完了自己需要的网课部分
1. 12月3日 12：55-14：15，近80min,进度：看计算机网络大题速成课

## 计算机网络概念

![image-20231201101026579](images/image-20231201101026579.png)

## 计算机网络体系结构

![image-20231201103542591](images/image-20231201103542591.png)

### OSI参考模型

![image-20231201103932124](images/image-20231201103932124.png)

![image-20231201115723590](images/image-20231201115723590.png)

**OSI七层参考模型的作用：**

物理层：在连接各种计算机的传输媒体上传输数据比特流

数据链路层：实现相邻网络实体间的数据传输

网络层：将数据包跨越网络从源设备发送到目的设备（host to host）

传输层：将数据从源端口发送到目的端口（进程到进程）

会话层：在应用程序之间建立和维持会话，并能使会话获得同步

表示层：关注所传递信息的语法和语义，管理数据的表示方法，传输的数据结构

应用层：通过应用层协议，提供应用程序便捷的网络服务调用

**核心思想：下层为上层服务**

### TCP/IP参考模型

![image-20231201105233615](images/image-20231201105233615.png)

## 物理层的基本概念

#### 物理层四大特性

![image-20231201111527042](images/image-20231201111527042.png)

### 物理层的两种信号

![image-20231201111607643](images/image-20231201111607643.png)

### 调制与编码

![image-20231201111652935](images/image-20231201111652935.png)

### 传输介质

![image-20231201111749135](images/image-20231201111749135.png)

### 物理层相关的三大部分

![image-20231201111839000](images/image-20231201111839000.png)

### 物理层基本通信技术

#### 复用技术

![image-20231201112347552](images/image-20231201112347552.png)

#### 四种信道复用技术

![image-20231201113112221](images/image-20231201113112221.png)

#### 数据传输方式

##### 并行/串行传输

![image-20231201113712930](images/image-20231201113712930.png)

##### 同步/异步传输

![image-20231201113751600](images/image-20231201113751600.png)

##### 其他传输方式

![image-20231201114146406](images/image-20231201114146406.png)

## 数据链路层

### 数据链路层基础概论

![image-20231201140318596](images/image-20231201140318596.png)

数据链路层概念：数据链路层是在物理层和网络层之间的协议，提供相邻结点的可靠数据传输。

MAC地址：每一张网卡的48位**独一无二**的地址

帧

![image-20231201133712812](images/image-20231201133712812.png)

### 数据链路层的通信协议

#### 冲突域和广播域

![image-20231201142815255](images/image-20231201142815255.png)

#### 虚拟局域网

![image-20231201142850524](images/image-20231201142850524.png)

#### 其他

![image-20231201142917292](images/image-20231201142917292.png)

## 网络层

网络层的作用：提供点到点的服务

![image-20231201215014692](images/image-20231201215014692.png)

网际层协议IP

![image-20231201215143706](images/image-20231201215143706.png)

### IP地址

![image-20231201215246490](images/image-20231201215246490.png)

#### IP地址的组成

![image-20231201222505468](images/image-20231201222505468.png)

#### IP地址的分类

![image-20231201222640017](images/image-20231201222640017.png)

## 概念

网桥：一种桥接器，连接两个局域网的一种存储/转发设备。

## 重要图

![image-20231205144757266](images/image-20231205144757266.png)

### 子网划分：均分

![image-20231207102104372](images/image-20231207102104372.png)

### 子网划分：不均分

![image-20231207105922729](images/image-20231207105922729.png)

### 数据报分片

![image-20231207130728888](images/image-20231207130728888.png)

![image-20231207131035166](images/image-20231207131035166.png)

### 路由表更新

![image-20231207140404709](images/image-20231207140404709.png)

![image-20231207140944982](images/image-20231207140944982.png)

### 拥塞避免算法

![image-20231207145028537](images/image-20231207145028537.png)

![image-20231207145238897](images/image-20231207145238897.png)