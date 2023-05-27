---
{"dg-publish":true,"permalink":"/MACD指标/","noteIcon":""}
---

MACD指标是《缠中说禅》中最重要的辅助指标，主要用来判断各级别股价运行过程中是否与该指标发生背驰走势，若背驰则股价就要发生反转。此文让你对此指标和中枢，有更进一步的理解。

# MACD基础知识

## 定义

MACD称为异同移动平均线，利用收盘价的短期与长期指数移动平均线之间的聚合与分离状况，研判买卖时机的技术指标。

**缺点**
- **震荡行情MACD指标可能失真**。MACD指标属于趋势性指标，如果股价进行箱体（水平箱体和斜箱体）运行，则MACD指标无效，按照信号进场后随即又要出场，用KDJ指标研判则更加有效。
- **MACD指标存在一定滞后性**：MACD的移动缓和，与行情有一定的时间差。当行情迅速大幅涨跌，MACD不会立即产生信号。

## 计算公式

白线，即DIFF线(Difference，也可以叫快线)：收盘价短期、长期指数平滑移动平均线间的差。

黄线，即DEA线(DifferenceExponentialAverage，也可叫慢线)：DIFF线的M日指数平滑移动平均线。

DIFF在DEA之上， MACD柱状表现为红柱。反之为绿柱。

MACD先计算快速（一般选12日）移动平均值与慢速（一般选26日）移动平均值（EMA），再通过快速减慢速计算“差离值”（DIF），最后计算DIF的N周期（一般选9日）的平滑移动平均线DEA（也叫MACD、DEM）线。具体计算过程如下：
1. 计算移动平均值（EMA）
   1. 12日EMA：EMA（12）=前一日EMA（12）×11/(12+1)+今日收盘价×2/(12+1)
   2. 26日EMA：EMA（26）=前一日EMA（26）×25/(26+1)+今日收盘价×2/(26+1)
2. 计算离差值（DIF）
   1. DIF=EMA（12）－EMA（26）
3. 计算DIF的9日EMA，为不混淆，此值名DEA或DEM
   1. DEA（MACD）=前一日DEA×8/10+今日DIF×2/10
4. MACD柱状图
   1. MACD柱状=（DIF-DEA）×2

## 现象含义

- DIFF 与 DEA 均为正值，属多头市场。
- DIFF 与 DEA 均为负值，属空头市场。
- MACD 绿转红：MACD 值由负变正，市场由空头转为多头。
- MACD 红转绿：MACD 值由正变负，市场由多头转为空头。
- MACD金叉：DIFF 由下向上突破 DEA。
- MACD死叉：DIFF 由上向下突破 DEA。

日线级别中，MACD指标的0轴和60日均线是相同的，股价若上60日线，黄白线尤其是白线也必上0轴，同理，若黄白线上0轴，股价也必要冲上60日均线。

# MACD指标0轴之下离场


MACD指标，0轴分为多空主导。MACD指标在0轴之下，空头主导，必须远离。

这涉及时间周期，例如，1分钟就经常在0轴上下。可以根据自己的能力，决定一个最低的时间周期，例如：60分钟图上的或30分钟图上的，==一旦出现最低时间周期的MACD 0轴以下情况，就彻底离开这个市场，直到重新站住0轴再说==。

