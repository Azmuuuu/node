## 数组

数组是一种线性表的数据结构。它用一组连续的内存空间，来存储一组具有相同类型的数据。（下标随机访问）

## 线性表

每个线性表上的数据最多只有前后两个方向

## 非线性表

非线性表上数据不只是简单的前后关系

## 低效插入和删除

数据搬移

## 数组反问越界

c语言

## 大部分编程语言数组下标从0开始

下标随机访问时会少一次计算

```
下标从0开始：
a[k]_address = base_address + k * type_size
下标从1开始
a[k]_address = base_address + (k-1)*type_size
```

## 容器

编程语言对数组的封装

## 时间复杂度

插入、删除：O(n)

查找、修改：O(1)