# sonar-runner-windows
window 环境下 扫描代码
# 配置windows环境变量
将 sonar-runner工具下的bin目录的路径配置到windows path环境变量中   sonar-runner


# 需要配置两个文件
第一个是连接sonarqube服务（自己搭建）的配置文件  ，在conf 目录下 名为  sonar-runner.properties

第二个是sonar-project.properties 配置文件，放置到不同的项目下，根据想要扫描的目录,在里面配置对应的值。进入到 对应项目,存放该文件的位置.  执行  sonar-runner 命令,就会根据当前所在的目录下的配置文件扫描代码
