# 2020互联网秋招技术岗面试必备资料和总结

## 前言
1. **岗位需求和面经**
* 可以上[**牛客网**](https://www.nowcoder.com/interview/center)的**面试-面经汇总**版块看看自己的求职岗位面试官都会问什么问题，提前做好侧重点复习，事半功倍。
* 还可以去求职公司的官网或者其他招聘网站看求职岗位的 JD (Job Description，职位描述)，对症下药，投其所好，精准复习。
2. **互联网所有岗位通用的考察部分**
* 基础知识：
  * 数据结构
  * 操作系统、计算机网络
  * 数据库（MySQL/Redis）
* 计算机语言：
  * SQL (必会)
  * Linux (加分项)   
  * Python (这是博主熟悉的语言，大家可以选择性忽略，并选择自己熟悉的语言复习，例如 Java、C++、Go等)
* 算法题：
  * 不用说了，只能秃头刷两三遍[**剑指Offer**](https://leetcode-cn.com/problemset/lcof/)和[**LeetCode高频题**](https://leetcode-cn.com/problemset/top/)，才能无惧手撕算法，所向披靡，刷题前务必把该博文里的数据结构模块的内容过一遍，否则连题目和答案解析都看不懂。 (⭐⭐⭐⭐⭐)
3. **适合大数据岗位的部分**
* Hadoop生态圈：
  * 这块儿根据 JD 需求自己把握是否需要复习。

## 一. 关于数据结构
1. [**大话数据结构** (精华版总结)](https://www.cnblogs.com/anliux/p/10802321.html)
* 刷题前必看，分章节对《大话数据结构》这本书的重点和精华部分的概括 (对于来不及看书er超级有用)。
2. [**数据结构** (精简版总结)](https://github.com/Jack-Lee-Hiter/AlgorithmsByPython/blob/master/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md)
* 刷完上面的每一章之后看这个链接里对应的内容，是一种更加精简概括，适合用来巩固和面试前复习。
3. [**LeetCode官网数据结构分类简介** (含对应习题)](https://leetcode-cn.com/explore/learn/) (⭐⭐⭐⭐⭐)
* 这个可以在刷题前看一遍内容，对应习题看时间选择做与不做，主要还是先做Leetcode官网里剑指offer板块的题。
4. [**《算法与数据结构之美》的学习笔记**](https://blog.csdn.net/ityqing/article/details/82838524)
* 内含数据结构与算法思维导图、时间/空间复杂度分析、数组、链表、队列和栈、递归、排序 (冒泡排序、插入排序、选择排序、归并排序、快速排序、桶排序)、散列表的图解介绍，图画的很好看而且很直观，写的很好。
5. [**树与二叉树的学习总结** (分支介绍和详细总结)](https://blog.csdn.net/zhaoyun_zzz/article/details/88393380) (⭐⭐⭐⭐⭐)
* 内含二叉树的分类 (满二叉树、完全二叉树、二叉排序树)、遍历 (前序、中序、后序、层序)、变种 (AVL树、红黑树、B树、B+树、B\*树)。

## 二.关于操作系统和计算机网络
1. [**操作系统常见面试知识点1 (含答案)**](https://www.cnblogs.com/zhangfuxiao/p/11624261.html)
2. [**操作系统常见面试知识点2 (含答案)**](https://blog.csdn.net/xiaoming100001/article/details/94960922)
3. <span id="2.1">[**《图解HTTP》**](https://blog.csdn.net/zephyr999/article/details/80055420) & [**《TCP/IP详解卷1：协议》**](https://www.cnblogs.com/mengwang024/p/4425834.html)</span>
* 有时间的可以扫一遍，过一下基础知识，方便理解后面的博客内容。
4. [**计算机网络面试常考总结(一)**](https://blog.nowcoder.net/n/f3323ab8ceb047c28a039cd2143392d6) & [**计算机网络面试常考总结(二)**](https://blog.nowcoder.net/n/0660c422f7594d8eb752ab77fdb5d0ef)
* 没有时间看[1. 《图解HTTP》 & 《TCP/IP详解卷1：协议》](#2.1)的，可以直接看这一部分的总结，基本要点全部都包含了，而且重点明显。
5. [**详解TCP连接的三次握手与四次挥手**](https://baijiahao.baidu.com/s?id=1654225744653405133&wfr=spider&for=pc)
* 内含男女告白和分手过程类比，帮助理解。
6. [**TCP的三次握手与四次挥手理解及面试题 (很全面)**](https://www.cnblogs.com/bj-mr-li/p/11106390.html)
* 看完前面的详解再看这一条就十分清晰明了，再用面试题来巩固一下。
7. [**TCP和UDP的最完整的区别**](https://www.cnblogs.com/williamjie/p/9390164.html)
8. [**TCP滑动窗口和拥塞控制机制详解**](https://blog.csdn.net/genzld/article/details/85317565)
9. [**从输入URL到网页呈现的过程**](https://www.cnblogs.com/xufeimei/p/10745227.html)
10. <span id="2.10">[**计算机网络面试题总结**](https://blog.csdn.net/qq_42651904/article/details/91355804)</span>
* 全面覆盖知识点且逻辑层次很清晰，有答案解析。
11. [**计算机网络常见面试题详细版** (含答案)](https://blog.csdn.net/sdgihshdv/article/details/79503274)
* 适合看完[6. 计算机网络面试题总结](#2.10)再复盘一遍。
12. [**计算机网络常见面试题精简版** (含答案)](https://krahets.gitee.io/views/computer-network/2019-09-18-post-computer-network-interview.html#osi%E4%B8%83%E5%B1%82%E6%A8%A1%E5%9E%8B%E3%80%81tcp-ip%E5%9B%9B%E5%B1%82%E6%A8%A1%E5%9E%8B%E3%80%81%E4%BA%94%E5%B1%82%E5%8D%8F%E8%AE%AE) (⭐⭐⭐⭐⭐)
* 基本囊括所有面试题的精华，言简意赅，适合复盘时期阅读复习。

## 三. 关于MySQL
1. **MYSQL事务和隔离级别**：
* [详细介绍版 (讲的很全面和通俗易懂)](https://zhuanlan.zhihu.com/p/117476959)
* [精简版 (举的例子很清楚)](https://www.cnblogs.com/wyaokai/p/10921323.html)
2. **MYSQL索引**：
* [条理清楚版 (面面俱到又切中要点，很重要)](https://github.com/ZXZxin/ZXBlog/blob/master/DB/MySQL/advance/MYSQL%E7%B4%A2%E5%BC%95.md)
  * 内含为什么B+树更适合实际应用中操作系统的文件索引和数据库索引的原因，以及SQL如何做优化(面试常问的两个点)
 * 索引优化
```
- 避免使用select *
- count(1)或count(列) 代替 count(*)
- 创建表时尽量时 char 代替 varchar
- 表的字段顺序固定长度的字段优先
- 组合索引代替多个单列索引(经常使用多个条件查询时)
- 尽量使用短索引
- 使用连接(JOIN)来代替子查询(Sub-Queries)
- 连表时注意条件类型需一致
- 索引散列值(重复少)不适合建索引，例：性别不适合
```
* [精简版通俗易懂 (适合最后复习的时候回忆知识点)](https://www.jianshu.com/p/c82148473235)
3. **MYSQL锁机制**：
* [详细介绍版 (讲的很全面且有英文原版对照)](https://blog.csdn.net/Saintyyu/article/details/91269087)
* [精简总结版 (带例分析)](https://www.cnblogs.com/rjzheng/p/9950951.html)
* [各大存储引擎锁的区别分析](https://zhuanlan.zhihu.com/p/29150809)
* [锁的常见面试题汇总 (含答案)](https://zhuanlan.zhihu.com/p/123096947)
4. [**MYSQL主从复制**](https://www.jianshu.com/p/faf0127f1cb2)
5. [**MYSQL分表分区**](https://www.jianshu.com/p/2084216e81ce)
6. [**MVCC**](https://blog.51cto.com/12182612/2486731?source=dra)
7. **MySQL面试题汇总 (含答案)**：
* [几率大的数据库 (MySQL) 面试题](https://blog.csdn.net/Butterfly_resting/article/details/89704636)
 * 覆盖面非常广但是精准，适合第一次看完所有上述基础知识后来一次巩固检测。
* [数据库常见面试题](https://blog.csdn.net/qq_22222499/article/details/79060495)
 * 用表格和一句话概括答案的形式精简化回答，易于记忆。
8. [**MySQL常见面试题一网打尽**](https://snailclimb.gitee.io/javaguide/#/docs/database/MySQL?id=%e4%b8%80%e6%9d%a1sql%e8%af%ad%e5%8f%a5%e6%89%a7%e8%a1%8c%e5%be%97%e5%be%88%e6%85%a2%e7%9a%84%e5%8e%9f%e5%9b%a0%e6%9c%89%e5%93%aa%e4%ba%9b%ef%bc%9f) (⭐⭐⭐⭐⭐)
* 内容精简且全面直击要害，适合最后复盘。

## 四. 关于Redis
1. [**Redis (Remote Dictionary Server) 和MySQL的区别**](https://blog.csdn.net/qq_38311489/article/details/84255532)
2. [**非关系型数据库(NoSql)的分类介绍**](https://blog.csdn.net/weixin_35353187/article/details/83026884)
3. [**简洁明了的面试题40道** (含答案)](https://blog.csdn.net/Design407/article/details/103242874)
4. [**详细的面试题汇总** (含答案)](https://blog.csdn.net/Butterfly_resting/article/details/89668661)
5. [**面试题快问快答精准版** (含答案)](https://juejin.im/post/5cb13b4d6fb9a0687b7dd0bd) (⭐⭐⭐⭐⭐)
* 基本囊括所有面试题的精华，言简意赅，适合复盘时期阅读复习。
6. [**什么是缓存穿透、缓存击穿、缓存雪崩以及怎么解决**](https://blog.csdn.net/ityqing/article/details/104675298)

## 五. 关于SQL
1. [**`group by`时`select`后跟聚合函数与否的剖析**](https://blog.csdn.net/u014717572/article/details/80687042)
2. [**`on`和`where`的区别**](https://www.jianshu.com/p/d923cf8ae25f)
* 概括说明：先执行 `on`，后执行 `where`；`on` 是建立关联关系 (无论条件真假都会建表，不辨真伪)，`where` 是对关联关系的筛选 (在建表后辨真伪完成筛选)。
3. [**各种表连接的区别**](https://www.runoob.com/sql/sql-join.html)
* 外连接`outer join`：
>* `left join`：联结结果保留左表的全部数据
>* `right join`：联结结果保留右表的全部数据
>* `full join`：联结结果保留左右表的全部数据 (MySQL中不支持`full join`，可以在 SQL Server使用)
* 内连接`inner join`：取两表的公共数据 
* 交叉连接`cross join`：返回被连接的两个表的笛卡尔积，返回结果的行数等于两个表行数的乘积 (注意：select * from 表1，表2实现自身级联，和`cross join`一样也是笛卡尔积的结果) 
* 上下连接`union`：内部的每个select语句必须拥有相同数量的列，列也必须拥有相似的数据类型，同时每个select语句中的列的顺序必须相同。`union`只会选取不同的值 (直接做了去重再连表)，`union all`可以用来选取重复的值！ 
4. [**`rank()/dense_rank()/row_number`用于排名问题的剖析**](https://www.linuxidc.com/Linux/2015-04/116349.htm)
* 说明：使用`rank over()`的时候，空值是最大的，如果排序字段为null， 可能造成null字段排在最前面，影响排序结果。可以这样：`rank over(partition by course order by score desc nulls last)`。
5. **`partition by`和`group by`的区别**
* `partition by`用于给结果集进行分区, 只是将原始数据进行名次排列 (记录数不变)
* `group by`是对原始数据进行聚合统计 (记录数可能变少，每组返回一条)
6. [**面试题原型题50道**](https://blog.csdn.net/hundan_520520/article/details/54881208)
* 这个有时间的话非常值得脑子里过一遍代码，Leetcode题基本都是从这些题变种来的。
7. [**Leetcode题**](https://leetcode-cn.com/problemset/database/) (⭐⭐⭐⭐⭐)
* 必刷，时间有限的话也要全部掌握非会员题，就20道左右，足够应对面试。

## 六.关于Linux
* [**常用命令解析和汇总**](https://segmentfault.com/a/1190000021950993)
* [**面试题汇总1**](https://blog.csdn.net/Butterfly_resting/article/details/89668744)
* [**面试题汇总2**](https://blog.csdn.net/Design407/article/details/103735538)

## 七. 关于Python
1. [**时间/空间复杂度分析**](https://blog.csdn.net/haha223545/article/details/93619874)
2. [**切片**](https://www.jianshu.com/p/15715d6f4dad)
3. [**复制/浅拷贝/深拷贝**](https://blog.csdn.net/bufengzj/article/details/90486991)
* 说明：常用的是浅拷贝 (".copy()"或者"[:]")，而不是深拷贝".deepcopy()"；深拷贝与浅拷贝唯一区别是除了外围元素，内层元素也做了复制，原数据变化后，复制的数据不会变化；浅拷贝只复制了外围元素，原数据外围元素变化时复制数据不变，但是原数据内层元素变化时复制数据跟着变化；复制 (即"=") 前后，原数据和复制数据的id相同，浅拷贝和深拷贝前后数据的id不同。
>备注：浅拷贝只复制指向某个对象的指针，而不复制对象本身，新旧对象还是共享同一块内存。但深拷贝会另外创造一个一模一样的对象，新对象跟原对象不共享内存，修改新对象不会改到原对象。
4. [**Python中is和==的区别**](https://www.cnblogs.com/wangkun122/p/9082088.html)
4. [**continue 和 break 的区别**](https://www.cnblogs.com/NancyRM/p/7998088.html)
5. [**双边队列**](https://www.cnblogs.com/lincappu/p/12890765.html)
6. [**Python实现单例模式**](https://github.com/taizilongxu/interview_python#16-%E5%8D%95%E4%BE%8B%E6%A8%A1%E5%BC%8F)

## 八.关于算法
1. [**各类题型算法模板**](https://greyireland.gitbook.io/algorithm-pattern/)
2. [**leetCode算法模板(Python3)**](https://blog.csdn.net/fuxuemingzhu/article/details/101900729)
3. [**LeetCode高频率题目分类标记** (好心人开了会员截图展示)](https://ac.nowcoder.com/discuss/292850)
4. [**LeetCode大佬的博客**](https://krahets.gitee.io/) 
* 说明：他对剑指offer所有题的解析非常好，有PPT动图解析，在leetcode里都是精选排名最靠前的解析，而且人还超级nice。
5. [**海量数据处理-10亿个数中找出最大的10000个数 (top K问题)](https://blog.csdn.net/zyq522376829/article/details/47686867) (⭐⭐⭐⭐⭐)

## 关于Hadoop生态圈
1. [**Hadoop面试知识点**](https://www.jianshu.com/p/a8e7e98298cc)

## 九.其他人的面试准备汇总
1. [**面面俱到又清晰明了的面试题总结** ](https://github.com/CyC2018/CS-Notes#pencil2-%E7%AE%97%E6%B3%95)
* 说明：你想要的他都有的面试总结, 强推。
2. [**全方位面试题总结**](https://github.com/taizilongxu/interview_python)
* 说明：有Python语言特性、数据库、操作系统、计算机网络、数据结构等，面向面经复习很有用。
3. [**各大公司的面试题的分类汇总以及各大模块内容的分类总结**](https://github.com/0voice/interview_internal_reference)


