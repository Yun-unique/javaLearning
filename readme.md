@[TOC](这是菜鸟的java学习仓库，持续更新中)

# 一、学习路线：


## [java](https://github.com/Sommer1111/javaLearning/tree/master/Java)
### 视频资源
- **B站黑马视频**，一直看到换老师，这一段老师讲的很好。基本对Java的**框架**就出来了，以及一些基本的**规则**。
- 第二段基础的学习：选择B站**尚硅谷30天Java学习宋红康视频**，相对于黑马视频，内容更加细致、练习更多
- 此时基本了解：**反射、IO、注解、多线程、集合、枚举、常用API、泛型、新特性**

***
### 书籍资源
- **《Head First Java》**，趣味性，帮助理解
- **《Java核心技术卷I》**，知识详细，当查阅资料

### 总结
- 缺少自己相关的延伸和疑问思考，一定要考虑为什么这样写，以及老师写出来的代码、功能是否能优化
- 缺少练习，视频就看敲一遍就觉得学完了。多敲
- 复习。忘记的快，只能通过常用多练实践出真知。
## 2.实用工具一：
***
###  [Git](https://github.com/Sommer1111/javaLearning/tree/master/Git%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86)
***
#### 第一步：了解Github
- 首先你需要了解Github————>移步**b站搜相关视频**
- 进入**github官网**创建你的`github`账号以及初次使用
&nbsp;
#### 第二步：了解git
你会遇到以下问题：
- b站的视频很多很乱很杂，学起来完全没有头绪。不知道怎么筛选
- `git`开始只需要**了解一些基本的操作、指令**，并不需要非常深入。所以先不要看书  
&nbsp;
#### 第三步：了解使用IDEA里面内置的Git
你会遇到以下问题：
- b站里面没有视频
- `IDEA`里面是**英文**的，大部分时候有些丈二的和尚摸不着头脑。
- 一搜文章一大堆，**越看越懵**，你需要一个简单明了的教程
&nbsp;
#### 四、资源推荐
1、**git教程，不看视频**，直接：[廖雪峰的Git教程](https://www.liaoxuefeng.com/wiki/896043488029600)
  - 此教程体系清晰、简单易懂
  - 每一篇下面有遇到问题、思考的问题讨论。
  - 照猫画老虎学习此时会遇到一些问题，各种百度谷歌。你就会慢慢熟悉使用。
  
2、**IDEA内置Git了解**，推荐这篇文章：
  -  [IDEA内置git功能的使用教程 ](https://my.oschina.net/u/4288213/blog/3603611)
&nbsp;
&nbsp;
###  [Linux](https://github.com/Sommer1111/javaLearning/tree/master/Linux%E5%AD%A6%E4%B9%A0)


***
#### 第一步：对比视频，学习“尚硅谷的Linux教程”。
- 首先搭建环境：**VM12 + centOS7** 创建第一个Linux环境。

- 学习 尚硅谷的linux教程，相关笔记。
- 此时linux用的比较少。只需要对**基本的使用了解**，对大体的知识**粗略了解**就可，**不应深究细节**。
&nbsp;


#### 第二步：理解`【linux的架构】`
```java

①底层通过内核与硬件交互，来控制硬件

②内核对硬件的交互太细节化，将细节整合成功能接口库产生了系统调用（在汉字中相当于笔画）

③系统调用依旧不够便利，于是再进一步集成库函数 （相当于汉字中的偏旁），更加人性化

④库函数：可以对应于编程语言的API。

⑤shell命令解释器：下通系统调用，上通各种应用。也就是你与硬交互的中间人。
 你输入命令——>shell1获取这个输入（程序）——>操作要求传到内核——>内核控制硬件——>硬件运行
      
⑥应用软件：通过编程调用一系列的函数控制底层硬件的运行，最终实现某些功能。
```
&nbsp;




## [数据结构与算法](https://github.com/Sommer1111/javaLearning/tree/master/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%8E%E7%AE%97%E6%B3%95%E5%AD%A6%E4%B9%A0)
### 资源
- 视频：B站**尚硅谷 数据结构与算法**是争对Java的讲解
- 练习：`Leetcode网站`天天刷题


### 书籍
- **《大话数据结构》**，趣味性，帮助理解
- **《算法图解》**，趣味性，帮助理解
- **《算法（第4版）》**，知识齐全

### 总结
- 算法的**关键节点，没有那么容易理解**
   - 自己推算一下。就清晰了 
  * 用 `Debug`调试 
  &nbsp;
- 很多思路没有不是自己笨，这些思维是可以学会的。需要一个**积累的过程**
&nbsp;
- **递归**为什么是这个步骤有时有点**难理解**。 这个时候可以直接看拆分到最小的情况，它的步骤要怎样。
&nbsp;
- **太拘泥于参考代码**
有时不理解，一直纠结它为什么要这样写。其实写法又很多，人家只是碰巧这样写了，并没有必要一定跟他一样，只要最终都可实现，殊途同归。 往往一定要跟他写的一模一样，毕竟不是我的思维，有时就是理解不了他为什么要这样写。 
&nbsp;
- **编程抽象从易到难**：
- 先分析**最基本的情况**
- 再写**其它情况**
- 找出**共性**
- 最后**抽象**写出最终代码，推及到所有情况。
&nbsp;
&nbsp;
## [操作系统与计算机网络](https://github.com/Sommer1111/javaLearning/tree/master/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C)
&nbsp;
## 【操作系统】篇
***
####  第一步：理解操作系统
- **定义**：一组控制硬件的软件集合。（所以称作操作+系统）
   -  涉及到内核底层的东西，就有很重要的一部分内容：**用户管理**，有些地方不能随便让所有人都可以访问
    &nbsp;
 - 与java无处不对象的理念相似，在linux中**无处不文件**。
 &nbsp;
####  第二步：资源推荐
- 视频选择：`B站 《王道考研操作系统》`
- 参考文章：[Linux架构](https://www.cnblogs.com/vamei/archive/2012/09/19/2692452.html)

 &nbsp;
## 【计算机网络】篇
***
####  第一步：理解计算机网络
- daibuc
 &nbsp;
####  第二步：资源推荐
- 视频选择：B站 [韩立刚老师《计算机网络》](https://www.bilibili.com/video/BV1Hx411D7rn?from=search&seid=9782034372486691962)


 &nbsp;
## 数据库MySQL
## Web前端
## 实用工具二：
### Maven
### Docker
## JavaWeb

