---
weight: 10
title : "重要知识"
---

<font color=#DC143C>

**警告：**

如果是防入室盗窃，防入侵，最佳方案一定是专业报警系统，不要用监控替代，否则会发生谋财害命的严重后果，这样的案例已经发生过多起了，所以在此特别提醒。

如果运气好，监控系统会记录下整个犯罪过程，但破案的概率其实很低，派出所里有大量的带监控记录的案子都没有破获，况且惯犯都会带手套、口罩、穿鞋套入室，进门后的第一件事情先拉闸断电，只要看到有监控，肯定会破坏销毁。

如果能现场躯离入侵者，还能及时给用户打电话，将可能会是最好的结局，监控系统确实没有这两个功能，恰好这是报警系统最主要的两个功能，这就是为什么要优先选择报警系统抵御入侵的原因。当然如果有条件将监控作为补充，最好不过了。

报警系统本身带后备电源，断电拉闸后能继续工作，触发后第一时间启动警报器，警报器声音足够驱离入侵者，并通过短信和电话通知用户，这是减小损失最有效的方式。除了这些，入户门其实是很关键的一个环节，有了专业的门禁系统，又会多一层防护，在此推荐门锁尽量用电插锁。至于为什么，请看[这里](/help/node1/lock-safety-analysis/)。

**特别提醒：**

因为现在有线电话和以太网都是通过光纤入户的，一旦断电，光猫（调制解调器）将无法工作，会导致无法上网和打电话，为了防止这种情况，我们推荐采用报警系统电源给光猫（调制解调器）统一供电，避免拉闸或停电后系统不能发消息给用户或中心。

</font>

<h2 id="j10">基本概念</h2>

---

安防即安全防范的简称。是做好准备和保护，以应付攻击或者避免受害，从而使被保护对象处于没有危险、不受侵害、不出现事故的安全状态。安防系统由报警系统、视频监控系统、门禁系统等系统的统称。这些系统不能相互替代，取长补短，相互配合，共同组成一个完整的安防系统。

<h3 id="j12">报警系统</h3>

报警系统利用传感器技术和电子信息技术探测并指示非法进入或试图非法进入设防区域的行为、处理报警信息、发出报警信息的电子系统或网络。入侵报警系统是在事情发展之前即起作用，可以防患于未然，避免财产损失。

报警系统由前端探测器，主机，操作键盘，电源（含UPS），警号，通信模块组成。

报警主机：报警系统的“大脑”部分，接收前端设备信号并处理运算，如果发生报警，启动警号，及时制止事态进一步发展，并且通过电话、短信和网络等方式发出报警消息到用户手机或者接警中心。

<h3 id="j13">视频监控系统</h3>

视频安防监控系统利用视频技术探测、监视设防区域并实时显示、记录现场图像的电子系统或网络。监控系统主要作用是事后取证。

<h3 id="j14">门禁系统</h3>

门禁系统利用自定义符识别或/和模式识别技术对出入口目标进行识别并控制出入口执行机构启闭的电子系统或网络。门禁系统是出入口管制。

<h2 id="j20">报警系统 - 专业名词解释</h2>

---

<h3 id="j201">防区（Zone）</h3>

<p id="j2011">最小防护的区域。通常是指一个探测器。防区类型是指对防区触发时相应的基本分类。通常主要有三种，立即防区、延时防区和24小时防区。</p>

- 立即防区（Instant Zone）：触发时立即报警；
- 延时防区（Delay Zone）：触发后如果在延时内未及时撤防将会报警，通常将安装出入口处的防区设置为进入延时防区；
- 24小时防区（24hr. Zone）：是指在任何时候触发都会立即报警，跟系统是否布撤防无关，如烟雾探测器，有毒气体探测器，紧急求助按钮，水浸探测器等。

<h3 id="j202">分区（Partition）</h3>

分区：是对防区的分组。对系统布撤防指的是对分区的布撤防，并不是针对某个防区。

<p id="j2021">退出延时（Exit Delay）：系统布防后会启动倒计时，方便用户布防后安全撤离。</p>

- 布防是让系统进入防守状态，分为两类：外出布防和留守布防
  - **外出模式（Away）**：顾名思义，就是用户离开防护区域，在这种布防模式下，系统中所有的防区将会启动工作。
  - **留守模式（Stay）**：同理，指系统留给用户某些活动区域，这些区域的防区暂时停止工作，但其他区域的防区会进入工作模式，这种模式能让用户自由活动确不失安全，通常的做法是把室内活动区域作为留守防区，留守布防后仅室外防区生效。
- 撤防（Disarm）：解除系统警戒状态，可以通过键盘，遥控器，手机，电脑等方式实现。

