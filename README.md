# springCloud_MC
springcloud 微服务学习
## 项目来源
哔哩哔哩：尚硅谷2020最新版SpringCloud(H版&alibaba)框架开发教程全套完整版从入门到精通(大牛讲授spring cloud)
视频连接：https://www.bilibili.com/video/BV18E411x7eT
## 依赖版本
'''  

<properties>  
        
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>  
        
        <maven.compiler.source>1.8</maven.compiler.source>  
        
        <maven.compiler.target>1.8</maven.compiler.target>  
        
        <junit.version>4.12</junit.version>  
        
        <lombok.version>1.16.18</lombok.version>  
        
        <log4j.version>1.2.12</log4j.version>  
        
        <mysql.version>8.0.15</mysql.version>  
        
        <druid.version>1.1.12</druid.version>  
        
        <mybatis.spring.boot.version>2.1.2</mybatis.spring.boot.version>  
        
</properties>  

'''
### 具体可参考代码父pom中配置  

## Eureka服务注册与发现  
官网连接：https://docs.spring.io/spring-cloud-netflix/docs/2.2.5.RELEASE/reference/html/#service-discovery-eureka-clients  
https://docs.spring.io/spring-cloud-netflix/docs/2.2.5.RELEASE/reference/html/#spring-cloud-eureka-server  

## Zookeeper服务注册与发现  

未进行代码实现  

## Consul 服务注册与发现  

未进行代码实现  

## Ribbon 负载均衡服务调用  
官网连接：https://docs.spring.io/spring-cloud-netflix/docs/2.2.5.RELEASE/reference/html/#spring-cloud-ribbon  
客户端负载均衡 @LoadBlance
## OpenFeign 服务接口调用  
官网连接：https://docs.spring.io/spring-cloud-openfeign/docs/2.2.5.RELEASE/reference/html/
## Hystrix断路器  
官网连接：https://docs.spring.io/spring-cloud-openfeign/docs/2.2.5.RELEASE/reference/html/#spring-cloud-feign-hystrix  
实现服务降级，熔断，限流 @HystrixCommand
## zuul路由网关  

未进行代码实现(在他的旧版视频中讲过)  

## Gatway新一代网关  
官网连接：https://docs.spring.io/spring-cloud-gateway/docs/2.2.5.RELEASE/reference/html/#gateway-starter
## Spring Cloud Config 分布式配置中心  
官网连接：https://spring.io/projects/spring-cloud-config
## Spring Cloud Bus消息总线  
官网连接：https://spring.io/projects/spring-cloud-bus
## Spring Cloud Stream消息驱动  
官网连接：https://spring.io/projects/spring-cloud-stream
## Spring Cloud Sleuth分布式请求链路跟踪  
官网连接：https://spring.io/projects/spring-cloud-sleuth


## Spring Cloud Alibaba Nacos服务注册和配置中心  

官网连接：https://nacos.io/zh-cn/docs/quick-start.html  

官网连接：https://spring-cloud-alibaba-group.github.io/github-pages/hoxton/en-us/index.html#_spring_cloud_alibaba_nacos_discovery
## Spring Cloud Alibaba Sentinel实现熔断与限流  
官网连接：https://spring-cloud-alibaba-group.github.io/github-pages/hoxton/en-us/index.html#_spring_cloud_alibaba_sentinel
## Spring Cloud Alibaba Seata处理分布式事务  

未进行代码实现  

官网连接：https://github.com/seata/seata/  

