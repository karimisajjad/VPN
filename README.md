## 梯子-科学上网 请访问：科学上网工具使用教程：

**[https://github.com/xiaoming2028/kexueshangwang/wiki](https://github.com/xiaoming2028/FreePAC/wiki)**


.
.
.

### 点赞分享

**点赞**：如果你喜欢本项目，如果您是github用户，请给我们“点个赞”，请点GitHub右上角的star。同时您还可以通过GitHub的Fork功能（点右上角Fork）备份和二次开发本项目。

**收藏**：也推荐您可以将当前页面网址放入您的浏览器收藏夹、书签栏等

**收藏方法**：电脑访问可按Ctrl+D 键，手机访问请按手机收藏方法收藏

.
.
.

## 为什么要自己搭建科学上网服务？

你也许会觉得买科学上网服务也很方便，但是你得要考虑以下几个问题。首先，买的科学上网服务，限制很多，终端可能只能同时在线 2 个，每个月就一点点流量可能价格却不便宜，有时候还被别人做手脚，流量跑的贼快；其次，别人收钱跑路怎么办？很多这种情况的；更重要的是，如果有心人做了一点手脚，是可以得到你的访问记录的；而自己搭建科学上网服务，一键脚本也就 10 来分钟就可以搞定。

.
.
.

## ===VPS推荐===

1、[**Hostwinds**](https://affiliates.hostwinds.com/hostwinds.php?id=7011&tid2=github&url=1224) 是一家美国主机商，成立于 2010 年，国内站长使用较多的是 Hostwinds 美国 VPS 主机产品。由于 [Hostwinds](https://bit.ly/2UQ0Zqd) 美国 VPS 主机采用的是 SSD 硬盘，而且所有方案都有全球 CDN 加速功能，因而也备受用户青睐。 如今 Hostwinds 主机商提供的产品方案也非常丰富，包括虚拟主机、云主机、VPS主机以及独立主机等。目前 [Hostwinds](https://affiliates.hostwinds.com/hostwinds.php?id=7011&tid2=github&url=1216) 主要有达拉斯、西雅图 2 个数据中心，其中西雅图数据中心在国内访问速度最快。

现在 [Hostwinds](https://affiliates.hostwinds.com/hostwinds.php?id=7011&tid2=github&url=1216) 提供免费更换IP了，没错，就是免费，免费，随意更换，可以一键解决 IP 被墙的问题了。

限时活动，通过 [**本优惠链接**](https://affiliates.hostwinds.com/hostwinds.php?id=7011&tid2=github&url=1224) 进入Hostwinds 首页可以获得 6 折优惠，支持支付宝付款，欢迎购买注册。


.
.
.

#### 如果无法查看图片，可以访问：[美国VPS一键脚本搭建V2Ray最新中文教程](https://freepac.siterubix.com/%e7%be%8e%e5%9b%bdvps-hostwinds%e4%b8%80%e9%94%ae%e8%84%9a%e6%9c%ac%e6%90%ad%e5%bb%bav2ray%e6%9c%80%e6%96%b0%e4%b8%ad%e6%96%87%e6%95%99%e7%a8%8b/)

## **1、V2Ray简介**

#### **什么是V2Ray**

Project V 提供了单一的内核和多种界面操作方式。内核（V2Ray）用于实际的网络交互、路由等针对网络数据的处理，而外围的用户界面程序提供了方便直接的操作流程，简单来说，V2Ray就是一个代理软件，可以用来科学上网学习国外先进科学技术。

#### **V2Ray与Shadowsocks区别**

V2Ray是在Shadowsocks的作者被请喝茶之后出现的一个开源项目，目的就是为了更好的科学上网。相比于ss，V2Ray的定位是一个平台，任何开发者都可以在这个平台上利用V2Ray开发出一个新的代理软件，简单来说，ss的定位比较简单，功能也比较单一，而V2Ray的功能非常强大，相对的，V2Ray的**配置就会复杂很多**，喜欢鼓捣的同学可以试试。

#### **V2Ray的优势**

> - **更完善的协议:** V2Ray 使用了新的自行研发的 VMess 协议，改正了 Shadowsocks 一些已有的缺点，更难被墙检测到（不保证可靠性）
> - **更强大的性能:** 网络性能更好，具体数据可以看 V2Ray 官方博客
> - **更丰富的功能:**
>
> 以下是部分 V2Ray 的功能
>
> - mKCP: KCP 协议在 V2Ray 上的实现，不必另行安装 kcptun
> - 动态端口：动态改变通信的端口，对抗对长时间大流量端口的限速封锁
> - 路由功能：可以随意设定指定数据包的流向，去广告、反跟踪都可以
> - 传出代理：看名字可能不太好理解，其实差不多可以称之为多重代理。类似于 Tor 的代理
> - 数据包伪装：类似于 Shadowsocks-rss 的混淆，另外对于 mKCP 的数据包也可伪装，伪装常见流量，令识别更困难
> - WebSocket 协议：可以 PaaS 平台搭建V2Ray，通过 WebSocket 代理。也可以通过它使用 CDN 中转，抗封锁效果更好
> - Mux:多路复用，进一步提高科学上网的并发性能

## 2、美国VPS Hostwinds 购买

[**Hostwinds**](https://bit.ly/2RkMzMK) 是一家美国主机商，成立于 2010 年，国内站长使用较多的是 Hostwinds 美国 VPS 主机产品。由于 [Hostwinds](https://bit.ly/2UQ0Zqd) 美国 VPS 主机采用的是 SSD 硬盘，而且所有方案都有全球 CDN 加速功能，因而也备受用户青睐。 如今 Hostwinds 主机商提供的产品方案也非常丰富，包括虚拟主机、云主机、VPS主机以及独立主机等。目前 [Hostwinds](https://bit.ly/2RkMzMK) 主要有达拉斯、西雅图 2 个数据中心，其中西雅图数据中心在国内访问速度最快。现在 [Hostwinds](https://bit.ly/2UQ0Zqd) 提供免费更换IP了，没错，就是免费，免费，随意更换，可以一键解决 IP 被墙的问题了。通过 Hostwinds 搭建 V2ray 是不错的选择，今天就讲解下 Hostwinds 搭建 V2ray 教程。

首先确认不要使用任何代理，网络是什么 IP 就是什么 IP ，不然可能需要人工审核，导致 Hostwinds VPS 购买显示 "Pending" 状态， 不能即时创建服务激活。

1、通过[ Hostwinds 优惠链接进入](https://affiliates.hostwinds.com/hostwinds.php?id=7011&tid2=github&url=1224)Hostwinds 首页，选择 “VPS” 下的 "Unmanaged VPS" ，这里是最便宜的**(注意千万不要选择页面上 3.29 美元那个，那个是虚拟空间，不是 VPS !!!)**。

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218123839832-773141474.jpg)

2、进入 VPS 选择页面后，根据自己的需要的配置选择套餐，一般我们选择最低配置就够用了，然后点击 “Order” 按钮进入信息填写页面，如下所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218123900867-1301510135.jpg)

3、进入信息填写页面后首先填写账号信息，一般是新用户我们填写左边的姓、名、邮箱、密码，然后点击 “Submit” 进入下一步，如下图所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218123924864-1748236610.jpg)

4、页面跳转后填写用户信息，如下图所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218123926145-1078179475.jpg)

5、然后选择购买时间、数据中心 、操作系统，红色部分需要自己选择，绿色一般我们默认，可以按月购买，但是建议第一次购买时间选择长一点，这样优惠要大很多，不然后面续费优惠力度就没有这么大了。 如下图所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218123927440-696552732.jpg)

6、默认是自动云备份的，如果不需要去掉勾选， 如下图所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218123930711-100437514.jpg)

