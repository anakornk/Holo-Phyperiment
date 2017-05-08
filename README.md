[![DEMO VIDEO](http://www.anakornk.com/wp-content/uploads/2017/05/20170506_220435_HoloLens-300x169.jpg)](https://www.youtube.com/playlist?list=PL88LTPWeq-Yb7Tv-adJTSefEAbGpzaLAF)


### ENGLISH VERSION

## Inspiration

Helping kids learn the laws of physics while having fun playing with our mixed reality HoloLens application.

## What it does

Users can construct their own world by using our built-in models, add cool physics features and see how objects react.

## How we built it

Holo-Phyperiment was developed in C# using Unity3D during HACKPKU 2017. We use the "HoloToolKit for Unity" Package to ease the development. We first started off by brainstorming the key features of what a physics experiment application should have. After having a clear idea of what we will be building, we watched tutorials on Unity3d development for the HoloLens on Microsoft's HoloLens Academy website, seeking for features given by HoloLens that could be use in our application to enhance a rich mixed reality experience.
Three main features we used were Gaze, Gesture and Voice Recognition. 

## Challenges we ran into
HoloLens/AR is considered as a new emerging technology.Although Microsoft did provide us with a great documentation,
due to our lack of experience with the product itself, we ran into different kinds of problems. 
1) The HoloToolKit for Unity contains tons of code, it would be impossible to digest it in a couple of days.
2) The product is still in development stage, this means that there isn't much help you can get when encounter find bugs.
3) Most of us are Unity3D beginners.
4) Adapting our design for Augmented Reality.
5) There is no good way to let user input a precise number. (for e.g. 123.4456) 

## Accomplishments that we're proud of
We managed to create key features of what a physics experiment application should have.
1) Users can create and destroy models.
2) Users can control and manipulate our 3D built-in models by using voice and gesture commands. 
3) Users can view the state of an object (for e.g. it's speed and the force given to it.)
4) Users can change the mass and apply force to the object.
5) Users can speed up or slow down the physics engine, this allows you to see the action in slow motion.
6) Users can manipulate gravity. (Ever wonder what it's like when you reverse gravity?)

## What we learned
We learned how to use Unity3D to create a mixed reality application and deploy it to a HoloLens device. 
During the process, we also learned how to work efficiently in a team environment and how to stay alive while sleeping only 5-6 hours in a 40 hours coding period.

## What's next for Holo Phyperiment
We are planning to do some adjustments to smooth the user experience and add new models and features to the application. We even thought of submitting it to the app store.

-------------------
### CHINESE VERSION

## Inspiration

Holo Phyperiment 是一款应用MR技术来模拟基础物理实验的应用，通过它，你可以方便快捷地搭建自己想要的实验环境，并且通过各种方法使得你的观察更加细致与相近，此外你还可以舍去物理实验的因素，单纯地构造自己喜欢的模型，（类似于Minecraft），并且通过我们提供的有趣的操作来达到不可思议的效果。


## What it does
基于HoloLens的特性，充分运用Unity的物理引擎，来模拟经常出现在中学课本中的物理实验，特别是一些理想实验模型，值得一提的是，在现实生活中几乎没有可能完成这种实验（如十大经典物理实验中伽利略的自由落体实验，和加速度验证实验），在我们的应用中都可以十分简便的再现。而且对于实验环境的搭建提供了丰富和简便的工具和方法，适合有基础的任意年龄段的人来操作。


## How we built it
Holo-Phyperiment 是在 HackPKU期间 在Unity3D上用C#开发的一款Hololens相关的产品
我们用"HoloToolKit for Unity"来方便开发
首先我们精心筛选收集各种基础模型，同时也自己组装搭建了一些由基础模型拼接的简易模型.
接下来对Unity3D API整体进行了熟悉，主要用到了Unity 3D 物理引擎
HoloLens中主要用到的是Gaze, Gesture, Voice recognition等功能。
由于HoloLens功能过于强大，用了很多复杂的Unity的功能，代码过于冗余而长，不能够在很短的时间内理解很长的代码，难以入手，所以我们最终使用了HoloLens Academy官方网提供的HoloLens简化的Toolkit  
 
## Challenges we ran into
首先HoloLens作为一款比较新的产品，相关的技术比较新颖，很少人有相关的开发经历，相应地，网上类似的资料比较少，而我们的时间又十分有限，从配置环境到熟悉工具的过程所经历过的困难是比想象中要大的多的，此外，由于价格原因，像我们这种大学生很难会有或者可以接触到一台这样的产品，而很多实验效果在模拟器上是看不出来的，所以在比赛之前即使是想做相关方面的准备也是十分困难，而在比赛的过程中，虽然微软提供了足够数量的设备供我们使用，但是与选用其它技术的组相比，我们还缺乏相关技术人员的现场支持，某种程度上也增加了我们开发难度，可以说在短短的两天时间内，经历了从入门到放弃再到入门的过程。

## Accomplishments that we're proud of
我们可以支持使用者通过语音或者手势控制菜单来创建10余种基础模型（如小球，方块，圆环，斜坡等等你能想到的大部分模型），并且对模型和环境进行相应的操作。
对于模型的操作主要分五种（创建，移动，旋转，放大缩小，删除），
为了更好的模拟物理环境，使用者可以设置g(引力常量)的大小，甚至可以设置它的方向，来达到神奇的效果（如模拟失重环境，超重环境）
为了方便观察（有的实验发生的过快来不及观察，或者有的实验持续时间较长比较无聊），使用者可以通过语音调整对时间的控制，目前支持让时间变慢，变快，停止，继续的操作。
对于物体，使用者可以通过语音来设置它的质量，可以对其施加合适方向合适大小的力，以及可以在设置后对力的大小进行再控制。
我们设计的模式是，创建好各种模型，并且对于不同模型添加不同的力，设置好环境后，可以通过一条指令让物理事件发生，你不必担心对于多个物体存在的实验中如何进行方便的操作。通过以上操作可以模拟大部分的经典基础物理实验了，你还可以通过自己搭建各种环境，通过对于g和力的控制，来展示出各种精彩的效果。

## What we learned
通过开发该项目，我们学习了如何通过Unity3D来创建一个Mixed Reality Application并且把它应用到HoloLens硬件上
在比赛过程中，我们学习到了如何在一个小团队中有效的沟通并且提高效率，如何在接近40个小时的过程中只睡5-6个小时并且还不会轻易的Go Die, （PS昨天晚上仅有的4个小时睡眠中边睡觉边流鼻血，自己意识到了都懒得理自己）
## What's next for Holo Phyperiment
在可预见的未来中，我们希望让该应用的用户体验更加的流畅和友好，并且添加一些新的特性和模型在上面，我们准备把它添加到app store上。
