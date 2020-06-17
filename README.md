# ibm_cf_restart-actions
使用Github Actions定时重启IBM Cloud Foundry应用程序

## 使用之前，有几项准备工作
1. IBMCloud的账号密码
2. Cloud Foundry应用程序的区域
3. Cloud Foundry应用程序的名称

## 使用方法

### 1 Fork此仓库

### 2 设置此仓库的变量

![](http://tu.yaohuo.me/imgs/2020/06/750d9a9a867979ce.png)

依次添加名为**MAIL**、**PWD**、**RGN**、**CFNAME**的变量  
值分别为邮箱(账号)、密码、区域、Cloud Foundry应用程序的名称(同时是链接前缀)  

### 3 确定Github Action正常工作

点击修改任意文件后提交使Actions激活  

此前，可能需要点击**Pull requests**与**Projects**之间的**Action**进去点一下允许之类的

### 变量示例
MAIL====>12345@qq.com  
PWD====>123456QWER  
RGN====>us-south  
CFNAME====>cxkjntm  

## 其他

配置完毕，将会在每天的04:15重启Clou
