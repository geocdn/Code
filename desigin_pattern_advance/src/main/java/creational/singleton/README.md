## 单例模式
保证一个类仅有一个实例，并提供一个全局访问点

## 类型
创建型

## 使用场景
确保任何场景下，只有一个实例

## 优点
* 减少内存开销
* 避免对资源的多重占用
* 设置全局访问点，严格控制访问

## 缺点
没有接口，扩展困难

## 重点
* 私有构造器
* 线程安全
* 延迟加载
* 序列化和反序列化安全
* 反射 防止反射攻击


## 序列化会破坏单例模式
* ObjectOutputStream会破坏单例模式
* 可以通过使用readResolve方法

## 推荐enum，可以防止反射破坏反序列化

## 单例模式和享元模式

## 单例模式和工厂模式

## 线程池

## 容器单例

* 统一管理
* 使用hashmap ,存在线程安全问题
* 使用hashtable,存在效率低的问题

## 案例

1. Runtime
2. ErrorContext 