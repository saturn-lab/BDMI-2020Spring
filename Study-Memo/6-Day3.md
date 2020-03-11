# 第三次课程小结
## 快速排序与桶排序
+ 快速排序的难点在于确定轴点（partition）
+ 桶排序并非比较排序，虽然时间复杂度O(n)，但空间占用太大
+ 比较排序的时间复杂度最优也是O(nlogn)
## 数据结构
+ 二叉搜索树，元素从左到右递增，树高期望logn
+ 但一般很难实现logn，需要其他方法来平衡树高
+ B树可以在一个节点放多个元素
+ 红黑树根据一定的规则可以避免最坏情况的出现，从而实现logn高度