7、然后选择付款方式，一般我们选择支付宝进行付款 （只有国内 IP 访问的时候才有支付宝付款方式），如下图所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218123932418-465353102.jpg)

8、最后确认价格（不同时期可能价格有些许不同，如果通过前面优惠链接点击购买会有优惠），勾选同意协议，然后点击“Complete Order”按钮进行下单， 如下图所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218123934326-55279680.jpg)

9、下单完成后订单结果如下图所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218123936407-829196891.jpg)

10、完成购买后，你会收到一封邮件，里面包含 VPS 的IP地址、用户名、密码、ssh连接端口。如下图所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218123937796-250045283.jpg)

## 3、远程连接Hostwinds VPS

首先你需要通过 SSH 连接 [Hostwinds](https://bit.ly/2RkMzMK) 的 Linux VPS，连接 Linux VPS 需要使用 SSH 工具，这里推荐使用 Xshell 可以复制粘贴命令，Xshell 本身是需要付款的，作为中国人当然是使用 XX 版了，这里提供下载包如下所示：

Xshell 下载地址：<https://pan.baidu.com/s/1v7RCM0IjZGn_q5aWS1WXWg>，提取码: q3jw

下载后解压安装即可。

#### 使用 Xshell 连接 Linux VPS

1、打开 Xshell，点击左上角“文件”-“新建”，打开连接弹出库。

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124244713-1647003591.jpg)

