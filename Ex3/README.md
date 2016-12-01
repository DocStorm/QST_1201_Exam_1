题目3：编写MapReduce，统计这两个文件

`/user/hadoop/mapred_dev_double/ip_time`

`/user/hadoop/mapred_dev_double/ip_time_2`

当中，重复出现的IP的数量(40分)

---
代码与练习二 的一样，运行第一份数据得到去重后的IP数1218个，运行第二份得到IP为1249个；
把两份数据一起输入，得到两份数据一起去重的IP为1917个；
所以重复的IP数量为1218+1249-1917=550个。
