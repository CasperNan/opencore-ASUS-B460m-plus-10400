# opencore-ASUS-B460m-plus-10400

设备配置
- Asus B460m plus
- Intel 10400
- AMD 5500xt

机型配置
- MacPro7,1
- 独显驱动 输出 已硬解

![系统信息](https://github.com/CasperNan/opencore-ASUS-B460m-plus-10400/blob/master/images/image1.jpeg?raw=true)

![VideoProc](https://github.com/CasperNan/opencore-ASUS-B460m-plus-10400/blob/master/images/image2.png?raw=true)

目前已知可使用功能
- 已驱动独显 实现硬解 因为主板原因 只能驱动一个显卡 若只想驱动核显 需要试试plaform_id和机型 此机型只能有一个显卡
- usb可使用（此处用别人的usbport的驱动，若机型不同要进入kext中的content增加机型的配置）
- viedoPro硬解
- opencore启动增加图形化界面
- 解决了内存显示错误的问题
- 声卡正常

感谢各位大佬的教程及驱动！敬礼！