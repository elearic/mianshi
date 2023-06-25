##  eureka

​			eureka-client：客户端

​			eureka-server:  服务端

​		服务注册:

​			微服务启动的时候，调用server的REST API的  register方法，进行服务注册

​		服务下线：

​		    微服务关闭的时候，通过钩子函数或者其他生命周期的回调方法调用server的de-register			方法，来删除自身服务实例的信息。

​			异常下线：

​			client注册后，会定时发送心跳，若client异常，则server会在服务注册表主动提出client

​		服务续约

​			client 向 server定时发送心跳

​		自我保护机制

​		

## feign

​			声明式的WebService客户端





Ribbon



Zuul



Gateway



