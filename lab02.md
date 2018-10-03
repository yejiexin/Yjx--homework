#制作HTML5游戏1（入门篇）

嗯...要我怎么说呢？这个作业还真不容易，明明是一个爱国说国语的计算机小白，却非要我看着英文搞游戏制作，表示教授您真的下手好重。嗐！没办法，谁叫我是中大的有志青年，这点小困难还是可以克服滴。诶，我都说了什么？以上不算，这是一篇严肃的技术博客，对，严肃！

  那么，我们要怎样制作一个简易有趣的2D小游戏呢？按照教授大人的指示，首先，你要准备好自己的实验/学习工具：Construct2（https://www.scirra.com/construct2 ）。
  差不多长这个样：
  ![](31.png)
然后，就请在座的你跟随我的步伐，来制作一个有趣的小游戏吧！

1.双击此图标（这不废话吗）

2.这时你会看到这个白白的界面（也可能不是？这不是重点！）请注意，点击左上角的文件。如图红圈圈：

![](32.png)  

点击新建New，谢谢

![](33.png)  

然后什么也不要点哦，如下图的蓝色框，接着笑笑地点击Open。此时它不再那么单调（至少多了好多你喜欢的英文单词哦!）

![](35.png)  

3.接着双击中间的白色界面，会出来下面这个图图：

![](36.png)  


请跟随红色框框，双击或单击该图标后点击Insert。这时它会出现一个十字标，以此单击中间界面，出现了下图，请一定要点击红色圈圈所圈图标：  

![](37.png)  

在里面会有你之前所储存的所需图片，（什么，我没提过吗？来来，告诉你我的操作：为图方便，请在桌面新建一个文件夹，然后请勤快的上网查询你喜欢的游戏界面与人物，自己抠图哦！最后把它们放进该文件夹即可）首先请先选择你要的游戏背景（双击即可）。然后会出现这么个东西：  

![](38.png)  

(嘿嘿，酷吧！)
接下来，请不要怀疑，直接将这玩意关闭（点击 X ）。然后？你又得重来了（哈哈）。开玩笑的，接着你就会发现它奇迹般地出现在中间的界面上了。然后请将注意力放到左边的好多英文的界面（请不要慌）,看到下图的红框框没，请看好数字。  

![](39.png)  

然后点击空白区域，再回到左栏，将Layer Size调整到同样大小。（这里看你个人意愿，直接拉动中间界面的小白点也是可以的）  

![](40.png)  

然后，点击右边界面的Layers,如图操作：  

![](41.png)  

然后改一下Layer_0的名字，以防后面分不清谁是谁（后面你会知道为啥），接着点击上图左上角的加号，是不是出现了Layer_1呀，再来一次操作2，改改名啊。这样是不是清晰多了啊。
现在让我们把注意力转到中间界面上方的Layout 1(点击),再双击中间界面的空白区，再次出现上次双击出现的版面，这次 *注意了注意了：*   

![](43.png)  

==这两个玩意一定要像上次操作一样Insert哈！==曾今我就栽在这个问题上！  

4.现在，是时候把我们的游戏人物与物体添加进去了。想知道怎么搞吗？就不告诉你！  

好的，结束！  



开玩笑的！
请再次双击...你懂的。  

![](44.png)  

看到蓝色圈圈了吗？双击！
又出现了十字标，请单击，按步骤3点击左上角的文件夹图，
然后选择你所需要的精灵（就是你要的人物或物体），重复操作多次直到你不要更多了。
效果如下：  

![](45.png)  

哦，对了，这次也要给自己的精灵们改名字哟！  

![](46.png)  

5.现在我们要来添加动作了。
首先让我们来为player添加动作:  

![](47.png)  

如图点击操作，出现了  

![](48.png)  

这么个玩意。
点击左上角 + ，出现  

![](49.png)  

点击黄圈圈然后点击Add.同样的操作，直到如下：  

![](99.png)  

请别问我这都是啥，请自行百度。
现在关掉它，咱来实验一下  

![](51.png)  

点击左上角的那啥，来，动动你的上下左右键盘，是不是很神奇！
j接下来同样点击bullet和slash(在这里我要提醒一句，每一个精灵的Layer都必须是Main即layer_1>)，然后同样操作，这次点这两个：  

![](56.png)  

