# go 模块化思考


## 浅谈
	今天做了官网的例子，在结合自己前端node_modules模块化，现在对go模块有了
加深了一些理解。

1. 我们可以自己写一个库上传到github
2. 然后本地进行引入之后就会加深对go 模块化的认识。


## 大致流程
1. 我们新建一个项目
2. go mod init  github.com/yourgithubname/yourlibname
3. write this and git commit to github
4. we can reference which in our new loacl project by import and go mod tidy 







## go mod 和  go get的区别？

[go mod 基本操作](https://www.jianshu.com/p/760c97ff644c)