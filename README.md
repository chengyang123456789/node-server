# node-server

1. 通过http.createServer创建一个服务器
2. 调用函数routePath，进行请求参数和路径的处理
3. 对象routes里面包含了有多条路由，通过对象属性匹配路径，获得相应的值
4. 通过if判断是否是已经存在的路径，如果不是就返回静态目录下的文件test.html
