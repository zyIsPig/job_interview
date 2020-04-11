# 面经
按照时间顺序，具体时间记不清。从面试新手到面试老鸟，手里有美团基础研发部，小米运维，腾讯pcg腾讯文档，字节飞书的offer
自我介绍和问答环节基本都有，略过，在项目介绍的时候最好做点ppt之类的方便展示，线上不容易讲明白，*讲的时候不要只顾着自己讲自己的要注重面试官的感受*。
面试遇到不会的，下来一定要搞明白。
## 美图基础研发部后端
美团的面试过程是真的舒服，面试官特别尊重你，很积极的再跟你互动。
### 一面
- 1.问了笔试的算法题，什么地方可以优化（时间，空间）
- 2.Q：操作系统学了么？A：学到进程   那好不问了。
- 3.tcp udp的区别
- 4.说下tcp的三次握手，为什么要三次
- 5.说下浏览器输入url按下回车后发生了什么
- 6.场景设计题，假如你开了一家餐厅，有自己的外卖配送系统，设计一个数据库（这种开放性题目一定要跟面试官多沟通，把需求搞清楚）。设计完之后面试官一直在问为什么这样设计，有没有别的设计。
- 7.项目
### 二面
- 1.直接讲项目，dns_tunnel，面试官比较感兴趣，一直在探讨，因为做的时候比较花心思又准备了ppt所以细节、优化都能展示出来。面试官印象不错。之后一直探讨网络的问题。
- 2.tcp time wait状态，为什么要有这个，没有会出现什么情况。
- 3.算法  一个排好序的连续的数组（都为正），扣掉一个元素，问你扣掉的是哪个（二面问这个有点侮辱我。。）  eg：0 1 2 3 4 5-> 0 2 3 4 5，返回 1
- 4.问了下面试地点时间
## 腾讯光子
### 一面
直接无，知识广度cover不住
- 1.java内存模型 （不会）
- 2.cpp多态,如何实现（不会）
- 3.数据库索引原理，b/b+树区别
- 4.tcp握手挥手，流量控制，拥塞控制
- 5.说下浏览器输入url按下回车后发生了什么
- 6.说下服务器集群的负载均衡（不会）
## 腾讯微信
### 一面
无
- 1.线程和进程的区别（这时候理解不够，没答好）
- 2.场景模拟：假如你电脑上不去网了，你会怎么排除问题
- 3.自己设计一个hashmap类，需要什么函数，什么属性（要求很高，rehash效率要高），说下扩容因子为什么0.75
- 4.海量数据：100亿个ip，怎么去重。（第一次遇到，凉）
## pcg腾讯文档
### 一面
面试官记错时间了晚来了40min
- 1. 算法:[爬楼梯](https://leetcode-cn.com/problems/climbing-stairs/)
- 2. 知道哪些排序算法，说下你最熟悉的一个。是不是稳定的。
- 3. tcp握手挥手
- 4. timewait
- 5. session/cookie 区别
- 6. https/http1.0/http1.1/http1.1
### 二面
- 1.算法：求一个排好序的数组的中位数（topk）
- 2.有多个排好序的数组，求全部的中位数
- 3.场景模拟：设计一下滴滴打车的算法，需要考虑些什么？dijstra为什么不合适，应该用什么。
- 4.数据库三大设计范式
- 5.项目哪个收获最大，讲下你能从项目中获得什么?遇到问题怎么解决。
### hr面
前两面很顺利，基本全部ac，hr面谈的不太好，勉强给过了。这次hr是最大阻碍，hr面千万别掉以轻心，还是得稍微准备准备,啥该说啥不该说要掂量掂量。
- 1.自我介绍，我自己金融转计算机。面试官可能觉得我转专业比较水，感觉一直在批评我（可能是压力测试）
- 2.gpa多少，专业排名。我说具体排名我不知道，然后被一顿怼，说我不关心自己的成绩，企业里面什么什么的。
- 3.我问问题，我问您觉得这个岗位需要什么特质。

我打了打电话催了催offer，效率很高，两天就有了

## 字节飞书 base深圳
飞书我早就投简历了，拿到腾讯offer的那天刚收到笔试邀请，然后我找了字节的hr说了说情况（tx需要三天内签完，笔试流程走不下来了），然后直接绿色通道笔试免了，当天晚上直接约了一面。
### 一面
不得不说字节面试确实硬核，比别的难度大不少
由于有了腾讯offer保底，心态比较好，不会很紧张了
字节缺失难度大，每一个话题基本都是问到你不会为止，面完感觉特别累
- 1.学了什么课程？
- 2.直接甩算法：一个无序数组，有正有负,找出第一个缺失的正数（时间复杂度O(n),空间复杂度O(1)） eg: [-1,-8,1,2,4,5,-3,-2]->ans:3
- 3.讲下项目（讲了dns_tunnel，面试官觉得我网络比较好就没问网络的问题）
- 4.写sql。。。（太久没写，写不出来，说了会查api）
- 5.给了两个sql语句，问哪个查询速度快（考察索引原理）
- 6.线程进程区别
一面面评很好，除了写sql其他都答得很满意
### 二面
面试官晚来了10min，上来我tm垃圾电脑摄像头不亮语音不通，重启的电脑
二面有点死亡，下午四点半直接面到晚上七点半（字节的人都不吃饭？）面试官水平确实高，所有问题都很有深度，需要有很高的理解，有些问题答案我现在还没搞明白，之后需要再去研究下
- 1.说下进程和线程的区别
- 2.fork做了什么事情
- 3.说下为什么要做同步？说下什么情况有mutex，什么时候用spin lock，spin lock会被抢占么？
- 4.假如你的内存只有3G，操作系统占了1G，剩下2G，有个进程内核占了100M，其他都在内核态，fork一下会发生什么？
- 5.假如你有一台电脑，你tcp能同时连接多少服务器？都是跟什么变量有关
- 6.假如你管理一台服务器，有多少台电脑能连接到你的服务器？跟什么有关
- 7.python是多线程的还是多进程的？假如现在有两个socket在监听，一个socket执行connect的时候是阻塞的，会很慢影响到另一个socket，请问有什么办法么？我说协程。那你讲下协程原理。
- 8.海量字符串统计有多少种
- 9.写道题吧，给你一串数字，用4个‘*’把他们分隔开5段，每段不能超过600，把所有情况打印出来。不能暴力。
eg: 123123123123123->123*123*123*123*123可以
eg: 1231231231231231->123*123*123*123*1231不可以

面完了感觉很凉，因为面试官每个问题都问的很深，把你的毕生所学和理解全扒出来，每个问题到最后要不然就不确定要不然就是不会。只能说面试官太猛。
没想到最后给过了，面平还不错？可能字节都这样子，一直问反正都撑不到最后？看能接几招？

### hr面
hr小姐姐特别好，聊了30多分钟，全程吹水，没压力。



