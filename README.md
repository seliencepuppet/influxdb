# influxdb

<br/>

influxdb的简介

1) influxdb使用go语言开发, 是一种时间序列数据库
2) influxdb的查询语句类似于mysql的 select * from users
3) schemaless: 结构型数据库类似Mysql需要先定义列, influxdb无需预先定义, 无结构的数据库 -> measurement 类似于表 -> points 数据

influxdb的points数据说明

1) 一个是time, 默认存储数据会有时间, 时间无需关心, 会帮我们自动插入
2) 一个是tags, 用来存储数据标识 cpu.idle
3) 一个是fields, 用来存储数据 value=90


influxdb官网打开很慢

下载链接: https://dl.influxdata.com/influxdb/releases/influxdb-1.6.0.x86_64.rpm

百度网盘下载链接: https://pan.baidu.com/s/1c6V7qmiKXJJpYIT-D1vz6g#list/path=%2F 密码: 37i4

安装方法: rpm -ivh influxdb-1.6.0.x86_64.rpm, 安装完成后默认会有个influxdb用户

