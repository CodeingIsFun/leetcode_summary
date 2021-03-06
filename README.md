# Leetcode总结
HELLO，这里是Kevinlee21，

本开源项目用于总结自己和小伙伴刷leetcode算法题，使用的语言为JavaScript（由kevinlee21编写），python（由WJH编写）

目前小组成员有：[kevinlee21(lee.x.x)](https://github.com/lxxxxxxx21)，[Tranfer(Janhui Wang)](https://github.com/Xtuxiaojian)

目前按照分类有：

+ [每日一题](https://github.com/lxxxxxxx21/Leetcode_summary/tree/master/daily "From 2020/5/27")
+ [精选TOP面试题](https://github.com/lxxxxxxx21/Leetcode_summary/tree/master/TOP_interview)
+ [two-points【双指针】](https://github.com/lxxxxxxx21/Leetcode_summary/tree/master/two-points)
+ [DP【动态规划】](https://github.com/lxxxxxxx21/Leetcode_summary/tree/master/DP)
+ [Binary_tree【二叉树】](https://github.com/lxxxxxxx21/Leetcode_summary/tree/master/Binary_tree)
+ [string【字符串】](https://github.com/lxxxxxxx21/Leetcode_summary/tree/master/string)

******

**每日一题**（FROM 2020/5/27）

|   编号   |                             题目                             |  难度  |                             解法                             |                           图文思路                           | 日期 | beats Runtime |
| :------: | :----------------------------------------------------------: | :----: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--: | ------------- |
|   974    | [和可被K整除的子数组](https://leetcode-cn.com/problems/subarray-sums-divisible-by-k/) | Medium | [前缀和](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/daily/974/solution2.js) |                             暂无                             | 5/27 | 100%          |
|   394    | [ 字符串解码](https://leetcode-cn.com/problems/decode-string/) | Medium | [栈](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/daily/394/solution.js) |                             暂无                             | 5/28 | 17.45%        |
|   198    |  [打家劫舍](https://leetcode-cn.com/problems/house-robber/)  |  Easy  | [DP](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/daily/198/solution.js) | [点击进入](https://mp.weixin.qq.com/s/sQ9Ogvvt_ALGaqLTdqL1hg) | 5/29 | 13.60%        |
|    84    | [柱状图中最大的矩形](https://leetcode-cn.com/problems/largest-rectangle-in-histogram/) |  Hard  | [栈](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/daily/84/solution.js) |                             暂无                             | 5/30 | 53.62%        |
|   101    | [对称二叉树](https://leetcode-cn.com/problems/symmetric-tree/) |  Easy  | [栈](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/daily/101/solution.js) |                             暂无                             | 5/31 | 77.97%        |
|   1431   | [拥有最多糖果的孩子](https://leetcode-cn.com/problems/kids-with-the-greatest-number-of-candies/) |  Easy  | [数组](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/daily/1431/solution.js) |                             暂无                             | 6/1  | 60.9%         |
| 面试题64 | [求1+2+…+n](https://leetcode-cn.com/problems/qiu-12n-lcof/)  | Medium | [快速乘(JS版本)](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/daily/面试题64/solution.js)/[快速乘(python版本)](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/daily/面试题64/solution.py) |                             暂无                             | 6/2  | 54.4%         |
|   837    |   [新21点](https://leetcode-cn.com/problems/new-21-game/)    | Medium | [DP(python版本)](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/daily/837/solution.py) | [点击进入](https://mp.weixin.qq.com/s?__biz=MzIzNTU0MDY0Mw==&mid=2247483704&idx=1&sn=b6a43295f5434963f1a84524ecef438b&chksm=e8e4d8f4df9351e25657294924b9efd73f14b7cdaadf2cbb17df8215e8a62baa5c8518d197db&token=1309723332&lang=zh_CN#rd) | 6/3  | 99.2%         |

******

**精选TOP 面试题**

| 编号 |                             题目                             |  难度  |                             解法                             | 图文思路 | beats Runtime |
| :--: | :----------------------------------------------------------: | :----: | :----------------------------------------------------------: | :------: | :-----------: |
| 289  | [ 生命游戏](https://leetcode-cn.com/problems/game-of-life/)  | Medium | [模拟+位运算](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/289/solution.js) |   暂无   |    65.36%     |
| 238  | [除自身以外数组的乘积](https://leetcode-cn.com/problems/product-of-array-except-self/) | Medium | [数组](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/238/solution1.js) |   暂无   |    87.33%     |
| 131  | [分割回文串](https://leetcode-cn.com/problems/palindrome-partitioning/) | Medium | [DP + 回溯](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/131/solution.js) |   暂无   |    29.64%     |
| 208  | [实现 Trie (前缀树)](https://leetcode-cn.com/problems/implement-trie-prefix-tree/) | Medium | [Dictionary_Tree](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/208/solution.js) |   暂无   |    15.41%     |
|  73  | [矩阵置零](https://leetcode-cn.com/problems/set-matrix-zeroes/) | Medium | [数组](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/73/solution.js) |   暂无   |    52.59%     |
| 230  | [二叉搜索树中第K小的元素](https://leetcode-cn.com/problems/kth-smallest-element-in-a-bst/) | Medium | [Binary_tree](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/230/solution.js) |   暂无   |    32.17%     |
| 279  | [完全平方数](https://leetcode-cn.com/problems/perfect-squares/) | Medium | [BFS](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/279/solution.js) |   暂无   |    31.51%     |
| 347  | [前 K 个高频元素](https://leetcode-cn.com/problems/top-k-frequent-elements/) | Medium | [桶排序](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/347/solution.js) |   暂无   |    20.81%     |
| 215  | [数组中的第K个最大元素](https://leetcode-cn.com/problems/kth-largest-element-in-an-array/) | Medium | [堆](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/215/solution.js) |   暂无   |     5.02%     |
| 328  | [奇偶链表](https://leetcode-cn.com/problems/odd-even-linked-list/) | Medium | [链表](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/328/solution.js) |   暂无   |    12.36%     |
| 454  |   [四数相加 II](https://leetcode-cn.com/problems/4sum-ii/)   | Medium | [Hash_Map](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/TOP_interview/454/solution.js) |   暂无   |    64.85%     |



******

**双指针**

| 编号 |                             题目                             | 难度 |                             解法                             |                           图文思路                           | beats Runtime |
| :--: | :----------------------------------------------------------: | :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-----------: |
| 167  | [两数之和 II - 输入有序数组](https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/) | Easy | [双指针](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/two-points/167/solution.js) | [点击进入](https://mp.weixin.qq.com/s/17fr1jqHkTgvblx-d6fZgA) |    10.66%     |
|  76  | [最小覆盖子串](https://leetcode-cn.com/problems/minimum-window-substring/) | Hard | [位运算+Hash](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/two-points/76/solution.js) |                             暂无                             |    56.63%     |



**动态规划**

| 编号 |                             题目                             |  难度  |                             解法                             | 图文思路 | beats Runtime |
| :--: | :----------------------------------------------------------: | :----: | :----------------------------------------------------------: | :------: | :-----------: |
| 131  | [打家劫舍 II](https://leetcode-cn.com/problems/house-robber-ii/) | Medium | [DP](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/DP/131/solution.js) |   暂无   |    33.91%     |
|      |                                                              |        |                                                              |          |               |



**二叉树**

| 编号 |                             题目                             |  难度  |                             解法                             | 图文思路 | beats Runtime |
| :--: | :----------------------------------------------------------: | :----: | :----------------------------------------------------------: | :------: | :-----------: |
| 337  | [打家劫舍 III](https://leetcode-cn.com/problems/house-robber-iii/) | Medium | [DFS](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/Binary_tree/337/solution.js) |   暂无   |     8.04%     |
|      |                                                              |        |                                                              |          |               |

**字符串**

| 编号 |                             题目                             |  难度  |                             解法                             |                           图文思路                           | beats Runtime |
| :--: | :----------------------------------------------------------: | :----: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-----------: |
|  8   | [字符串转换整数 (atoi)](https://leetcode-cn.com/problems/string-to-integer-atoi/) | Medium | [DFA(有限状态机)](https://github.com/lxxxxxxx21/Leetcode_summary/blob/master/string/8/solution.js) | [点击进入](https://mp.weixin.qq.com/s?__biz=MzIzNTU0MDY0Mw==&mid=2247483687&idx=1&sn=111c891298461052f45fc058aaa3cc60&chksm=e8e4d8ebdf9351fdf1df06033be4a066ceaaf857bee23658f4e2258f915b2ffa9a8732bcaa7a&token=1404226965&lang=zh_CN#rd) |    13.61%     |
|      |                                                              |        |                                                              |                                                              |               |

