# golearning
go语言学习笔记
# go代码示例
https://gobyexample.com/
# go教程(李文周)
https://www.liwenzhou.com/posts/Go/go_menu/
# 交叉编译 (跨平台编译)
 ## Mac 下编译 Linux 和 Windows 64位可执行程序
```
  CGO_ENABLED=0 
  GOOS=linux 
  GOARCH=amd64 
  go build main.go
  ​
  CGO_ENABLED=0 
  GOOS=windows 
  GOARCH=amd64 
  go build main.go
```
