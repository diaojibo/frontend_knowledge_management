## day1
找到几个对应可参考的project，尝试run起来。

安装了mongodb，必须进入到mongodb的bin目录运行mongod.exe

并且运行服务的端口要记下，在project中进行修改。

bcrypt不可用，查找stackoverflow以后改成了bcryptjs，并在对应的文件里修改了require语句。

webpack打包失败，发现了两个插件的版本不兼容，react版本改成了15.4.0.react-tap-event-plugin改成了2.0.0

run成功了。。。。

接着考察webpack，了解了配置文件中entry的意义。