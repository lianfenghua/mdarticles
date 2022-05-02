# 数学的想象力

## 序

四月中旬的 S 城热起来了，连续晴朗了数日，施白鹿的内心也被太阳晒得没了生气。晚上 9 点已过，他还在路旁兀自走着，抬头望见一轮明月挂在东南方的天空。虽然月朗星稀，但右下方依然有一颗亮星肉眼可见，他没好气地想：“哼，角宿合月，有什么好看？”

低下头，他又回想起赖特 · 米尔斯在《社会学的想象力》中的话：“……这种心智品质能够有助于他们运用信息、发展理性，以求清晰地概括出周边世界正在发生什么，他们自己又会遭遇什么。我的主张是，从记者到学者，从艺术家到公众，从科学家到编辑，都越来越期待具备这种心智品质，我们不妨称之为社会学的想象力。”琢磨了两遍，自言自语道：“社会学的想象力，心理学的想象力，好像啥都能说个想象力。换个视角，然后感到惊奇：这算啥感受？我就不信数学也有想象力！”

## 心情不好，就去跑步

“心情不好，就去跑步”，他想起一个朋友的提醒，慢慢加快了脚步。几分钟后，白鹿暂时沉浸在运动中，“不知道我和牛顿谁跑得更快些，牛顿在描述运动时还提出了微积分，据说那是十七世纪最重大的发明。”

运动的时候，我有时候跑得快些，有时候跑得慢些，用一段时长去除这段时间内跑过的距离就可以衡量跑的快慢了：真是个好主意。他们居然把这个主意用到了无限小的时间段，这本不足为奇，但他们称之为导数而且居然能够把脑袋分析得七零八落，这就怪了。拿运动来说，速度是位置对时间的导数，也就是每个时刻下在单位时长内能跑多远。不管了，用字母表示变量，借莱布尼兹的符号写一下：

<img src="https://www.zhihu.com/equation?tex=v=\frac{ds}{dt},
" alt="v=\frac{ds}{dt},
" class="ee_img tr_noresize" eeimg="1">
用  <img src="https://www.zhihu.com/equation?tex=v" alt="v" class="ee_img tr_noresize" eeimg="1">  表示速度 (Velocity, *V*)， <img src="https://www.zhihu.com/equation?tex=s" alt="s" class="ee_img tr_noresize" eeimg="1">  表示位置 (Position) 或位移 (Displacement)——位置的移动量， <img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1">  表示时刻或时长 (Time)。反之，知道了每个时刻的速度，把它们加起来自然就是一长段时间内的位移了，他们把这个过程叫积分：

<img src="https://www.zhihu.com/equation?tex=\Delta s=s_2-s_1=\int_{t_1}^{t_2} v dt.
" alt="\Delta s=s_2-s_1=\int_{t_1}^{t_2} v dt.
" class="ee_img tr_noresize" eeimg="1">
大功告成。不过我还想知道此刻的速度是拖了后腿呢，还是拉了前腿？也就是从我跑步到现在，此刻的速度比不比我刚刚那段时间的平均速度快呢？那再定义一个平均速度吧。假如我开始跑步时记作时刻为零 ( <img src="https://www.zhihu.com/equation?tex=t=0" alt="t=0" class="ee_img tr_noresize" eeimg="1"> )，位置也记为零 ( <img src="https://www.zhihu.com/equation?tex=s=0" alt="s=0" class="ee_img tr_noresize" eeimg="1"> )，那么到现在为止我的平均速度就是

<img src="https://www.zhihu.com/equation?tex=v_a=\frac{s}{t},
" alt="v_a=\frac{s}{t},
" class="ee_img tr_noresize" eeimg="1">
 <img src="https://www.zhihu.com/equation?tex=v_a" alt="v_a" class="ee_img tr_noresize" eeimg="1">  是平均速度 (Average velocity, *AV*)。

我让我的位置按抛物线变化吧，毕竟大自然不喜欢直线，先给个表达式：

