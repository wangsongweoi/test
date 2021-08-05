shell命令学习：

if [ -z "$str" ]; 判断字符串str长度是否为0，为0，返回为true

if [ -n "$str" ];判断字符串str长度是否不为0，不为0，返回为true

$@ 返回当前脚本的所有参数

$# 返回当前脚本的参数个数

for slave in `echo "$HOSTLIST"`;do echo $slave; done 循环遍历

-------------

java中常见的设计模式：

​	单例----->懒汉式

​	装饰

​	模板

​	工厂

​	代理

​		动态代理

​			基于接口的动态代理：jdk中自带的Proxy

​			基于子类的动态代理：cglib.jar

​		静态代理

​	