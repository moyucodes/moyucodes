# 第一节  
- 在线运行 HelloWorld （golang payground）
- 介绍程序结构 package func main
- 下载安装本地运行 go run/ go build
# 演讲稿：  
- 简介：Go（又称Golang）是Google开发的一种静态强类型、编译型、并发型，并具有垃圾回收功能的编程语言；简单易学、开发效率高、性能好、稳定性好
- 那哪些公司使用呢？目前几乎所有互联网公司，比如 BAT、B站、今日头条、滴滴等等，所以golang语言优势还是非常大的；
- 首先，我们先来运行个例子，先打开：https://play.studygolang.com/
- 然后Run起来，可以看到 “Hello, playground”，第一个go程序已经跑起来了，并有在控制台看到结果；
- 整个程序以package、func main、fmt组成：
    - package，go包名一般是目录名，进行组成程序结构；
    - func main，一个程序函数入口，会一行行运行到结束；
    - fmt，go中格式化输入包，有一些字符格式化和输出功能；
- 本安装golang，我们以mac为例进行安装：brew install golang
    - mkdir -p ~/moyucodes/01-hello
    - cd ~/moyucodes/01-hello
    - vim main.go
    - go build
    - ./01-hello
