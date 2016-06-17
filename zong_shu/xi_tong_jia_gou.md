## 系统架构

图1.3-1 系统架构图

SOMA系统包括Controller、M&A、Node、Redis、Resource Store和CMDB等部分组成。

Controller为中心控制器，负责响应客户端的请求接入，调度各个功能组件协同工作。

M&A为监控分析服务器，负责收集、分析监控数据和业务数据。

Node为节点上的代理执行器，负责执行任务。

Resource Store为资源库，负责存放资源，如软件安装介质、虚机模板等。

CMDB为控制数据库。

应用管理平台的基于WEB管理门户，提供基于REST-like的API,以开放API的形式对应用管理平台的管理资源提供服务。

图1.3-2Controller架构图