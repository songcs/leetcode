# Description

这个仓库是为了leetcode刷题用的
目录`solutions`存储解题报告，`anki`存放制作的anki卡片

|一|二|
|:--:|:--:|
|[分类刷题](#分类刷题)|[全部](#leetcode)


## 分类刷题

> 此分类来自于[链接](https://github.com/arkingc/note/blob/master/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%8E%E7%AE%97%E6%B3%95/%E7%AE%97%E6%B3%95%E9%A2%98%E6%80%BB%E7%BB%93.md)
> 正在改造为自己习惯的格式，如果题目不是处于表格中，则说明未改造完成，里面的链接不可用

| 一 | 二 | 三  | 四 | 五 | 六 | 七  | 八 | 九 | 十 |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|[数组](#数组)|[字符串](#字符串)|[链表](#链表)|[树](#树)|[栈和队列](#栈和队列)|[数学](#数学)|[图](#图)|[设计](#设计)|[海量数据](#海量数据)|[C/C++基础](#C/C++基础)|


### 数组

#### *二分查找*
|来源|题目|本地题解报告|难度|
|----|----|----|----|
|lc:35|[Search Insert Position](https://leetcode.com/problems/search-insert-position/description/)|[python](./solutions/35.md) [cpp](./solutions/35.md)|easy|
|牛客网|[旋转数组的最小数字](https://www.nowcoder.com/practice/9f3231a991af4f55b95579b44b7a01ba?tpId=13&tqId=11159&tPage=1&rp=2&ru=%2Fta%2Fcoding-interviews&qru=%2Fta%2Fcoding-interviews%2Fquestion-ranking)|||
|lc:33|[Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)|[python](./solutions/33.md)|medium|
|lc:81|[Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/description/)|[python](./solutions/81.md)|medium|
|lc未找到|有序数组中查找数字的范围|||
|lc:162|[Find Peak Element](https://leetcode.com/problems/find-peak-element/description/)|[python](./solutions/162.md)|medium|
|lc:4|[Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/description/)|[python](./solutions/4.md)|hard|
||[缺失的数字](https://github.com/arkingc/note/blob/master/数据结构与算法/算法题总结.md#缺失的数字)|||
||[数组中数值和下标相等的元素](https://github.com/arkingc/note/blob/master/数据结构与算法/算法题总结.md#数组中数值和下标相等的元素)|||

#### *其它查找*
  + Leetcode41：[缺失的第一个正数](#缺失的第一个正数)（`交换` `hard`）
  + Leetcode287：[寻找数组中重复的数](#寻找数组中重复的数)（`二分查找` `链表` `medium`）
  + Leetcode268：[0~n中缺失的数字](#0n中缺失的数字)（`位运算` `easy`）
  + Leetcode136：[只出现1次的数字](#只出现1次的数字)（`位运算` `easy`）
  + 《剑指offer》面试题56(题目一)：[数组中只出现1次的2个数](#数组中只出现1次的2个数)（`位运算`）
  + 《剑指offer》面试题56(题目二)：[数组中唯一只出现1次的数字](#数组中唯一只出现1次的数字)（`位运算`）
  + 《剑指offer》面试题41：[数据流的中位数](#数据流的中位数)（`堆`）
  + 《剑指offer》面试题57(题目一)：[和为s的两个数字](#和为s的两个数字)（`双指针`）
  + 《剑指offer》面试题57(题目二)：[和为s的连续正数序列](#和为s的连续正数序列)（`双指针`）
  + Leetcode217：[判断数组是否包含重复元素](#判断数组是否包含重复元素)（`哈希表` `easy`）
  + Leetcode1：[两数之和](#两数之和)（`哈希表` `easy`）
  + Leetcode15：[三数之和](#三数之和)（`排序` `双指针` `medium`）
  + Leetcode18：[四数之和](#四数之和)（`排序` `双指针` `medium`）
  + Leetcode454：[四数之和II](#四数之和ii)（`哈希表` `medium`）
  + 《剑指offer》面试题39：[数组中出现次数超过一半的数字](#数组中出现次数超过一半的数字)（`partition`）
  + 《剑指offer》面试题40：[数组中最小的k个数](#数组中最小的k个数)（`partition` `海量数据`）
  + Leetcode347：[出现频率最高的k个数字](#出现频率最高的k个数字)（`medium`）
  + Leetcode350：[两个数组的交集II](#两个数组的交集ii)（`easy`）
#### *数组操作*
+ Leetcode26：[删除排序数组中的重复项](#删除排序数组中的重复项)（`双指针` `easy`）
+ Leetcode27：[删除数组中值为val的元素](#删除数组中值为val的元素)（`双指针` `easy`）
+ Leetcode189：[旋转数组](#旋转数组)（`easy`）
+ Leetcode283：[将数组中的零移到尾部](#将数组中的零移到尾部)（`easy`）
#### *子数组与连续子数组*
  + 《剑指offer》面试题42：[连续子数组的最大和](#连续子数组的最大和)（`动态规划`）
  + Leetcode152：[连续子数组的最大积](#连续子数组的最大积)（`动态规划` `medium`）
  + Leetcode128：[最长连续序列](#最长连续序列)（`哈希表` `hard`）
  + Leetcode300：[最长升序子序列](#最长升序子序列)（`动态规划` `medium`）
  + Leetcode334：[数组的三元升序子序列](#数组的三元升序子序列)（`medium`）
#### *排列组合*
  + 《剑指offer》面试题38(相关题一)：[正方体顶点上放数字](#正方体顶点上放数字)（`全排列`）
  + 《剑指offer》面试题38(相关题二)：[八皇后](#八皇后)（`全排列`）
  + Leetcode52：[N皇后II](#n皇后ii)（`全排列` `hard`）
  + Leetcode51：[N皇后](#n皇后)（`全排列` `hard`）
  + Leetcode31：[下一个排列](#下一个排列)（`排列` `medium`）
  + Leetcode60：[第K个排列](#第k个排列)（`排列` `medium`）
  + Leetcode46：[不含重复元素数组的全排列](#不含重复元素数组的全排列)（`全排列` `medium`）
  + Leetcode47：[含重复元素数组的全排列](#含重复元素数组的全排列)（`全排列` `medium`）
  + Leetcode77：[1~n中所有k个数的组合](#1n中所有k个数的组合)（`组合` `medium`）
  + Leetcode78：[不含重复元素集合的所有子集](#不含重复元素集合的所有子集)（`组合` `medium`）
  + Leetcode90：[含重复元素集合的所有子集](#含重复元素集合的所有子集)（`组合` `medium`）
  + Leetcode39：[和为target的数字组合](#和为target的数字组合)（`组合` `medium`）
  + Leetcode40：[和为target的数字组合II](#和为target的数字组合ii)（`组合` `medium`）
#### *排序*
+ 《剑指offer》面试题21：[调整数组顺序使奇数位于偶数前面](#调整数组顺序使奇数位于偶数前面)（`partition`)
+ 《剑指offer》面试题61：[扑克牌中的顺子](#扑克牌中的顺子)
+ Leetcode75：[颜色分类](#颜色分类)（`medium`）
+ Leetcode179：[将一组数拼接成最大数字](#将一组数拼接成最大数字)（`medium`）
+ Leetcode88：[合并两个有序数组](#合并两个有序数组)（`归并` `easy`）
+ 《剑指offer》面试题51：[数组中的逆序对](#数组中的逆序对)（`归并`）
+ Leetcode315：[计算右侧小于当前元素的个数](#计算右侧小于当前元素的个数)（`归并` `BST` `hard`）
+ Leetcode324：[摆动排序](#摆动排序)（`medium`）
+ Leetcode384：[打乱数组](#打乱数组)（`Fisher–Yates shuffle洗牌算法` `medium`）
#### *场景*
  + Leetcode134：[加油站](#加油站)（`贪心` `medium`）
  + Leetcode121：[买卖股票的最佳时机](#买卖股票的最佳时机)（`easy`）
  + Leetcode122：[买卖股票的最佳时机II](#买卖股票的最佳时机ii)（`贪心` `easy`）
  + Leetcode123：[买卖股票的最佳时机III](#买卖股票的最佳时机iii)（`动态规划` `hard`）
  + Leetcode188：[买卖股票的最佳时机IV](#买卖股票的最佳时机iv)（`动态规划` `hard`）
  + Leetcode198：[打家劫舍](#打家劫舍)（`动态规划` `easy`）
  + Leetcode213：[打家劫舍II](#打家劫舍ii)（`动态规划` `medium`）
  + Leetcode337：[打家劫舍III](#打家劫舍iii)（`动态规划` `medium`）
  + Leetcode322：[找钱](#找钱)（`动态规划` `medium`）
  + 拼多多内推笔试：[装载货物的最少货车数量](#装载货物的最少货车数量)（`贪心`）
#### *二维数组*
  + 《剑指offer》面试题4：[二维数组中的查找](#二维数组中的查找)
  + Leetcode378：[有序矩阵中第K小的元素](#有序矩阵中第k小的元素)（`优先队列` `二分查找` `medium`）
  + 《剑指offer》面试题29：[顺时针打印矩阵](#顺时针打印矩阵)
  + Leetcode48：[90度旋转图片](#90度旋转图片)（`medium`）
  + 《剑指offer》面试题66：[构建乘积数组](#构建乘积数组)
  + Leetcode73：[矩阵置零](#矩阵置零)（`medium`）
  + Leetcode289：[细胞自动机的下一个状态](#细胞自动机的下一个状态)（`位运算` `medium`）


### 字符串
  - *字符串与数字*
      + 《剑指offer》面试题20：[判断字符串是否表示一个数值](#判断字符串是否表示一个数值)（`鲁棒性`）
      + 《剑指offer》面试题67：[把字符串转换成整数](#把字符串转换成整数)（`鲁棒性`）
  - *字符查找*
      + 《剑指offer》面试题50(题目一)：[字符串中第一个只出现一次的字符](#字符串中第一个只出现一次的字符)（`哈希表`）
      + 《剑指offer》面试题50(题目二)：[字符流中第一个只出现一次的字符](#字符流中第一个只出现一次的字符)（`哈希表`）
  - *翻转*
      + 《剑指offer》面试题58(题目一)：[翻转单词顺序](#翻转单词顺序)
      + 《剑指offer》面试题58(题目二)：[左旋转字符串](#左旋转字符串)
      + Leetcode344：[翻转字符串](#翻转字符串)（`双指针` `easy`）
  - *排列组合*
      + 《剑指offer》面试题38：[字符串的排列](#字符串的排列)（`排列`）
      + 《剑指offer》面试题38(扩展)：[求字符的所有组合](#求字符的所有组合)（`组合`）
  - *删除替换*
      + 《剑指offer》面试题5：[替换空格](#替换空格)
      + Leetcode71：[简化路径](#简化路径)（`medium`）
  - *异位词*
      + Leetcode49：[字母异位词分组](#字母异位词分组)（`排序` `哈希表` `medium`）
      + Leetcode242：[有效的字母异位词](#有效的字母异位词)（`排序` `哈希表` `easy`）
  - *单词查找*
      + 《剑指offer》面试题12：[单词搜索](#单词搜索)（`DFS`）
      + Leetcode212：[单词搜索II](#单词搜索ii)（`Trie` `DFS` `hard`）
  - *字符串转换*
      + Leetcode91：[数字字符串解码](#数字字符串解码)（`动态规划` `medium`）
      + Leetcode127：[单词阶梯](#单词阶梯)（`BFS` `medium`）
      + Lintcode119：[单词转换的最少次数](#单词转换的最少次数)（`动态规划` `medium`）
  - *子串与子序列*
      + Leetcode28：[子串查找](#子串查找)（`KMP` `easy`）
      + Leetcode3：[不含重复字符的最长子串](#不含重复字符的最长子串)（`滑动窗口` `哈希表` `medium`）
      + Leetcode395：[至少有K个重复字符的最长子串](#至少有k个重复字符的最长子串)（`二分法` `哈希表` `medium`）
      + Leetcode76：[最小覆盖子串](#最小覆盖子串)（`滑动窗口` `哈希表` `hard`）
      + Leetcode30：[所有单词相连的子串](#所有单词相连的子串)（`哈希表` `hard`）
      + Leetcode5：[最长回文子串](#最长回文子串)（`动态规划` `medium`）
      + Leetcode125：[判断字符串是否是回文串](#判断字符串是否是回文串)（`双指针` `easy`）
  - *字符串拆分*
      + Leetcode131：[分割回文串](#分割回文串)（`动态规划` `DFS` `medium`）
      + Leetcode139：[单词拆分I](#单词拆分i)（`动态规划` `medium`）
      + Leetcode140：[单词拆分II](#单词拆分ii)（`动态规划` `hard`）
  - *字符串匹配*
      + Leetcode10：[正则表达式匹配](#正则表达式匹配)（`动态规划` `hard`）
      + Leetcode44：[通配符匹配](#通配符匹配)（`动态规划` `hard`）
  - *最长公共问题*
      + Lintcode77：[两个字符串的最长公共子序列](#两个字符串的最长公共子序列)（`动态规划` `medium`）
      + Lintcode79：[两个字符串的最长公共子串](#两个字符串的最长公共子串)（`动态规划` `medium`）
      + Leetcode14：[多个字符串的最长公共前缀](#多个字符串的最长公共前缀)（`扫描` `分治` `二分查找` `Trie` `easy`）

<h2 id="list"></h2>

### 链表
  - *遍历*
      + 《剑指offer》面试题6：[从尾到头打印链表](#从尾到头打印链表)（`栈`）
      + Leetcode234：[回文链表](#回文链表)（`栈` `easy`）
      + 《剑指offer》面试题22：[链表中倒数第k个节点](#链表中倒数第k个节点)（`双指针`）
      + Leetcode19：[删除链表倒数第n个节点](#删除链表倒数第n个节点)（`双指针` `鲁棒性` `medium`）
      + 《剑指offer》面试题22(相关题)：[链表的中间节点](#链表的中间节点)（`双指针`）
      + Leetcode141：[判断链表是否有环](#判断链表是否有环)（`双指针` `easy`）
      + 《剑指offer》面试题23：[链表中环的入口节点](#链表中环的入口节点)（`双指针`）
  - *节点删除*
      + 《剑指offer》面试题18(题目一)：[删除链表中的节点](#删除链表中的节点)
      + Leetcode203：[删除链表中等于给定值的所有节点](#删除链表中等于给定值的所有节点)（`鲁棒性` `easy`）
      + Leetcode83：[删除有序链表中的重复节点](#删除有序链表中的重复节点)（`easy`）
      + 《剑指offer》面试题18(题目二)：[删除有序链表中的重复节点II](#删除有序链表中的重复节点ii)（`鲁棒性` `medium`）
      + 《剑指offer》面试题62：[圆圈中最后剩下的数](#圆圈中最后剩下的数)
      + 腾讯面试题：[实现双链表节点删除函数](#实现双链表节点删除函数)（`鲁棒性`）
  - *单链表处理*
      + 《剑指offer》面试题24：[反转链表](#反转链表)（`栈`）
      + 《剑指offer》面试题35：[复杂链表的复制](#复杂链表的复制)
      + Leetcode61：[旋转链表](#旋转链表)（`medium`）
      + Leetcode24：[成对交换链表的节点](#成对交换链表的节点)（`鲁棒性` `medium`）
      + Leetcode25：[K个一组翻转链表](#k个一组翻转链表)（`鲁棒性` `hard`）
      + Leetcode148：[链表节点排序](#链表节点排序)（`分治归并` `medium`）
      + Leetcode328：[将链表偶数位置的节点移至尾部](#将链表偶数位置的节点移至尾部)（`medium`）
  - *多链表处理*
      + Leetcode2：[两数相加](#两数相加)（`数学` `medium`）
      + 《剑指offer》面试题25：[合并两个有序链表](#合并两个有序链表)
      + Leetcode23：[合并k个有序链表](#合并k个有序链表)（`多路归并` `堆` `分治` `hard`）
      + 《剑指offer》面试题52：[两个链表的第一个公共节点](#两个链表的第一个公共节点)（`双指针`）

### 树
- *遍历*
    + 《剑指offer》面试题7：[重建二叉树](#重建二叉树)（`前序` `中序`）
    + 《剑指offer》面试题8：[中序遍历的下一个节点](#中序遍历的下一个节点)（`中序`）
    + 《剑指offer》面试题26：[树的子结构](#树的子结构)（`前序`）
    + 《剑指offer》面试题37：[序列化二叉树](#序列化二叉树)（`前序`）
    + Leetcode94：[输出二叉树的中序遍历序列](#输出二叉树的中序遍历序列)（`中序` `递归` `迭代` `medium`）
    + Leetcode98：[判断一棵二叉树是否是BST](#判断一棵二叉树是否是bst)（`BST` `中序` `medium`）
    + 《剑指offer》面试题33：[BST的后序遍历序列](#bst的后序遍历序列)（`BST` `后序`）
    + 《剑指offer》面试题36：[BST转双链表](#bst转双链表)（`BST` `中序` `双链表`）
    + Leetcode108：[有序数组转BST](#有序数组转bst)（`BST` `分治` `easy`）
    + Leetcode109：[单链表转BST](#单链表转bst)（`BST` `中序` `单链表` `medium`）
    + 《剑指offer》面试题54：[BST第k小的节点](#bst第k小的节点)（`BST` `中序`）
    + Leetcode116：[填充同一层的兄弟节点](#填充同一层的兄弟节点)（`BFS` `前序` `medium`）
    + 《剑指offer》面试题32(题目一)：[按层不分行输出二叉树](#按层不分行输出二叉树)（`BFS`）
    + 《剑指offer》面试题32(题目二)：[按层分行输出二叉树](#按层分行输出二叉树)（`BFS`）
    + 《剑指offer》面试题32(题目三)：[之字形打印二叉树](#之字形打印二叉树)（`BFS` `栈`）
- *对称二叉树*
    + 《剑指offer》面试题27：[二叉树的镜像](#二叉树的镜像)（`递归` `迭代`）
    + 《剑指offer》面试题28：[对称的二叉树](#对称的二叉树)（`递归` `迭代`）
- *路径*
    + 《剑指offer》面试题34：[二叉树中和为某一值的路径](#二叉树中和为某一值的路径)（`回溯`）
    + Leetcode124：[二叉树的最大路径和](#二叉树的最大路径和)（`动态规划` `后序` `hard`）
    + Leetcode863：[二叉树中与target距离为K的结点](#二叉树中与target距离为k的结点)（`DFS(前序)` `BFS` `medium`）
- *深度*
    + 《剑指offer》面试题55(题目一)：[二叉树的深度](#二叉树的深度)（`递归`）
    + 《剑指offer》面试题55(题目二)：[平衡二叉树AVL](#平衡二叉树avl)（`后序`）
- *公共祖先*
    + 《剑指offer》面试题68：[两个节点的最低公共祖先](#两个节点的最低公共祖先)


### 栈和队列
- *设计*
    + 《剑指offer》面试题9：[用两个栈实现队列](#用两个栈实现队列)（`栈` `队列`）
    + 《剑指offer》面试题9(相关题)：[用两个队列实现栈](#用两个队列实现栈)（`栈` `队列`）
    + 《剑指offer》面试题30：[包含min函数的栈](#包含min函数的栈)（`栈`）
    + 《剑指offer》面试题59(题目二)：[包含max函数的队列](#包含max函数的队列)（`队列`）
- *其它*
    + 《剑指offer》面试题31：[栈的压入弹出序列](#栈的压入弹出序列)（`栈`）
    + Leetcode20：[有效的括号](#有效的括号)（`栈` `easy`）
    + Leetcode32：[最长有效括号](#最长有效括号)（`栈` `hard`）
    + 《剑指offer》面试题59(题目一)：[滑动窗口的最大值](#滑动窗口的最大值)（`队列`）


### 数学
- *斐波那契数列*
    + 《剑指offer》面试题10(题目一)：[斐波那契数列](#斐波那契数列)（`动态规划`）
    + 《剑指offer》面试题10(题目二)：[跳台阶](#跳台阶)（`动态规划`）
    + 《剑指offer》面试题10(题目三)：[变态跳台阶](#变态跳台阶)（`动态规划`）
    + 《剑指offer》面试题10(题目四)：[矩形覆盖](#矩形覆盖)（`动态规划`）
- *特殊*
    + 《剑指offer》面试题49：[丑数](#丑数)
    + Leetcode36：[有效数独](#有效数独)（`哈希表` `medium`）
    + Leetcode204：[计数质数](#计数质数)（`easy`）
    + Leetcode279：[完美平方数](#完美平方数)（`动态规划` `medium`）
- *进制*
    + 《剑指offer》面试题15：[二进制中1的个数](#二进制中1的个数)（`位运算`）
    + Leetcode7：[反转整数](#反转整数)（`鲁棒性` `easy`）
    + Leetcode43：[字符串相乘](#字符串相乘)（`鲁棒性` `medium`）
    + Leetcode66：[数组表示的数字加1](#数组表示的数字加1)（`easy`）
    + Leetcode171：[Excel表列序号（26进制转10进制）](#excel表列序号)（`easy`）
    + Leetcode190：[颠倒二进制位](#颠倒二进制位)（`位运算` `easy`）
- *倍数约数*
    + Leetcode412：[Fizz Buzz](#fizz-buzz)（`easy`）
- *次方与小数*
    + 《剑指offer》面试题16：[数值的整数次方](#数值的整数次方)（`位运算` `鲁棒性`）
    + Leetcode69：[求x的平方根](#求x的平方根)（`二分查找` `鲁棒性` `easy`）
    + Leetcode166：[求分数的值](#求分数的值)（`鲁棒性` `medium`）
    + Leetcode326：[3的幂](#3的幂)（`easy`）
- *找规律*
    + 《剑指offer》面试题43：[整数1~n中1出现的次数](#整数1n中1出现的次数)
    + Leetcode38：[报数](#报数)（`字符串` `easy`）
    + Leetcode172：[阶乘后的零](#阶乘后的零)（`鲁棒性` `easy`）
- *条件限制*
    + 《剑指offer》面试题64：[求1~n的和](#求1n的和)
    + 《剑指offer》面试题65：[不用加减乘除做加法](#不用加减乘除做加法)（`位运算`）
    + Leetcode29：[不用乘除取模实现整数除法](#不用乘除取模实现整数除法)（`位运算` `medium`）
- *表达式求值*
    + Leetcode150：[逆波兰表达式求值](#逆波兰表达式求值)（`栈` `medium`）
    + Leetcode227：[基础的计算器](#基础的计算器)（`medium`）
- *几何*
    + Leetcode11：[盛最多水的容器](#盛最多水的容器)（`双指针` `medium`）
    + Leetcode42：[接雨水](#接雨水)（`hard`）
    + Leetcode55：[合并区间](#合并区间)（`medium`）
    + Leetcode84：[柱状图中最大的矩形](#柱状图中最大的矩形)（`栈` `hard`）
    + Leetcode149：[直线上最多的点数](#直线上最多的点数)（`哈希` `hard`）
    + Leetcode218：[天际线问题](#天际线问题)（`hard`）

### 图
- *遍历*
    + 《剑指offer》面试题13：[机器人的运动范围](#机器人的运动范围)（`DFS`）
    + Leetcode62：[左上角到右下角的路径数](#左上角到右下角的路径数)（`DFS` `动态规划` `medium`）
    + Leetcode63：[左上角到右下角的路径数II](#左上角到右下角的路径数ii)（`DFS` `动态规划` `medium` ）
    + Leetcode64：[左上角到右下角的最短路径](#左上角到右下角的最短路径)（`DFS` `动态规划` `medium` ）
    + Leetcode130：[被包围的区域](#被包围的区域)（`DFS` `medium`）
    + Leetcode200：[岛屿的数量](#岛屿的数量)（`DFS` `easy`）
    + Leetcode695：[岛屿的最大面积](#岛屿的最大面积)（`DFS` `easy`）
    + Leetcode329：[矩阵中的最长递增路径](#矩阵中的最长递增路径)（`DFS` `动态规划` `hard`）
    + Leetcode55：[跳步游戏](#跳步游戏)（`贪心` `medium`）
    + Leetcode45：[跳步游戏II](#跳步游戏ii)（`动态规划` `BFS` `hard`）
- *拓扑排序*
    + Leetcode207：[课程安排](#课程安排)（`BFS` `DFS` `medium`）
    + Leetcode210：[课程安排II](#课程安排ii)（`BFS` `DFS` `medium`）
- *最短路径*
    + hihoCoder1081：[Dijkstra算法](#dijkstra算法)（`dijkstra` `Lv.2`）
- *最小生成树*
    + hihoCoder1097：[连通所有城市的最短道路](#连通所有城市的最短道路)（`prim` `Lv.2`）


### 设计
- Leetcode146：[LRU缓存机制](#lru缓存机制)（`哈希表` `链表` `hard`）
- Leetcode208：[实现Trie树(前缀树)](#实现trie树)（`Trie` `设计` `medium`）
- Leetcode341：[扁平化嵌套列表迭代器](#扁平化嵌套列表迭代器)（`栈` `medium`）
- Leetcode380：[实现O(1)的插入删除与随机获取](#实现o1的插入删除与随机获取)（`哈希表` `medium`）

### 海量数据
- *公共部分*
    + 《王道程序员求职宝典》：[两个文件共同的url](#两个文件共同的url)（`hash` `分治`）
- *频率最高*
    + 《王道程序员求职宝典》：[按频率排序多个文件中的query记录](#按频率排序多个文件中的query记录)（`hash` `分治`）
    + 《王道程序员求职宝典》：[找出文件中频率最高的100个词](#找出文件中频率最高的100个词)（`Top K` `hash` `分治`）
    + 《王道程序员求职宝典》：[海量日志中提取访问百度次数最多的IP](#海量日志中提取访问百度次数最多的ip)（`Top K` `hash` `分治`）
- *中位数*
    + BAT面试经典题：[100亿个整数的中位数](#100亿个整数的中位数)（`二分查找` `分桶`）
- *位图*
    + 《王道程序员求职宝典》：[实现位图](#实现位图)（`位图`）
    + 《王道程序员求职宝典》：[统计不同号码的个数](#统计不同号码的个数)（`位图`）
    + 《王道程序员求职宝典》：[查找某个数是否在40亿个数当中](#查找某个数是否在40亿个数当中)（`位图`）
    + 《王道程序员求职宝典》：[2.5亿整数中只出现一次的整数](#25亿整数中只出现一次的整数)（`位图`）
- *其它*
    + 《王道程序员求职宝典》：[布隆过滤器](#布隆过滤器)
    + 《王道程序员求职宝典》：[倒排索引法](#倒排索引法)


### C/C++基础
- *C库函数*
    + [实现strlen](#1实现strlen)
    + [实现strcmp](#2实现strcmp)
    + [实现strcat](#3实现strcat)
    + [实现strcpy](#4实现strcpy)
    + [实现strstr](#子串查找)
    + [实现memcpy](#1实现memcpy)
- *结构体与联合*
    + [实现一个函数确定主机字节序](#1实现一个函数确定主机字节序)
    + [实现计算结构体成员偏移量的宏](#2实现计算结构体成员偏移量的宏)
- *动态内存管理*
    + [手写实现智能指针](#手写实现智能指针)

## leetcode

|编号|题目|本地题解报告|难度|
|----|----|----|----|
|1|[Two Sum](https://leetcode.com/problems/two-sum/description/)|[python](./solutions/1.md)|easy|
|2|[Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)|[python](./solutions/2.md)|medium|
|3|[Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/description/)|[python](./solutions/3.md)|medium|
|4|[Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/description/)|[python](./solutions/4.md)|hard|
|5|[Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/description/)|[python](./solutions/5.md)|medium|
|6|[ZigZag Conversion](https://leetcode.com/problems/zigzag-conversion/)|[python](./solutions/6.md)|medium|
|7|[Reverse Integer](https://leetcode.com/problems/reverse-integer/description/)|[python](./solutions/7.md)|easy|
|8|[String to Integer (atoi)](https://leetcode.com/problems/string-to-integer-atoi/description/)|[python](./solutions/8.md)|medium|
|9|[Palindrome Number](https://leetcode.com/problems/palindrome-number/)|[python](./solutions/9.md)|easy|
|10|[Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/description/)|||
|11|[Container With Most Water](https://leetcode.com/problems/container-with-most-water/description/)|[python](./solutions/11.md)|medium|
|12|[Integer to Roman](https://leetcode.com/problems/integer-to-roman/description/)|[python](./solutions/12.md)|medium|
|13|[Roman to Integer](https://leetcode.com/problems/roman-to-integer/description/)|[python](./solutions/13.md)|easy|
|14|[Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/)|[python](./solutions/14.md)|easy|
|15|[3Sum](https://leetcode.com/problems/3sum/description/)|[python](./solutions/15.md)|medium|
|16|[3Sum Closest](https://leetcode.com/problems/3sum-closest/)|[python](./solutions/16.md)|medium|
|17|[Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/description/)|[python](./solutions/17.md)|medium|
|18|[4Sum](https://leetcode.com/problems/4sum/description/)|[python](./solutions/18.md)|medium|
|19|[Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)|[python](./solutions/19.md)|medium|
|20|[Valid Parentheses](https://leetcode.com/problems/valid-parentheses/description/)|[python](./solutions/20.md)|easy|
|21|[Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)|[python](./solutions/21.md)|easy|
|22|[Generate Parentheses](https://leetcode.com/problems/generate-parentheses/description/)|[python](./solutions/22.md)|medium|
|23|[Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/description/)|||
|24|[Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/)|[python](./solutions/24.md)|mediun|
|25|[Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/)|[python](./solutions/25.md)|hard|
|26|[Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/description/)|[python](./solutions/26.md)|easy|
|27|[Remove Element](https://leetcode.com/problems/remove-element/)|[python](./solutions/27.md)|easy|
|28|[Implement strStr()](https://leetcode.com/problems/implement-strstr/description/)|[python](./solutions/28.md)|easy|
|29|[Divide Two Integers](https://leetcode.com/problems/divide-two-integers/description/)|[python](./solutions/29.md)|medium|
|31|[Next Permutation](https://leetcode.com/problems/next-permutation/description/)|[python](./solutions/31.md)|medium|
|32|[Longest Valid Parentheses](https://leetcode.com/problems/longest-valid-parentheses/description/)|||
|33|[Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)|[python](./solutions/33.md)|medium|
|34|[Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/description/)|[python](./solutions/34.md)|medium|
|35|[Search Insert Position](https://leetcode.com/problems/search-insert-position/description/)|[python](./solutions/35.md) [cpp](./solutions/35.md)|easy|
|36|[Valid Sudoku](https://leetcode.com/problems/valid-sudoku/description/)|[python](./solutions/36.md)|medium|
|37|[Sudoku Solver](https://leetcode.com/problems/sudoku-solver/description/)|||
|38|[Count and Say](https://leetcode.com/problems/count-and-say/description/)|[python](./solutions/38.md)|easy|
|39|[Combination Sum](https://leetcode.com/problems/combination-sum/description/)|[python](./solutions/39.md)|medium|
|40|[Combination Sum II](https://leetcode.com/problems/combination-sum-ii/description/)|[python](./solutions/40.md)|medium|
|41|[First Missing Positive](https://leetcode.com/problems/first-missing-positive/description/)||hard|
|42|[Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/description/)|[python](./solutions/42.md)|hard|
|43|[Multiply Strings](https://leetcode.com/problems/multiply-strings/description/)|[python](./solutions/43.md)|medium|
|44|[Wildcard Matching](https://leetcode.com/problems/wildcard-matching/description/)|||
|45|[Jump Game II](https://leetcode.com/problems/jump-game-ii/description/)|||
|46|[Permutations](https://leetcode.com/problems/permutations/description/)|[python](./solutions/46.md)|medium|
|47|[Permutations II](https://leetcode.com/problems/permutations-ii/description/)|[python](./solutions/47.md)|medium|
|48|[Rotate Image](https://leetcode.com/problems/rotate-image/description/)|[python](./solutions/48.md)|medium|
|49|[Group Anagrams](https://leetcode.com/problems/group-anagrams/description/)|[python](./solutions/49.md)|medium|
|50|[Pow(x, n)](https://leetcode.com/problems/powx-n/description/)|[python](./solutions/50.md)|medium|
|51|[N-Queens](https://leetcode.com/problems/n-queens/)|||
|52|[N-Queens II](https://leetcode.com/problems/n-queens-ii/description/)|||
|53|[Maximum Subarray](https://leetcode.com/problems/maximum-subarray/description/)|[python](./solutions/53.md)|easy|
|54|[Spiral Matrix](https://leetcode.com/problems/spiral-matrix/description/)|[python](./solutions/54.md)|medium|
|55|[Jump Game](https://leetcode.com/problems/jump-game/description/)|[python](./solutions/55.md)|medium|
|56|[Merge Intervals](https://leetcode.com/problems/merge-intervals/description/)|[python](./solutions/56.md)|medium|
|57|[Insert Interval](https://leetcode.com/problems/insert-interval/description/)|||
|57|[Length of Last Word](https://leetcode.com/problems/length-of-last-word/)|[python](./solutions/58.md)|easy|
|59|[Spiral Matrix II](https://leetcode.com/problems/spiral-matrix-ii/description/)|[python](./solutions/59.md)|medium|
|60|[Permutation Sequence](https://leetcode.com/problems/permutation-sequence/description/)|||
|61|[Rotate List](https://leetcode.com/problems/rotate-list/)|[python](./solutions/61.md)|medium|
|62|[Unique Paths](https://leetcode.com/problems/unique-paths/description/)|[python](./solutions/62.md)|medium|
|63|[Unique Paths II](https://leetcode.com/problems/unique-paths-ii/)|[python](./solutions/63.md)|medium|
|64|[Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/description/)|[python](./solutions/64.md)|medium|
|65|[Valid Number](https://leetcode.com/problems/valid-number/description/)|||
|66|[Plus One](https://leetcode.com/problems/plus-one/description/)|[python](./solutions/66.md)|easy|
|67|[Add Binary](https://leetcode.com/problems/add-binary/description/)|||
|68|[Text Justification](https://leetcode.com/problems/text-justification/description/)|||
|69|[Sqrt(x)](https://leetcode.com/problems/sqrtx/description/)|[python](./solutions/69.md)|easy|
|70|[Climbing Stairs](https://leetcode.com/problems/climbing-stairs/description/)|[python](./solutions/70.md)|easy|
|71|[Simplify Path](https://leetcode.com/problems/simplify-path/description/)|[python](.solutions/71.md)|medium|
|72|[Edit Distance](https://leetcode.com/problems/edit-distance/description/)|||
|73|[Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/)|[python](./solutions/73.md)|medium|
|74|[Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/description/)|[python](./solutions/74.md)|medium|
|75|[Sort Colors](https://leetcode.com/problems/sort-colors/description/)|[python](./solutions/75.md)|medium|
|76|[Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/description/)|||
|77|[Combinations](https://leetcode.com/problems/combinations/description/)|[python](./solutions/77.md)|medium|
|78|[Subsets](https://leetcode.com/problems/subsets/description/)|[python](./solutions/78.md)|medium|
|79|[Word Search](https://leetcode.com/problems/word-search/description/)|||
|80|[Remove Duplicates from Sorted Array II](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/description/)|||
|81|[Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/description/)|[python](./solutions/81.md)|medium|
|82|[Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/description/)|||
|84|[Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/description/)|||
|85|[Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/description/)|||
|88|[Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/description/)|||
|90|[Subsets II](https://leetcode.com/problems/subsets-ii/description/)|||
|91|[Decode Ways](https://leetcode.com/problems/decode-ways/description/)|||
|96|[Unique Binary Search Trees](https://leetcode.com/problems/unique-binary-search-trees/description/)|||
|98|[Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/description/)|||
|101|[Symmetric Tree](https://leetcode.com/problems/symmetric-tree/description/)|||
|104|[Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/description/)|||
|108|[Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/description/)|||
|110|[Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/description/)|||
|111|[Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/description/)|||
|112|[Path Sum](https://leetcode.com/problems/path-sum/description/)|||
|113|[Path Sum II](https://leetcode.com/problems/path-sum-ii/description/)|||
|115|[Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/description/)|||
|116|[Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/description/)|||
|117|[Populating Next Right Pointers in Each Node II](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/description/)|||
|121|[Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/description/)|||
|122|[Best Time to Buy and Sell Stock II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/description/)|||
|123|[Best Time to Buy and Sell Stock III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/description/)|||
|124|[Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/description/)|||
|125|[Valid Palindrome](https://leetcode.com/problems/valid-palindrome/description/)|||
|126|[Word Ladder II](https://leetcode.com/problems/word-ladder-ii/description/)|||
|127|[Word Ladder](https://leetcode.com/problems/word-ladder/description/)|||
|128|[Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/description/)|||
|130|[Surrounded Regions](https://leetcode.com/problems/surrounded-regions/description/)|||
|133|[Clone Graph](https://leetcode.com/problems/clone-graph/description/)|||
|134|[Gas Station](https://leetcode.com/problems/gas-station/description/)|||
|138|[Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)|||
|139|[Word Break](https://leetcode.com/problems/word-break/)|||
|140|[Word Break II](https://leetcode.com/problems/word-break-ii/description/)|||
|142|[Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/description/)|||
|146|[LRU Cache](https://leetcode.com/problems/lru-cache/description/)|||
|149|[Max Points on a Line](https://leetcode.com/problems/max-points-on-a-line/description/)|||
|150|[Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/description/)|||
|152|[Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/description/)|||
|153|[Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/description/)|||
|154|[Find Minimum in Rotated Sorted Array II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/description/)|||
|155|[Min Stack](https://leetcode.com/problems/min-stack/description/)|||
|157|[Read N Characters Given Read4](https://leetcode.com/problems/read-n-characters-given-read4/description/)|||
|158|[Read N Characters Given Read4 II - Call multiple times](https://leetcode.com/problems/read-n-characters-given-read4-ii-call-multiple-times/description/)|||
|161|[One Edit Distance](https://leetcode.com/problems/one-edit-distance/)|||
|162|[Find Peak Element](https://leetcode.com/problems/find-peak-element/description/)|[python](./solutions/162.md)|medium|
|163|[Missing Ranges](https://leetcode.com/problems/missing-ranges/description/)|||
|168|[Excel Sheet Column Title](https://leetcode.com/problems/excel-sheet-column-title/description/)|||
|171|[Excel Sheet Column Number](https://leetcode.com/problems/excel-sheet-column-number/description/)|||
|173|[Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/description/)|||
|174|[Dungeon Game](https://leetcode.com/problems/dungeon-game/description/)|||
|186|[Reverse Words in a String II](https://leetcode.com/problems/reverse-words-in-a-string-ii/description/)|||
|188|[Best Time to Buy and Sell Stock IV](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/description/)|||
|189|[Rotate Array](https://leetcode.com/problems/rotate-array/description/)|||
|191|[Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/description/)|||
|198|[House Robber](https://leetcode.com/problems/house-robber/)|||
|200|[Number of Islands](https://leetcode.com/problems/number-of-islands/)|||
|201|[Bitwise AND of Numbers Range](https://leetcode.com/problems/bitwise-and-of-numbers-range/description/)|||
|202|[Happy Number](https://leetcode.com/problems/happy-number/description/)|||
|204|[Count Primes](https://leetcode.com/problems/count-primes/description/)|||
|205|[Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/description/)|||
|207|[Course Schedule](https://leetcode.com/problems/course-schedule/description/)|||
|208|[Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/description/)|||
|209|[Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/description/)|||
|210|[Course Schedule II](https://leetcode.com/problems/course-schedule-ii/description/)|||
|211|[Add and Search Word - Data structure design](https://leetcode.com/problems/add-and-search-word-data-structure-design/description/)|||
|212|[Word Search II](https://leetcode.com/problems/word-search-ii/description/)|||
|213|[House Robber II](https://cspiration.com/leetcodeClassification)|||
|214|[Shortest Palindrome](https://leetcode.com/problems/shortest-palindrome/description/)|||
|215|[Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/description/)|||
|216|[Combination Sum III](https://leetcode.com/problems/combination-sum-iii/description/)|||
|217|[Contains Duplicate](https://leetcode.com/problems/contains-duplicate/description/)|||
|218|[The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/description/)|||
|219|[Contains Duplicate II](https://leetcode.com/problems/contains-duplicate-ii/description/)|||
|220|[Contains Duplicate III](https://leetcode.com/problems/contains-duplicate-iii/description/)|||
|221|[Maximal Square](https://leetcode.com/problems/maximal-square/description/)|||
|224|[Basic Calculator](https://leetcode.com/problems/basic-calculator/description/)|||
|225|[Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues/description/)|||
|226|[Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/description/)|||
|227|[Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/description/)|||
|228|[Summary Ranges](https://leetcode.com/problems/summary-ranges/description/)|||
|230|[Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/description/)|||
|231|[Power of Two](https://leetcode.com/problems/power-of-two/description/)|||
|232|[Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/description/)|||
|235|[Lowest Common Ancestor of a Binary Search Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/description/)|||
|236|[Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/description/)|||
|238|[Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/description/)|||
|239|[Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/description/)|||
|240|[Search a 2D Matrix II](https://leetcode.com/problems/search-a-2d-matrix-ii/description/)|||
|241|[Different Ways to Add Parentheses](https://leetcode.com/problems/different-ways-to-add-parentheses/description/)|||
|242|[Valid Anagram](https://leetcode.com/problems/valid-anagram/description/)|||
|244|[Shortest Word Distance II](https://leetcode.com/problems/shortest-word-distance-ii/description/)|||
|245|[Shortest Word Distance III](https://leetcode.com/problems/shortest-word-distance-iii/description/)|||
|249|[Group Shifted Strings](https://leetcode.com/problems/group-shifted-strings/description/)|||
|251|[Flatten 2D Vector](https://leetcode.com/problems/flatten-2d-vector/description/s)|||
|252|[Meeting Rooms](https://leetcode.com/problems/meeting-rooms/description/)|||
|253|[Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/description/)|||
|254|[Factor Combinations](https://leetcode.com/problems/factor-combinations/description/)|||
|256|[Paint House](https://leetcode.com/problems/paint-house/description/)|||
|257|[Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/description/)|||
|261|[Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/description/)|||
|263|[Ugly Number](https://leetcode.com/problems/ugly-number/description/)|||
|264|[Ugly Number II](https://leetcode.com/problems/ugly-number-ii/description/)|||
|265|[Paint House II](https://leetcode.com/problems/paint-house-ii/description/)|||
|268|[Missing Number](https://leetcode.com/problems/missing-number/description/)|||
|269|[Alien Dictionary](https://leetcode.com/problems/alien-dictionary/description/)|||
|270|[Closest Binary Search Tree Value](https://leetcode.com/problems/closest-binary-search-tree-value/description/)|||
|271|[Encode and Decode Strings](https://leetcode.com/problems/encode-and-decode-strings/description/)|||
|273|[Integer to English Words](https://leetcode.com/problems/integer-to-english-words/description/)|||
|274|[H-Index](https://leetcode.com/problems/h-index/description/)|||
|275|[H-Index II](https://leetcode.com/problems/h-index-ii/description/)|||
|276|[Paint Fence](https://leetcode.com/problems/paint-fence/description/)|||
|277|[Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/description/)|||
|278|[First Bad Version](https://leetcode.com/problems/first-bad-version/description/)|||
|279|[Perfect Squares](https://leetcode.com/problems/perfect-squares/description/)|||
|280|[Wiggle Sort](https://leetcode.com/problems/wiggle-sort/description/)|||
|282|[Expression Add Operators](https://leetcode.com/problems/expression-add-operators/description/)|||
|283|[Move Zeroes](https://leetcode.com/problems/move-zeroes/description/)|||
|284|[Peeking Iterator](https://leetcode.com/problems/peeking-iterator/description/)|||
|285|[Inorder Successor in BST](https://leetcode.com/problems/inorder-successor-in-bst/description/)|||
|286|[Walls and Gates](https://leetcode.com/problems/walls-and-gates/description/)|||
|287|[Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/description/)|||
|288|[Unique Word Abbreviation](https://leetcode.com/problems/unique-word-abbreviation/description/)|||
|289|[Game of Life](https://leetcode.com/problems/game-of-life/description/)|||
|290|[Word Pattern](https://leetcode.com/problems/word-pattern/description/)|||
|291|[Word Pattern II](https://leetcode.com/problems/word-pattern-ii/description/)|||
|293|[Flip Game](https://leetcode.com/problems/flip-game/description/)|||
|294|[Flip Game II](https://leetcode.com/problems/flip-game-ii/description/)|||
|295|[Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/description/)|||
|296|[Best Meeting Point](https://leetcode.com/problems/best-meeting-point/description/)|||
|297|[Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/description/)|||
|298|[Binary Tree Longest Consecutive Sequence](https://leetcode.com/problems/binary-tree-longest-consecutive-sequence/description/)|||
|299|[Bulls and Cows](https://leetcode.com/problems/bulls-and-cows/)|||
|300|[Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/description/)|||
|301|[Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/description/)|||
|302|[Smallest Rectangle Enclosing Black Pixels](https://leetcode.com/problems/smallest-rectangle-enclosing-black-pixels/description/)|||
|305|[Number of Islands II](https://leetcode.com/problems/number-of-islands-ii/description/)|||
|307|[Range Sum Query - Mutable](https://leetcode.com/problems/range-sum-query-mutable/description/)|||
|308|[Range Sum Query 2D - Mutable](https://leetcode.com/problems/range-sum-query-2d-mutable/description/)|||
|309|[Best Time to Buy and Sell Stock with Cooldown](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/description/)|||
|311|[Sparse Matrix Multiplication](https://leetcode.com/problems/sparse-matrix-multiplication/description/)|||
|312|[Burst Balloons](https://leetcode.com/problems/burst-balloons/description/)|||
|314|[Binary Tree Vertical Order Traversal](https://leetcode.com/problems/binary-tree-vertical-order-traversal/description/)|||
|316|[Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/description/)|||
|317|[Shortest Distance from All Buildings](https://leetcode.com/problems/shortest-distance-from-all-buildings/description/)|||
|318|[Maximum Product of Word Lengths](https://leetcode.com/problems/maximum-product-of-word-lengths/description/)|||
|322|[Coin Change](https://leetcode.com/problems/coin-change/description/)|||
|323|[Number of Connected Components in an Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/description/)|||
|324|[Wiggle Sort II](https://leetcode.com/problems/wiggle-sort-ii/description/)|||
|325|[Maximum Size Subarray Sum Equals k](https://leetcode.com/problems/maximum-size-subarray-sum-equals-k/)|||
|329|[Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/description/)|||
|334|[Increasing Triplet Subsequence](https://leetcode.com/problems/increasing-triplet-subsequence/description/)|||
|336|[Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/description/)|||
|337|[House Robber III](https://leetcode.com/problems/house-robber-iii/description/)|||
|338|[Counting Bits](https://leetcode.com/problems/counting-bits/description/)|||
|339|[Nested List Weight Sum](https://leetcode.com/problems/nested-list-weight-sum/description/)|||
|340|[Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/description/)|||
|341|[Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/)|||
|346|[Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/description/)|||
|347|[Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/description/)|||
|348|[Design Tic-Tac-Toe](https://leetcode.com/problems/design-tic-tac-toe/description/)|||
|350|[Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/description/)|||
|351|[Android Unlock Patterns](https://leetcode.com/problems/android-unlock-patterns/description/)|||
|352|[Data Stream as Disjoint Intervals](https://leetcode.com/problems/data-stream-as-disjoint-intervals/description/)|||
|353|[Design Snake Game](https://leetcode.com/problems/design-snake-game/description/)|||
|354|[Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/description/)|||
|355|[Design Twitter](https://leetcode.com/problems/design-twitter/description/s)|||
|359|[Logger Rate Limiter](https://leetcode.com/problems/logger-rate-limiter/description/)|||
|361|[Bomb Enemy](https://leetcode.com/problems/bomb-enemy/description/)|||
|362|[Design Hit Counter](https://leetcode.com/problems/design-hit-counter/description/)|||
|364|[Nested List Weight Sum II](https://leetcode.com/problems/nested-list-weight-sum-ii/description/)|||
|367|[Valid Perfect Square](https://leetcode.com/problems/valid-perfect-square/description/)|||
|374|[Guess Number Higher or Lower](https://leetcode.com/problems/guess-number-higher-or-lower/)|||
|375|[Guess Number Higher or Lower II](https://leetcode.com/problems/guess-number-higher-or-lower-ii/description/)|||
|376|[Wiggle Subsequence](https://leetcode.com/problems/wiggle-subsequence/description/)|||
|377|[Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/description/)|||
|378|[Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/description/)|||
|379|[Design Phone Directory](https://leetcode.com/problems/design-phone-directory/description/)|||
|380|[Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/)|||
|381|[Insert Delete GetRandom O(1) - Duplicates allowed](https://leetcode.com/problems/insert-delete-getrandom-o1-duplicates-allowed/)|||
|384|[Shuffle an Array](https://leetcode.com/problems/shuffle-an-array/)|||
|385|[Mini Parser](https://leetcode.com/problems/mini-parser/description/)|||
|389|[Find the Difference](https://leetcode.com/problems/find-the-difference/description/)|||
|394|[Decode String](https://leetcode.com/problems/decode-string/)|||
|398|[Random Pick Index](https://leetcode.com/problems/random-pick-index/)|||