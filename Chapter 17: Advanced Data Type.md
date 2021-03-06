# Advanced Data
---
1. 链表：
    * 链表是一个列表，其中的每一项都包含描述何处能找到下一项的信息；
    * 头指针（head pointer）：指向数据项链表的第一项；
2. 抽象数据类型(Abstract Data Type)：
    * 一个类型指定两类信息：一个属性集和一个操作集；
    * 如何定义一个新的数据类型：
        * 提供存储数据的方式；
        * 提供操作数据的方式；
    * 定义新类型从抽象到具体的过程：
        * 为类型的属性和可对类型执行的操作提供一个抽象的描述（ADT）；
        * 开发一个实现该ADT的编程接口；
        * 编写代码实现这个接口；
3. 队列、环形队列；
4. 如何访问列表中的成员：
    * 随机访问：可以通过索引直接访问任意元素；
    * 顺序访问：必须从列表头开始，逐个节点的移动到所需的节点处；
5. 如何选择列表类型：
    * 链表：支持频繁的插入和删除元素，不需要经常搜索时选择；
    * 数组：经常需要搜索，不需要频繁的插入和删除；
    * 二叉搜索树：既支持频繁的插入和删除元素又支持频繁搜索的数据类型；
6. 二叉搜索树：
    * 一种结合了折半搜索策略的链接结构；
    * 树中的每一个节点都包含一个项目和两个指向其他节点的指针；
    * 左节点的项目是父节点中项目的前序项；
    * 右节点中的项目是父节点中项目的后序项；
    * 二叉搜索树只在满员时效率最高；
                        
