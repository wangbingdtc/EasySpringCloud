# Zipkin Server

Sleuth 和 Zipkin 分布式服务追踪系统(Distributed Systems Tracing System)。

支持：
- HTTP 收集器 + Mem 存储
- Kafka 收集器 + Mem 存储
- RabbitMQ 收集器  + Mem 存储
- Kafka 收集器 + ElasticSearch 存储
- RabbitMQ 收集器 + ElasticSearch 存储



## 需求

JRE 8+

- 可能需要
    - Kafka
	- RabbitMQ 
	- ElasticSearch 

## 启动

Run `.bat` or `.sh`.

## 访问 UI

`http://your_host:9411/zipkin/`

## EasySpringCloud

**EasySpringCloud 所有的项目默认均使用 Kafka 作为收集器。**

# END

