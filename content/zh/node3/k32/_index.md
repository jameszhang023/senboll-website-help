---
title : "键盘(K32)说明书"
linktitle: 键盘(K32)使用说明
description: 这是K32操作键盘说明书
date: 2020-11-27
publishdate: 2020-11-27
lastmod: 2020-11-27
keywords: [ssg，static，performance，security]
menu:
  docs:
    parent: "用户指南"
    weight: 94
weight: 90
sections_weight: 30
draft: false
aliases: []
layout: single
toc: true
---

## 简介

这款键盘最多支持32个防区，面板上只有按钮和led指示灯，如果熟练掌握了使用方法，会很简单易用，缺点是不够直观。

![k32操作键盘](images/keypad-k32+-english-thumbnail.png)

## 功能参数

- 时尚的3D外观设计
- 支持StayD安全模式
- 32防区状态LED实时显示
- 每个分区有独立的 布防 / 睡眠 / 留守 / 撤防 的LED状态指示
- 通过307USB和WinLoad进行现场固件升级
- 1个键盘防区输入
- 独立设置的门铃防区
- 7个一键式操作功能键定义
- 同时按下3个键激活的紧急警报(110报警，119火警，120急救)
- 可调背光亮度
- 连接到4芯通讯总线
- 与MG5000，MG5050，MG5075和Spectra SP系列兼容
- 符合安规 EN50131 二级

## 使用指南

面板图标说明：
![k32操作键盘](images/k32-button-description.png)

### 布防

