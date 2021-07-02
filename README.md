
### 一、项目简介

&emsp;&emsp;1. **物美智能([wumei-smart](http://www.wumei.live/introduce.html))]是一套开源的软硬件系统，可用于二次开发和学习，快速搭建自己的智能家居系统。** 硬件工程师可以把自己的设备集成到系统；软件工程师可以使用项目中的设备熟悉软硬件交互。<br />
![说明](https://gitee.com/kerwincui/wumei-smart/raw/master/document/desc.png)<br /><br />

&emsp;&emsp;2. 服务端使用spring boot、数据库mysql和redis、前端vue、移动端android、硬件端ESP-IDF和Arduino。软硬件交互基于mqtt协议，使用EMQ代理服务器。系统架构图如下：
<br /><br />
![架构](https://gitee.com/kerwincui/wumei-smart/raw/master/document/sys.png)  
<br />
 
### 二、技术栈    
* 后端
    - 相关技术：Spring boot、MyBatis、Spring Security、Jwt、Mysql、Redis、Mongodb、Mqtt等
    - 开发工具：IDEA    
* 前端
    - 相关技术：ES6、Vue、Vuex、Vue-router、Vue-cli、Axios、Element-ui等 
    - 开发工具：Visual Studio Code    
* 安卓
    - 相关技术：XUI、XPage、XAop、XHttp2等
    - 开发工具：Android Studio    
* 硬件端
    - 相关技术： ESP-IDF、Arduino、FreeRTOS等
    - 开发工具：Visual Studio Code

<br />

### 三、快速搭建系统
#### 1.安装docker，[官方下载docker](https://docs.docker.com/get-docker/)
#### 2.docker安装成功后，打开命令窗口运行如下命令：

`
docker run 
--name wumei-smart 
--publish 80:80 
--publish 18083:18083 
--publish 1883:1883 
--publish 3306:3306 
--publish 6379:6379 
--restart always 
--detach 
kerwincui/wumei-smart:1.0
`

#### 3.扫码下载APP安装,打开APP配置服务端地址

&emsp;&emsp;&emsp;&emsp;<img src="https://gitee.com/kerwincui/wumei-smart/raw/master/document/download.png" />

#### 4.硬件代码烧录

&emsp;&emsp;&emsp;&emsp;[进入详细搭建教程](http://wumei.live/)

<br />

### 四、系统部分图片
![分类](https://gitee.com/kerwincui/wumei-smart/raw/master/document/a.png)
![设备列表](https://gitee.com/kerwincui/wumei-smart/raw/master/document/b.png)
![EMQX](https://gitee.com/kerwincui/wumei-smart/raw/master/document/c.png)
![设备详情](https://gitee.com/kerwincui/wumei-smart/raw/master/document/d.png)
![配置](https://gitee.com/kerwincui/wumei-smart/raw/master/document/e.png) 

<br />

##### 加入讨论群：1073236354
<a target="_blank" href="https://qm.qq.com/cgi-bin/qm/qr?k=P_oc91N6KC39zp2PEV_-BY3xMnAokeZ8&jump_from=webapi"><img border="0" src="//pub.idqqimg.com/wpa/images/group.png" alt="物美智能wumeismart" title="物美智能wumeismart"></a> 
