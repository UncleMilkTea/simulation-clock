# simulation-clock
一款漂亮的美女模拟时钟Demo

# HYKsimulationclockDemo

- 根据控件的layer属性修改锚点,通过锚点旋转实现表针效果
- 通过NSRunLoop来刷新表针的转动和美女手中的数字的更新
- 同时获取系统的时分秒来确定表针的初始角度
- 根据分针的实时旋转角度来更新时针的旋转角度,这样时针不会一次跳转一个小时
- 通过运行时来动态修改DatePicker的线条颜色属性
- 利用循环生成屏幕上的小星星,位置随机生成,限定范围为屏幕内

![](/Snip20160305_0.png)

![](/Snip20160305_1.png)

## TODO

- 万年历功能
- storyboard搭建基本界面
- 同步更新系统时间
- 通过遍历来搜索私有属性

## Author

Weibo: [@确实草蛋][1]
http://weibo.com/caoeggs/home

Github: [houyukun][2]