<img src="https://www.zhihu.com/equation?tex=s=t^2+16.
" alt="s=t^2+16.
" class="ee_img tr_noresize" eeimg="1">
 <img src="https://www.zhihu.com/equation?tex=t=0" alt="t=0" class="ee_img tr_noresize" eeimg="1">  时  <img src="https://www.zhihu.com/equation?tex=s" alt="s" class="ee_img tr_noresize" eeimg="1">  咋不是 0 呢？嘿嘿，一开始呆了几秒看月亮，就把我的位置多加个 16 米吧。如果有人问起，我就说起跑时瞬移了 16 米，这不是啥稀奇事，那时高维空间的碎片正经过地球，而我恰好进了高维空间然后被往前带了 16 米而已。这就是它的图像：

<img src="https://raw.githubusercontent.com/lianfenghua/mdarticles/master/Data/imagination/s.png" style="zoom: 33%;" />

看看平均速度和瞬时速度怎么变的：

<img src="https://www.zhihu.com/equation?tex=v_a=t+\frac{16}{t}, \\
v=2t.
" alt="v_a=t+\frac{16}{t}, \\
v=2t.
" class="ee_img tr_noresize" eeimg="1">
<img src="https://raw.githubusercontent.com/lianfenghua/mdarticles/master/Data/imagination/va_v.png" style="zoom: 33%;" />

图中蓝线表示平均速度，红线表示瞬时速度。可知 *V* 曲线与 *AV* 曲线在 *AV* 曲线的最低点处相交。这是必然的，因为

<img src="https://www.zhihu.com/equation?tex=\frac{dv_a}{dt}=0 \implies \frac{d}{dt}\Big(\frac{s}{t}\Big)=
\frac{\frac{ds}{dt}t-s}{t^2}=0 \\
\implies \frac{ds}{dt}=\frac{s}{t}, \text{ or } v=v_a.
" alt="\frac{dv_a}{dt}=0 \implies \frac{d}{dt}\Big(\frac{s}{t}\Big)=
\frac{\frac{ds}{dt}t-s}{t^2}=0 \\
\implies \frac{ds}{dt}=\frac{s}{t}, \text{ or } v=v_a.
" class="ee_img tr_noresize" eeimg="1">

我的平均速度先减小后增大，一开始平均速度特别大（瞬移的威力！），跑步时我的速度自然比不上瞬移，于是就把我的平均速度给拖慢了。只要我的速度比平均速度小，平均速度就会被继续拖慢，直到它俩相等。我越跑越快，当速度比平均速度还大时，就会把平均速度拉高。这样说来，*V* 自然会在 *AV* 的最低点和 *AV* 相交了。

想到这里，白鹿露出了满意的笑容，然后心想：这算是跑步令人愉悦的见证吗？还没想清，就听到左前方草丛里窸窣作响， “不会是蛇吧？”正疑惑间，忽地狂风大作，伴着凄厉的叫声，一个黑影飞速掠过，不知是人是鬼。

## 夜跑总叫人怕

第二天，白鹿叫哥哥青崖一起跑步：“昨天晚上那条路奇怪得紧，想去看看，可是有些怕。”青崖说：“小鹿胆子就是小，我还要送东西，你叫周冲去吧。”不一会儿，白鹿和周冲就来到了昨天那条路，向前看去，树丛幽深，山石险恶，四周无人，一片寂静，二人感到寒意袭来。“小鹿，你胆子真够大的，不过我喜欢这刺激的地方，”看着白鹿走到前方一块大石头旁，周冲继续说，“我就匀速跑了，省力，你别跑太远。”当周冲匀速跑到石头旁时，白鹿按下计时器，开始按昨天的方式加速，就在按下计时器后一刹那，白鹿瞬移到前方 16 米处，而周冲居然未察觉这一点。不一会儿，周冲超过了白鹿，白鹿被越落越远，心里开始发慌，他想知道什么时候会被落在后面最远，毕竟那个时刻就是他最害怕的时刻，他想记下那个难忘的时刻。

把周冲 (*A*) 和我 (*B*) 的位移、速度随时间的变化情况写成表达式：

<img src="https://www.zhihu.com/equation?tex=s_A=10t, \\
v_A=10. \\
s_B=t^2+16, \\
v_B=2t.
" alt="s_A=10t, \\
v_A=10. \\
s_B=t^2+16, \\
v_B=2t.
" class="ee_img tr_noresize" eeimg="1">
想一下速度函数的图像，绿线表示 *A* 的速度，红线表示 *B* 的速度。