然后操作大概同上：（来来来，秀一段英文）
- Add the Bullet movement and Destroy outside layout to the Bullet（or slash） object (no surprises there)
- Add the Bullet movement to the monster object,archer1 and archer2 (because they just moves forwards as well).
- Add the Fade behavior to the Explosion object.
自行百度哦！
再次点击 monster object,archer1 和 archer2，  

![](57.png)  

请把Speed从400改为80.
同样，把bullet和slash改为600，explotion的Fade in time改为0.5。  

6.现在我们来创造更多的敌人：点击monster或者其他敌人，不要松手，将其拖入中间界面，多次操作即可。  

7.好了，现在请点击：  

![](58.png)  

别让我解释这是啥，现阶段我们只要知道接下来如何操作即可（好吧，我也不懂）。
双击中间界面，出现：  

![](59.png)  

戳它！  

![](60.png)  

再戳它！
然后出现个不可描述的东西，在它尾巴点击Add action，  

![](61.png)  

点击Player,再点它：  

![](62.png)  

要这样填哦：  

![](63.png)  

8.好了，咱再来一波英语操作：  

![](88.jpg)  

1. Double-click to insert a new event, or click an Add action link to add an action.
2. Double-click the object the condition/action is in.
3. Double-click the condition/action you want.
4. Enter parameters, if any are needed.

Condition: Mouse -> On click -> Left clicked (the default)
Action: Player -> Spawn another object -> For Object, choose the slash object. For Layer, put 1 (the "Main" layer is layer 1 - remember Construct 2 counts from zero). Leave Image point as 0.
没错，自行翻译！最后给你们看看完成后的样子：  

![](69.png) 

这时你会发现运行时slash不是从剑端发出，这怎么行，所以：  

![](70.png)  

鼠标右击Player,如图点击颜色不同处。然后： 

![](71.png)
![](72.png)
![](73.png)  

嗯，只可意会，不可言传。
然后关掉它。重新运行....好吧没什么太大效果。但这么操作是没毛病滴！ 

9.现在我们要如何消灭敌人呢？
我打累了，来，再来一次英文：
不玩了，其实操作基本和上同：
Condition:slash->On collision with another object -> pick monster.
Action: monster -> Destroy
Action: slash->Spawn another object -> Explosion, layer 1
Action: slash -> Destroy
这是一个重复的过程。总之，在一波艰苦操作后，结果如下： 

![](75.png) 

10.但细心的你会发现，当程序运行时，会有如图情况： 

![](99.jpg) 

这并不是我们想要的效果，所以，请左击右栏Object或Project里的 explosion，将目光投放到左栏，找到Blend mode,将其中的Normal改为Additive,再运行一次，嗯，感觉舒服多了。 

11.现在，我们要让敌人变得更聪明点（让它们不是直线行走而是到处乱走）。怎么做呢？
Condition: System -> On start of Layout
Action: Monster -> Set angle -> random(360)
大概如此： 

![](80.png) 

还有，我们不能让敌人走出边界时继续在外游荡，所以我们要让他们回来：
Condition: monster（archer） -> Is outside layout
Action: Monster -> Set angle toward position -> For X, Player.X - for Y, Player.Y.
这样： 

![](81.png) 

12.现在，我们必须考虑要砍几刀才让敌人destory呢？一刀就完是很无聊的，这里我们让他砍三刀：
Instance variables保证了每个敌人能够储存自己的健康值。唉，我为啥要解释这个？总之，首先你要点击monster和其他敌人，然后左栏走起： 

![](54.png) 

点他！ 

![](82.png) 

点他！ 

![](83.png) 

输入！
完美！！！ 

13.现在我们回到event sheet1，当slash攻击到敌人时我们要把敌人销毁，所以再： 

![](84.png)  

![](85.png)   

接着：

![](86.png)   

然后：
Choose Monster -> Subtract from (in the Instance variables category) -> Instance variable "health"，在Value处输入1，结束。
大概如此： 

![](87.png) 

14.现在我们每攻击敌人一次，他们就掉一个health，但我们还没做一个事件去杀死敌人（当他们的health为0时），所以：
Condition: Monster -> Compare instance variable -> Health, Less or equal, 0
Action: Monster -> Spawn another object -> Explosion, layer 1
Action: Monster -> Destroy 

![](88.png) 

15.玩游戏怎么能不计分呢？所以，请右击中间界面event sheef空白处，然后点击Add global variable。接着： 

![](89.png) 

然后最上方就有了这个 

![](90.png) 

