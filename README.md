# JDBC-orm
JDBC
常见数据库连接URL：
对于 Oracle 数据库连接，采用如下形式： 
jdbc:oracle:thin:@localhost:1521:atguigu
对于 SQLServer 数据库连接，采用如下形式：
jdbc:microsoft:sqlserver//localhost:1433; DatabaseName=sid
对于 MYSQL 数据库连接，采用如下形式：   
jdbc:mysql://localhost:3306/atguigu
win 10系统中mysql安装：
常见错误：
1.cmd中输入mysql，出错"mysql"不是内部或外部命令，也不是可运行的程序或批处理文件
解决方法：
重新配置环境变量：
① 、win+r-->services.msc-->右击mysql服务-->属性-->找到可执行路径并复制出来
②、右击“我的电脑”-->属性-->高级系统设置-->环境变量-->系统变量-->PATH-->新增-->上面的“可执行路径”
③、耐心的等一分钟吧，我一开始直接试了，结果还是报错，过了一会儿又试了一下就成功连接了，哈哈，估计Win10的系统进程刚刷新吧。
④. 之后在cmd里面输入 mysql -u root -p

2. mysql connections错误
① 首先检查mysql服务器是否开启 ： win+r-->services.msc-->右击mysql服务