2、在 Xshell 弹出框中输入 IP 和端口，端口一般是 22 默认，然后点击确认按钮，如下图所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124250720-300330092.jpg)

3、然后输入用户名 root，勾选记住用户名。

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124253161-1240759410.jpg)

4、然后输入密码，勾选记住密码，点击确定。

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124257243-392999321.jpg)

完成以上步骤后就可以看到连接成功的界面，如下图所示：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124314766-1649919428.jpg)

## 4、一键脚本搭建V2Ray

在上图的待输入内容处，粘贴下面的命令（复制下面的命令，然后在 Xshell 待输入内容处“鼠标右键”/“粘贴”即可）：

```
bash <(curl -s -L https://git.io/v2ray.sh)
```

> 如果提示 curl: command not found ，那是因为你的 VPS 没装 Curl
> ubuntu/debian 系统安装 Curl 方法: `apt-get update -y && apt-get install curl -y`
> centos 系统安装 Curl 方法: `yum update -y && yum install curl -y`
> 安装好 curl 之后就能安装脚本了

然后选择安装，即是输入 1 回车

选择传输协议，如果没有特别的需求，使用默认的 TCP 传输协议即可，直接回车

选择端口，如果没有特别的需求，使用默认的端口即可，直接回车

是否屏蔽广告，除非你真的需要，一般来说，直接回车即可

![Hostwinds搭建V2Ray](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124416227-1611081541.jpg)

是否配置 Shadowsocks ，如果不需要就直接回车，否则就输入 Y 回车

Shadowsocks 端口，密码，加密方式这些东西自己看情况配置即可，我个人当然是全部直接回车

OK，按回车继续

![Hostwinds一键搭建V2Ray](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124420241-1642255162.jpg)

安装信息，如果确保没有什么问题了，按回车继续

![VPS一键搭建V2Ray](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124430066-2136737201.jpg)

OK，出现这个界面就表示 V2Ray 已经安装完成了。

![VPS如何一键搭建V2Ray](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124432388-391582516.jpg)

如上图所示，V2Ray 配置信息，Shadowsocks 配置信息都有了

如果你使用过 Shadowsocks ，那么现在你可以测试一下 Shadowsocks 配置了，看看是否能正常使用。

如果你使用过 V2Ray 某些客户端，那么现在也可以测试一下配置了。

(备注，可能某些 V2Ray 客户端的选项或描述略有不同，但事实上，上面的 V2Ray 配置信息已经足够详细，由于客户端的不同，请对号入座。)

### 优化 V2Ray

由于本人的脚本在 Debian9 系统会自动开启 BBR 优化加速了，所以不需要再安装 BBR 优化了，如果你是使用其他商家的 VPS 并且是按照此教程流程来安装 V2Ray 的话，那么你可以输入 

```
v2ray bbr
```

回车，然后选择安装 BBR 或者 锐速 来优化 V2Ray

只是还想再啰嗦一下，如果你是使用国际大厂的 VPS，并且是按照此教程流程来安装 V2Ray 的话，请自行在安全组 (防火墙) 开放端口和 UDP 协议 (如果你要使用含有 mKCP 的传输协议)

## 5、客户端配置

下载地址：[客户端](https://github.com/v2ray/v2ray-core/releases)

对`v2ray-windows-64.zip`进行解压，然后将下载的`V2RayN.exe`复制到解压后的目录，即两个下载好的文件需要在同一目录。

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124455881-799496503.jpg)

**配置**

运行 V2RayN.exe，然后进行配置。

客户端的配置需要根据你的服务端进行相应的配置，因为你的服务端协议可能是 vmess,shadowsocks 等。

如果你的服务端配置是协议 vmess，则配置如下：

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124504308-202577752.jpg)

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124507038-1609781508.jpg)

![](https://img2018.cnblogs.com/blog/1765496/202002/1765496-20200218124510077-1432761155.jpg)

## 6、Hostwinds 搭建 V2Ray 总结

以上就是美国 VPS [Hostwinds](https://bit.ly/2RkMzMK) 搭建 V2Ray 的教程，通过教可以轻松实现 Hostwinds 搭建 V2Ray，希望可以帮助需要使用 Hostwinds 搭建 V2Ray 的朋友。

[Hostwinds 最好美国VPS低至4.49美元/月](https://affiliates.hostwinds.com/hostwinds.php?id=7011&tid2=github&url=1224)，支持支付宝付款，欢迎购买注册。


## 梯子-科学上网 请访问：科学上网工具使用教程：

**[https://github.com/xiaoming2028/kexueshangwang/wiki](https://github.com/xiaoming2028/FreePAC/wiki)**