现在。。。额，你们还是看图吧！ 

![](91.png) 

丢给你操作方法：click Add action, and select System -> Add to (under Global & local variables) -> Score, value 
不客气哦！
接着我们要让这个分数显示出来。
先来段英文：Go back to the layers bar we used earlier. Add a new layer called HUD. Make sure it's at the top, and selected (remember this makes it the active layer). The Properties bar should now be displaying its properties. Set the Parallax property to 0, 0 (that's zero on both the X and Y axes).
双击中间空白界面（Layout 1） 

![](92.png) 

单击界面，然后看向左栏 

![](94.png) 

修改标注处！尽量使颜色鲜明，字体清晰。
再回到event sheet,在我们早先添加的Every tick中，我们再添加action Text -> Set text.然后 

![](96.png) 

现在我们就能计分了！（但好像没显示出来呢，自己看看出了什么问题吧） 

16.最后，我们来让敌人有规律地复活。
Condition: System -> Every X seconds -> 3
Action: System -> Create object -> Monster, layer 1, 1400 (for X), random(1024) (for Y) 

![](97.png) 

然后，我们还要让敌人也能消灭玩家。
Condition: Monster -> On collision with another object -> Player
Action: Player -> Destroy 

![](98.png) 

**这样，我们终于完成了属于自己的游戏！！！**
接下来是小小的gif动图哦！（该图会和上面的操作有些不同，但这不影响教学效果,为了让自己加深印象，请自己找出不同之处哟！） 

![](GIF.gif) 

哎呀呀，终于搞定！！！开始你的游戏之旅吧！







#微信小游戏开发技术与应用

说实话，作为一个连游戏都不怎么玩的小白，竟然敢上来就写一篇游戏开发的技术博客，我这是作死呢？还是作死呢？但是，一个人只有勇于尝试，勇于锻炼，才能有所成长，所以，今天的我“大言不惭”，来说说微信小游戏开发的一二事。  

而在这之前，我们首先要了解，游戏开发，究竟是一个怎样的概念？上百度一搜，你会看到这样的一段话：  

![](q.png)  

这样，我们就对游戏开发有了一个大概的了解，但更深入的理解，还需我们不断地去接触与学习，相信在你我的努力下，我们会对它产生不一样的感觉。  

现在，我们要来了解一下，什么是微信小游戏呢？ 我们来看看官方的表示： 

![](e.png) 

下面是其中一个游戏的一个gif动图：

![](w.jpg)

是不是很熟悉？这就是在大人界也十分受欢迎的==跳一跳==。

好了，热身结束，让咱们进入正题（可能看着有点晕哟）：

#微信小游戏的小特别
微信小游戏是在H5游戏的基础上增加微信社交能力、文件系统、工具链，去掉一些对游戏开发不是那么重要的，像Dom、Bom等，这里就不对H5游戏做详细的介绍，有兴趣的可以上网查询，下面只给出这这二者的一些对比：

 ![](r.jpg)

从这张图可以看出来，微信小游戏没有webview了，H5规范API这里是微信小游戏sdk自己实现的，比如canvas webgl。然后还有就是 游戏引擎这一层，是做了一个适配.

![](t.jpg) 

#小游戏资源加载

目前微信的核心游戏包4M（用于首次加载），可以实现即下即玩，大概需3~5秒的下载时间.

![](y.jpg)

理论上，用户若不主动删除，微信客户端只会更新不会删除；容量没有固定值，只有不够用的情况下根据LRU(Least recently used)规则进行删除。 

#小游戏的（Adapte）适配器

微信小游戏运行在iOS 上是 JavaScriptCore，在 Android 上是 V8，，没有提供 DOM、BOM 接口。为了让基于 Web 环境开发的游戏引擎能够快速适配，而提供了一个 Adapter （注意adapter是为了基于web环境开发的游戏引擎而提供的，不是为了让现有的H5小游戏源码直接可以转换为微信小游戏而提供的），它的作用是基于小游戏接口做一层封装，在全局暴露一些 DOM、BOM 接口。
当前提供的 Adapter 会内置于小程序内，开发者无需自行引入。后续 Adapter 项目将不再内置于小程序内，开发者可以选择自行引入 Adapter 来适配，也可以完全基于小游戏平台重新开发。
引入 Adapter 之后，会在全局暴露一个 canvas 对象，所有的绘图命令必须通过这个全局的 canvas 来发出。此外还会暴露 window、document 等 DOM API，开发者可将其当作跟浏览器一样的环境来开发。
详情请查看微信小游戏开发文档，或者请提供adapter官方给予解答。下面是大概的描述图：

