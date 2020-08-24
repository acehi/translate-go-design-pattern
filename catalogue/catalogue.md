# 设计模式

## 前言（O:Preface）
## 内容简介（O:What this book covers）
## 本书约定（O:Conventions）
## 示例代码（O:Downloading the example code）
## 第一章 准备！走你（O:1. Ready... Steady... Go!）
### 第1节 一点GO历史（O:A little bit of history）
### 第2节 安装GO（O:Installing Go）
#### 1、Linux环境安装（O:LINUX）
##### a. GO Linux环境的高级安装（O:Go Linux advanced installation）
#### 2、Windows环境安装（O:Windows）
#### 3、Max OSX环境安装（O:Mac OS X）
#### 4、设置工作区-Linux和Max OSX（O:Setting the workspace - Linux and Apple OS X）
### 第3节 通过 Hello World 开始新世界大门（O:Starting with Hello World）
### 第4节 集成开发环境-IDE（O:Integrated Development Environment - IDE）
### 第5节 类型（O:Types）
### 第6节 变量和常量（Variables and constants）（O:Variables and constants）
### 第7节 运算符（Operators）（O:Operators）
### 第8节 流程控制（Flow control）（O:Flow control）
#### 1、If...else语句（O:The if... else statement）
#### 2、Switch语句（O:The switch statement）
#### 3、For...range语句（O:The for…range statement）
### 第9节 函数（O:Functions）
#### 1、函数长什么样（O:What does a function look like?）
#### 2、匿名函数（O:What is an anonymous function?）
#### 3、闭包（Closures）（O:Closures）
#### 4、错误处理（O:Creating errors, handling errors and returning errors.）
#### 5、变长函数（O:Function with undetermined number of parameters）
##### a、命名返回类型（O:Naming returned types）
### 第10节 数组、切片和映射（O:Arrays, slices, and maps）
#### 1. 数组（O:Arrays）
##### a. 初始化（O:Zero-initialization）
#### 2. 切片（O:Slices）
#### 3. 映射（O:Maps）
### 第11节 导出（Visibility）（O:Visibility）
### 第12节 零值-初始化（O:Zero-initialization）
### 第13节 指针和结构体（O:Pointers and structures）
#### 1、指针（O:What is a pointer? Why are they good?）
#### 2、结构体（O:Structs）
### 第14节 接口（O:Interfaces）
#### 1、接口-签合同（O:Interfaces - signing a contract）
### 第15节 测试和TDD（O:Testing and TDD）
#### 1、测试包（O:The testing package）
#### 2、什么是TDD（O:What is TDD?）
### 第16节 库（O:Libraries）
### 第17节 获取工具（O:The Go get tool）
### 第18节 管理JSON数据（O:Managing JSON data）
#### 1、编码包（O:The encoding package）
### 第19节 工具集（O:Go tools）
#### 1、golint（O:The golint tool）
#### 2、gofmt（O:The gofmt tool）
#### 3、godoc（O:The godoc tool）
#### 3、goimport（O:The goimport tool）
### 第20节 Github贡献（O:Contributing to Go open source projects in GitHub）
### 第21节 本章总结（O:Summary）

