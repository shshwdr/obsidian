套娃装盒[[仓库番Sokoban]], 可以用集合论set theory知识理解，递归
能在箱子里推箱子，并把箱子推出箱子的神奇游戏，里面的箱子可能是有障碍的，也可能是空箱子，需要把其他箱子推进去，然后在外面把整个大箱子作为载具推走，有的需要多层嵌套，有的需要利用载具的不同开口来过弯
可以把外箱子推向内箱子，把内箱子吞噬
箱子里面可能有需要推过去的需求或者终点
地图也做成了推箱子的样子
可以嵌套，推的箱子显示的是地图，如果从外层的出口出去，则会从内层的出口出来，来到外层。多层嵌套用不同颜色表示
有时候会触发无限效果。。我还没想通，头好痛。
有一关展示了把箱子全部平铺开，用ascii码表示的效果
克隆关推进去以后在另一个里面会克隆一个，有点类似[[a game inside a game]]
玩家关卡，玩家可以作为载具大箱子吃别的箱子，或者有多个玩家箱子一起动

之后还有改优先级的关卡。正常优先级是推＞吃和进入离开（远端优先）＞换魂，那个关卡把推的优先级降到吃和进入离开下面
还有向墙的一边离开的话可以把原箱子挤开
可以在大箱子里推箱子

用程序语言中指针的概念会更好理解，递归就是一个对象（箱子）里有一个指向自己的指针。我一边玩一边在想如何用程序实现这样的机制，结果发现并不难实现，也不需要任何抽象的结构

罗素悖论：
**对于任意一个集合A，A要么是自身的元素，即A∈A；A要么不是自身的元素，即A∉A**
无限进入会得到无穷小，无限退出会获得无穷大
无穷还可以有层数，一层无穷二层无穷。。https://www.bilibili.com/video/av467992770/?vd_source=02f370fa612da38b6e4caa46c7e01b69


有多位观众指出3:20 附近讲得不严谨，确实，这就是为什么集合论不能完美地解释这个游戏——因为会出现罗素悖论。而如果把罗素悖论看成是一个"合理"的东西，也会出现更多千奇百怪的悖论。  
为了解决集合论带来的漏洞与不严谨，一个较好的解决方法就是引入"范畴"(category)的概念，感兴趣的同学可以想想怎么把这个视频中的例子改写成范畴的形式。

让我想到一个形式化分析工具叫Alloy
![[Pasted image 20230129162504.png]]
![[Pasted image 20230129162425.png]]
![[Pasted image 20230129151703.png]]
![[Pasted image 20230129011440.png]]
![[Pasted image 20230129011255.png]]
![[Pasted image 20230129010859.png]]
![[Pasted image 20230129010636.png]]
![[Pasted image 20230129010539.png]]
![[Pasted image 20230129010356.png]]
![[Pasted image 20230129010146.png]]
![[Pasted image 20230129005747.png]]
![[Pasted image 20230129005444.png]]
![[Pasted image 20230125030009.png]]
![[Pasted image 20230125025924.png]]
![[Pasted image 20230125025704.png]]
![[Pasted image 20230125025655.png]]