![](u.jpg)

当然，游戏引擎也自己做了适配，例如coso.

![](i.jpg) 

#小游戏开发技术品类 

下面会给你们发一张配图，嘛，作为小白大概是不知道这都是啥的，你我只要大概知道这些东西的存在即可:

![](o.jpg)

==目前是6大类 24个子类== 

#小游戏开放能力及API 
 
![](p.jpg) 

在这里我顺便查了一下何为API： 

API主要分为两大类：Windows API和linux API,鉴于我的语言表达能力有限，咱们就直接引用百度词条上的解释: 

![](s.png)
![](d.png)
![](a.jpg)

觉得了解不够？丢你链接：
<https://baike.baidu.com/item/api/10154>
不用谢的！

#小游戏开放工具

![](f.jpg) 

看不懂？没关系，以后你会懂的（只要你想学）。

![](g.jpg) 

#小游戏开发工具

![](h.jpg)

为了帮助开发者简单和高效地开发和调试微信小程序、微信小游戏，微信在原有的公众号网页调试工具的基础上，推出了全新的 微信开发者工具，集成了公众号网页调试和小程序、小游戏开发两种开发模式，而且自带小游戏demo。详情可参考<https://mp.weixin.qq.com>

你也可以s上网定制你的小游戏,开启你的盈利模式（如果你有兴趣的话）。事先说明，我没有试过，所以下面的网站请谨慎对待
<http://xcx.jjsjqp.com/> 

#小游戏营销体系的建设

对于大部人来说，制作游戏除了对于游戏的喜欢与热爱，营销也是很重要的目的，所以如果真要做好游戏，建设好自己游戏的营销体系是十分重要的。但我们这篇博客以技术开发为主，所以只简单讲一下，剩下的就靠你百度咯。  

首先你要考虑游戏的面向对象，这决定了你游戏的推广面的大小。
小游戏的宣传可以说是挺重要的一项，就微信来说，你是需要与官方达成一定的协议，以期其在微信上有所体现，在这之后还有游戏的推进与更新。在这之中可以添加一些营销手段，比如现在还一直盛行的充值体验，不过需注意的是，在微信上的这些小游戏的竞争上，我觉得这或许不是什么明智之举。总之这要靠你开动脑洞。最后给个建议：阿里双十一、天猫狂欢城......你懂的。

# 游戏预热及用户沉淀

这个比较简单，一句话概括就是来个简单试玩版，提升玩家对游戏的期待，以此达到沉淀用户的目的。不过如果真的只是个小游戏，弄个试玩版其实也没什么太大作用，重要的是能让用户真正的喜欢，因此我比较提议从用户体验方面下手，想想如果自己是用户，对自己设计的这款游戏的期待到底是什么，或许你就能从中得到有用的信息，以此修补不足。 

#APP导流

这里不说废话，直接百度：

![](l.png)

#品牌传播

如果你的目标不是仅仅停留在小游戏，这个还真挺重要，It is known for all,中国现阶段无论是企业还是个人的品牌；意识还不够强烈，但许多人乃至国家都认识到了这一点，所以你、我也必须有所了解。

百度百科有云：*品牌传播是企业的核心战略也是超越营销的不二法则。品牌传播的最终目的就是要发挥创意的力量利用各种有效发声点在市场上形成品牌声浪，有声浪就有话语权。传播是品牌力塑造的主要途径。对于“品牌”，美国营销协会曾做出这样的定义：品牌是一种名称、术语、标记、符号或设计，或是它们的组合运用，其目的是借以辨认某个生产者或某个生产者的产品或服务，并使之与竞争对手的产品和服务区别开来。品牌对于一个企业来说是至关重要的一场竞争、建立品牌忠诚度、树象的重要保证。*

就传播方式而言，可以分为==人际传播、促销传播、公关传播、广告传播==等等，这里不加赘述。

好了，这次的介绍到这里就结束了。感谢您的观看！
---
本文内容基本来自网上一篇博客<https://blog.csdn.net/rolan1993/article/details/79625587>,在此基础上本人做了一些改进，我也不知这算不算抄袭，总之我已尽自己最大的努力写了这篇博客，其中有何不足请望海涵！























  