# Ajax的掌握

- form的作用

  用form定义传输数据的地址`https://baidu.com`,get传输数据的方式,点击submit会跳转,地址会显示如下

  ![](https://github.com/viewdegree/course-of-javacript/blob/feature/class1-ajax/class1ajax/img/result/1.jpg)

  用post的方式去传输数据

  ![](https://github.com/viewdegree/course-of-javacript/blob/feature/class1-ajax/class1ajax/img/result/2.jpg)

- ajax的基础用法

  ajax也是用来传输数据的,不过ajax不会强制跳转就可以发送请求和接受响应,但存在跨区阻止

  ![](https://github.com/viewdegree/course-of-javacript/blob/feature/class1-ajax/class1ajax/img/result/3.jpg)

- ajax的封装

  注意success函数在接受返回的responseText的时候,要JSON序列化一下,即将字符串转换为对象,不然的话这位字符串,不利于以后操作

- jq的ajax使用

- 获取数据后的数据处理

