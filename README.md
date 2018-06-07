# Zabbix

1. Start up containers:
```
docker-compose up
```

2. Go to the Zabbix web interface: [Zabbix web interface](http://localhost/) username: Admin password: zabbix

### Usage

Please follow usage instructions of each component image:

Components:

* [zabbix-server](https://hub.docker.com/r/zabbix/zabbix-server-mysql/) - Zabbix server with MySQL database support
* [zabbix-web](https://hub.docker.com/r/zabbix/zabbix-web-nginx-mysql/) - Zabbix web interface
* [mysql-server](https://hub.docker.com/_/mysql/) - Mysql image