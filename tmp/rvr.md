# 花式骚操作，玩转Rover小车



##封面

空间编程中的rover小车可以通过语音命令控制，也可以通过交通标志卡片来控制，还可以通过废旧的游戏机手柄来控制，甚至可以用手势来用手势来隔空操作小车，在小小创造家的客户端里你想怎么控制就怎么控制，我们提供丰富的积木插件，让孩子们可以充分发挥自己的想象力，自由快乐的创造世界！

<img src="../rvr/IMG_1848.PNG" alt="avatar" style="zoom:60%;" />
![mkdocs](images/IMG_1848.PNG "cover")


### 引入

国内儿童编程教育大多采用基于scratch的图形化编程环境，整个界面左侧是支持逻辑与运算的积木代码块，右侧是一个2D舞台，孩子们根据自己设计的故事情节在舞台上搭建出各种角色，并使用scratch提供的声音与图像引擎来做出各种动画与音效。孩子们在编程的时候往往面对的仅仅是一个像素的舞台，自己并不能置身其中，无法获得身临其境的感受，如果我们能够把这个2D的舞台扩展到真实的物理空间中，孩子就可以进入到这个空间舞台中控制天上飞的无人机、地上爬的机器人小车，以及与整个房间中的各种智能家居设备进行交互，这样的空间编程的感受会是多么摄人心魄。

<img src="/Users/changpeng/Documents/工作文档/公众号文章/scratch3.0.png" alt="avatar" style="zoom:30%;" />



### 01

### 空间编程中自由移动的四个轮子

在小小创造家客户端里，我们就为这个物理空间添加了一个履带式的rover小车角色，孩子们可以使用我们提供的积木块来控制小车的前进、后退、转向以及开关车灯的操作。

​          <img src="/Users/changpeng/Documents/工作文档/公众号文章/rvrstudioweb-0321.jpg" alt="rvrstudioweb-0321" style="zoom:35%;" />                   <img src="/Users/changpeng/Documents/工作文档/公众号文章/rover-block.png" alt="rover-block" style="zoom:35%;" />

 

在空间编程中Rover小车作为机器人腿的角色，可以自由自在的移动到空间中的任意位置，如果单纯只使用图形代码块进行驱动小车，未免感觉到乏味枯燥；在我们的小小创造家客户端里，我们可以使用编程空间中的其他任何智能体来来丰富小车的交互体验，比如我们就可以使用空间中的摄像头来为小车装上眼睛，用空间中音箱来为小车装上耳朵，用空间中各种游戏手柄来为小车装上方向盘，甚至我们可以用空间中的手势识别传感器来隔空操作小车，在我们的小小创造家的客户端里，你的想象力有多大，世界就有多大。

### 02

###拥有了眼睛的小车

我们为编程空间中添加了摄像头并接入了机器学习能力，孩子们自己就可以使用我们提供的teachable Machine工具来对交通卡片进行分类训练学习，进而使用机器学习结果积木块与小车控制积木块进行自由拼搭，完成一个识图控制小车的功能。

为方便孩子们理解和使用机器学习，我们重新设计了机器学习使用工具，孩子们可以在了解基本的机器学习的概念，比如数据、算法与训练学习的基本流程，就可以通过点击按钮进行训练学习，进而做出一个交通图标的分类器。在演示视频中，我们为了增强演示效果，特意新增了百度大脑的文字播报能力，在我们小小创造家的客户端里有丰富的机器学习插件供孩子们自由选择，孩子可以根据自己喜好来任意搭配各种人工智能的积木块实现各种创意的想法。

<img src="/Users/changpeng/Documents/工作文档/公众号文章/img_classifier.png" alt="rvrstudioweb-0321" style="zoom:40%;" />            <img src="/Users/changpeng/Documents/工作文档/公众号文章/img_rover.png" alt="rvrstudioweb-0321" style="zoom:35%;" />



<video src="/Users/changpeng/Documents/工作文档/公众号文章/tm.mp4" style="zoom:30%" allowfullscreen></video>



### 03

###拥有了耳朵的小车

我们为编程空间中添加了各种音箱并接入了百度大脑的语音识别能力，孩子们坐在沙发上就可以用语音来控制小车的启停与转向，就像小车自身拥有了耳朵可以听懂主人下发的各种语音命令；孩子们也可以定义自己的语音命令积木块，来让小车做出各种花式的轨迹，比如画圆、画正方形，画三角形，孩子们在玩的同时也开始接触最基本的数学知识。

​        <img src="/Users/changpeng/Documents/工作文档/公众号文章/tmall.png" alt="rvrstudioweb-0321" style="zoom:35%;" />            <img src="/Users/changpeng/Documents/工作文档/公众号文章/voice_rover.png" alt="rvrstudioweb-0321" style="zoom:35%;" />





<video src="/Users/changpeng/Documents/工作文档/公众号文章/voice.mp4" style="zoom:30%" allowfullscreen></video>

### 04

### 拥有了方向盘的小车

孩子们在玩单机游戏时候最喜欢使用JoyStick系列的各种游戏手柄，在我们的小小创造家客户端里我们为各种游戏手柄提供了积木插件，孩子们可以将自己在家闲置的各种游戏手柄拿过来控制小车，就像控制电脑上卡丁车一样来控制Rover小车。

​              <img src="/Users/changpeng/Documents/工作文档/公众号文章/joystick.png" alt="rvrstudioweb-0321" style="zoom:20%;" />           <img src="/Users/changpeng/Documents/工作文档/公众号文章/joystick_rover.png" alt="rvrstudioweb-0321" style="zoom:35%;" />

<video src="/Users/changpeng/Documents/工作文档/公众号文章/handler.mp4" style="zoom:60%" allowfullscreen></video>



### 05

### 拥有了隔空操作能力的小车

在西游记中每次看到孙悟空可以隔空操物，都会觉得好神奇。在我们的小小创造家的客户端里，我们会让你拥有与孙悟空一样的能力，隔空用手势来控制Rover小车。在编程空间中我们接入了手势传感器leapmotion可以非常精准的计算出你的手指的各个坐标，进而使用右手在水平方向移动的位移映射到小车旋转角度，这样我们就可以使用右手的左右移动来控制小车的左右转向了，神奇不？

​                <img src="/Users/changpeng/Documents/工作文档/公众号文章/leapmotion.png" alt="rvrstudioweb-0321" style="zoom:50%;" />          <img src="/Users/changpeng/Documents/工作文档/公众号文章/leapmotion_rover.png" alt="rvrstudioweb-0321" style="zoom:30%;" />

<video src="/Users/changpeng/Documents/工作文档/公众号文章/gesture.mp4" style="zoom:30%" allowfullscreen></video>



### 06

### 互联空间编程中的各个神经元，让孩子可以自由的组合出自己的机器人

在空间编程中，我们将小车、无人机、各种智能家居设备都积木化，同时我们接入了各种人工智能的能力（语音识别、图像分类以及OpenCV），在这个物理空间中各种硬件及软件都是我们空间中的一个个神经元，孩子们可以根据自己需要任意组合成各种实际用途的机器人，比如基于rover小车与百度大脑组合成一个救灾机器人，也可以组合成一个探月小车在月球表面进行探索，也可以是一个农业检测蝗虫的巡检小车等等。万物互联、万物积木化，将物理世界规律限制取消，让孩子们可以自由的发挥自己想象力，来快乐的创造世界是我们小小创造家的使命！
