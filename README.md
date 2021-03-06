## Tank-Game 基于 Basys3 的坦克大战游戏

本设计是基于Xilinx Basys3的坦克大战游戏，通过Basys3板卡控制“坦克”的移动和射击，由拨码开关控制游戏的开始、模式选择等。游戏分为经典模式和无尽模式，经典模式中有4辆“敌方坦克”追击“己方坦克”，被击中后血量减一，直至血量为零后游戏终结，同时每击毁5辆坦克可使血量加一；无尽模式中以时间为游戏进度，倒计时结束后游戏终止，两种模式下击毁的坦克数均显示在开发板的数码管上。同时设置了道具机制，游戏中可随机掉落“加速”、“激光”、“冻结”等不同的道具，分别对应不同效果，丰富了游戏体验。

<img src="https://picture-1256315926.cos.ap-shanghai.myqcloud.com/img/20190621002341.png" width="600" height="600">

## Snake-Game 基于 Basys3 的贪吃蛇游戏

本设计实现了一个基于Basys3平台的贪吃蛇游戏。利用Basys3上的VGA接口连接显示器作为游戏界面，利用Basys3板卡上的按键进行控制，实现了贪吃蛇游戏的基本功能，同时添加了“奖励机制”，随机掉落一些奖励如加分、减缓速度等。

<img src="https://i.loli.net/2019/06/21/5d0c458bbadfc23980.png" width="600" height="600">
