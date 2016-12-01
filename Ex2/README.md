
题目2：编写MapReduce，统计`/user/hadoop/mapred_dev/ip_time` 中去重后的IP数，越节省性能越好。（35分）

---
Reduce input groups=1218
一共1218个
用了wordcount 的思路，以IP为Key，个数为value，因为相同的Key会放在一个桶里，相当于去重了，所以reduce输出的行数就是IP数。
