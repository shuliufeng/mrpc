# mrpc
 本项目用C++实现了一个简单的RPC分布式网络通信框架。
## mrpc介绍
1.	使用mymuduo网络库作为项目的网络核心模块，提供高并发网络IO服务；
2.	使用Protobuf作为数据序列化和反序列化的通信协议；
3.	采用ZooKeeper实现分布式服务注册和服务发现；
4.	基于线程安全的缓冲队列实现了异步日志；

## 平台工具

vscode远程Linux开发 + CMake构建 + Linux Shell输出项目编译脚本

## mrpc通信框架流程图
![image](https://user-images.githubusercontent.com/94746995/177962409-95d567e6-b129-4ff3-980c-4ef0494113cc.png)

