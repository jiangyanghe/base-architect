## 第十六章节 实例管理
	从资产 容器 应用各项管理来达到应用实例的管理  

### 16.1 资产管理
对硬件实体机或宿主机进行管理 创建主机 主机基础信息录入(cpu型号核数 内存大小 硬盘等等) 与容器存在依赖关系  

### 16.2 容器管理
对容器进行管理 一键创建删除容器 配置容器各参数(cpu核数 内存等) 与应用服务存在依赖关系 可通过服务治理中心直接创建容器并匹配到具体应用  

### 16.3 应用管理
分配容器给所需应用服务 包括各项优化参数等(jvm)  

### 16.4 弹性扩容
通过实例管理 来弹性的扩容实例机器 横向上下架硬件主机  
场景:  
1)举办活动 流量突发上涨  
2)需要一次性的离线计算 增强大数据的计算能力  
3)迁移文件数据需要副本主机  


 <a href="subject-15.md">上一章节</a>  <a href="subject-17.md">下一章节</a>