## 第二章 创建型模式（Creational）（O:2. Creational Patterns - Singleton, Builder, Factory, Prototype, and Abstract Factory Design Patterns）
### 第1节 单例设计模式（O:Singleton design pattern - having a unique instance of a type in the entire program）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：唯一计数器（O:Example - a unique counter）
#### 4、要求和验收标准（O:Requirements and acceptance criteria）
#### 5、单元测试（O:Writing unit tests first）
#### 6、实现（Implementation）（O:Implementation）
#### 7、多说几句（O:A few words about the Singleton design pattern）
### 第2节 生成器设计模式（O:Builder design pattern - reusing an algorithm to create many implementations of an interface）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：造车（O:Example - vehicle manufacturing）
#### 4、要求和验收标准（O:Requirements and acceptance criteria）
#### 5、单元测试（O:Unit test for the vehicle builder）
#### 6、实现（O:Implementation）
#### 7、小结（O:Wrapping up the Builder design pattern）
### 第3节 工厂方法（O:Factory method - delegating the creation of different types of payments）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：为商店提供支付方式的工厂（O:The example - a factory of payment methods for a shop）
#### 4、验收标准（O:Acceptance criteria）
#### 5、单元测试（O:First unit test）
#### 6、实现（O:Implementation）
#### 7、Upgrading the Debitcard method to a new platform（？）（O:Upgrading the Debitcard method to a new platform）
#### 8、从工厂模式学到的（O:What we learned about the Factory method）
### 第4节 抽象工厂-工厂们之上的工厂（O:Abstract Factory - a factory of factories）
#### 1、描述（O:Description）
#### 2、目的（O:The objectives）
#### 3、例子：再次以造车为例（O:The vehicle factory example, again?）
#### 4、验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Unit test）
#### 6、实现（O:Implementation）
#### 7、总结（O:A few lines about the Abstract Factory method）
### 第5节 原型设计模式（O:Prototype design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objective）
#### 3、例子（O:Example）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Unit test）
#### 6、实现（O:Implementation）
#### 7、从工厂模式学到的（O:What we learned about the Prototype design pattern）
### 第6节 本章总结（O:Summary）

## 第三章 结构型模式（O:3. Structural Patterns - Composite, Adapter, and Bridge Design Patterns）
### 第1节 组合设计模式（O:Composite design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：游泳者和鱼（O:The swimmer and the fish）
#### 4、要求和验收标准（O:Requirements and acceptance criteria）
#### 6、实现（O:Creating compositions）
#### 7、二叉树组合（O:Binary Tree compositions）
#### 8、组合模式与继承（O:Composite pattern versus inheritance）
#### 9、小结（O:Final words on the Composite pattern）
### 第2节 适配器设计模式（O:Adapter design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：对适配器对象使用不兼容的接口（O:Using an incompatible interface with an Adapter object）
#### 4、要求和验收标准（O:Requirements and acceptance criteria）
#### 5、单元测试（O:Unit testing our Printer adapter）
#### 6、实现（O:Implementation）
#### 7、GO源码中的适配模式的使用（O:Examples of the Adapter pattern in Go's source code）
#### 8、小结（O:What the Go source code tells us about the Adapter pattern）
### 第3节 桥接设计模式（O:Bridge design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：两台各自有两种打印方式的打印机（O:Two printers and two ways of printing for each）
#### 4、要求和验收标准（O:Requirements and acceptance criteria）
#### 5、单元测试（O:Unit testing the Bridge pattern）
#### 6、实现（O:Implementation）
#### 7、用桥接模式重构（O:Reuse everything with the Bridge pattern）
### 第4节 本章总结（O:Summary）

## 第四章 结构型模式（O:4. Structural Patterns - Proxy, Facade, Decorator, and Flyweight Design Patterns）
### 第1节 代理设计模式（O:Proxy design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子（O:Example）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Unit test）
#### 6、实现（O:Implementation）
#### 7、代理行动（Proxying around actions）（O:Proxying around actions）
### 第2节 装饰设计模式（O:Decorator design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子（O:Example）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Unit test）
#### 6、实现（O:Implementation）
#### 7、真实的例子：服务器中间件（O:A real-life example - server middleware）
##### a、从公共接口：http.Handler开始（O:Starting with the common interface, http.Handler）
#### 8、关于Go的接口（O:A few words about Go's structural typing）
#### 9、总结装饰模式-代理和装饰模式比较（O:Summarizing the Decorator design pattern - Proxy versus Decorator）
### 第3节 外观设计模式（O:Facade design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子（O:Example）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Unit test）
#### 6、实现（O:Implementation）
#### 7、使用外观设计模式创建的库（O:Library created with the Facade pattern）
### 第4节 享元设计模式（O:Flyweight design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：造车（O:Example）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、基本结构测试（O:Basic structs and tests）
#### 6、实现（O:Implementation）
#### 7、单例模式和享元模式有什么区别（O:What's the difference between Singleton and Flyweight then?）
### 第5节 本章总结（O:Summary）

