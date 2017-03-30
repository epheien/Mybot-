# MyBot 指南

## 系统要求
- 具备虚拟化特性的 64 位 CPU (Virtualization AMD-v/AMD-Vi 或 Intel VT-x/Intel VT-d)
- 4GB 内存
- 12GB 硬盘空间
- OpenGL ES 2.0兼容的显卡驱动程序
- 至少 1366 x 768 分辨率的屏幕
- Windows Vista/7/8/8.1/10

## 系统安装
- [Microsoft Visual C++ 2010 Redistributable Package (x86)](http://download.microsoft.com/download/5/B/C/5BC5DBB3-652D-4DCE-B14A-475AB85EEF6E/vcredist_x86.exe)
- [Microsoft .NET Framework 4.5](http://download.microsoft.com/download/E/2/1/E21644B5-2DF2-47C2-91BD-63C560427900/NDP452-KB2901907-x86-x64-AllOS-ENU.exe) 或之后的版本
- Direct X 9.0 或之后的版本

## 安装安卓模拟器（任一即可，务必以英文语言安装）
- [MEmu](http://www.memuplay.com/) (最稳定的[2.5版](http://filehippo.com/download_memu/download/55fa3990056fd57c0cc03165642c03f5/))
- BlueStacks 0.10.7.5601 Rooted [[Mega](https://mega.nz/#%21GFVilDAL%21Wkyp2xpxFOx8J_Gz8wIf0jGSxTT3IiT6xthvrHhRbME)] | [[OneDrive](http://1drv.ms/1n2z7M5)]
- [BlueStacks 2.X Rooted](https://mybot.run/forums/index.php?/topic/11452-bluestacks-app-player-pro-2025623-rootedoffline-v2025627-offline-mod-root-guide-all-versions/)
- [KOPLAYER](http://www.koplayer.com/)
- [Droid4X](http://www.droid4x.com/) （[参考](https://mybot.run/forums/index.php?/topic/22912-new-leapdroid-support/&page=1)）
- [LeapDroid](http://www.leapdroid.com/)
- [Nox](http://en.bignox.com/)

## 安装字体（非BlueStacks需安装）（用以检测系统信息，如无需自动捐兵可忽略）（[参考](https://mybot.run/forums/index.php?/topic/16840-guide-how-to-replace-memu-font/)）
1. 下载[工具](http://www21.zippyshare.com/v/VThOW30E/file.html)
1. 解压缩 ZIP 档
1. 双击 push_Roboto-Regular.bat 字体安装工具
1. 点击 Run 按钮
1. 开启安卓模拟器（多个亦可）（BlueStacks必须关闭）
1. 回到字体安装工具窗口后按任一键
1. 重新开机

## 安装
- 在安卓模拟器中安装对应的版本的部落冲突游戏（如昆仑，九游等）
- [AutoIt](https://autoitscript.com/cgi-bin/getfile.pl?autoit3/autoit-v3-setup.exe)(可选）
- 下载 [MyBot](http://pan.baidu.com/s/1b3aNk6)，并解压 ZIP 文件

## 使用注意事项
- 设定 Windows 桌面任务栏为自动隐藏，如你的屏幕分辨率为 1366 x 768
- 设定 Windows 永不进入睡眠
- 设定屏幕永不进入屏幕保护程序
- 设定屏幕永不关闭
- 设定屏幕文字为内定的 100% DPI（[参考](https://mybot.run/forums/index.php?/topic/15137-guide-change-dpi-to-100/)）
- 开启 Windows Aero 界面
- 用系统管理者权限执行安卓模拟器
- 用系统管理者权限执行 MyBot.Run.exe
- 设定 BlueStack 为 860 x 732（[参考](https://mybot.run/forums/index.php?/topic/478-guide-close-all-bluestacks-process-apply-860x732reg/)）
- 设定 BlueStack 成英文语言 (English) 
- 把部落衝突游戏画面设定成英文语言 (English) 
- 七本及以上可正常使用
- 六本及以下（不建议使用）：
    - 四到六本会有图形识别问题，尤其是在兵营和训练营升级时。
    - 必须同时有两座兵营才可使用，部队训练才会正常运作。
    - 一到四本只能使用兵营模式来训练部队。
    - 一到三本有极大风险会自动使用到宝石。
    - 本团队不建议使用于也不支持一到四本。

## 使用方法
1. 双击 MyBot.run.exe
1. 确定使用管理员权限运行
1. 点击“开始”按钮
1. 留意主窗口的日志信息判断机器人是否正确运行
    - 如你的部落冲突游戏版本为非Google版本，Mybot首次运行会启动游戏失败，只要再次点击“开始”按钮即可
    - 如你的安卓模拟器的分辨率不正确，Mybot会自动设置为正确的分辨率并重启安卓模拟器

## Mybot 打鱼设置参考
1. 村庄 -> 综合
    - 设置陷阱
    - 收集资源
    - 清除墓碑

2. 攻击计划 -> 训练军队 -> 军队/法术
    - 练兵计划

3. 攻击计划 -> 搜索&攻击 -> 死鱼 -> 搜索
    - 金和水：180000, 180000

4. 攻击计划 -> 搜索&攻击 -> 死鱼 -> 进攻
    - 使用男王
    - 使用女王
    - 使用大守护者
    - 出兵速度10
    - 下全兵种，后换边

5. 攻击计划 -> 搜索&攻击 -> 选项 -> 搜索
    - 禁用发现鱼时，系统弹出提醒
    - 重新开始，经过：100搜索

6. 攻击计划 -> 搜索&攻击 -> 选项 -> 杯段设置
    - 奖杯范围：1600-1700（各本通用）

7. 机器人 -> 选项
    - 禁用检查更新
    - 自动运行：3秒

8. 村庄 -> 部落城堡 -> 请求增援（宝宝号需要）
    - 请求援兵/法术（空字符）

9. 攻击计划 -> 训练军队 -> 选项（宝宝号需要）
    - 禁用关闭COC

