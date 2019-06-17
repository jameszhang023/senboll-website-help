---
weight: 10
title : "工具软件(Babyware)使用说明"
---

**目录**

- [简介](#j10)
- [准备工作](#j20)
  - [安装软件](#j201)
  - [安装驱动](#j202)
  - [必备硬件](#j203)
- [首次使用](#j30)
- [操作说明](#j40)
  - [操作说明 - 编程防区](#j401)
  - [操作说明 - 编程遥控器](#j402)
  - [操作说明 - 警号](#j403)
  - [操作说明 - 退出延时](#j404)
  - [操作说明 - 短信通知设置方法](#j405)
  - [操作说明 - 电话语音通知设置方法](#j406)
  - [操作说明 - 查看无线信号强度方法](#j407)

<h2 id="j10">简介</h2>

---

Babyware软件是用来设置、调试、售后维护枫叶安防系统的专用工具软件，非常直观，高效。支持汉语，支持枫叶全系列主机，支持串口、网络、拨号等通讯方式。

<h2 id="j20">准备工作</h2>

---

<h3 id="j201">安装软件</h3>

下载软件，下载Babyware请访问[资料服务器](http://support.senboll.com:8888/)。

![Babyware下载](/help/node2/babyware/images/babyware-download.png)

<h3 id="j202">安装驱动</h3>

如果是串口通讯方式，需要准备好307USB通讯模块，请先安装串口驱动。驱动下载请访问[资料服务器](http://support.senboll.com:8888/)。请根据Windows系统版本下载并安装驱动，如下图：

![307USB驱动下载](/help/node2/babyware/images/307usb-driver-download.png)

如果安装驱动遇到困难，请参考下面的步骤。

![307USB驱动安装](/help/node2/babyware/images/307usb-driver-install.gif)

<h3 id="j203">必备硬件</h3>

串口直连方式需要准备307USB模块：

![307USB](/help/node2/babyware/images/307usb.png)

以太网方式需要准备网络模块：

![IP150](/help/node2/babyware/images/ip150.png)

<h2 id="j30">首次使用</h2>

---

步骤一：启动Babyware，默认用户名是`Admin`,密码是`1234`。

步骤二：创建账户，选择主机型号，汉化软件，设置连接参数，请参考下面演示动画：

![初始化](/help/node2/babyware/images/babyware-initialize.gif)

设置连接方式，选择合适的方式建立连接。

- 串口方式，需要307USB通讯模块。
- IP/Panel S/N方式，需要网络模块，通过天鹅云方式连接，Panel S/N 填主机8位序列号，IP模块访问密码默认是`paradox`。
- IP/Static静态地址，通过IP地址连接，填入IP地址和IP Port（IP Port默认是10001），IP Module Password默认是`paradox`。

<h2 id="j40">操作说明</h2>

---

<h3 id="j401">操作说明 - 编程防区</h3>

防区分为有线防区和无线防区，其中有线防区分为板载防区和扩展防区，板载防区是主机板自带的防区，扩展防区是其他模块上的防区。下面演示一下编程方法：

**提示：防区类型的概念参考请点[防区类型说明](/help/node1/important-knowledge/#j2011)。**

板载防区编程方法：

![板载防区编程](/help/node2/babyware/images/babyware-programing-wire-zone-1.gif)

扩展防区编程方法：

![板载防区编程](/help/node2/babyware/images/babyware-programing-wire-zone-2.gif)

无线防区编程方法：

![板载防区编程](/help/node2/babyware/images/babyware-programing-wireless-zone.gif)

<h3 id="j402">操作说明 - 编程遥控器</h3>

请参考：

![初始化](/help/node2/babyware/images/babyware-programing-remote.gif)

<h3 id="j403">操作说明 - 警号</h3>

下面是无线警号编程方法演示：

![初始化](/help/node2/babyware/images/babyware-programing-wireless-siren.gif)

警号鸣笛时间设置请看下面演示：

![初始化](/help/node2/babyware/images/babyware-programing-bell-cut-off-timer.gif)

<h3 id="j404">操作说明 - 退出延时</h3>

**提示：退出延时的概念参考请点[退出延时概念](/help/node1/important-knowledge/#j2021)。**

![初始化](/help/node2/babyware/images/babyware-programing-exit-delay.gif)

<h3 id="j405">操作说明 - 短信通知设置方法</h3>

需要设置3个参数，分别是手机号，分配所属分区和通知事件类型。也可以通过触摸屏键盘进入菜单 → 高级设置 → SMS短信设置。Babyware软件方式设置请参考动画：

![初始化](/help/node2/babyware/images/babyware-sms-setting.gif)

通过Babyware设置中文短信，如果失效的话，请用键盘进入高级编程设置，具体的方法如下：

- EVO主机-在触摸屏键盘上操作步骤：菜单 → 高级设置 → 安装设置 → 系统编程 → 输入`000000` → 输入`2953` → 输入`019`。
- SP/MG主机-在触摸屏键盘上操作步骤：菜单 → 高级设置 → 安装设置 → 系统编程 → 输入`0000` → 输入`856` → 输入`019`。

<h3 id="j406">操作说明 - 电话语音通知设置方法</h3>

请参考动画：

![初始化](/help/node2/babyware/images/babyware-tel-setting.gif)

<h3 id="j407">操作说明 - 查看无线防区信号强度方法</h3>

**针对EVO系列主机：**

说明：EVO主机所有的无线设备是通过无线收发模块RTX3来接入的，每一个RTX3最多可以接入32个无线探测器，在RTX3里面有32个段号来查询每一个防区的信号强度，即：601-632，例如需要查询RTX3里第1个无线防区的信号强度，输入601即可，如果是第5个无线防区的信号强度，输入605即可。注意这里说的第一个无线防区，并不是防区001，而是此RTX3里定义的第一个防区，RTX3里的第一个防区可以通过编程设置为任何序号的防区，具体方法请参考上文中的防区编程。

如果要查询RTX3的第一个防区信号强度，请参考下面的步骤，其他以此类推：
在触摸屏键盘上操作步骤：**菜单** → **高级设置** → **安装设置** → **系统编程** → 输入`000000` → 输入`4003` → 输入RTX3八位序列号 → 输入`601` → 再去触发探测器，键盘上将会显示信号强度。`|<<<<<<<<<<|`这个表示信号是100%，即最强，如图：

![查看信号强度](/help/node2/babyware/images/view-wireless-signal-strength.png)