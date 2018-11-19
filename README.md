环境准备：启动Redis、初始化Mysql表数据；

修改Host文件：域名方式访问认证中心，模拟跨域与线上真实环境

### 在host文件中添加以下内容
127.0.0.1 xxlssoserver.com
127.0.0.1 xxlssoclient1.com
127.0.0.1 xxlssoclient2.com
分别运行 "xxl-sso-server" 与 "xxl-sso-web-sample-springboot"

cookie

1、SSO认证中心地址：
http://xxlssoserver.com:8080/xxl-sso-server

2、Client01应用地址：
http://xxlssoclient1.com:8081/xxl-sso-web-sample-springboot/

3、Client02应用地址：
http://xxlssoclient2.com:8081/xxl-sso-web-sample-springboot/


token

1、SSO认证中心地址：
http://xxlssoserver.com:8080/xxl-sso-server

2、Client01应用地址：
http://xxlssoclient1.com:8082/xxl-sso-token-sample-springboot/

3、Client02应用地址：
http://xxlssoclient2.com:8082/xxl-sso-token-sample-springboot/