##zookeeper zabbix监控脚本和模板

使用方法：

1. 将脚本放到/usr/local/zabbix下面，确保zabbix配置在/etc/zabbix/zabbix_agentd.conf中

2. 将监控配置文件放到/etc/zabbix/zabbix_agentd.d/中

3. yum install -y zabbix-sender

4. /etc/init.d/zabbix_agentd restart

这里使用的策略是agent主动发送数据到server，所以大部分数值的last check time是不会变的。
