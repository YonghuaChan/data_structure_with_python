# 3-链表

#### 为什么需要链表 <a id="&#x4E3A;&#x4EC0;&#x4E48;&#x9700;&#x8981;&#x94FE;&#x8868;"></a>

顺序表的构建需要预先知道数据大小来申请连续的存储空间，而在进行扩充时又需要进行数据的搬迁，所以使用起来并不是很灵活。

链表结构可以充分利用计算机内存空间，实现灵活的内存动态管理。

#### 链表的定义 <a id="&#x94FE;&#x8868;&#x7684;&#x5B9A;&#x4E49;"></a>

链表（Linked list）是一种常见的基础数据结构，是一种线性表，但是不像顺序表一样连续存储数据，而是在每一个节点（数据存储单元）里存放下一个节点的位置信息（即地址）。

![&#x5355;&#x5411;&#x94FE;&#x8868;&#x56FE;&#x793A;](../.gitbook/assets/image%20%288%29.png)

