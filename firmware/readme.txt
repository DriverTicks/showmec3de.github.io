此固件基于潘多拉官方固件修改而成，路由器直接刷入即可。
本固件未做各种型号路由的指示灯和复位按钮适配，可能存在指示灯显示异常，复位按钮无法使用的情况。其他功能均可正常使用。
刷写成功后使用WinSCP登陆后台（默认用户名root，默认密码admin，地址192.168.1.1，协议scp），

打开/etc/rc.button文件夹内pppoe_noauth，修改两处x.x.x.x为心跳服务器的IP，修改两处xxxx为心跳服务器端口，重启路由。



江西部分学校闪讯心跳     117.21.209.186
湖北电信心跳            58.53.196.172