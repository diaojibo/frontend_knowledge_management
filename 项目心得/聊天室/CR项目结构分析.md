## CR结构分析

### /server/bin/www
此乃入口文件，里面包含这几个函数。

 - normalizePort设定端口，默认3000.
 - 创建koa server的实例(从server文件夹中require app.js,创建整个客户端的实例)，创建socketio并绑定到对应的服务器上。
 - 