#什么是shadowsocks ？


Shadowsocks是一款比VPN更可靠、更高效的科学上网解决方案。
Shadowsocks使用自行设计的协议进行加密通信。加密算法有AES、Blowfish、IDEA、RC4等，除创建TCP连接外无需握手，每次请求只转发一个连接，因此使用起来网速较快，在移动设备上也比较省电。该协议的目标主要是为了协助上网用户在严苛的网络环境中突破封锁。

其使用方法：通过客户端以指定的密码、加密方式和端口连接服务器，成功连接到服务器后，客户端在用户的电脑上构建一个本地socks5代理。使用时将流量分到本地socks5代理，客户端将自动加密并转发流量到服务器，服务器以同样的加密方式将流量回传给客户端，以此实现保密的代理上网。



# 1. 下载客户端


windows 客户端下载：https://github.com/mockcoin/ss/raw/master/windows-ss-2.5.8.zip

mac 客户端下载：https://github.com/mockcoin/ss/raw/master/mac-ss.zip

其它未列出的客户端都可以在  https://github.com/shadowsocks 下载（包括windows 和 mac）。



#2. windows使用步骤
 ![image](https://github.com/mockcoin/ss/raw/master/win_1.png)

 ![image](https://github.com/mockcoin/ss/raw/master/win_2.png)

右击图标 在弹出菜单 上选上第一项 “启用代理模式”
打开任何浏览器， 可以上网了。

#3. mac

 ![image](https://github.com/mockcoin/ss/raw/master/mac_1.png)
 ![image](https://github.com/mockcoin/ss/raw/master/mac_2.png)
 
操作好之后打开任何浏览器， 可以上网了。
