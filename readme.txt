壁纸：
选择壁纸后等待一会
-------------------
字体：
前提条件：手机可root/本应用只限更改中文字体，更改字体前提把系统语言设置为简体中文
应用中暂时只添加了四种字体样式：
方正粗圆
方正古隶
华文行楷
华文新宋
在app中设置字体后请依次执行以下adb 命令，重启手机后即可更换系统字体
adb root
adb remount
adb pull /data/data/com.wind.wallpaperandfontsapp/files/ ./test
adb push test\fonts.xml system/etc/
adb push test\new.ttf system/fonts/
adb reboot