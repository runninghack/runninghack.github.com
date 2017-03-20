---
layout: post
title: 客制化键盘Build Log： 飞线直列60%键盘
---

完成时间： 2017-03-07

外壳入手途径： Alex Jackson 2017-02-05

![1]({{ site.url }}/assets/custom_keyboards/handwired/1.jpg)

成品的样子。没凑齐特别合适的键帽，暂时随便配的

![2]({{ site.url }}/assets/custom_keyboards/handwired/2.png)

外壳很简单，不锈钢定位板和不锈钢底壳。

![3]({{ site.url }}/assets/custom_keyboards/handwired/3.png)

底壳是一块钢板掰弯成这样的。

![4]({{ site.url }}/assets/custom_keyboards/handwired/4.jpg)

首先利用二极管的长针脚飞线矩阵的行（row）。我在弯曲针脚的时候拿另一根剪下来的针脚竖在那里，绕着弯曲，这样可以控制弯曲的位置和角度。

![5]({{ site.url }}/assets/custom_keyboards/handwired/5.jpg)

行快焊完了。

![6]({{ site.url }}/assets/custom_keyboards/handwired/6.jpg)

行全部焊完。注意左侧大键的处理。

![7]({{ site.url }}/assets/custom_keyboards/handwired/7.png)

接下来需要剪一些线，我没有合适的工具，只用尖嘴钳和剪线钳来处理。

![8]({{ site.url }}/assets/custom_keyboards/handwired/8.jpg)

列的焊接方法。

![9]({{ site.url }}/assets/custom_keyboards/handwired/9.jpg)

把有母头的线焊在主控（teensy 2.0）上。

![10]({{ site.url }}/assets/custom_keyboards/handwired/10.png)

把有公头的线焊在键盘矩阵的行和列上。

![11]({{ site.url }}/assets/custom_keyboards/handwired/11.jpg)

接下来处理外壳。

![12]({{ site.url }}/assets/custom_keyboards/handwired/12.jpg)

为了防止电路和钢板接触，用电工胶布做一下绝缘。

![13]({{ site.url }}/assets/custom_keyboards/handwired/13.jpg)

焊接了一个mini-usb的母头。

![14]({{ site.url }}/assets/custom_keyboards/handwired/14.jpg)

决定把母头焊在这个位置。

![15]({{ site.url }}/assets/custom_keyboards/handwired/15.jpg)

全部连接起来。

![16]({{ site.url }}/assets/custom_keyboards/handwired/16.jpg)

线太多了，外壳有点放不下，不过刷入固件（tmk）之后可以用了，测试成功，之后再优化。

![17]({{ site.url }}/assets/custom_keyboards/handwired/17.jpg)

这是从前面看的样子，mini-usb母头有点歪。

To be continued