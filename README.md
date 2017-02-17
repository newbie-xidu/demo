#冒泡排序

**时间复杂度 O(n2)，稳定**

每两个相邻的元素比较大小，大的放后面

#快速排序

**时间复杂度 O(n㏒?n)，不稳定**

找一个基准值，遍历数组将数组中小于基准值的数组成一个数组放在基准值左边，大于基准值的数组成一个数组放在基准值右边，再让分别让左边数组和右边数组调用函数quickSort。

#插入排序

**时间复杂度为O(n2)，稳定**

在数组中选择一个基准值放在新数组里，然后依次用数组中的数与之作比较，比其小的放在新数组的元素左边，比其大的放在值的右边，第二次与之作比较完还要再进行一次循环，判断它的大小（与新数组最后一个值或者第一个值比较），使其放在合适的位置。

#直接选择排序

**时间复杂度为O(n2),不稳定**

遍历数组，找到最小的数的下标，然后判断其是不是第一个数，如果不是更第一个数交换位置，以此类推。这样选择排序的每个最小值的筛选.只需要一次元素的交换。

#归并排序

**时间复杂度为O(n㏒?n),稳定**

将已有序的子序列合并，得到完全有序的序列；即先使每个子序列有序，再使子序列段间有序。若将两个有序表合并成一个有序表，称为二路归并。