# 2.3 抓拍机模式

## 抓拍机模式

## 一、系统网络图

1. 参考下图，将各个设备加入同一局域网络内。  


   ![img](../../.gitbook/assets/wang-luo-zhua-pai-ji.png)  

## 二、设置抓拍机设备

1. 使用Chrome浏览器，登陆到抓拍机Web页面。 不同的抓拍机登陆界面不尽相同，本文中以大华抓拍机\(IPC-HFW4243K-ZFD-LED\)举例说明。  ![](../../.gitbook/assets/image2019-2-28_20-52-29.png) 
2. 进入存储管理，打开存储，配置左右两个ftp如图所示。  ![](../../.gitbook/assets/image2019-3-7_14-19-30.png) 
3. 设置FTP存储地址到SE3  ![](../../.gitbook/assets/image2019-2-28_21-7-14.png) 
4. 确认打开智能方案中的人脸检测。  ![](../../.gitbook/assets/image2019-3-7_14-12-38.png) 
5. 确认启用人脸检测和人脸抓图。  ![](../../.gitbook/assets/image2019-3-7_14-20-47.png) 
6. 选择要修改的用户名。  ![](../../.gitbook/assets/image2019-3-6_16-11-36.png)
7. 点击修改密码, 设置pyonvif得用户名和密码为：admin 和 bitmain2018。  ![](../../.gitbook/assets/image2019-3-7_17-32-46.png) 
8. 重启抓拍机。

## 三、SE3 AI迷你机设置

1. 使用Chrome浏览器，打开SE3 web界面: [https://se3-ip:8886/，然后输入用户名和密码（默认均为admin）。](https://se3-ip:8886/，然后输入用户名和密码（默认均为admin）。)  ![](../../.gitbook/assets/image2019-2-28_15-51-13.png) 
2. 设置工作模式为“本地模式”  ![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_19-30-18.png](../../.gitbook/assets/image2019-2-28_19-30-18%20%281%29.png) 
3. 设置摄像机类型为“抓拍模式”  ![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_20-37-45.png](https://github.com/Bitmain-103105/AIBOXAPI/tree/37bce7deb4738bb8902aae06dc43e37c365521b2/zh/V2R2C01/imgs/image2019-2-28_20-37-45.png?version=1&modificationDate=1551357465000&api=v2) 
4. 添加对应用用户组

增加完成后如下图所示。可以点 “Add”继续增加其它用户组。  


![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_16-17-32.png](../../.gitbook/assets/image2019-2-28_16-17-32.png)

![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_16-11-21.png](../../.gitbook/assets/image2019-2-28_16-11-21%20%281%29.png)

1. 为用户组增加相应的用户  ![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_16-12-24.png](../../.gitbook/assets/image2019-2-28_16-12-24.png)  ![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_16-23-3.png](../../.gitbook/assets/image2019-2-28_16-23-3.png)  增加完毕后，用户列表显示如下：  ![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_16-26-35.png](../../.gitbook/assets/image2019-2-28_16-26-35.png) 
2. 添加抓拍机  


   ![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_20-40-7.png](../../.gitbook/assets/image2019-2-28_20-40-7.png)

   通常网络环境下，所有连接到局域网中的抓拍机设备会自动出现在列表中，请按需要勾选并添加。但如抓拍机没有自动出现在设备列表中，这时你也可以选择手工添加的方式添加设备。  
    ![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_20-43-36.png](../../.gitbook/assets/image2019-2-28_20-43-36.png)  


   选择 Details 编辑设备信息  
    ![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_20-46-32.png](../../.gitbook/assets/image2019-2-28_20-46-32.png)  


   ![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_20-47-43.png](../../.gitbook/assets/image2019-2-28_20-47-43.png)

## 四、系统功能验证

1. 人脸识别验证

   请系统中已经注册的人员站在抓拍机的合适位置（抓拍机焦距不同，对应的可识别位置范围也不同，以实际为主）。再到事件历史记录页面查看历史记录，正常情况下，可以看到识别成功的事件。  


   ![AI BOX &amp;gt; &#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x7CFB;&#x7EDF;&#x6293;&#x62CD;&#x673A;&#x6A21;&#x5F0F;&#x5FEB;&#x901F;&#x914D;&#x7F6E;&#x6307;&#x5357; &amp;gt; image2019-2-28\_21-11-2.png](../../.gitbook/assets/151566441615_.pic_hd.jpg)  

