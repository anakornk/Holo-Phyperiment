# Holo-Phyperiment

**项目介绍：**

基于HoloLens的特性，充分运用Unity的物理引擎，来模拟经常出现在中学课本中的物理实验，特别是一些理想实验模型，值得一提的是，在现实生活中几乎没有可能完成这种实验（如十大经典物理实验中伽利略的自由落体实验，和加速度验证实验），在我们的应用中都可以十分简便的再现。而且对于实验环境的搭建提供了丰富和简便的工具和方法，适合有基础的任意年龄段的人来操作。与大部分MR类应用局限于专注游戏或者娱乐方面不同的是，我们更加关注其教育方面的意义。通过我们开发的应用，可以在十分有趣的尝试过程中学习到更多的物理知识，并且通过实实在在的观察加深学习的印象而不只是局限与书本和视频。你还可以单纯的来搭建各种有趣的模型（类似于Minecraft），并且通过我们提供的有趣的操作来达到不可思议的效果。

**项目细节操作：**

关于应用中各种命令详情见帮助文档， 这里说一下大部分的功能，我们可以支持你用语音或者通过手势菜单来创建几乎达10种基础模型（如小球，方块，圆环，斜坡等等你能想到的大部分模型），对于模型的操作主要分五种（创建，移动，旋转，放大缩小，删除），同时为了更好的模拟物理环境，我们可以设置g(引力常量)的大小，甚至可以设置它的方向，来达到神奇的效果（如模拟失重环境，超重环境），同时为了方便观察，我们还可以让时间变慢，或者时间变快，或者时间停止来达到更好的观察效果。对于物体，我们可以设置它的质量，可以对其施加的力，以及对力的大小的控制。通过以上操作可以模拟大部分的经典基础物理实验了，你还可以自己搭建各种环境，通过对于g和力的控制，来展示出各种精彩的效果。

**项目技术原理：**

硬件： HoloLens

软件： Unity , HoloToolkit-Unity,  VS 2017, HoloLens Emulator， Windows 10 Pro

	  首先HoloLens是比较新的产品，相关的技术比较新颖，很少人有相关的开发经历，类似的资料比较少，而我们的时间又十分有限，所以相关的环境配置起来是很麻烦的，我们克服了很多的困难（陈同学电脑是MAC特地装了双系统， 王同学主要是用Ubuntu,Windows版本是8.1特地升级到10的家庭版又升级到专业版）
由于价格原因，像我们这种大学生很难会有一台这样的产品，所以在比赛之前几乎是很难做什么准备，而在比赛的过程中，曾经满怀憧憬地期待相关技术人员的现场支持，而微软的工作人员由于工作原因也没有到场，某种程度上也增加了我们开发难度，但是还是期待相关开发人员的指点。
技术上的实现，首先我们精心筛选收集各种基础模型，同时也自己组装搭建了一些由基础模型拼接的简易模型，然后对Unity 3D API整体进行了熟悉，主要用到了Unity 3D 物理引擎，HoloLens中主要用到的是Gaze, Gesture, Voice recognition等功能。由于HoloLens功能过于强大，用了很多复杂的Unity的功能，代码过于冗余而长，不能够在很短的时间内理解很长的代码，难以入手，所以我们用了HoloLens Academy官方网提供的HoloLens简化的Toolkit 

