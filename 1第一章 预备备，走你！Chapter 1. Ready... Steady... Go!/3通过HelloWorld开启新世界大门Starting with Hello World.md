没有一本正经的书是不存在Hello World示例的。我们的Hello World示例非常简单。打开您最爱的编辑器，并在路径 `$GOPATH/src/[your_name]/hello_world` 之下
创建一个名为`main.go`的文件，其内容如下：

```go
package main 
 
func main(){ 
    println("Hello World!") 
}
```

保存文件后运行我们的的程序。打开您操作系统的终端窗口：

 - 在Linux中，进入“程序”，找到一个名为“Terminal”的程序。
 - 在Windows中，点击Windows + R，在新窗口中输入cmd，然后回车。
 - 在Mac OS X中，按Command + Space打开spotlight搜索，输入不带引号的terminal。终端应用程序必须高亮显示后再按回车键。

进入终端后，导航至`main.go`文件所在的文件夹即路径 `$GOPATH/src/[your_name]/hello_world` ，然后执行它：

````go
go run main.go
// 输出Hello World!
````

这就完事了！`go run [file]` 命令将编译并执行我们的应用程序，但它不会生成一个可执行文件。如果你只是想构建它并获取一个可执行文件，你必须使用以下命令构建应用程序:

````go
go build -o hello_world
````

看上去什么也没发生。但你如果查看当前的目录，会发现出现一个名为hello_world的可执行文件。在上面构建时，通过`-o hello_world`参数将"hello_world"这个名称赋予了可执行文件。你现在可以执行这个文件:

````go
/hello_world
// 输出Hello World!
````

结果出现了！

> 小贴士
>
> 执行 go run [my_main_file.go] 时是不会带着中间文件（例如依赖库）一并构建和执行程序的。而 go build -o [filename] 命令将创建一个可执行文件，在任何地方可以使用并不存在依赖关系。
