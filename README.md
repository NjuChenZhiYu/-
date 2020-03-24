面经整理 持续更新中

#付顺面经汇总 

腾讯CDG事业群（二面凉）
3.9 电话沟通
3.12 19:00-20:10 一面
自我介绍？
jdk了解么？
hashmap底层？扩容实现？多线程问题？
concurrentHashMap？读写操作实现？锁机制？实现维持map大小的LRU算法？

volatile关键字？volatile修饰数组？修饰对象？

找两条链表公共节点？
如何判断循环链表？

mysql索引？B+数搜索复杂度？
mysql事务？

进程线程区别？
进程池？
进程几种状态？调用sleep方法进程是什么状态？
单线程，4核cpu，如何让cpu维持50%使用率？

http了解么？包含什么？
输入url之后过程？
tcp如何保证稳定性准确性？

controller如何知道信息？
信息如何从网卡到controller？
一个请求如何被服务器得知？Tomcat如何知道有请求？
NIO？
如何实现一个服务器端？

你有什么问题问我？



3.15 9:00-9:30 腾讯二面

自我介绍
详细说说自己的经历
详细说说做的项目
你认为后端开发主要做些什么？
你认为做开发你的优势是什么？

前后端交互协议？
http（结构？第一行是什么？）
http1.0/1.1/2.0区别？
ref？（查了下是Dubbo里的，之前完全没接触过。。。）
操作系统原理？应用场景？（听不懂问题。。。）
缓存作用，应用场景？
自己实现一个缓存（用什么数据结构？需要快速查询和实现LRU）
学习能力如何？具体例子？



3.20 阿里巴巴笔试（2道，一道都没做出来QAQ）
3.22 21:30--23:20一面
自我介绍
个人经历
为何转行
项目详情
mysql索引？
知道组合索引么？
知道mysql执行计划么？
事务隔离级别？
秒杀场景，库存超卖如何解决？
乐观锁和悲观锁？sql怎么写？
mysql优化策略？用户订单表如何分表？
分布式事务？
exception，throwable，error？
runtime能catch么
throwable能catch么？
说说快排和堆排序一般的应用场景，时间复杂度
4个足球队，两两比赛，赢得3分，平手1分，输0分，4个足球队加起来总分有几种情况？取值范围？
笔试两道题有下去查过么？怎么解决？
hashmap，hashtable区别
hashmap底层构造，常用方法实现
设计模式了解哪些？认为哪个好
volatile实现
threadLocal
redis
一致性哈希







3.19 美团笔试 （5道做出来1.5道QAQ）
3.23 14:30--15:40 美团一面
自我介绍
StringBuilder，StringBuffer区别
List，Set区别，使用场景，可以有null值么，有多个可以么
深拷贝，浅拷贝，如何实现
hashmap底层，扩容机制，扩容有什么问题？多线程应用有什么问题？
jvm内存分区s0，s1
创建对象在jvm内存中的具体流程
gc算法
线程池常用参数？CorePoolSize一般设多大？
提交任务流程，缓存队列设计为无界队列可以么？
有界队列和无界队列？
线程状态
进程间通信机制
mysql索引
索引中，用where（给出了各种实例）索引怎么用的
事务隔离级别
mvcc
cas aba问题，如何解决？
volatile关键字，synchronized关键字
tcp、udp区别，在4层结构哪一层
tcp流量控制实现
tcp三次握手，四次挥手（答到一半被打断了，嫌我说太多。。。）
linux查找文件中的字段并高亮显示
手撕代码：快排实现
平时如何学习？
你有什么问题问？

3.24 二面 11:30--12:35
自我介绍
项目详细介绍，为什么重构它，有什么问题？
spring核心原理ioc，aop，SpringBean生命周期过程
MyBatis映射文件
手撕算法：
2N个数，N+1个不同，N个相同，找出相同的那个数
给他说了暴力1/2算法，排序算法，计数法，滑动窗口，最后写了滑动窗口，最后改良为直接比较

二叉树前序遍历非递归写法
你有什么想问？




3.24 腾讯一面 20:20-21:50
手撕算法并改进
1、两个有序（从小到大）单链表，构造一条新链表，包含出现在两个链表的等值节点
struct LinkNode {
  int value;
  struct LinkNode * next;
};
struct LinkNode * intersect( struct LinkNode * firstLink, struct LinkNode * secondLink );

2、设定如下的对应关系( A=1,B=2,C=3,...,Z=26,AA=27,AB=28,...,AAA=xxx,... )，编写一个转换函数，根据上面的规则把一个字符串转换为数字
int StrToInt( const char * str );


3、在二叉排序树上面找出第3大的节点。注意：不能把二叉树全量存储到另外的存储空间，比如存储到数组中，然后取出数组的第三个元素。
struct TreeNode {
        int value;
        struct TreeNode * left, * right;
};
struct TreeNode * find( struct TreeNode * root );

4、给定一个数字串，使用","将数字串拆分为不大于1000的多个的数字，输出所有可能性
例如数字串 1111 可拆分为：
1,1,1,1
1,1,11
1,11,1
1,111
11,1,1
11,11
111,1

做过什么项目？
平时刷题多么？
以前是什么专业？多久毕业？

------
# 陈治宇面经汇总

wxg 微信事业群 
3.22日
一面
自我介绍
聊项目
算法
1、链表的快排
2、能否成环，以及环的入口
3、数的开平方
4、AVL树的旋转
5、AVL树与堆的区别

MySQL
1、查询优化
2、表是如何设计的
3、表的连接

网络
1、Http的请求函数
2、三次握手协议
3、Socket与SocketServer的实现连接与发送请求

Java
1、Map底层的源码 ：HashMap  ConcurrentMap  HashTable

Linux
1、文件操作的指令
2、查看网络的指令
