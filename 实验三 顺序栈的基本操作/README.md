# 实验三 顺序栈的基本操作

## 基础操作
设计字符顺序栈的基本运算程序，并用相关数据进行测试

## 拓展设计
设计一个算法，利用顺序栈的基本运算删除栈st中所有值为e的元素（这样的元素可能有多个），并且保持其他元素次序不变。并用相关数据进行测试。

算法思路：给定栈st，建立一个临时栈tmpst并初始化。退栈st的所有元素x，当x 不为e时将其进栈到tmpst中。将tmpst的所有元素退栈并进栈到st中。最后销毁临时栈tmpst。




