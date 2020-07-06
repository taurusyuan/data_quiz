# 关于大数据开发岗位面试的一些资料总结和经验

## 一. 关于数据结构
1. **大话数据结构（精华版总结）**：https://www.cnblogs.com/anliux/p/10802321.html
* 说明：刷题前必看，分章节对《大话数据结构》这本书的重点和精华部分的概括（对于来不及看书er超级有用）。
2. **数据结构**：https://github.com/Jack-Lee-Hiter/AlgorithmsByPython/blob/master/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md
* 说明：刷完上面的每一章之后看这个链接里对应的内容，是一种更加精简概括，适合用来巩固和面试前复习。
3. **二叉树**的分支介绍和详细总结：https://blog.csdn.net/zhaoyun_zzz/article/details/88393380  &  https://zhuanlan.zhihu.com/p/27700617

## 二. 关于MySQL
1. **MYSQL事务和隔离级别**：
* 详细介绍版（讲的很全面和通俗易懂）：https://zhuanlan.zhihu.com/p/117476959
* 精简版（举的例子很清楚）：https://www.cnblogs.com/wyaokai/p/10921323.html
2. **MYSQL索引**：
* 条理清楚版（面面俱到又切中要点，很重要）：https://github.com/ZXZxin/ZXBlog/blob/master/DB/MySQL/advance/MYSQL%E7%B4%A2%E5%BC%95.md
>内含为什么B+树更适合实际应用中操作系统的文件索引和数据库索引的原因，以及SQL如何做优化（面试常问的两个点）
* 精简版通俗易懂（适合最后复习的时候回忆知识点）：https://www.jianshu.com/p/c82148473235
* 详细介绍版（讲的很全面和通俗易懂）：https://www.jianshu.com/p/0d6c828d3c70
3. **MYSQL锁机制（行锁/表锁等）**：
* 详细介绍版（讲的很全面且有英文原版对照）：https://blog.csdn.net/Saintyyu/article/details/91269087
* 精简总结版（带例分析）：https://www.cnblogs.com/rjzheng/p/9950951.html
* 各大存储引擎锁的区别分析：https://zhuanlan.zhihu.com/p/29150809
* 刷完上面的帖子来波新鲜的面试问题检验一下学习成果：https://zhuanlan.zhihu.com/p/123096947
4. **MYSQL主从复制**：https://www.jianshu.com/p/faf0127f1cb2
5. **分表分区**：https://www.jianshu.com/p/2084216e81ce
6. **MVCC**：https://blog.51cto.com/12182612/2486731?source=dra
7. **MySQL面试题汇总**：
* https://blog.csdn.net/Butterfly_resting/article/details/89704636
* https://blog.csdn.net/qq_22222499/article/details/79060495

## 三. 关于Redis
1. Redis和MySQL的区别：https://blog.csdn.net/qq_38311489/article/details/84255532
2. 简洁明了的面试题40道（含答案）：https://blog.csdn.net/Design407/article/details/103242874
3. 详细的面试题汇总（含答案）：https://blog.csdn.net/Butterfly_resting/article/details/89668661
4. 面试题快问快答：https://segmentfault.com/a/1190000017339258 & https://blog.csdn.net/weixin_34163553/article/details/91450473


## 四. 关于SQL
1. **`group by`时`select`后跟聚合函数与否的剖析**：https://blog.csdn.net/u014717572/article/details/80687042
2. **`on`和`where`的区别**：https://www.jianshu.com/p/d923cf8ae25f
* 概括说明：先执行 `on`，后执行 `where`；`on` 是建立关联关系(无论条件真假都会建表，不辨真伪)，`where` 是对关联关系的筛选 (在建表后辨真伪完成筛选)。
3. **各种表连接的区别**：https://www.runoob.com/sql/sql-join.html
>* 外连接`outer join`：
>>* `left join`：联结结果保留左表的全部数据
>>* `right join`：联结结果保留右表的全部数据
>>* `full join`：联结结果保留左右表的全部数据 (MySQL中不支持`full join`，可以在 SQL Server使用。)
>* 内连接`inner join`：取两表的公共数据 
>* 交叉连接`cross join`：返回被连接的两个表的笛卡尔积，返回结果的行数等于两个表行数的乘积(注意：select * from 表1，表2实现自身级联，和`cross join`一样也是笛卡尔积的结果) 
>* 上下连接`union`：内部的每个select语句必须拥有相同数量的列，列也必须拥有相似的数据类型，同时每个select语句中的列的顺序必须相同。`union`只会选取不同的值(直接做了去重再连表)。`union all`可以用来选取重复的值！ 
4. **`rank()/dense_rank()/row_number`用于排名问题的剖析**：https://www.linuxidc.com/Linux/2015-04/116349.htm
* 说明使用`rank over()`的时候，空值是最大的，如果排序字段为null, 可能造成null字段排在最前面，影响排序结果。可以这样：`rank over(partition by course order by score desc nulls last)`
5. **`partition by`和`group by`的区别**
* `partition by`用于给结果集进行分区, 只是将原始数据进行名次排列(记录数不变)
* `group by`是对原始数据进行聚合统计(记录数可能变少, 每组返回一条)
6. 面试题原型题50道：https://blog.csdn.net/hundan_520520/article/details/54881208

## 五.关于Linux
* 面试题汇总1：https://blog.csdn.net/Butterfly_resting/article/details/89668744
* 面试题汇总2：https://blog.csdn.net/Design407/article/details/103735538

## 五. 关于Python
0. **时间/空间复杂度分析**：https://blog.csdn.net/haha223545/article/details/93619874
1. **切片**：https://www.jianshu.com/p/15715d6f4dad
2. **复制/浅拷贝/深拷贝**：https://blog.csdn.net/bufengzj/article/details/90486991
* 说明：常用的是浅拷贝（".copy()"或者"[:]"），而不是深拷贝".deepcopy()"；深拷贝与浅拷贝唯一区别是除了外围元素，内层元素也做了复制，原数据变化后，复制的数据不会变化；浅拷贝只复制了外围元素，原数据外围元素变化时复制数据不变，但是原数据内层元素变化时复制数据跟着变化；复制（即"="）前后，原数据和复制数据的id相同，浅拷贝和深拷贝前后数据的id不同。
【备注：浅拷贝只复制指向某个对象的指针，而不复制对象本身，新旧对象还是共享同一块内存。但深拷贝会另外创造一个一模一样的对象，新对象跟原对象不共享内存，修改新对象不会改到原对象】
3. **continue 和 break 的区别**：https://www.cnblogs.com/NancyRM/p/7998088.html
4. **双边队列**https://www.cnblogs.com/lincappu/p/12890765.html
