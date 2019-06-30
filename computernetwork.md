# 计算机网络基础

- [计算机网络概述](computernetwork-description)
- [计算机网络-物理层](computernetwork-physical-layer)
- [计算机网络-数据链路层](computernetwork-link-layer)
- [计算机网络-网络层](computernetwork-network-layer)
- [计算机网络-传输层](computernetwork-transmision-layer)
- [计算机网络-应用层](computernetwork-application-layer)

# 计算机网络复习脉络

```c
复习方法：反复理解记忆，多问为什么，物理层几乎不需要掌握。

1. TCP/IP协议体系的认知
2. 数据链路层
	（1）以太网帧格式
	（2）MTU的概念
	（3）ARP协议和RARP协议（严格上说ARP协议归类于网络层），掌握ARP缓存的原理
3. 网络层
	（1）掌握IP的首部格式
	（2）掌握IP的分片
	（3）掌握IP的选路，即路由表
	（4）ICMP协议
		1) 掌握报文格式
		2）分类：查询+差错
		3）两种+五种
4.传输层
	（1）UDP，次要一点，掌握特点和首部各个字段
	（2）掌握TCP
		1）特点+首部字段+传输可靠机制
		2）连接控制：三次握手，四次挥手，同时打开，同时关闭，半关闭
		3）流量控制机制：滑动窗口，慢启动，拥塞控制，快速重传，快速恢复
		4）超时重传机制
5.应用层
	（1）掌握DNS协议
		1）名字空间
		2）指针查询（反向查找或逆向解析）基本原理
		3）DNS协议
	（2）FTP协议
		1）控制流和数据流
		2）两种工作模式：PASV和PORT
		3）各种指令和响应码
		4）断点重传和匿名FTP的概念
	（3）HTTP协议
		1）报文格式：请求报文，响应报文，请求头各种字段，响应头各种字段
		2）HTTP的状态码
	（4）HTTPS协议
		1）握手的详细过程
		2）摘要算法，数字签名，数字证书的原理和过程
```

# 计网面试题

附件：<a href="https://docsify-1258928558.cos.ap-guangzhou.myqcloud.com/computer-network-interview.pdf" download="计算机网络面试.pdf">计算机网络面试题总结.pdf</a>

<br/>
<br/>

**作者信息**
* 个人博客：https://bestzuo.cn
* Github：https://github.com/Sanarous
* 邮箱：zuoxiang@whut.edu.cn