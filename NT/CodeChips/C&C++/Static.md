- Static 在头文件定义全局变量 不能被外部文件修改和引用 
- 通常在CPP定义static全局变量，在h文件用extern关键字引用
- static 类函数不属于对象，属于类
- static 的类成员变量如果定义在H文件。在CPP必须要单独初始化，用类似 `int Class::iner = 0;`的方式
- 定义静态函数的好处： • 静态函数不能被其它文件所用； • 其它文件中可以定义相同名字的函数，不会发生冲突；