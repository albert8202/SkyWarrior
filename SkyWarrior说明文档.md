# Sky Warrior说明文档

> author:1751188 李佳诺

[TOC]

## 设计思路

**Sky Warrior**是一款提供**多人称视角**的**3D**战斗机作战游戏。游戏玩家作为空军飞行员，需要负责守卫基地的安全，在空中击退来犯的敌机。

## 游戏介绍

![image-20200610212713050](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610212713050.png)

共有三种模式，分别是***Classic, Modern, Invasion***，即经典空战，现代战争，异形入侵三种模式。每种模式，对应不同的地图，玩家会驾驶不同的机型，配备有不同的武器，提供的视角也会多种多样，而同时来犯的敌机也会不同。玩家的职责就是在避免自己被击落的情况下，击退尽可能多的敌机，成为天空勇士。

### 场景介绍

- `Classic`：经典空战模式，采取传统的空战方式，飞行员主要通过机关或者机载火炮，凭借肉眼瞄准，击落敌机

  ![image-20200610213554990](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610213554990.png)

  

  - 机型：P51A“野马”
  - 武器：1. 连发机枪 ；2. 机载火炮
  - 瞄准方式：第三人称下通过画面中心的准心进行瞄准，第一人称下通过物理瞄准器瞄准

  ![image-20200610214022472](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610214022472.png)

- `Modern`：现代战争模式，智能化信息系统的空战，飞行员可以通过电子瞄准，发射短距离红外跟踪导弹击落敌机，不过，此时的敌机也有较高机动性，有一定概率规避来袭导弹

  ![image-20200610215900747](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610215900747.png)

  

  - 机型：F16"战隼"
  - 武器：1. 短距离红外跟踪导弹 ；2. 对地轰炸炸弹；3. 机载火炮
  - 瞄准方式：可以通过界面中心准星瞄准，也可以通过智能火控瞄准系统，锁定敌机后发射导弹即可

  ![image-20200610220017059](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610220017059.png)

- `Invasion`：异形入侵模式，该模式下，采用未来战争的理念，对抗外来物种的入侵，外来物种驾驶着超高性能的飞机，玩家需要驾驶F16击退他们。

  ![image-20200610221013607](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610221013607.png)

  - 机型：F16"战隼"
  - 武器：1. 短距离红外跟踪导弹 ；2. 对地轰炸炸弹；3. 机载火炮
  - 瞄准方式：可以通过界面中心准星瞄准，也可以通过智能火控瞄准系统，锁定敌机后发射导弹即可

  ![image-20200610220639655](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610220639655.png)

### 操作介绍

- 操控飞机：按键盘A，D或者⬅，➡控制转向，鼠标移动控制爬升，俯冲，翻滚
- 火力控制：鼠标左键发射，右键切换武器
- 视角切换：按C切换视角
- 平衡控制：按M使飞机恢复平衡

## 功能

### 1 多种地图

三种不同的地图

![image-20200610213554990](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610213554990.png)

![image-20200610215900747](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610215900747.png)

![image-20200610221013607](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610221013607.png)

### 2 多种武器

有普通火炮，机枪，炸弹，与跟踪导弹

![image-20200610222215000](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610222215000.png)

![image-20200610222253845](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610222253845.png)

![image-20200610222355543](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610222355543.png)

### 3 多种视角

提供多人称视角，使得玩家更好地把控战场全局

![image-20200610222632146](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610222632146.png)

![image-20200610222647541](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610222647541.png)

![image-20200610222702994](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610222702994.png)

### 4 自动瞄准

飞机的瞄准系统可以为飞机自动瞄准敌机，识别敌机，标注距离，并且锁定后可以发射导弹

![image-20200610221817648](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610221817648.png)

### 5 智能辅助驾驶

配备有先进的航电系统，可以实时显示来犯敌机的位置，还可以感知自己的飞行姿态

![image-20200610222845406](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610222845406.png)

![image-20200610223043463](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200610223043463.png)



### 6 AI敌机

敌机会越来越”聪明“，利用超高的机动性躲避玩家发射的导弹，并且会与玩家展开缠斗，使得游戏更加逼真刺激

## 项目特点

3D粒子效果，打击感非常强，飞机模型、战场环境逼真，飞行感知灵敏智能，火控系统先进，非常有挑战性。

## 开发环境

前端开发框架：WebAssembly，WebGL

引擎：Unity，packages: TextMesh Pro，Timeline

服务器：Python

## 运行方式

- 打开cmd，进入web文件内
- 运行指令：python -m http.server 8000
- 待命令行中显示已经在8000端口开启服务后，打开了浏览器，输入http://localhost：8000即可
- 想要成为Sky Warrior吗？快来玩叭！