# androidPN

基于androidpn的推送服务器方案，加入断线重连、心跳包、离线推送、标签推送、别名推送。

## 开始前请准备：

  androidpn-client：<br> 
  1、修改res/raw/androidpn.properties配置文件<br> 
  2、把xmppHost=127.0.0.1改成你自己的ip；模拟器设置为：10.0.2.2<br> 

  androidpn-tomcat：<br> 
  1、用到了java的spring框架<br> 
  2、修改resources/jdbc.properties配置文件<br> 
  3、查看WebRoot/WEB-INF/dispatcher-servlet.xml配置文件<br> 
  4、访问地址为；http://127.0.0.1:8080/ 端口号为tomcat所使用的端口号<br> 

<br/><br/>
## v1.0.0 更新于 2017.12.31

  1.基于androidpn开源项目方案修改。<br> 
  2.加入断线重连、心跳包、离线推送、标签推送、别名推送等功能。<br> 
  3.修复了若干问题。<br> 
