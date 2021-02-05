变量是计算机内存中存储的可以在程序运行期间改变的值。变量或常量类型和前文中说的类型都相似。我们无需显示的声明它们（尽管可以这么做）。这种不需要明确声明类型的属性叫做类型推断。例子：

````go
// 显式的声明一个变量

var explicit string = "你好，我是一个显式声明的变量"
````

我们在上面声明了一个名为 `explicit` 的字符串变量，同时将 `你好，我是一个显式声明的变量` 这个值赋值给了它。

````go
// 通过类型推断隐式的声明一个变量
inferred :=  = "你好，我是一个隐式声明的变量"
````

上面的代码做了相同的事，但省略了关键字var以及声明string类型。
在Go的编译器内部会将变量推断为字符串类型。这样可以不必为每个变量定义而写更少的代码。

下面我们通过reflect包来获取变量的信息。我们用它来打印上述两个变量的类型：

````go
// 通过类型推断隐式的声明一个变量
fmt.Println("Variable 'explicit' is of type:", reflect.TypeOf(explicit))
fmt.Println("Variable 'inferred' is of type:", reflect.TypeOf(inferred))
````

执行程序并打印出以下结果：
````go
// 通过类型推断隐式的声明一个变量
你好，我是一个显式声明的变量
你好，我是一个隐式声明的变量
Variable 'explicit' is of type: string
Variable 'inferred' is of type: string
````

如我们所说的，编译器也将隐式变量的类型推断为字符串。
