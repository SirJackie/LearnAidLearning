# 8900端口的不稳定页面

Terminal (总是无响应)

http://192.168.3.42:8900/root/User/demo/Terminal.htm

会跳转到http://192.168.3.42:8888/terminals/1

Auto Piano 游戏 (总是无响应)

http://192.168.3.42:5050/

Xfce 在线远程桌面 (可能会显示 Service not installed or started)

http://192.168.3.42:8900/root/User/demo/novnc.htm

VSCode (可能会显示 Service not installed or started)

http://192.168.3.42:8900/root/User/demo/VSCode.htm

Jupyter (总是无响应)

http://192.168.3.42:8900/root/User/demo/Jupyter.htm

回跳转到http://192.168.3.42:8888/

Service - Linux服务管理

http://192.168.3.42:8900/root/User/demo/Service.htm

回跳转到http://192.168.3.42:8082/

X模式（沉浸式Xfce在线远程桌面） (可能会显示 Service not installed or started)

http://192.168.3.42:8900/root/User/demo/novncx.htm

应用中心（依赖VNC Service） (可能会显示 Service not installed or started)

http://192.168.3.42:8900/root/User/demo/novncS.htm

Aid Bot（总是无响应）

http://127.0.0.1:8910/startbot

Weather（总是无响应）

https://tianqiapi.com/api.php?style=tw&skin=pitaya



# VS Code: 8008 端口 (总是failed to load)

http://192.168.3.42:8008/



# VNC Service: 5901 端口 (不稳定)

http://192.168.3.42:5901/



# Xfce 在线远程桌面: 6080 端口 (不稳定)

http://192.168.3.42:6080/

### 包含以下子页面

http://192.168.3.42:6080/vnc.html

http://192.168.3.42:6080/vnc_lite.html

### 进行如下操作时，会导致整个系统崩溃，所有端口失效

- 访问 http://192.168.3.42:6080/vnc.html
- 点击页面左边全屏按钮
- 接着，会自动跳转到http://192.168.3.42:8900/root/User/demo/novnc.htm
- 又跳到http://192.168.3.42:6080/vnc.html?host=192.168.3.42&port=6080&password=123456

​	Click 链接 and then jump to this URL:

​	http://192.168.3.42:8900/root/User/mac/demo.html

​	then every thing shut off.



# Jupyter Service: 8888 端口 (总是无响应)

http://192.168.3.42:8888/

