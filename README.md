# soft-book

* [微服务架构 - Microservice Architecture](./MicroserviceArchitecture/README.md)
  * 常用微服务模式
    * 聚合器微服务设计模式
    * 代理微服务设计模式
    * 链式微服务设计模式
    * 分支微服务设计模式
    * 数据共享微服务设计模式
    * 异步消息传递微服务设计模式
  * [微服务框架/RPC框架](MicroserviceArchitecture/MicroserviceFramework/README.md)
    * Spring Cloud
    * Dubbo
    * brpc/baidu-rpc
    * Tars
    * ServiceComb
  * 服务治理
    * 服务注册与发现：Eurake，Dobbo，Consul，ZooKeeper
    * 服务配置：Spring Cloud Config，Archaius
    * 服务熔断：Hystrix，resilience4j
    * 网关：Zuul，Spring Cloud Gateway
    * 负载均衡：Ribbon，Feign
    * 追踪工具：Sleuth，Zipkin，Htrace
    * 日志采集：ElasticSearch,logback，
    * 监控平台：Promethues，Kibana，grafna，Spring boot admin
* [分布式系统](DistributedSystem/README.md)
  * 设计原则
    * [CAP](DistributedSystem/cap.md)
    * BASE
* Unix
  * [网络编程中的五种IO模型](Unix/NIO/README.md)
    1. Blocking IO - 阻塞IO
    2. NoneBlocking IO - 非阻塞IO
    3. IO multiplexing - IO多路复用
    4. signal driven IO - 信号驱动IO
    5. asynchronous IO - 异步IO
* Java
  * JVM