## 第五章 行为型模式（O:5. Behavioral Patterns - Strategy, Chain of Responsibility, and Command Design Patterns）
### 第1节 策略设计模式（O:Strategy design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、渲染图片或文字（O:Rendering images or text）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、实现（O:Implementation）
#### 6、解决库中的小问题（O:Solving small issues in our library）
#### 7、小结（O:Final words on the Strategy pattern）
### 第2节 责任链设计模式（O:Chain of responsibility design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、一条多逻辑链（O:A multi-logger chain）
#### 4、单元测试（O:Unit test）
#### 5、实现（O:Implementation）
#### 6、闭包？（O:What about a closure?）
#### 7、小结（O:Putting it together）
### 第3节 命令设计模式（对象行为性模式）（O:Command design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、一个简单的队列（O:A simple queue）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、实现（O:Implementation）
#### 6、更多例子（O:More examples）
#### 7、命令责任链（O:Chain of responsibility of commands）
#### 8、向上舍入的命令模式（O:Rounding-up the Command pattern up）
### 第4节 本章总结（O:Summary）

## 第六章 行为型模式（O:6. Behavioral Patterns - Template, Memento, and Interpreter Design Patterns）
### 第1节 模版设计模式（O:Template design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：一个简单的延迟步骤算法（O:Example - a simple algorithm with a deferred step）
#### 4、要求和验收标准（O:Requirements and acceptance criteria）
#### 5、单元测试（O:Unit tests for the simple algorithm）
#### 6、实现（O:Implementing the Template pattern）
#### 7、匿名函数（O:Anonymous functions）
#### 8、如何避免在接口中修改（O:How to avoid modifications on the interface）
#### 9、Go源码中的模版模式（O:Looking for the Template pattern in Go's source code）
#### 10、小结（O:Summarizing the Template design pattern）
### 第2节 备忘录设计模式（O:Memento design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：造车（O:A simple example with strings）
#### 4、要求和验收标准（O:Requirements and acceptance criteria）
#### 5、单元测试（O:Unit test）
#### 6、实现（O:Implementing the Memento pattern）
#### 7、用命令和外观模式的另一个例子（O:Another example using the Command and Facade patterns）
#### 8、小结（O:Last words on the Memento pattern）
### 第3节 解释器模式（O:Interpreter design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：波兰计算器（O:Example - a polish notation calculator）
#### 4、要求和验收标准（O:Acceptance criteria for the calculator）
#### 5、单元测试（O:Unit test of some operations）
#### 6、实现（O:Implementation）
#### 7、解释器的复杂性（O:Complexity with the Interpreter design pattern）
#### 8、使用接口实现解释器（O:Interpreter pattern again - now using interfaces）
#### 9、解释器的强大（O:The power of the Interpreter pattern）
### 第4节 本章总结（O:Summary）

## 第7章 行为型模式（O:7. Behavioral Patterns - Visitor, State, Mediator, and Observer Design Patterns）
### 第1节 访客模式（O:Visitor design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、日志收集器（O:A log appender）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Unit tests）
#### 6、实现（O:Implementation of Visitor pattern）
#### 7、其他例子（O:Another example）
#### 8、访问者的救赎（？）（O:Visitors to the rescue!）
### 第2节 状态设计模式（O:State design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、一个猜数字的小游戏（O:A small guess the number game）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、实现（O:Implementation of State pattern）
#### 6、输和赢的状态（O:A state to win and a state to lose）
#### 7、使用状态模式构建游戏（O:The game built using the State pattern）
### 第3节 中介者设计模式（O:Mediator design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、一个计算器（O:A calculator）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、实现（O:Implementation）
#### 6、用中介者解藕的两种类型（？）（O:Uncoupling two types with the Mediator）
### 第4节 观察者设计模式（O:Observer design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、通知者（O:The notifier）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Unit tests）
#### 6、实现（O:Implementation）
#### 7、小结（O:Summary）

