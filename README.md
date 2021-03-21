# 野兽争霸斗兽棋AI V1.3

![](https://cloud.githubusercontent.com/assets/6532225/18883792/44b26bbe-8517-11e6-8f14-896c01d77724.png)

## 更新日志

### 2021年3月21日（V1.3）

1.修复规则问题。（V1.3将狼大于狗更正为狗大于狼）

2.提高了计算层数。（计算10秒，V1.3：13层，V1.28：12层）

## 采用规则

本AI采用野兽争霸斗兽棋规则。（链接：www.doushouqi.net）

斗兽棋的棋盘

斗兽棋的棋盘横七列，纵九行，棋子放在格子中。双方底在线各有三个陷阱（作品字排）和一个兽穴(于品字中间)。 棋牌中部有两片水域，称之为小河。


斗兽棋的棋子

斗兽棋棋子共十六个，分为红蓝双方，双方各有八只一样的棋子（下称为：兽 或 动物），按照战斗力强弱排列为：象>狮>虎>豹>狗>狼>猫>鼠。


斗兽棋的走法

游戏开始时，红方先走，然后轮流走棋。每次可走动一只兽，每只兽每次走一方格，除己方兽穴和小河以外，前后左右均可。但是，狮、虎、鼠还有不同走法：

狮虎跳河法：狮虎在小河边时，可以纵横对直跳过小河，且能把小河对岸的敌方较小的兽类吃掉，但是如果对方老鼠在河里，把跳的路线阻隔就不能跳，若对岸是对方比自己战斗力前的兽，也不可以跳过小河；

鼠游过河法：鼠是唯一可以走入小河的兽，走法同陆地上一样，每次走一格，上下左右均可，而且，陆地上的其他兽不可以吃小河中的鼠，小河中的鼠也不能吃陆地上的象，鼠类互吃不受小河影响。


斗兽棋的吃法

斗兽棋吃法分普通吃法和特殊此法，普通吃法是按照兽的战斗力强弱，强者可以吃弱者。

特殊吃法如下：

1、鼠吃象法：八兽的吃法除按照战斗力强弱次序外，惟鼠能吃象，象不能吃鼠。

2、互吃法：凡同类相遇，可互相吃。

3、陷阱：棋盘设陷阱，专为限制敌兽的战斗力（自己的兽，不受限制），敌兽走入陷阱，即失去战斗力，本方的任意兽类都可以吃去陷阱里的兽类。

综合普通吃法和特殊吃法，将斗兽棋此法总结如下：

鼠可以吃象、鼠

猫可以吃猫、鼠；

狼可以吃狼、猫、鼠；

狗可以吃狗、狼、猫、鼠；

豹可以吃豹、狗、狼、猫、鼠；

虎可以吃虎、豹、狗、狼、猫、鼠；

狮可以吃狮、虎、豹、狗、狼、猫、鼠；

象可以吃象、狮、虎、豹、狗、狼、猫；


斗兽棋胜负判定:

1、任何一方的兽走入敌方的兽穴就算胜利（自己的兽类不可以走入自己的兽穴）；

2、任何一方的兽被吃光就算失败，对方获胜；

3、任何一方所有活着的兽被对方困住，均不可移动时，就算失败，对方获胜；

4、任何一方走棋时间用完，就算失败，对方获胜；

5、任何一方中途离开游戏，就算逃跑，对方获胜；

6、在双方同意的情况下可和棋；

7、在连续100回合内，双方均无动物被吃，就算和棋。


斗兽棋违例处理:

1、为了防止无赖长杀，在连续7步棋内，如果同一动物连续超过3次进入同一棋格，在接下来的第8步棋将禁止该动物进入该棋格（若7步内有进入陷阱，则不受该限制；被追动物不受该限制），该规则简称7-3违例规则；

2、为了防止武松长杀，在连续17步棋内，如果只操作同一个动物，且该动物的活动范围不超过5个棋格，在接下来的第18步棋将禁止该动物进入上述5个棋格中的任意一个（若17步内有进入陷阱，则不受该限制），该规则简称17-5违例规则；

3、若棋局在10个回合内结束，双方均不得分（为了防止刷分，比赛时不受此限制）。

## 战绩

截止2021年3月14日，累计胜34局，负7局。

估计该AI（1秒1步）水平接近人类高手（0.7~0.8*人类顶尖）。

野兽争霸斗兽棋账号：AI测试

## 下载链接

https://github.com/WZ403809264/animalcraft/releases/tag/V1.28

## 线上交流

QQ群：523715143
