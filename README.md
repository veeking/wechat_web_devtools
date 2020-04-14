# Linux微信web开发者工具

## Usage
1、``docker run -d --name wxwebdevtool -p 6080:80 -v /path:/path veekingsen/wxwebdevtool:latest``

2、浏览器打开``localhost:6080``vnc

3、在vnc容器根目录里``cd wxdt``

4、运行``./bin/wxdt``安装开发者工具并打开，然后手动开启开发者工具服务端口``

5、设置特定端口并打开开发者工具 ``cli open --port 9000``