## 第8章 Go的并发介绍（O:8. Introduction to Gos Concurrency）
### 第1节 一点历史和理论（O:A little bit of history and theory）
#### 1、并发和并行（O:Concurrency versus parallelism）
#### 2、CSP与基于参与者的并发比较（？）（O:CSP versus actor-based concurrency）
### 第2节 Goroutines（O:Goroutines）
#### 1、第一个Goroutine（O:Our first Goroutine）
#### 2、用新的Goroutine启动匿名函数（O:Anonymous functions launched as new Goroutines）
#### 3、WaitGroups（O:WaitGroups）
### 第3节 竞争（Callbacks）（？）（O:Callbacks）
#### 1、竞争地狱（O:Callback hell）
### 第4节 互斥锁（O:Mutexes）
#### 1、例子：并发计数器（O:An example with mutexes - concurrent counter）
#### 2、介绍竞争探针（O:Presenting the race detector）
### 第5节 通道（O:Channels）
#### 1、第一个通道（O:Our first channel）
#### 2、缓冲通道（O:Buffered channels）
#### 3、单向通道（O:Directional channels）
#### 4、选择声明（O:The select statement）
#### 3、作用域（？）（O:Ranging over channels too!）
### 第6节 全部使用-并发性单例（O:Using it all - concurrent singleton）
#### 1、单元测试（O:Unit test）
#### 2、实现（O:Implementation）
### 第7节 本章总结（O:Summary）

## 第9章 并发型模式（O:9. Concurrency Patterns - Barrier, Future, and Pipeline Design Patterns）
### 第1节 阻塞性并发模式（O:Barrier concurrency pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、HTTP GET聚合器（O:An HTTP GET aggregator）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Unit test - integration）
#### 6、实现（O:Implementation）
#### 7、用阻塞性并发设计模式等待响应（O:Waiting for responses with the Barrier design pattern）
### 第2节 前戏并发模式（？）（O:Future design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、一个简单的异步请求者（O:A simple asynchronous requester）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Unit tests）
#### 6、实现（O:Implementation）
#### 7、将前戏做整套（？）（O:Putting the Future together）
### 第3节 管道设计模式（O:Pipeline design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、并发操作（O:A concurrent multi-operation）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Beginning with tests）
#### 6、实现（O:Implementation）
##### a、列表生成器（O:The list generator）
##### b、将数字提高至2的倍数（？）（O:Raising numbers to the power of 2）
##### c、最终还原操作（？）（O:Final reduce operation）
##### d、开启管道模式（？）（O:Launching the Pipeline pattern）
#### 7、小结（O:Final words on the Pipeline pattern）
### 第4节 本章总结（O:Summary）

## 第10章 并发型模式（O:10. Concurrency Patterns - Workers Pool and Publish/Subscriber Design Patterns）
### 第1节 线程池（O:Workers pool）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、管道池（O:A pool of pipelines）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、实现（O:Implementation）
##### a、调度员（O:The dispatcher）
##### b、管道（O:The pipeline）
#### 6、使用线程池的应用（O:An app using the workers pool）
#### 7、没有测试？（O:No tests?）
#### 8、本章总结（O:Wrapping up the Worker pool）
### 第2节 并发的发布/订阅者设计模式（O:Concurrent Publish/Subscriber design pattern）
#### 1、描述（O:Description）
#### 2、目的（O:Objectives）
#### 3、例子：广播（O:Example - a concurrent notifier）
#### 4、要求和验收标准（O:Acceptance criteria）
#### 5、单元测试（O:Unit test）
##### a、测试订阅者（O:Testing subscriber）
##### b、测试发布者（O:Testing publisher）
#### 6、实现（O:Implementation）
##### a、实现发布者（O:Implementing the publisher）
##### b、处理没有竞争的通道（O:Handling channels without race conditions）
#### 7、小结（O:A few words on the concurrent Observer pattern）
### 第3节 本章总结（O:Summary）