<img src="https://raw.githubusercontent.com/lianfenghua/mdarticles/master/Data/imagination/v_v.png" style="zoom: 33%;" />

为求 *B* 落后于 *A* 的最大距离，把 *A* 领先 *B* 的位移写成一个函数：

<img src="https://www.zhihu.com/equation?tex=s=s_A-s_B =-t^2+10t-16=-(t-5)^2+9.
" alt="s=s_A-s_B =-t^2+10t-16=-(t-5)^2+9.
" class="ee_img tr_noresize" eeimg="1">
那什么时候我被落得最远呢？这是 stationary value 的问题，最大值在导数为零处取得，令

<img src="https://www.zhihu.com/equation?tex=\frac{ds}{dt}=\frac{ds_A}{dt}-\frac{ds_B}{dt}=v_A-v_B=0.
" alt="\frac{ds}{dt}=\frac{ds_A}{dt}-\frac{ds_B}{dt}=v_A-v_B=0.
" class="ee_img tr_noresize" eeimg="1">
哦，当我们速度相等时相距最远。根据

<img src="https://www.zhihu.com/equation?tex=v_A=v_B \implies 10=2t \implies t=5 \implies s=9.
" alt="v_A=v_B \implies 10=2t \implies t=5 \implies s=9.
" class="ee_img tr_noresize" eeimg="1">
于是最远距离就是 9 m. “九米而已，还好啦。”今晚虽然没有黑影出现，但瞬移的事情却越来越想不通，“难道世上真有魔法？还是我小说看多了？那到底是真实经历的，还是我幻想出来的？啊，不对！”白鹿忽然轻呼一声，好像想到了什么，显得十分震惊。

回到家中，白鹿心想：夜跑总叫人怕，算了，反正也搞不清，还是想些可以搞清的吧，于是提笔写下：

- 速度曲线 (*V*) 与平均速度曲线 (*AV*) 在平均速度曲线的最低点处相交；
- 在周冲领先我的距离最大的那个时刻，我们的速度相等 (*V* of A = *V* of B)。

<img src="https://raw.githubusercontent.com/lianfenghua/mdarticles/master/Data/imagination/va_v_v.png" style="zoom: 33%;" />

## 来做冰淇淋吧

经过几日阴雨，转眼来到了五月。阴霾初散，天气转晴，趁着暮春时节，人们纷纷来野外露营。大沙河旁，连营百米；梧桐山麓，点缀数人。施白鹿与姜枫、奚午、孟芳邻四人一早就来到山脚，靠东找一处阳光还没晒到的地方，支起帐篷，铺开毯子，放好饮料，撒上零食，天南海北摆起龙门阵来。不一会儿，太阳当空，树荫减少，几人嫌起了渐热的天气。只有姜枫独自歪在一棵槐树旁，轻声絮叨：“难道擅萝国就真的没办法对付了吗？”三人转向姜枫，只听他继续说道：“家里有个祖传的冰淇淋秘方，如果趁现在……岂非……”断断续续听不太清。

奚午接道：“对对对，研究一下，权当玩儿。不过这玩艺儿成本高吗？”

## 这玩艺成本高吗？

白鹿说道：“看看有哪些成本吧。得租个地方、租个设备，这些租金要按小时付，每小时都是固定的。”奚午接着说：“如果要多做些，少不得要再请几个人来做，那就得发些酬劳，就算是人力成本吧。”“还有冰淇淋本身的各种配料。”芳邻补充道。

白鹿分析：有些成本每小时是固定不变的，就叫固定成本；有些是可变的，随人数或产量在变，就叫可变成本吧；它们加起来就叫总成本。我先写个分类：

