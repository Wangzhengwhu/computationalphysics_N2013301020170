# computationalphysics_N2013301020170
# Cmd Markdown （1）



---

##**2016/3/6**

###今天第一次使用markdown，课上听蔡老师说的很神奇，自己用起来好麻烦的软件。

###首先来张插图，在作业部落插图好像要会员，这个问题先留下，我们待会再说，进入下一步。
![此处输入图片的描述][1]

###公式编辑
$sinx'$=$cosx$

$$f(x)=\sqrt{x^\alpha}$$

$$\sum_{i=1}^n a_i$$

$$\frac{1}{x^p}$$

一些简单的公式编辑，希腊字母的输入在latex上也能不是和容易的写出,刚开始写感觉有点麻烦，不像在math type能更加直观的体现出来。

###一些小程序也可以放在这里与大家分享
对于从来没有学过程序语言的我来说，经常听一些厉害的同学窝在寝室写程序，就觉得超级厉害。
在网上摘了一段小程序，作为学这门课的开始吧。

def f(x):
    if x == 0:
        return x
    else:
        return f(x-1) * 2 + x * x

for x in xrange(1,10):
    print f(x)

这段程序我感觉应该是找到相应的f(x),x的取值在1-10之间，寻找使得等式成立的方程吧。

最后来说说这门课吧，我觉得计算物理这门课听老师说的比较有趣，更是他极力地向我们推荐liux系统，但是看到好多小伙伴装新系统结果导致原系统也崩溃的情况，的确打击我装新系统的欲望。

[1]: https://raw.githubusercontent.com/caihao/computational_physics_whu/7d7b4c0cbd5a32db80a8458729c1aff754eaf743/MomKm1.png
