# date

码农的生活总是昼夜颠倒的，这导致像我这样的人总记不住时间，在 Windows 里我习惯时不时地瞄一眼屏幕右下方，就像这样（图片来自网络）

![current-time-in-windows](date/win7-time.png)

可是在 Unix 中，我经常全屏和黑漆漆的命令行打交道，懒得切换页面看时间。（归根结底还是懒……）那么就可以用`date`这个命令来显示当前时间：

```bash
$ date
Sun Jan  6 21:20:07 EST 2019
```

你也可以用`cal`来显示日历：
```bash
$ cal
    January 2019
Su Mo Tu We Th Fr Sa
       1  2  3  4  5
 6  7  8  9 10 11 12
13 14 15 16 *17* 18 19
20 21 22 23 24 25 26
27 28 29 30 31
```

注：17实际为背景色重点标注