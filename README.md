# ChromeAutoUpdate
一个自动更新chrome的小工具

第一次使用的时候会下载chrome最新版，需要稍微等待。

360会有各种提示，卸载360即可[doge]。

打开桌面快捷方式时，会检测更新，然后就会关闭自己，没有驻留进程，也不会开机自动。

会根据你的操作系统，自动选择32位、64位版chrome。

每次更新，均在你下次重新启动chrome生效。

目前是测试版，功能还不齐全，每天都会更新添加功能。

注意:本工具不支持xp。

bug反馈联系微博@你的档案。

主页:http://chrome.wbdacdn.com/

#更新原理
请求更新接口，下载chrome新版安装包，解压覆盖。

#更新日志
1.11.1.17:支持升级默认安装的chrome(如果安装在系统目录，会申请管理员权限)，也可以修改配置文件定义chrome安装路径。