> <p id="j2022">枫叶安防系统的布防模式说明：</p>
>
> - EVO系列：
>   - 外出模式：
>      - **常规布防（Regular Arming）**，所有防区（防区都必须是闭合的）将会被布防。
>      - **强制布防（Force Arming）**，布防的时候若有开路的防区，**会暂时忽略开路的防区**，然后执行布防，被忽略的开路防区一旦闭合，将会被重新启用。
>   - 留守模式：
>      - **立即布防（Instant Arming）**，所有非留守防区都会被布防（防区选项被定义为Stay的防区将会失效），且延时防区一旦被触发，会立即报警。
>      - **留守布防（Stay Arming）**，所有非留守防区都会被布防（防区选项被定义为Stay的防区将会失效）。
>
> - SP/MG系列：
>   - 外出模式：
>      - **常规布防（Arming）**，所有防区（防区都必须是闭合的）将会被布防。
>   - 留守模式：
>      - **留守布防（Stay Arming）**，留守布防（防区类型被定义为Full或Sleep的防区将会失效）是一种部分区域布防的模式。
>      - **睡眠布防（Sleep Arming）**，睡眠布防（防区类型被定义为Full的防区将会失效，防区类型被定义为Sleep的防区一旦触发，在发生报警前会启动一个延时）是为了更细化留守情况下的一种模式，也属部分区域布防模式。
>
><font color=#DC143C>**注意：**</font>
>
> 1. <font color=#DC143C>只有**强制布防**可以忽略当前开路（触发）状态的防区，前提是这些开路防区的强制属性（默认开启）必须是开启的。其余布防方式都必须在防区闭合（非触发）状态才可以操作。</font>
>
> 2. <font color=#DC143C>**强制布防**的时候，清楚防区开路的原因、且被忽略不影响系统安全性的前提下才可以操作。</font>

<h3 id="j203">用户</h3>

用户是系统一个重要的组成部分，每一个用户拥有一个独立的密码、遥控器、无线紧急求助按钮或者卡，有了密码、遥控器就可以对系统进行布/撤防等操作，每个用户拥有不同权限，有使用系统的最高权限的用户是管理员，其次是普通用户，普通用户的权限是管理员去分配。另外还有安装者，安装者拥有安装和调试系统的所有权限。

这里解释一下胁迫密码，在编程的时候，将某一个用户的胁迫属性开启后，这个用户的密码将具有胁迫属性，如果发生报警后，用户手机或者接警中心会受提示这条事件是在胁迫下发生的。

注意，安装者和管理员并不是权限一样大，只是职责不同，安装者虽然有设置系统的权利，但是必须是管理员授权的时候才可以。

<h3 id="j204">探测器</h3>

探测器从原理上分有红外、微波、震动、烟雾探测、温度探测、湿度探测、气体探测、压力、玻璃破碎，三维坐标位移、压力、水浸探测等。

入侵探测器主要是红外原理，分主动红外和被动红外，对射是典型的主动红外，在门/窗/空间防护上主要是被动红外探测器。

微波探测器应用的是多普勒效应原理。在微波段，当以一种频率发送时，发射出去的微波遇到固定物体时，反射回来的微波频率不变，即f发=f收，探测器不会发出信号。当发射出去的微波遇到移动物体时，反射回来的微波频率就会发生变化，即f发≠f收，此时微波探测器将发出信号。

为了提高探测精度，通常将多种不同技术原理的探测器整合在一起，只有当2种探测技术的传感器都探测到人体移动时才报警的探测器称为双鉴探测器。市面上常见的双鉴探测器以微波加被动红外居多。为了进一步提高探测器的性能，在双鉴探测器的基础上又增加了第三种技术的探测器称为三鉴探测器。在三鉴探测器上再增加另一种技术的探测器成为四鉴探测器。

震动探测器是以探测入侵者进行破坏活动时所产生的振动信号作为触发依据，例如,入侵者在进行凿墙、钻洞、撬保险柜等破坏活动时，都会引起这些物体的振动。以这些振动信号来作为触发依据的探测器就称为震动探测器。据所使用的振动传感器的不同,振动探测器可分为：机械式振动探测器、惯性棒电子式振动探测器、电动式振动探测器、压电晶体振动探测器、电子式全面型振动探测器等多种类型。近来常见的以压电晶体振动探测器居多，其原理是利用压电晶体的压电效应。压电晶体是一种特殊的晶体,它可以将施加于其上的机械作用力转变为相应大小的电信号，其电信号的频率及幅度与机械振动的频率及幅度成正比，当信号值达到设定值时就发出信号。

当敲击玻璃而玻璃还未破碎时会产生一个超低频的弹性振动波,这种机械振动波低于20Hz，属于次声波。玻璃破碎时发出的响亮刺耳的声音频率大约在10～15KHZ的范围内，属于高频声音。玻璃破碎探测器同时检测到低频与高频时将会触发。

探测器标准输出有源总线数字信号和无源开关量信号，开关量方式有常开、常闭、或常开/常闭可选型，其中常闭多见，常开少见，原因是常开探测器接入要回路中没有形成回路（或者要借助电阻才能形成回路），有安全隐患。

<h3 id="j208">其他</h3>

警号（Bell）：

现场报警，启动警号发出警报声和闪灯，起到提醒和警示作用，或驱离入侵者，是重要组成部分，绝不可缺。

电源（UPS）：

不间断电源，异常断电后使系统继续正常工作，是重要组成部分，绝不可缺。

键盘（Keypad）：

人机交互的介质，用来布撤防系统、维护系统、报警记录查询（事后取证）等功能，是重要组成部分，绝不可缺。

接警中心（CMS）：

通过电话，网络等方式接收报警信号到报警接收机然后上传到接警服务器电脑，通过平台软件解析、呈现并做出响应。

报警（Alarm）：

启动的防区在被触发后会引发系统报警，通过键盘，警号提示，并将报警消息发送至用户手机或者接警中心的行为。

继电器（PGM）：

可编程继电器，报警系统可以在某个条件（可以通过系统编程设置触发的条件）满足的时候自动驱动继电器输出信号。