下图大盘60分钟图，5200点MACD跌破0轴并反抽确认后，一直到现在3000多点，一直就在0轴下晃悠。
![图103-1 上证指数 60分级别走势图](https://pic1.zhimg.com/80/v2-2bc48724172741d925724dd1b9a25b78_720w.jpg)

# MACD指标判断背离

MACD指标主要由三个分指标构成：黄白线（常用）、红绿柱（较常用）、红绿柱面积（大多不用）。若有一项背驰，就要注意，若是黄白线背驰，则注意程度加大。若有两项同时背驰，则基本就确定是背驰了，若三项财时背驰，那必定是背驰了。

五分钟以上级别，可以用黄白线来判断，有时可以结合红绿柱的长短。一分钟级别，只用红绿柱长短即可。

## 黄白线离0轴远近的判断

这个指标主要是指，股价创出新高或新低，但黄白线却没有创出新高或新低，而是呈现出的与股价走势相背的方向。

下图中，股价在不断新高的过程中，MACD黄白线，却是不断走低的，形成背驰。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKMYDdliaSsyn6XJKNJgPyGjf01uEjKTCLiaM8OLic1Reg0rSKqNABN6OjWFyYUgtibQnUsF7eDptqibb8w/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

下图中，股价不断新低，但MACD指标的黄白线，绿柱长短和面积，形成背驰。

![pic](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKMYDdliaSsyn6XJKNJgPyGjfaxIp3aZ2AfuwHKmTkicANK1GvkqDBgMo1icHaurAMnaVv0XrUAw8qu1g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

## 红绿柱长短的判断

红绿柱的长短，可用于对背驰的辅助判断。红绿柱长短与白线（DIFF）和黄线（DEA）间乖离度有关。行情变化快，白线和黄线的乖离度就大，柱子就长。

下图中，000912泸天化在股价创出新高之后，下面的黄白线高低目测基本变化不大，但红柱却是明显的变短的，呈现出背驰或盘整背驰的走势。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKMYDdliaSsyn6XJKNJgPyGjfuLuTgdUBywlQzeyBtcLznsK4zsyQO7UPh12pYTIU4m6lEFA7Wm4oibg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

下图中，002571两波下跌低点时（2个方框，2个例子），黄白线不最低，绿柱明显变短，甚至前一波是变的非常的短。呈现出与股价明显的背驰走势。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMYDdliaSsyn6XJKNJgPyGjfmCJWXCHdnclOauf9qAIBvOsuv3A8IGuvlmvpZXibCEUkRTgbOOdWiacw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

在绝大部分情况下，柱子的长短与黄白线的高低是呈正相关的。也就是说，对于上涨，若股价创新高，红柱却变短，这时对应的黄白线也离0轴变近；对于下跌，若股价创出新低，但绿柱变短，这时的黄白线也大数离0轴变近。

## 红绿柱堆面积

利用红绿柱面积判断背驰。不常用，多出现在特殊的个股走势中，且量不多，因此，只作为了解内容。下面给一个图谱，大家自己看看就行了。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKMYDdliaSsyn6XJKNJgPyGjfelH7WHy5aic0GPNo6UBhmAkibWj16ffrb1f06ibQmHvYDImkNgdsmD1zw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

## DIFF新低辅助判断背离

背离的意义是速度。下跌趋势中，跌势减速DIFF就拐头，底背离就成立；上涨趋势中，上涨速度减速DIFF也会拐头，顶背离成立。

有些行情3浪下跌的结束点也会呈现下跌速度变慢的走势，但不是真正的底部。

![](https://mmbiz.qpic.cn/mmbiz_png/GvM5fFd6qKTcwq4pBNicOkedDqeybqNjC9ZQS8yzPOvMSvT0y7C97UDy9u0NuOfCD5xg07sxFtH2brh35J6gUeg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

如何应对3浪底产生的假底背离？其实方法就是==DIFF创新低止损==。在上图下跌趋势中，红色5浪下行过程中，DIFF很难破掉3浪下跌新低的。忍过去后就是最后黄色走势供你获利出局。

如果DIFF再创新低，就说明指数的下行速度加快了，这不符合5浪末端速度变慢的波浪描述，所以自然就需要对抄底预期做修正，落实到交易动作上就是：止损。

因此：用60分DIFF新低做止损。

## 注意事项

- 抄底一定要等背离出现，而且指标要形成共振金叉。如果没有金叉，第二天继续跌，背离就消失了，抄底怎么背离后还有背离，就是这个原因。
- 严重大幅杀跌的标的会持续背离，不会抄底进场。选择强势调整的底背离结构。
- 连续的顶部背离，需要一个充分的振荡调整时间，形成一个高位箱体的盘整结构，会出现了多次的短线机会，需要我们技术的去把握。
- 60分钟底背离反弹的周期是一周

# MACD黄白线判断中枢

## 中枢形成过程中黄白线的走势

对于任何级别的股票，其黄白线与股价呈正相关走势：
- 多头行情中，股价上涨，黄白线上行，远离0轴；股价下跌，黄白线下行，回试0轴。
- 空头行情中，股价上涨，黄白线上行，回试0轴，股价下跌，黄白线下行，远离0轴。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASXj2J4fFnoRqwr9Kk4pfs8JVBUVKlvcdsRqiak7iciagnvshIsMcs94Ing/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

股价运行必然要形成中枢，黄白线对应有如下走势，如上图：
1. 01笔上涨，黄白线上穿0轴，并逐步走高远离0轴。在高点1处，黄白线达到第一个高位a处。
2. 12笔回调，到低点2处，黄白线从a下到b点，回试0轴。大多数情况下，第一次回调并不能使黄白线充分回到0轴附近。
3. 23笔上涨。黄白线从先前的死叉下行，转出第一次金叉向上，但幅度不会太远。绝大多数情况下，第二笔上涨可能突破前高点，如23笔突破前高点1，但黄白线并不必然会突破前面的高位，一般会低于前高位处，如c处明显低于前高点a处。
4. 34笔回调，黄白线也随之二度死叉下行，绝大多数要回到0轴附近，甚至击穿0轴。这时构成上涨中枢的12、23、34三笔全部走出，后面就有可能是出中枢的一笔上涨。

形成中枢过程中，黄白线至少两次向0轴靠近。若中枢延伸，黄白线相应要再度向0轴回压，击穿0轴的情况就较多了。

![菲达环保日线](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASLibuHOmqdTDkg2IIgZKlNBgJPNDgu8iaacTxOWH58aaZ0qziaboCkzSLw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

上图是菲达环保的日线图谱，其构成中枢的第一笔回试，黄白线就充分的回试到了0轴附近，其第二次回试，仍是回到0轴附近的，只是第三笔击穿了0轴，当然，这个第三次下调的笔，属于中枢延伸出来的笔。

在第一个上涨中枢中，第二笔下跌的低点，属类二买。较多的情况是，若这一笔对应的黄白线回试到了0轴附近，其出中枢的概率相对就大，尤其是在第一笔没有回试到0轴附近，而第二笔接着继续下行回到0轴附近时，它出中枢的概率相对加大。

黄白线只有从远离0轴，经过形成中枢之后，充分回到了0轴附近，这时出中枢的一笔，才是真定意义上的背驰段。对于第一个上涨中枢，它有可能回试一笔形成第三类买点，对于第二个或以上上涨中枢，背驰段最终背驰，是形成第一类卖点的。

## 中枢形成过程中黄白线三种走势

在中枢形成过程中，MACD指标的黄白线有如下三种运行方式：

1、第一笔回调即回到0轴附近

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASJRTRvFmc8d1fbVgeiaMW5A21enXX7NNGPDyoNUfATR7EvhVGlqichSiag/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

如上图300315掌趣科技的日线图谱。第一笔下行成笔时，黄白线就回到0轴附近，后面的反弹形成中枢第一笔上涨时，黄白线在0轴之上，先金叉再死叉，黄白线高度明显低于前者，且红柱高度或红柱堆都较小，后面的第二笔下，黄白线再度回到0轴附近。黄白线的两次向0轴靠近过程，使得股价在震荡过程中形成中枢。

由于一笔上涨之后的第一次回调，很可能构成上涨中枢的第一笔下行。若其下面对应的黄白线当即就回到0轴附近，后面虽然仍会从0轴之处向上离开，却较大可能是在形成上涨中枢的第一笔上涨，因此，在前高点附近即开始第二笔下跌是较大概率的事，因此，虽然是0轴之上的第一次金叉（后金叉），由于较大概率是要形成中枢的且是第一笔上涨，并基本会有前高点附近结束上涨，因为，这一笔的上涨幅度就有限了。

2、两次回调才回到0轴

这种情况是指黄白线下降过程中，由于股价是震荡形成上涨中枢的过程中，必然会有一笔上涨，那么，它有较大的可能使得黄白线先金叉之后再死叉一次，但总体呈下降趋势。如下图。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASpUBLr0awCUWdogrwdibiax0eF5007l0K9D0pcTz5mECpafHbibhWJEUgQ/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

上图是000570苏常柴A的日线图谱。股价在形成中枢的第一笔下时，黄白线从远离0轴开始向0轴靠近，只是在第一笔下跌结束时，黄白线仍离0轴较远，股价反抽，形成中枢的第一笔上，黄白线先金叉后死叉，只是显得非常的弱，其对应的红柱少而短。反弹结束后，股价第二次回落，这时，黄白线继续下行，并回到了0轴附近。在整个中枢形成过程中，黄白线虽然有一个金叉过程，但总趋势呈下降明显。

黄白线通过中枢形成过程中的两次回调才回到了0轴附近，这时，后面的走势有较大可能的是向上出中枢，较小可能的是中枢延伸，最小可能的是向下继续跌落。相对于前一种回试0轴的情况，这种情况后面上涨并突破的概率就较大了，它显得比第一种情况的回试0轴要有利的多。

3、中枢形成但黄白线没有在中途形成有效的金叉

这种情况是指黄白线在第二笔下结束时回试到0轴，但它在上涨一笔过程中，黄白线没有返身向上形成金叉，只是白线向黄线靠近了一次，没能形成金叉就继续下行的情况。如下图。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASqEaAw5b0u98n7EmJ3aTdicrDI4XAHmJvJWj8pQTAcM2rbhYMuFn4oJQ/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

上图是002632道学光明的日线图谱。在其上涨中枢的形成过程中，由于中间一笔上涨中有下跌K线，使得这一笔上涨的空间距离较小，但却成笔。还有一种情况就是前面的上涨幅度较大，在回调的第一笔时，黄白线从离0轴较远的地方开始下降，中间反抽一笔，虽然有可有不存在下降K线的问题，却也不能使黄白线下降过程中的返身相交，并形成有效的金叉，或只是相交一下，白线最终没有上到黄线之上，表现为没有出现红柱，就继续下行，在第二笔的下行结束时回到了0轴附近。

由于这种情况表现为黄白线总体为一次就回归到了0轴附近，且能在0轴之上形成后金叉，最主要的是，它上面相对应的股价在震荡过程中已经形成了中枢，因此，其后面上涨一笔出中枢的概率就极大，这是三种形成中枢过程中用黄白线回归0轴后较好的一种买点。

## 利用黄白线判断中枢级别

利有黄白线是否充分的回试了0轴，还可以用来判断中枢级别的。比如某一级别震荡形在中枢，在次级别中也必然有一个对应的中枢，这时，怎么来判断这个中枢级别是本次级别，不是次级别的呢？就是要看是本级别中，黄白线充分的回试了0轴，还是次级别中，黄白线充分的回试了0轴。

对于上述中的包钢股份和菲达环保两个图谱来说，由于中枢形成过程中，黄白线均有一次以上充分的回到了0轴附近，那么，这两个图中的中枢，就是日线级别的。当中枢延伸时，只要有一次充分的回试0轴的动作，就是这个级别的中枢，不要求全部都回到0轴附近。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASGslewGucDJe0mJNRuSFRO4sV0iaZYeRaGy1s156pcodY8PcozO50L9A/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

上图是天邦股份在下跌时形成中枢过程中黄白线的运行状态。在形成中枢的上下上三笔中，黄白线两次均回到了0轴附近，后面的延伸一笔的上涨，黄白线是击穿了0轴的。形成中枢时，有一次是充分的回到了0轴附近，就是合适的。

黄白线是否充分回试了0轴，可以稍微宽松一些，离0轴稍高一些或稍击穿0轴都可以。如中枢出现延伸，可以有那么几笔击穿0轴，但至少要有一笔是刚好回到0轴附近的。

某一级别的图谱中，中枢在形成过程中，不管它是上涨中枢或是下跌中枢，只有出现一次黄白线充分的回试到0轴附近的情况，那么，这个中枢级别就是该图谱的级别，若离的太远或击穿的较深，中枢的级别就不是所看的图谱的级别。

下图是002469的日线图谱，它显然是有两个中枢的。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASZAFS1M2mtyteyicR6ygaA2ticHjSBsPMouicmEibM76gbKRyYQNib4KDKDg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

上图中三维工程的下面一个中枢，显然有充分的且不止一次的回试到0轴附近的过程，其中枢级别当为日线级别的。但上面的小方框内仍有一个中枢，从这个中枢下方的黄白线来看，它显然不是日线级别的，因为离0轴太远。

下图就是三维工程日线图中小方框中中枢对应的30分钟和60分钟两个级别的图谱。从30分钟的图谱中看，股价震荡过程中，黄白线第一次回试离0轴太远，第二次以后即全部击穿0轴，且较深。显然，说它是三十分钟级别的中枢，显然是不合适的。

而60分钟的图谱中，第一次回试就回到了0轴附近，虽然后面也击穿了0轴，但有一次较为充分的回试0轴的动作，那么，它显然是60分钟级别的中枢。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASVTGB6icQnx0YMx5t9juCwnmMCFeiap1LHaRHyqQU6gmDcKZeibPFwQ77g/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

# 红绿柱长短对次级别的判断

红绿柱长短还有一个重要作用，就是对次级别的辅助判断上。

在本级别图谱中，若股价上涨创出了新高，这时的黄白线也略高于前面的高点，但红柱明显比前高点时的红柱变短，此时构成次级别背驰。

下图是601668中国建筑的日线图谱，且也是一个较为特殊的例子，说它特殊，是因为股价上涨途中三根阴线调整，并没有使黄白线死叉，没有出绿柱，股价再度新高时，红柱虽然结束变短并再度伸长，却伸长无力，总体呈现股价新高，红柱不最长的形态。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKMYDdliaSsyn6XJKNJgPyGjfgPQibKvXjcDQC6aD0nbZrwa8aMXaibNK2EBialZlQshMXrUibXmZAeoQVQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

下图是其30分钟图谱，在这个图中，可以明显的看出来本级别是背驰的。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKMYDdliaSsyn6XJKNJgPyGjfq4icN0hBgOPnGrqiaKavqeWyA17HVtyXz1ibL6JyB81c6jicQodFsQspDg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

绝大多数情况下，股价经过一波的上涨之后，回调的较为明显，最主要表现在黄白线有一次死叉过程，出现了绿柱。然后再上涨，创新高，黄白线在离0轴较远的上方再度金叉，并新高，但红柱却较短，本级别不背驰，次级别背驰。因为前面我们说过，黄白线在MACD的三个指标中是最主要的，它与股价同时新高，说明本级别是不背驰的。若此时股价新高时，红柱不能最长，则次级别是背驰的。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKMYDdliaSsyn6XJKNJgPyGjficxn3QKibicEcUO9NcvNt66JpwM6gFB4FthyYPib1NzZnXia1TycJbVebyA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

上图是长亮科技的日线图谱，股价上涨，黄白线也跟着新高，但红柱却没能伸长，每次回调均出现了绿柱，说明黄白线在股价回调时死叉了。尤其是股价最高时，虽然黄白线最高，但红柱最短，这时，就能断定，次级别背驰了。下图是其三十分钟图谱，在此级别中股价最高时，黄白线也不最高，且红柱只有两根小小的。本级别背驰。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKMYDdliaSsyn6XJKNJgPyGjflKMFhnr0TYON4D5Zia2lV1RM1A2fZWtzibArLHql7GBnMPGOzlwicHUAw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

在绝大多数情况下，若背驰出现，表现的均为黄白线和红柱同时不新高的情况，前面说的是较特殊的且是较少的情况，下面也给一个大众图谱。这种情况是最多的。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKMYDdliaSsyn6XJKNJgPyGjfVfDU7MMicV3lz2pjbhs8W59zKABwlBuUJLPGo2zPROe59EPvAicSgFQA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)


# MACD形态解读

## MACD指标中黄白线的双头形态

简称为MACD双头形态或黄白线双头形态。

黄白线的双头形态，指股价上涨过程中，有一次小的回试，且这次回试使得黄白线有一次死叉过程，只是回试的力度较小，然后继续上涨，并创出新高，此时黄白线再度金叉，只是这个金叉的位置离0轴较远，黄白线上升到前高点附近，就结束上涨，基本与前高点持平，或略高，或略低都可以，但不能相差太远。此时的红柱肯定是短的，因为红柱变短，但对应的是股价的新高中，所以，它次级别背驰，必然有一波回调，且力度会较大。

绝大多数情况下，黄白线的双头形态，必然使得后面有一笔下行走势，它的力度可强可弱，只是，黄白是必要回到0轴附近的，且双头形态的后面一笔回调，较多的情况下，是力度较大的。

下图是601111中国国航股价在最高时，MACD指标的黄白线的双头形态，黄白线在0轴之上且离0轴很远的地方，先死叉，再金叉，由于黄白线离0轴较远，虽然再度金叉，却限制了后面涨升空间。股价新高时，黄白线与前面略低一点儿，但红柱却是明显的短很多，且面积也小很多的。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKPAQH7ToywJw5DsPx6FxlmoNMLYxmE7hyicB2aBDSGId3IbZ4FdiaMj8hRM5jQR8lPsB6V6IphRxL2A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

黄白线双头形态之后的最主要的走势，肯定有一笔下跌的，黄白线绝大多数情况下要回试0轴。这个回试，有可能跌破0轴，也有的会在0轴之上附近止跌，黄白线的这种走法，各占一半的概率。比如上图中，黄白线双头之后的下行，是击穿了0轴的。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKPAQH7ToywJw5DsPx6FxlmomR3RV26Rbdib2aQ57rrqUNBG31fg8U5rYCwLNSpsjBYpLkLgVGOTjKw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

双头形态的最主要特征有三个，一个是黄白线在离0轴较远的位置先死叉，再金叉，二是出现绿柱，三是黄白线基本水平，但可以放宽这个条件，就是可以略高或略低，但不能太多。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKPAQH7ToywJw5DsPx6Fxlmo68uewIWrSiavcOlHmrMqNQGj24ibGObedjyMJDDIkqvqG1grJPepkwibA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

上图中的000069华侨城A就不能算是双头形态，主要是后面的黄白线与前面的相比较不是略高，是显然高的太多。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKPAQH7ToywJw5DsPx6FxlmogNLJCGCUgd3SWRX0mh04mlQ366nwiaicTu6lsKHWmkqIv5bzUsPoUEpA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

上图中000411英特集团也不能算是双头形态，因后面后的黄白线与前面相比较，不是略低，是低的太多了。

双头形态最关键的走法，就是使黄白线在接下来的走势中回到0轴附近，甚至击穿0轴。当然，这伴随着此级别的一笔下行，这笔下行倒不一定就必然跌的很快。

## MACD指标中黄白线的双底形态

简称为MACD的双底形或黄白线的双底形态。

双头和双底是对应的，把前一部分的内容反过来理解就行了，但仍担心一些人理解不了，简单再写下。

双底形态是指在一波下跌过程中，股价有一波反抽，致使黄白线也有一个向0轴靠近的动作，但这个动作，走的不远，然后再度死叉下行，使得黄白线在前低点附近止跌，并再次向0轴大幅靠近。

它的主要技术特征是，一、两个小底的黄白经高低差不多，可略高或略低，但不能太远；二是必须在第一次回试0轴时，且离0轴较远，有一个先金叉后死叉的过程；三是第一次回试过程中必须出了红柱。

双底形态的后续走势，也是一笔上涨过程，当然，这个上涨，或快可慢，也没有幅了限制，最主要的是，它必然使黄白线在这一笔上涨过程中，回到了0轴附近，甚至站上了0轴。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKPAQH7ToywJw5DsPx6FxlmoVuQl6ykXeC7L95mJZsEWpoVxVCzBHdxHyS90xnHF0WYyhNaMCBsGQA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

上图是002526山东矿机的日线图谱，股价在第一笔下跌时，就使黄折线从0轴之上向下击穿0轴，且远离0轴，后面的一笔反抽时，黄白线第一次向0轴靠近，只是走的不远，再度死叉下行，黄白线的低点与前低点基本相当，但绿柱缩短，这是次级别背驰的特征。然后随着一笔上涨，黄白再度向0轴靠近，最终站上了0轴。

下图是一个较特殊的例子，在形态双底之后，它不是随之一笔上涨，而是横盘震荡，形成一个小级别中枢，而就是这个小中枢的震荡过程中，黄白线已经上行并接近了0轴。

![img](https://mmbiz.qpic.cn/mmbiz_png/fhlusniafmKPAQH7ToywJw5DsPx6FxlmoUFzsAcXLu16uhEfoA2LEVHk9Xdu1kqGWRHgjwIN7EGRKdb5ZYaiadBA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

下图是002563森马服饰的日线图谱，它在前一波的下行过程中，曾先后出现两个双底形态，前一个离0轴较远，但随后一笔也回到了0轴。后一下离0轴相对近一些，但与黄白线的总体来看，仍为双底形态，只是第二个小低点略高于前一个小低点，随后虽然仍是震荡盘跌，但黄白线却背驰上涨，并最终回到0轴附近。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKPAQH7ToywJw5DsPx6FxlmofBUcibKzjK1TV1icmicFJPPSa2RHgjDulVR5ENHJAqZjbuAIsJLiceWuwA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

与双头形态一样，黄白线的双底形态，也是考虑的随后一笔的上涨，使黄白线回归0轴的动作。因为这个回归0轴的动作，绝大多数情况下，是伴随一笔上涨的，且占一半的概率涨的较好、较快。

## 0轴之上后金叉

0轴之上后金叉也是针对MACD的黄白线来讲的。是指股价经过一波反弹、拉升走势之后，使得黄白线第一次从0轴之下回到0轴之上，进入多头形态，并且向上远离0轴。然后随着一波段拉升的结束，股价开始第一次回调。此时，部分个股会在股价第一次回调中，黄白线就充分的回到了0轴上方，且离0轴较近。随着股价回调的结束，再度上涨，此股黄白线也在0轴之上（且是附近）再度金叉向上，这个金叉，就是0轴之上后金叉。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASp5YzEzdiczYcMsAUM8NYEdLmibRSnrWL14Q9ZHLibVFZWic4jBPOib5up0w/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

从上图中我们可以看出，股价先是缓慢的上涨，然后出现一波极速上涨走势，使MACD的黄白线从0轴之下上升到了0轴之上，并且快速远离0轴，股价在随后回出的一笔回调中，黄白线也第一次从远离0轴的地方回归0轴附近，并且在其上，随后金叉向上，股价再度走出一大笔上涨走势。

0轴之上后金叉，主要是考量的这个金叉的位置，它最后是在0轴之上，且是离0轴越近越好的，因为这样后面起涨一笔，力度会大一些，涨的也会快一些。金叉的位置略微高一些的，也可以，但太高了，其后的上涨空间就会受到限制，主要是因为太高时，股价稍微上涨，就在其突破前高点时，黄白线也上来了，但红柱子却不能有效的伸长，于是就形成一个次级别背驰的状态。

由于要求后金叉的位置越低越好，但得在0轴之上，就有可能会是白线稍微的击穿0轴，但黄线仍在0轴之上的情况，这时的金叉，也在0轴之上。

下图是000927一汽夏利的日线图谱，它有两次日线成笔回试过程，且对应的黄白线也都是回到了0轴附近。只后第二次的白线，略微的击穿了0轴，但黄线仍在0轴之上，且其后形成的金叉，也在0轴之上。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBAS80roH3tFvb4JaRrCXXh426xFuwg8IgickLGFBmGHx3DGqeqXRFU69JQ/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

## 0轴之下后死叉

这是与0轴之上后金叉相反的一个技术形态。随着一波股价下跌，致使黄白指标从0轴之上回到了0轴之下，进入空头形态，并且向下远离0轴。但在股价随后的第一笔反抽，即让黄白线从远离0轴向上回到了0轴附近，但仍在0轴之下。但股价再度下跌，黄白线也在0轴之下附近再度死叉，并迅速下行。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASTRiaZJL7ZAyVffyWflJYU5MB54HibojQk2EvTibgcib9vy4yTAFicItIKng/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

由于其和0轴之上后金叉是对应的相反的关系，这一次只给一个实例图谱。一般来说，第一次回试到0轴附近后的死叉下行，可能对应着一笔快速下跌走势。

## MACD指标黄白线的双回试形态

以上涨为例：黄白线的双回试形态，是指股价形成中枢的第一笔回试时，其对应的MACD指标的黄白线就充分的回试到0轴附近，随着股价的再次上涨，黄白线从0轴之上形成金叉后离开0轴，但这次的高点一般不会高过前一笔上涨的黄白线的高点，随着股价的再次下跌，黄白线也随之死叉下行，并随==股价的回跌结束而再次回到0轴附近==，形成第二次回试0轴的过程，称为双回试形态。

在前面讲中枢时，其中有一部分内容是讲中枢形成过程中黄白线的运行特征的，我讲了三种情况，
1. 构成中枢的第一笔，黄白线就回到0轴附近；构成最关注的两种技术形态—MACD指标黄白线的双回试和0轴之上后金叉（或0轴之下后死叉的）的前提。
2. 中间有一次金叉、死叉过程，黄白线有一个中继下跌（或上涨）过程，随后回试到0轴；
3. 虽然形成中枢过程中有黄白线有靠近性动作，却没有形成金叉或死叉，随后在中枢形成时回试到0轴。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASAZOgBm0vUWyRrbKFe7CdicG3QiagMbVoaTpI1sGic07FPiaSokPb6IuyTg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

上图是300278的日线图谱，股价在形成中枢的过程，黄白线有两次回试0轴的动作，且每次均回试到0轴附近，不是那种离0轴较远或击穿0轴的情况，随后出现一笔幅较大的上涨。

回拉零轴的关键在于：盘整段内前低附近要做出本级别底分型，以判定回拉成功，不会下穿零轴。操作要点是右侧底分出现后尝试进场，止损放到前一个底分型低点即可。<span class=cmt>此段其它文章内容，待验证</span>

双回试形态也可以出现在下跌过程中的反抽走势中，一般如果经过两次非常接0轴的回拉，仍没能使黄白线站上0轴，后面就有出现一笔相对较大幅度的下跌走势。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASe7kpJa7OPaKTaw1FBoarYdcydTdrhgcGRETRg0JVZfGc3sF76PBcNw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

无论是上涨过程中的双回试还是下跌走势中的双回试，都是形成中枢的过程。==对于上涨，若是利用双回试买入的，最好是利用形成第一个上涨中枢的双回试==，因为第二次回试的低点，是类二买点，其买入后上涨的概率较大。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASBINDY4sAfiaaenBG3icgABG05ZicLJvjC4kIssWFxSOz9R83y2c0XR3icA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

对于下跌，若双回试出现在第一个下跌中枢之后，其后面当会有较大的下跌幅度。

可以近似认为，无论上涨回调时或下跌反抽时，黄白线都要先从远离0轴的地方向0轴靠近，然后再考虑是否击穿。若两次均回到了0轴附近而不击穿，那么选择再度上涨或下跌的概率就较大了。

## 第二红峰起

第二红峰起，是针对MACD的红柱子指标来讲的。一般是指，股价经过一波相对较大的涨升之后，开始回调或横盘震荡，这时必然是白线向黄线慢慢靠近，二者乖离变小，红柱相应变短，在白线不死叉黄线（不出现绿柱子）前，调整结束，股价再次上涨，此时红柱子再度伸长，这就是第二红峰起。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASmhYjWEV9FGvzP1Jw4s4RdXQibjJ4QSRbAqVNB1NiaXKDicXpk7DhWwBpg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

上图是以震荡代替回试的走势，当然，这个震荡也是形态次级别中枢的过程。有时，回试幅度较小，本级别不成笔，或成笔但都是小线体，会使白线不死叉黄线，也就是不出现绿柱子，然后随着股价的回调结束并开始上涨，红柱子也再度伸长。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBAS2ibnLJHyfBJqhIamrveFwyicEbU61ojrfyIA7pFkNWNnVJj26GAQCcsA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

对于前一波上涨幅相对不大，但涨升速度较快的个股，若中间仅以横盘震荡代替回调，其后面的第二红峰起来之时，仍会有较大幅度的涨升空间。

第二红峰起并不必然后面的红柱子就会长于前面的红柱子，有一些个股，第二次红峰起来时，其红柱子比前一段上涨形成的红柱子要短的，这时，股价若创出新高，则成了次级别背驰的情况。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASSZNCByvh8lwoQeU64l0jDFRfePQUoGicp4unyPZKic6mk0Crf5YUt1ww/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

## MACD黄白线的高位横盘

在绝大多数情况下，MACD的黄白线，在成笔的回试（或反抽）、或形成中枢（或次级别中枢时）都是会向0轴靠拢的。但仍有少量个股，黄白线并不回试0轴，而是呈高位横盘走势，并反复缠绕或粘连。这种情况多为次级别的中枢。

这种形态多发生在日线级别中。它有如下特征：
1. 股价呈震荡攀升过程；
2. 黄白不下行，或初期稍下行一点之后即呈横向走势；
3. 股价以10日均线或20日均线作为支撑，多数情况下以20日均线支撑，不轻易击穿此线。若以10日均线为支撑时，有击穿此线过程，但都在20日线之上，并快速回到10日均线之上。
4. 黄白线呈两次以上缠绕过程，若只缠绕一次，后面可能稍稍会向上倾斜，但幅度不大。缠绕时，两线的震荡幅度也不大。

下图是300229拓尔思的日线图，它是沿10日均线震荡攀升的。盘中有轻微击穿10日均线的过程，但很快收上来。黄白线在相对高位横向推进，此股略向上，幅度不很明显。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASx1vqMwtxAQulx8KBVrHkIOJ7tmDq6WVWXOBSvSwtgGYQq8sgeqTeqw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

下图是002076雪莱特的日线图谱，是呈沿20日均线震荡攀升形态，这也是这种技术形态的最多的，即沿20日均线上升。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBASicjAskVuff02ib4oCadFSCZWgRuOg3pHpdFXricia5q33nmlCI4Bjdvrmg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

这种形态的共同特征，是形成的次级别中枢的每一笔的低点和高点都是抬升的，尤其是低点。在本级别和次级别，基本都属于通道式上涨形态。MACD黄白线高位横盘的最主要的意义在于，后期突破通道式上涨的上轨阻力之后，会来一波快速上涨，也就是快速出中枢过程。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/fhlusniafmKMQib53ibVFZ9Q9mEzJ4pLBAScpZiacYRiaz6dgNOUt0Xn8NpE0QpSQUNSt0NZOycPYhOJQwMicsvbIbMg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

# 相关参考

1. [[投资管理/投资理论/波浪理论/一致性获利法中MACD的使用\|一致性获利法中MACD的使用]]
2. [[投资管理/投资理论/纠缠理论/背驰及MACD的辅助判断\|背驰及MACD的辅助判断]]