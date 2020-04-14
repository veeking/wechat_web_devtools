# Linux微信web开发者工具

## Usage
1、``docker run -d --name wxwebdevtool -p 6080:80 -v /path:/path veekingsen/wxwebdevtool:latest``

2、浏览器打开``localhost:6080``vnc

3、在vnc容器里运行``./bin/wxdt``，手动开启开发者工具服务端口

4、设置端口并打开开发者工具,``cli open --port 9000``