---
title: 绿通智慧管理系统——常规维护办法
date: 2018-09-29 15:20:00
tags:
---
&emsp;&emsp;<font size=4>本文旨在向使用甘肃紫光绿通智慧管理系统的用户介绍绿通智慧管理系统的常规维护办法。</font>

# 一.手持机图片上传至监控室，收费管理软件无法调阅图片

# &emsp;解决方案：
&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>1.查看网络前缀长度是否配置为27（224），28（240），26（192）括号内数</font>
&emsp;&emsp;&emsp;<font size=4>字为对应网关的子网掩码，用户需根据各站点子网掩码选择填写的网络前缀长度。</font>
&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>2.检查图像服务器IP是否正确，若IP正确则pingIP检验网络是否畅通（进cmd：</font>
&emsp;&emsp;&emsp;<font size=4>pingIP）。或浏览器中，图像服务器ip：3000端口号，如下图：</font>

![image](/pub-images/news-images/maintain/browser.png)

# 二．一键联动提示“一键联动超时”

# &emsp;解决方案：
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>1.查看车道配置工具有没有启动绿通手持机。</font>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>2.查看车道软件上有没有进行“绿色通道”车情确认操作。</font>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>3.检查网络是否畅通。</font>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>4.车道机IP地址与手持机选择IP地址是否一致。</font>
# 三．输入法相关问题

# &emsp;解决方案：
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>1.输入法不方便的可以连接网络自行下载习惯的输入法。</font>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>2.讯飞输入法没有启用的可以参考本站中的“绿通智慧管理系统——手持机</font>
&emsp;&emsp;&emsp;&emsp;<font size=4>输入法启用”。</font>
# 四．上传数据之后监控未同意审批，车道票员可以正常放行车辆

# &emsp;解决方案：
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>审批这没有做强制是和收费处沟通确定的，如果需要强制，请给收费处反应。</font>
# 五．像主线站上班人员比较多，验货人员不能确定，绿通宝切换验货人员需要退出登	录从新登录

# &emsp;解决方案：
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>验货人员可以选择把一个班组的人都添加上，能够还原一个班组即可，不用细</font>
&emsp;&emsp;&emsp;&emsp;<font size=4>细化到每辆车是谁查验的。</font>

# 六．手持机界面提示“请输入正确的绿通设备IP地址”或“请输入正确的绿通设备端口号”如下图所示：
![image](/pub-images/news-images/maintain/error_ip.png)

# &emsp;解决方案：
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>在系统登陆界面，进入设备配置；关闭启用第三方检测。</font>

# 七．登陆界面提示“数据库文件异常”。

# &emsp;解决方案：
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=4>登陆界面，进入系统配置，检查配置是否正确（基本信息配置，服务配置）</font>

# 八．输入工号点击登陆时无反应或登陆成功，人员信息选择完成后点击确认无反应时。

# &emsp;解决方案：
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font size=5>请联系管理员。</font>

