#什么是shadowsocks ？
特点与安全性[编辑]
Shadowsocks使用自行设计的协议进行加密通信。[2] 加密算法有AES、Blowfish、IDEA、RC4等，除创建TCP连接外无需握手，每次请求只转发一个连接，因此使用起来网速较快，在移动设备上也比较省电。然而协议对双方的身份验证仅限于预共享密钥（pre-shared keys），亦无完全前向保密（perfect forward secrecy），也未曾有安全专家公开分析或评估协议及其实现。Shadowsocks不能替代TLS或者VPN，本质上只是设置了密码的网络代理协议，不能用作匿名通信方案，该协议的目标不在于提供完整的通信安全机制，主要是为了协助上网用户在严苛的网络环境中突破封锁。在某些极端的环境下，通过深度包检测（DPI）也有可能识别出协议特征。为了确保安全，用户应做好额外的加密和验证措施，以免泄露信息，无论使用的服务器来源是否可靠。

运行原理[编辑]
通过客户端以指定的密码、加密方式和端口连接服务器，成功连接到服务器后，客户端在用户的电脑上构建一个本地socks5代理。使用时将流量分到本地socks5代理，客户端将自动加密并转发流量到服务器，服务器以同样的加密方式将流量回传给客户端，以此实现代理上网。

停止维护
2015年8月22日，其作者Clowwindy在GitHub上称，警察在两日前要求他停止开发Shadowsocks并删除其所有代码。[3]之后，作者停止维护Shadowsocks，其GitHub页面已被清空。


# 1. 下载客户端

所有客户端都可以在  https://github.com/shadowsocks 下载。

为方便使用，特加了mac、windows在此处

windows 客户端下载：https://github.com/mockcoin/ss/raw/master/windows-ss-2.5.8.zip

mac 客户端下载：https://github.com/mockcoin/ss/raw/master/mac-ss.zip


#2. windows使用步骤
 ![image](https://github.com/mockcoin/ss/raw/master/win_1.png)

 ![image](https://github.com/mockcoin/ss/raw/master/win_2.png)

右击图标 在弹出菜单 上选上第一项 “启用代理模式”
打开任何浏览器， 可以上网了。

#3. mac

 ![image](https://github.com/mockcoin/ss/raw/master/mac_1.png)
 ![image](https://github.com/mockcoin/ss/raw/master/mac_2.png)
 
操作好之后打开任何浏览器， 可以上网了。
