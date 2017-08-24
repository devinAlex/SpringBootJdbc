# SpringBootJdbc

本地需要安装postman访问。</br>

访问URL:</br>

http://localhost:8080/account/list

http://localhost:8080/account/1

http://localhost:8080/account/1?name=zhangsan&money=500

http://localhost:8080/account?name=lisi&money=6666

@RequestParam注解主要有哪些参数：

value：参数名字，即入参的请求参数名字，如username表示请求的参数区中的名字为username的参数的值将传入；

required：是否必须，默认是true，表示请求中一定要有相应的参数，否则将报404错误码；

defaultValue：默认值，表示如果请求中没有同名参数时的默认值，默认值可以是SpEL表达式，如“#{systemProperties['java.vm.version']}”。
