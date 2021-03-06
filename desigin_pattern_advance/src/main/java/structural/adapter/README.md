## 适配器模式
* 将一个类的接口转换成为客户期望的另一个接口
* 使原本接口不兼容的类可以一起工作
* 结构性

## 应用场景
* 已经存在的类，它的方法和需求不匹配时（方法结果相同或相似）
* 不是软件设计阶段考虑的设计模式，是随着软件维护，由于不同产品，不同厂家造成功能类似而接口不相同的情况下的解决方案

## 优点
* 提供类的透明性和复用，现有的类复用但不需要改变
* 目标类和适配器类解耦，提高程序扩展性
* 符合开闭原则

## 缺点
* 需要全面考虑，可能会增加系统的复杂性
* 增加系统代码可读的难度

## 扩展
* 对象适配器
组合机制

* 类适配器
继承

## 相关设计模式
* 外观模式
外观定义新的接口，适配器复用已有的接口
外观提供一个更方便的访问入口，适配器是两个已有的接口协同工作。 


## 案例
javax.xml.bind.annotation.adapters.XmlAdaptern
org.springframework.aop.framework.adapter.AdvisorAdapter