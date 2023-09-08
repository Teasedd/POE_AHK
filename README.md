运用于POE 流放之路的自动判断喝药的AHK<br>
<br>
实现原理<br>
<br>
通过检测窗口屏幕坐标颜色进行判断来达到自动喝药的效果，也可以用于某些技能<br>
即在检测到左下角血量血线不等于预先设定的血线处颜色时(也就是血槽为空，颜色变化；MANA处同理)，就会触发效果，自动按下按键<br>
请在设置中更改血量条在保留生命/魔力后的显示设置，不显示保留区域效果<br>
<br>
使用方式
<br>
在POE窗口中按下`键(波浪键，1左边)开关，默认只在POE窗口中生效<br>
坐标颜色识别复制工具：开启后按下\键会开关显示鼠标处的坐标及颜色，按复制快捷键即可复制(复制之后记得关闭脚本，不然占用CTRL键导致无法正常复制粘贴)<br>
<br>
更改方式
<br>
可自行更改设置触发效果的血线处 即检测的坐标及颜色，以及触发后按下的按键，检测延迟，触发按键后再次按下按键的延迟<br>
使用工具获取POE窗口鼠标处的坐标及颜色，复制之后在代码中自行替换更改，推荐从左获取坐标颜色，因为右处会被能量护盾干扰
