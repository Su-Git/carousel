# ms.carousel.config.properties
```properties
## 设置引擎执行线程池最大线程数。
## 线程池越大处理能力越高，但需要的系统资源也越多。
#carousel.engine.pool-size = 5

## 设置是否自动重启流程。
## 如果设置为true则启动时将自动重启启动所有未执行完成的流程。
## 在单一节点中，必须设置为true；
## 在集群环境中，必须有且只有一个节点被设置为true。
#carousel.engine.auto = true

## 设置流程最大失败次数。
## 如果流程执行失败次数超过设置值，则该流程将不再被执行。
#carousel.process.max-failure = 9
```