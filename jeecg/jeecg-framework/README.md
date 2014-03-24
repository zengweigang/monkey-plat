版本号：jeecg-framework3.4.3

1.采用maven构建项目，eclipse作为开发工具
2.将项目导入到eclipse中，配置好maven相关参数
3.修改数据库连接
/jeecg-framework/src/main/resources/dbconfig.properties
  修改项目hibernate启动模式，改为hibernate.hbm2ddl.auto=create
4.对应创建数据库（不需要创建表，系统自动生成表）  
5.该版本带有onlinecoding和uitag的全部源码
6.启动成功
  访问：http://localhost:8080/jeecg/
  
  JEECG项目的maven依赖下载:
   http://pan.baidu.com/s/1pJBDlP5   