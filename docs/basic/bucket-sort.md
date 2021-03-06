计数排序也称桶排序，可以在 $O(n)$ 的时间复杂度内对数组进行排序，但是它的空间复杂度与需要排序的数组的值域相关。

但实际操作时，由于时空同阶，时间复杂度应为 $O(\max\left(n,U\right))$ ，其中 $U$ 代表数组元素的值域大小。

!!! warning "注"
    注意区分 **基数排序** 与 **桶排序** 

算法流程就是记录每一个数出现了多少次，然后从小到大依次输出。

一般考虑的是某一范围内的整数，但是计数排序也可以和 [离散化](/misc/discrete) 一起使用，来对浮点数、大整数进行排序。
