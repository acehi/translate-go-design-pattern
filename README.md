# translate-go-design-pattern
Translate GO DESIGN PATTERNS book，Mario Castro Contreras

# 目录

## 前言
## 内容简介
## 本书约定
## 示例代码
## 第一章 准备！走你
### 第1节 一点GO历史
### 第2节 安装GO
#### 1、Linux环境安装
##### a. GO Linux环境的高级安装
#### 2、Windows环境安装
#### 3、Max OSX环境安装
#### 4、设置工作区-Linux和Max OSX
### 第3节 通过 Hello World 开始新世界大门
### 第4节 集成开发环境-IDE
### 第5节 类型
### 第6节 变量和常量（Variables and constants）
### 第7节 运算符（Operators）
### 第8节 流程控制（Flow control）
#### 1、If...else语句
#### 2、Switch语句
#### 3、For...range语句
### 第9节 函数
#### 1、函数长什么样
#### 2、匿名函数
#### 3、闭包（Closures）
#### 4、错误处理
#### 5、变长函数
### 第10节 数组、切片和映射
#### 1. 数组
##### a. 初始化
#### 2. 切片
#### 3. 映射
### 第11节 导出
### 第12节 指针和结构体
#### 1、指针
#### 2、结构体
### 第13节 接口
#### 1、接口-签合同
### 第14节 测试和TDD
#### 1、测试包
#### 2、什么是TDD
### 第15节 库
### 第16节 获取工具
### 第17节 管理JSON数据
#### 1、编码包
### 第18节 工具集
#### 1、golint
#### 2、gofmt
#### 3、godoc
#### 3、goimport
### 第19节 Github贡献
### 第20节 本章总结

## 第二章 创建型模式（Creational）
### 第1节 单例设计模式
#### 1、描述
#### 2、目的
#### 3、例子：唯一计数器
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现（Implementation）
#### 7、多说几句
### 第2节 生成器设计模式
#### 1、描述
#### 2、目的
#### 3、例子：造车
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、小结
### 第3节 工厂方法
#### 1、描述
#### 2、目的
#### 3、例子：为商店提供支付方式的工厂
#### 4、验收标准
#### 5、单元测试
#### 6、实现
#### 7、Upgrading the Debitcard method to a new platform（？）
#### 8、从工厂模式学到的
### 第4节 抽象工厂-工厂们之上的工厂
#### 1、描述
#### 2、目的
#### 3、例子：再次以造车为例
#### 4、验收标准
#### 5、单元测试
#### 6、实现
#### 7、总结
### 第5节 原型设计模式
#### 1、描述
#### 2、目的
#### 3、例子
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、从工厂模式学到的
### 第6节 本章总结
## 第三章 结构型模式
### 第1节 组合设计模式
#### 1、描述
#### 2、目的
#### 3、例子：游泳者和鱼
#### 4、要求和验收标准
#### 6、实现
#### 7、二叉树组合
#### 8、组合模式与继承
#### 9、小结
### 第2节 适配器设计模式
#### 1、描述
#### 2、目的
#### 3、例子：对适配器对象使用不兼容的接口
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、GO源码中的适配模式的使用
#### 8、小结
### 第3节 桥接设计模式
#### 1、描述
#### 2、目的
#### 3、例子：两台各自有两种打印方式的打印机
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、用桥接模式重构
### 第4节 本章总结
## 第四章 结构型模式
### 第1节 代理设计模式
#### 1、描述
#### 2、目的
#### 3、例子
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、代理行动（Proxying around actions）
### 第2节 装饰设计模式
#### 1、描述
#### 2、目的
#### 3、例子
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、真实的例子：服务器中间件
##### a、从公共接口：http.Handler开始
#### 8、关于Go的接口
#### 9、总结装饰模式-代理和装饰模式比较
### 第3节 外观设计模式
#### 1、描述
#### 2、目的
#### 3、例子
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、使用外观设计模式创建的库
### 第4节 享元设计模式
#### 1、描述
#### 2、目的
#### 3、例子：造车
#### 4、要求和验收标准
#### 5、基本结构测试
#### 6、实现
#### 7、单例模式和享元模式有什么区别
### 第5节 本章总结
## 第五章 行为型模式
### 第1节 策略设计模式
#### 1、描述
#### 2、目的
#### 3、渲染图片或文字
#### 4、要求和验收标准
#### 5、实现
#### 6、解决库中的小问题
#### 7、小结
### 第2节 责任链设计模式
#### 1、描述
#### 2、目的
#### 3、一条多逻辑链
#### 4、单元测试
#### 5、实现
#### 6、闭包？
#### 7、小结
### 第3节 命令设计模式（对象行为性模式）
#### 1、描述
#### 2、目的
#### 3、一个简单的队列
#### 4、要求和验收标准
#### 5、实现
#### 6、命令责任链
#### 7、向上舍入的命令模式
## 第六章 行为型模式
### 第1节 模版设计模式
#### 1、描述
#### 2、目的
#### 3、例子：一个简单的延迟步骤算法
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、匿名函数
#### 8、如何避免在接口中修改
#### 9、Go源码中的模版模式
#### 10、小结
### 第2节 备忘录设计模式
#### 1、描述
#### 2、目的
#### 3、例子：造车
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、用命令和外观模式的另一个例子
#### 8、小结
### 第3节 解释器模式
#### 1、描述
#### 2、目的
#### 3、例子：波兰计算器
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、解释器的复杂性
#### 8、使用接口实现解释器
#### 9、解释器的强大
### 第4节 本章总结

