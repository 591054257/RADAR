# PUBG-Cloud-Radar
PUBG云雷达
更新日志
2018/05/03/6:48
升级成1.2+

修复一系列错误.包括雷达运行着无缘无故崩溃等问题.缩小GitHub项目体积 减少git的速度.

安装前记得先删除或者格式化之前的服务器数据(不然可能无法使用 因为与上个版本不兼容) 

<br>======================================</br>
2018/04/30/23:30
升级成1.2 修复地图放大时出现错位~

请重装服务器系统 或者格式化服务器数据~

<br>======================================</br>
2018/04/30/21:00
由于Pubgmap.io 地图服务器问题,导致地图载入不完全 ,本次更新把地图文件下载在 在服务器内 读取游戏地图

不在从Pubgmap.io调用地图  # 实现地图秒加载~

请重新安装雷达,简单暴力 服务器进行重装系统的操作...

修复雷达 敌人 车辆黑色 以及敌人ID错乱等问题

<br>======================================</br>
2018/04/27/18:37
Fixed an issue where the enemy could not be displayed.

修复由于游戏版本大更新,导致敌人不在雷达上显示的问题.

<br>======================================</br>
Cloud Radar1.2+ 安装前记得看更新日志
<br>======================================</br>
使用：
只要有浏览器(不限设备 手机电脑 平板随意) 只要有网络(不限网络 手机4G 还是电脑宽带)

打开浏览器输入网址即可享用雷达!
![image](https://github.com/1030125713/PUBG-Cloud-Radar/blob/master/1.jpg)
<br></br>
![image](https://github.com/1030125713/PUBG-Cloud-Radar/blob/master/3.jpg)
完美运行
<br>======================================</br>
yum install git

git clone https://github.com/1030125713/PUBG-Cloud-Radar [更具服务器的带宽 来决定速度快慢]

cd Cloud-Radar-Plus/

npm i

npm i -g pino

npm install -g forever

forever start index.js sniff eth0 XX.XX.XX.XX | pino

By:潘潘 <br></br>
雷达交流：1030125713  