<img src="https://www.zhihu.com/equation?tex=C_f = l, \\
C_v = m\ P+n\ Q, \\
C_t = l+m\ P+n\ Q,
" alt="C_f = l, \\
C_v = m\ P+n\ Q, \\
C_t = l+m\ P+n\ Q,
" class="ee_img tr_noresize" eeimg="1">
以上成本都按小时计，其中  <img src="https://www.zhihu.com/equation?tex=C_f" alt="C_f" class="ee_img tr_noresize" eeimg="1">  是固定成本 (Fixed cost, *FC*)，是个常数； <img src="https://www.zhihu.com/equation?tex=C_v" alt="C_v" class="ee_img tr_noresize" eeimg="1">  是可变成本 (Variable cost, *VC*)，包括随人数 ( <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1"> ) 增加的人力成本和随产量 ( <img src="https://www.zhihu.com/equation?tex=Q" alt="Q" class="ee_img tr_noresize" eeimg="1"> ) 增加的产品成本，假设均匀增加：每增加一个人，成本增加  <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> ，每生产一个产品，成本增加  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> ； <img src="https://www.zhihu.com/equation?tex=C_t" alt="C_t" class="ee_img tr_noresize" eeimg="1">  是总成本 (Total cost, *TC*)。

这里有两个变量 *P* 和 *Q*，它们的关系是生产函数。现在我们只想看看随产量变化的情况。人力之外的成本随产量线性增加，但人力成本随产量增加得越来越快，使得总成本随产量增加得越来越快。不过，在产量较小时可以看作线性增加。找个合适的函数（产量对人数的变化率随人数均匀减小）再画个图来表示：

<img src="https://raw.githubusercontent.com/lianfenghua/mdarticles/master/Data/imagination/cf_cv_ct.png" style="zoom:33%;" />

```
l = 300, m = 100, n = 5
```

虚线是固定成本，点线是可变成本，实线是总成本。

接下来让我们看看单位产量的成本吧，这才是我们关心的。既然是单位产量的成本，就叫它平均成本吧。好，平均成本表示生产单位产品需要的成本，用产量去除成本即可：

<img src="https://www.zhihu.com/equation?tex=C_{af} = \frac{C_f}{Q} = \frac{l}{Q}, \\
C_{av} = \frac{C_v}{Q} = \frac{mP}{Q}+n, \\
C_{at} = \frac{C_t}{Q} = \frac{l}{Q} + \frac{mP}{Q} + n.
" alt="C_{af} = \frac{C_f}{Q} = \frac{l}{Q}, \\
C_{av} = \frac{C_v}{Q} = \frac{mP}{Q}+n, \\
C_{at} = \frac{C_t}{Q} = \frac{l}{Q} + \frac{mP}{Q} + n.
" class="ee_img tr_noresize" eeimg="1">

再写一下各个成本的含义：

-  <img src="https://www.zhihu.com/equation?tex=C_{af}" alt="C_{af}" class="ee_img tr_noresize" eeimg="1"> , 平均固定成本, Average fixed cost, *AFC*;
-  <img src="https://www.zhihu.com/equation?tex=C_{av}" alt="C_{av}" class="ee_img tr_noresize" eeimg="1"> , 平均可变成本, Average variable cost, *AVC*;
-  <img src="https://www.zhihu.com/equation?tex=C_{at}" alt="C_{at}" class="ee_img tr_noresize" eeimg="1"> , 平均总成本, Average total cost, *ATC*.

画个图来表示，图例和上面的含义一致：

<img src="https://raw.githubusercontent.com/lianfenghua/mdarticles/master/Data/imagination/caf_cav_cat.png" style="zoom:33%;" />

可以看到，平均固定成本 *AFC* 随产量减小（反比例函数）；平均可变成本 *AVC* 随产量增加，产量较小时为线性增加，之后随着产量的增加上升得越来越快。由于二者共同作用，平均总成本 *ATC* 先减小后增加，呈现 U 形。

“等等等等，这么多成本，一大堆字母，我乱了，”奚午赶忙说道，“为了突出重点，先别分这么多成本，我们就按总成本往下分析吧。”白鹿接道：“没错，我也有点乱，下面就说总的吧。现在有了平均量，不过我们还不知道每个产量之下总成本会怎么变呢，让我们来求个导，经济学里喜欢叫边际量。”

总成本对产量求个导就是边际成本了，表示在每一产量之下，增加单位产量时成本的增加量。这里把成本看作  <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1">  和  <img src="https://www.zhihu.com/equation?tex=Q" alt="Q" class="ee_img tr_noresize" eeimg="1">  的二元函数，同时  <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1">  和  <img src="https://www.zhihu.com/equation?tex=Q" alt="Q" class="ee_img tr_noresize" eeimg="1">  可以相互转化，于是

<img src="https://www.zhihu.com/equation?tex=C_m=\frac{dC_t}{dQ}=m\frac{dP}{dQ}+n,
" alt="C_m=\frac{dC_t}{dQ}=m\frac{dP}{dQ}+n,
" class="ee_img tr_noresize" eeimg="1">

这里的  <img src="https://www.zhihu.com/equation?tex=C_m" alt="C_m" class="ee_img tr_noresize" eeimg="1">  就是边际成本 (Marginal cost, *MC*)，沿用之前那个合适的生产函数，继续画条线，用红色表示，可见边际成本随产量的增加而增加。

<img src="https://raw.githubusercontent.com/lianfenghua/mdarticles/master/Data/imagination/cat_cm.png" style="zoom:33%;" />

看图像可知 *MC* 曲线与 *ATC* 曲线在 *ATC* 曲线的最低点处相交。这是必然的，因为

<img src="https://www.zhihu.com/equation?tex=\frac{dC_{at}}{dQ}=0 \implies \frac{d}{dQ}\Big(\frac{C_t}{Q}\Big)=
\frac{\frac{dC_t}{dQ}Q-C_t}{Q^2}=0 \\
\implies \frac{dC_t}{dQ}=\frac{C_t}{Q}, \text{ or } C_m=C_{at}.
" alt="\frac{dC_{at}}{dQ}=0 \implies \frac{d}{dQ}\Big(\frac{C_t}{Q}\Big)=
\frac{\frac{dC_t}{dQ}Q-C_t}{Q^2}=0 \\
\implies \frac{dC_t}{dQ}=\frac{C_t}{Q}, \text{ or } C_m=C_{at}.
" class="ee_img tr_noresize" eeimg="1">

咦，这句话好像在哪里见过？是速度与平均速度的关系！原来它们是一样的。当边际成本等于平均总成本时平均总成本取最小值。

这是可以理解的，如果当前的边际成本小于平均总成本，那么增加一个产品，需要增加较少的成本，这使得平均总成本继续降低；反过来，当边际成本高于平均总成本时，每多生产一个产品，需要增加的成本较多，使得平均总成本升高；当边际成本等于平均总成本，此时多生产一个产品，需要增加的成本和之前的平均总成本一样多，那么平均总成本此刻不会变，达到了稳定的最小值。这样说来，*MC* 自然会在 *ATC* 的最低点和 *ATC* 相交了。

白鹿想：我该露出满意的笑容吗？但愿不要有黑影出现。接着记下几个结论：

- 平均总成本 (*ATC*) 先减小后增加，呈现 U 形；
- 边际成本 (*MC*) 随产量的增加而增加；
- 边际成本曲线 (*MC*) 与平均总成本曲线 (*ATC*) 在平均总成本曲线的最低点处相交。

## 收益怎么衡量？

白鹿道：“成本先分析到这里，接下来看看收益吧。”这时芳邻说：“这简单，收益跟成本分析起来差不多，都是钱嘛。”

好，那以小时为单位，我们就叫它总收益 (Total revenue, *TR*)，我们的收益就是产量乘以单价喽：


<img src="https://www.zhihu.com/equation?tex=R_t=PQ,
" alt="R_t=PQ,
" class="ee_img tr_noresize" eeimg="1">

这里  <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1">  是价格，不是之前的人数了。

仿照成本的分析，我们再定义一个平均收益 (Average revenue, *AR*)，也就是单位产量的收益，等于价格：

<img src="https://www.zhihu.com/equation?tex=R_a=\frac{R_t}{Q}=P.
" alt="R_a=\frac{R_t}{Q}=P.
" class="ee_img tr_noresize" eeimg="1">

当然还有边际收益 (Marginal revenue, *MR*)，指的是每一产量之下单位产量的收益：

<img src="https://www.zhihu.com/equation?tex=R_m=\frac{dR_t}{dQ}=\frac{d(PQ)}{dQ}=P+\frac{dP}{dQ}Q.
" alt="R_m=\frac{dR_t}{dQ}=\frac{d(PQ)}{dQ}=P+\frac{dP}{dQ}Q.
" class="ee_img tr_noresize" eeimg="1">

价格又不是我们能左右的，据说这叫完全竞争市场。“啥时候可以搞点垄断撒？”奚午幽幽地说。竞争市场简单一些，我们来看这个吧。如果价格是常数，那这几个量都是水平线：

<img src="https://www.zhihu.com/equation?tex=R_m=P=R_a.
" alt="R_m=P=R_a.
" class="ee_img tr_noresize" eeimg="1">

## 真的会有利润？

奚午接着说：“来算利润吧，不会真的有利润吧？”

收益减去成本就是利润 (Profit,  <img src="https://www.zhihu.com/equation?tex=P_{ro}" alt="P_{ro}" class="ee_img tr_noresize" eeimg="1"> ) 了：


<img src="https://www.zhihu.com/equation?tex=P_{ro}=R_t-C_t.
" alt="P_{ro}=R_t-C_t.
" class="ee_img tr_noresize" eeimg="1">

想一下边际总成本 (红线) 和边际收益 (绿线) 的图像：

<img src="https://raw.githubusercontent.com/lianfenghua/mdarticles/master/Data/imagination/cm_rm.png" style="zoom:33%;" />

那什么时候利润最大呢？这是 stationary value 的问题，最大值在导数为零处取得，令

<img src="https://www.zhihu.com/equation?tex=\frac{dP_{ro}}{dQ}=\frac{dR_t}{dQ}-\frac{dC_t}{dQ}=R_m-C_m=0.
" alt="\frac{dP_{ro}}{dQ}=\frac{dR_t}{dQ}-\frac{dC_t}{dQ}=R_m-C_m=0.
" class="ee_img tr_noresize" eeimg="1">
哦，当边际成本等于边际收益时利润最大。进而根据

<img src="https://www.zhihu.com/equation?tex=R_m=C_m \implies Q_{max} \implies P_{ro,max}.
" alt="R_m=C_m \implies Q_{max} \implies P_{ro,max}.
" class="ee_img tr_noresize" eeimg="1">
这是边际成本与边际收益之交点。咦，前面几句话怎么也挺耳熟，这不是跑步时我最难忘的那个时刻吗？想到这里，白鹿赶快在纸上写下几句话，总结这些分析：

- 边际成本曲线 (*MC*) 与平均总成本曲线 (*ATC*) 在平均总成本曲线的最低点处相交；
- 在总利润最大的那个时刻，边际成本等于边际收益 (*MC* = *MR*)。

<img src="https://raw.githubusercontent.com/lianfenghua/mdarticles/master/Data/imagination/cat_cm_rm.png" style="zoom:33%;" />

欣喜于某种相似性，紧接着补上几个概念以作类比：

| 运动学描述        |                  | 经济学描述        |                   |

| ----------------- | ---------------- | ----------------- | ----------------- |

| 甲的位移 *S1*     | 乙的位移 *S2*    | 总成本 *TC*       | 总收益 *TR*       |

| 甲平均速度 *AV1*  | 乙平均速度 *AV2* | 平均总成本 *ATC*  | 平均收益 *AR = P* |

| 甲的速度 *V1*     | 乙的速度 *V2*    | 边际成本 *MC*     | 边际收益 *MR*     |

| 当 *V1 = V2* 时， | 距离最大/最小。  | 当 *MC = MR* 时， | 利润最大。        |


白鹿想：十七世纪的这一洞见，竟提供了如此有效的分析工具，不同现象的描述，通过它竟变得如出一辙。恐怕这样的例子俯拾皆是哩，从许多现象抽象出相同的模式，再在不同地方转换视角等同视之，难怪有人说数学在于抽象，这算是数学的想象力吗？可恶，当这样想的时候，我就已经落入某个圈套了。稍移目光，白鹿看到姜枫倚在槐树旁，半梦半醒地看着什么，顺着他的目光仔细观察，几只蚂蚁正在树根旁穿梭忙碌。

## 终

当几个人知道怎么确定最佳产量时，一番研究总算没白费。奚午摇了摇姜枫：“枫姐，就靠你的秘方了。”

“什么秘方？”姜枫惊讶地问道。
