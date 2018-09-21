# Tutorial for SS

* [Android](#Android)
* [IOS](#IOS)
* [Windows](#Windows)
* [MacOS](#MacOS)

## Android

下载安装以下两个app

* [shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases/download/v4.5.7/shadowsocks-arm64-v8a-4.5.7.apk)
* [simple-obfs-android](https://github.com/shadowsocks/simple-obfs-android/releases/download/v0.0.5/obfs-local-nightly-0.0.5.apk)

安装完成后打开shadowsocks点击右上角的`+`号，然后选择扫描二维码。成功识别出配置之后，点击右下角的图标就能用啦。

## IOS

1. 在App store下载ShadowRocket
![](/images/IMG_0042.png)

2. 添加相应配置
![](/images/IMG_0041.jpg)

3. 完成之后点击首页中间的按钮即可使用啦
![](/images/IMG_0043.png)

## Windows

1. 此处下载[Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases)最新版（选择latest release那份）

![](/images/7.png)

2. 直接解压打开`Shadowsocks.exe`，右下角会出现`纸飞机`图标

![](/images/8.png)

3. 右键点击`纸飞机`图标，选择`Servers`-->`Edit Servers`，然后点击左下角`Add`添加配置，像手机一样配置好服务器IP地址、端口、密码、还有加密算法即可。
![](/images/9.png)

4. 继续右键点击`纸飞机`图标，点击`Enable System Proxy`，并且选择`Mode`-->`PAC`，然后就可以畅游网络了。

5. 以下步骤是可选的，如果想要更好的体验，那么建议继续往下走

6. （若已安装Chrome，直接跳到第七步）上述步骤完成后，选择`Mode`-->`Global`，打开[https://www.google.com/chrome/](https://www.google.com/chrome/)，下载安装Chrome浏览器。安装完成之后再把设置改回`Mode`-->`PAC`

7. 打开[Chrome Store](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif)，安装`Proxy SwitchyOmega`插件。

8. 右键击此图标，选择`Options`

![](/images/10.png)

9. 点击右下角`New profile`，Profile name命名为`Shadowsock`

![](/images/11.png)

10. 填写如下配置

![](/images/13.png)

11. 点击左下角`AutoProxy`，按照下图填写配置，Rule List URL为：`https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt`，填写好后点击`Download Profile Now`

![](/images/12.png)

12. 点击右下角`Apply changes`，关闭页面，左键点击右上角的图标，选择`AutoProxy`。OK全部完成，可以畅游网络了。

## MacOS

1. 此处下载[ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG/releases)的最新版（选择latest release那份）

![](/images/3.png)

2. 直接打开解压安装，右上角会出现一个`纸飞机`的图标

![](/images/4.png)

3. 点击它，选择服务器设置

![](/images/5.png)

4. 跟手机一样，配上IP地址、端口、加密算法、密码

![](/images/6.png)

5. 如上面第三步的截图一样，选择配置好的服务器（打勾）。然后选择`PAC自动模式`就OK了，直接打开浏览器就能畅游网络。如果还遇到访问不了的网站，就切换到`全局模式`再试试。