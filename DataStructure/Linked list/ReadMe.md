
# Linked List
在计算机科学里，链表是数据元素的线性集合。链表中的线性顺序不是指内存中按顺序排列的物理位置，而是每一个元素指向下一个元素的位置。最简单的链表形式是单向链表（single linked list）每一个结点都由数据和指向下一个元素的指针（pointer）/引用（reference）/链接（link）组成。这种结构可以在<b>迭代</b>中对序列中的任意位置进行有效的数据插入和移除。另外还有双向链表（double linked list），也就是除了数据和下一个结点的引用之外还有上一个结点的引用。

## 复杂度
时间复杂度：

| Access	 | Search	 | Insertion	 | Deletion |
|:------:|:------:|:---------:|:--------:|
|  O(n)	  |  O(n)	  |    O(1)	   |   O(1)   |

空间复杂度：O(n)

## Array VS Linked List
[![FCExqx.md.png](https://s1.ax1x.com/2018/11/21/FCExqx.md.png)](https://imgchr.com/i/FCExqx)

## Reference:
- https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/linked-list
- https://www.youtube.com/watch?v=9YddVVsdG5A
