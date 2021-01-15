# NetWorkProgramming

SQL原理及优化

本Repo主要是学习[B站诸葛大佬的视频](https://www.bilibili.com/video/BV1xh411Z79d?from=search&seid=13825300358552977702)

记笔记，写代码，做心得总结

# P1&P2 

**索引**是帮助MySQL高效获取数据的排好序的数据结构

**索引数据结构：**

二叉树

红黑树

Hash表

B-Tree

[](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)

MySql早期有尝试过二叉树数据结构，但是二叉树在最差的情况下，已经退化成链表了，复杂度直接O(n)

红黑树是二叉平衡树，相对于二叉树更优，但是平衡消耗也会比较大,而且树的高度也会很高...

最后MySql用的是B+树，为什么呢？因为对于查找来说，控制树的高度对于效率很重要，多点横向结点能存储更多的元素就可以了...