## 第7章 行为型模式
### 第1节 访问者模式
#### 1、描述
#### 2、目的
#### 3、日志收集器
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、其他例子
#### 8、访问者的救赎（？）
### 第2节 状态设计模式
#### 1、描述
#### 2、目的
#### 3、一个猜数字的小游戏
#### 4、要求和验收标准
#### 5、实现
#### 6、输和赢的状态
#### 7、使用状态模式构建游戏
### 第3节 中介者设计模式
#### 1、描述
#### 2、目的
#### 3、一个计算器
#### 4、要求和验收标准
#### 5、实现
#### 6、用中介者解藕的两种类型（？）
### 第4节 观察者设计模式
#### 1、描述
#### 2、目的
#### 3、通知者
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、小结
## 第8章 Go的并发介绍
### 第1节 一点历史和理论
#### 1、并发和并行
#### 2、CSP与基于参与者的并发比较（？）
### 第2节 Goroutines
#### 1、第一个Goroutine
#### 2、用新的Goroutine启动匿名函数
#### 3、WaitGroups
### 第3节 竞争（Callbacks）（？）
#### 1、竞争地狱
### 第4节 互斥锁
#### 1、例子：并发计数器
#### 2、介绍竞争探针
### 第5节 通道
#### 1、第一个通道
#### 2、缓冲通道
#### 3、单向通道
#### 4、选择声明
#### 3、作用域（？）
### 第6节 全部使用-并发性单例
#### 1、单元测试
#### 2、实现
### 第7节 本章总结
## 第9章 并发型模式
### 第1节 阻塞性并发模式
#### 1、描述
#### 2、目的
#### 3、HTTP GET聚合器
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、用阻塞性并发设计模式等待响应
### 第2节 前戏并发模式（？）
#### 1、描述
#### 2、目的
#### 3、一个简单的异步请求者
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、将前戏做整套（？）
### 第3节 前戏设计模式（？）
#### 1、描述
#### 2、目的
#### 3、一个简单的异步请求者
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
#### 7、将前戏做整套（？）
### 第4节 管道设计模式
#### 1、描述
#### 2、目的
#### 3、并发操作
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
##### a、列表生成器
##### b、将数字提高至2的倍数（？）
##### c、最终还原操作（？）
##### d、开启管道模式（？）
#### 7、小结
### 第5节 本章总结
## 第10章 并发型模式
### 第1节 线程池
#### 1、描述
#### 2、目的
#### 3、管道池
#### 4、要求和验收标准
#### 5、单元测试
#### 6、实现
##### a、调度员
##### b、管道
#### 7、使用线程池的应用
#### 8、没有测试？
#### 9、本章总结
### 第2节 并发的发布/订阅者设计模式
#### 1、描述
#### 2、目的
#### 3、例子：广播
#### 4、要求和验收标准
#### 5、单元测试
##### a、测试订阅者
##### b、测试发布者
#### 6、实现
##### a、实现发布者
##### b、处理没有竞争的通道
#### 7、小结
### 第3节 本章总结
