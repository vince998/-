# -logagen:
1、etcd:配置中心
2、tail:读取日志文件,推送到kafka
3、kafak:日志中心
4、config:etcd、kafka连接信息
5、utils:获取本机ip信息


#-logTransfer:
1、ES:搜索引擎，读取存储在kafka中的日志，推送到ES,做可视化
