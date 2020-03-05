js斗地主游戏

服务器 : node.js

客户端:   cocos creator2.0

数据库 ：mysql

![server](https://github.com/tinyshu/ddz_game/blob/master/image/1.png)



![server](https://github.com/tinyshu/ddz_game/blob/master/image/2.png)



![server](https://github.com/tinyshu/ddz_game/blob/master/image/3.png)



![server](https://github.com/tinyshu/ddz_game/blob/master/image/4.png)



![server](https://github.com/tinyshu/ddz_game/blob/master/image/5.png)

​                        

​                            ![server](https://github.com/tinyshu/ddz_game/blob/master/image/6.png)


客户端: 使用cocoscreator2.0.10
服务器:node.js
数据库:mysql
整套客户端服务器源码全部从零开始编写，完成如下功能:
1.登录
2.游戏大厅
3.创建，加入房间
4.房间管理
5.洗盘，发牌，全部出牌逻辑

开源全部代码和资源，可自己部署运行，觉得不错的老铁在github给点个start，后续有更多开源项目，
https://github.com/tinyshu/ddz_game593

编译步骤:
1.新建一个数据库名字ddz,导入帐号表,sql文件在ddz_server_node/sql下
2.在服务器ddz_server_node增加配置db_config.js文件(这个配置没放到github因为里面记录了我的公网数据库信息)
内容如下
exports.dbconfig = {
"host": "db的ip",
"port": db端口,
"user": "db账号",
"password": "db的密码",
"database": "db名称"
};

3.保证测试机器上安装了node.js和nmp
4.在命令行控制台cd到ddz_server_node目录下
5.然后在控制台执行 nmp start 服务就启动了



​					