**布防**：顾名思义布置防护，让系统启动防护功能，或进入防护工作状态，此时已布防的防区一旦触发，会发生[报警](../../node1/important-knowledge/#%E6%8A%A5%E8%AD%A6alarm)。布防可以通过安防操作键盘，遥控器，手机APP，短信，电话，电脑等方式实现。

1. 键盘上输入用户密码（默认1234）→ {{< button >}}ARM{{< /button >}}灯闪烁，开始倒计时，{{< button >}}ARM{{< /button >}}灯常亮，系统布防成功。
2. 在键盘上长按{{< button >}}ARM{{< /button >}}键2秒以上，{{< button >}}ARM{{< /button >}}灯闪烁，开始倒计时，{{< button >}}ARM{{< /button >}}灯常亮，系统布防成功。

### 撤防

**撤防**：顾名思义撤销防护，让系统撤销防护功能，或停止防护工作状态，此时已撤防的防区触发，不会发生报警。

键盘上输入用户密码（默认1234）- {{< button >}}OFF{{< /button >}}灯常亮，系统撤防成功。

### 解除报警

{{< warning >}}
一旦有报警发生，应第一时间力求减少人身和财产的损失，直到这种危险解除后，才能解除报警！
{{< /warning >}}

当系统发生报警时，键盘会显示某个防区报警，直接输入用户密码（默认1234），系统会解除报警，当系统有多个分区报警时，仅解除当前处于报警状态的分区，其余分区状态不变。

{{< tip >}}
另外如果有紧急按钮触发过报警，在系统解除报警后，需要使用专用复位钥匙（紧急按钮出厂带的专用配件）对其复位。
{{< /tip >}}

### 查看防区状态

键盘上{{< button >}}1{{< /button >}} - {{< button >}}0{{< /button >}}，10个数字按钮分别对于1-10防区的状态，哪个防区开路（触发），哪个按钮就会亮，这些待机状态时总是实时显示的。

### 查看故障

{{< warning >}}
一旦有故障发生，都会实时显示到屏幕上，为了系统正常使用，应尽快排除故障。如需支持，请联系安装人员或者直接拨打全国服务热线400-002-5577。
{{< /warning >}}

按{{< button >}}TBL{{< /button >}}键去查看故障显示，当系统每产生一个新的故障，键盘将会每5秒发出‘滴滴’声，按{{< button >}}TBL{{< /button >}}键停止发声，对照下表按相应的按键，查看具体故障，按{{< button >}}CLEAR{{< /button >}}退出。

故障说明如下：

| 故障主菜单 | 故障子菜单 |
|---|---|
|{{< button >}}1{{< /button >}}无线防区低电量|{{< button >}}1{{< /button >}}到{{< button >}}32{{< /button >}}防区低电量|
|{{< button >}}2{{< /button >}}电源故障|{{< button >}}1{{< /button >}}报警主机低/无电量</br>{{< button >}}2{{< /button >}}报警主机交流电故障</br>{{< button >}}3{{< /button >}}报警主机辅助电源过载</br>{{< button >}}4{{< /button >}}无线键盘AC故障</br>{{< button >}}5{{< /button >}}无线键盘蓄电池故障</br>{{< button >}}6{{< /button >}}无线中继器AC故障</br>{{< button >}}7{{< /button >}}无线中继器蓄电池故障</br>{{< button >}}8{{< /button >}}无线声光警号交流电故障</br>{{< button >}}9{{< /button >}}无线声光警号电池故障|
|{{< button >}}3{{< /button >}}警铃故障|{{< button >}}1{{< /button >}}警铃未接</br>{{< button >}}2{{< /button >}}警铃过载|
|{{< button >}}4{{< /button >}}通讯故障|{{< button >}}1{{< /button >}}报警主机电活线监测故障</br>{{< button >}}2{{< /button >}}中心电话号码1与报警主机通讯失败</br>{{< button >}}3{{< /button >}}中心电话号码2与报警主机通讯失败</br>{{< button >}}4{{< /button >}}寻呼机号码与报警主机通讯失败</br>{{< button >}}5{{< /button >}}语音电话号码与控制主机通讯失败</br>{{< button >}}6{{< /button >}} PC与报警主机通讯失败</br>{{< button >}}7{{< /button >}}与IP接收机或2通讯失败(GPRS)</br>{{< button >}}8{{< /button >}}与IP接收机或2通讯失败(IP)</br>{{< button >}}9{{< /button >}}GSM无服务(GSM网络故障)</br>{{< button >}}10{{< /button >}}IP模块无服务(网络故障)</br>{{< button >}}STAY{{< /button >}}GSM  RF干扰</br>{{< button >}}OFF{{< /button >}}IP接收机没有注册(IP/GPRS)|
|{{< button >}}5{{< /button >}}防拆和防区线路故障|{{< button >}}1{{< /button >}}到{{< button >}}32{{< /button >}}防区防拆和线路故障|
|{{< button >}}6{{< /button >}}模块防拆故障|{{< button >}}1{{< /button >}}2WPGM防拆故障</br>{{< button >}}2{{< /button >}}键盘总线防拆故障</br>{{< button >}}3{{< /button >}}ZX8总线模块防拆故障</br>{{< button >}}4{{< /button >}}RTX3总线模块防拆故障</br>{{< button >}}5{{< /button >}}无线声光警号故障|
|{{< button >}}7{{< /button >}}火警回路故障|{{< button >}}1{{< /button >}}到{{< button >}}32{{< /button >}}火警防区回路故障|
|{{< button >}}8{{< /button >}}时间丢失|-|
|{{< button >}}9{{< /button >}}无线防区监测失败|{{< button >}}1{{< /button >}}到{{< button >}}32{{< /button >}}防区监测失败</br>{{< button >}}STAY{{< /button >}} RF干扰故障|
|{{< button >}}0(10){{< /button >}}模块监测失败|{{< button >}}1{{< /button >}} 2WPGM</br>{{< button >}}2{{< /button >}}键盘总线故障(主机恢复不能清除此故障，要清除此故障，查看段号{{< button >}}955{{< /button >}})</br>{{< button >}}3{{< /button >}} ZX8总线模块故障</br>{{< button >}}4{{< /button >}}RTX3总线模块故障</br>{{< button >}}5{{< /button >}}无线键盘监测丢失</br>{{< button >}}6{{< /button >}}无线中继器监测丢失</br>{{< button >}}8{{< /button >}}VDMP3模块故障</br>{{< button >}}9{{< /button >}}PCS系列模块故障</br>{{< button >}}10{{< /button >}}IP模块故障</br>{{< button >}}STAY{{< /button >}}无线声光警号|
|{{< button >}}16{{< /button >}}键盘故障( K32/ K32RF)||
|{{< button >}}17{{< /button >}}请将主机升级到V32或更高版本||
|{{< button >}}SLEEP{{< /button >}}键盘故障(K10V/H  K636)||

### 查看报警记录

在系统撤防情况下，当有报警记录时，{{< button >}}MEM{{< /button >}}键会亮起，按下{{< button >}}MEM{{< /button >}}键，键盘上哪个键亮灯，说明该防区之前报警了，按{{< button >}}CLEAR{{< /button >}}退出。

### 设置门铃防区

如果有个防区触发后，键盘或主机会有类似门铃的声音提示，这就是门铃防区功能。可以用来提示是否有人出现，通常在出入口会用到。

长按{{< font-segmdl2 >}} &#xEB0F {{< /font-segmdl2 >}}3秒，当响起‘滴滴’声，输入2位数防区号，比如输入02表示防区2，同时对于的防区led会闪烁，表示该防区的门铃功能已开启，取消门铃设置的方法同理，防区指示led灭表示门铃关闭。

### 校正系统时间

对于整个系统来说，需要记录所有发生的事件或者日志所发生的时间，就需要时钟功能，由于系统的时钟通常不能联网自动校准，时间长了会有误差，就需要人为校正。

1. 按下{{< font-segmdl2 >}} &#xE7E8 {{< /font-segmdl2 >}}键
2. 输入管理员密码（默认1234），此时{{< font-segmdl2 >}} &#xE7E8 {{< /font-segmdl2 >}} 和按钮{{< button >}}1{{< /button >}}开始闪烁
3. 按{{< button >}}TBL{{< /button >}}键
4. 按{{< button >}}5{{< /button >}}键，此时{{< button >}}ARM{{< /button >}}灯闪烁
5. 输入时间HH:MM，此时{{< button >}}ARM{{< /button >}}灯常亮，{{< button >}}SLEEP{{< /button >}}闪烁
6. 输入年份YYYY，此时{{< button >}}SLEEP{{< /button >}}灯常亮，{{< button >}}STAY{{< /button >}}闪烁
7. 输入月份MM，此时{{< button >}}STAY{{< /button >}}灯常亮，{{< button >}}OFF{{< /button >}}闪烁
8. 输入日期MM，此时{{< button >}}OFF{{< /button >}}，{{< button >}}TBL{{< /button >}}和{{< button >}}5{{< /button >}}闪烁
9. 按{{< button >}}CLEAR{{< /button >}}退出

注意：依次按照HH:MM，YYYY，MM，DD输入时间。当输入小时HH=0-12，会出现3个选项，分别是{{< button >}}1{{< /button >}}24小时制，{{< button >}}2{{< /button >}}AM，{{< button >}}3{{< /button >}}PM；当输入HH=13-23，没有选项。
