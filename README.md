<!-- markdownlint-disable MD033 MD041 -->
<p align="center">
</p>

<div align="center">

# Maa for ETERNAL TREE

</div>

本项目是基于 [MaaFramework](https://github.com/MaaXYZ/MaaFramework) 所开发的悠久之树自动脚本

MET是为减轻悠久之树挂机刷本负担的自动脚本.使用此脚本,可以自动解决体力补充/卡车/卡死/掉线等问题,让你解放双手,放心挂机

MET功能:

支持自动重复进行`神使难度的特异点讨伐战` `机偶试炼战` `幻象征伐战`的刷取

支持`一键邀请`和`等待被邀请`

支持自动扫荡`困难与极难主线`

支持自动完成每日/每周的`助战任务`(自动识别任务是否完成)

支持`自动补体` `自动建房` `卡死重启` `掉线重连` `自动跨夜`

支持通过`加入房间`进行蹭车,解决自己刷的过慢的问题

# 使用方法

**将要借的助战虚数体的好友打上星标(主页右侧好友栏内),并确保要借的助战虚数体恒定在助战栏的前4个位置**

请将模拟器的分辨率设置为`1920*1080`(可以将显示的窗口缩小)，DPI为`280`,并确保开启**本地adb连接**

将压缩包解压到文件夹后，双击`MaaPiCli.exe`(命令行)或者`MFAWPF.exe`(图形化)

***建议使用mumu12模拟器(注意关闭后台保活)***

# 下载地址
[点此下载](https://github.com/shanchuan001/MET/releases)

**请下载"MET-win-x86_64"版**--GUI暂不支持maafw2.0


# 更新日志
**9月17日更新**  **v1.2.2**

  -新增了一键拉人/等待被邀请的功能

  -新增了自动扫荡困难与极难难度主线的功能

  -适配了MaaFW2.0

  -新增了自动完成每日/每周的助战任务(支持自动识别任务是否已完成)的功能
  
  -使用[MFAWPF](https://github.com/SweetSmellFox/MFAWPF)项目的图形化界面(暂不支持maafw2.0)

**9月13日更新**  **v1.1.1**

  -修复了蹭车模式的一些问题

  -修复了选择属性时点击过快导致的选择错误

  -修复了在创建房间时小概率发生的未点上"返回房间自动出击"

  -新增了多人战蹭车模式

**9月9日更新**  **v1.0.2**
  -修复了每天第一次登录/过夜挂机时在每日签到的物资领取界面卡住
  
  -修复了队伍在属性选择时小概率选择错误
  
  -优化了方阵/老王的选择.现在只用选择助战虚数体是老王还是方阵,不用选择助战虚数体属性,并且只会选择满破的助战虚数体了
  
  -优化了重启流程,减少了等待时间

  -支持官服/B服双服

# 悠久之树bug统计

  -"不再加入此房间"按钮概率不生效

  -偶尔会出现:加入房间后不准备不选助战直接开进入战斗

  -有时出现:点击"加入房间"按钮将一直处于搜索中,无论有没有可以加入的房间,超过正常最大搜索时间(1分钟)也不停止

  -必定出现:在房间中强制退出游戏后再次登录,并且在弹出的"是否回到房间"提示界面点击右上角的叉或是旁边空白区域将会导致在加入/创建房间时一直提示"已在房间中".直到重启并在下一次弹出的界面中选择取消或者加入

  -多次快速点击一个或者一些按钮数次(有时在房间中也会触发,具体触发原因不明)大概率会导致之后的点击无效(画面正常进行),直到重启

  **欢迎提pr**

## 鸣谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！
 
感谢 **[MFAWPF](https://github.com/SweetSmellFox/MFAWPF)** 提供的GUI!

