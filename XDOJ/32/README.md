标题:
角谷定理

类别:

时间限制:
2 S

内存限制:
10000 Kb

问题描述:	

角谷定理定义如下：
对于一个大于1的整数n，如果n是偶数，则n = n / 2。如果n是奇数，则n = 3 * n +1，反复操作后，n一定为1。
例如输入22的变化过程： 22 ->11 -> 34 -> 17 -> 52 -> 26 -> 13 -> 40 -> 20 -> 10 -> 5 -> 16 -> 8 -> 4 -> 2 -> 1，数据变化次数为15。
输入一个大于1的整数，求经过多少次变化可得到自然数1。

输入说明	
输入为一个整数n，1<n<100000。

输出说明	
输出变为1需要的次数

输入样例	
样例1输入
22
样例2输入
33

输出样例
样例1输出	
15
样例2输出
26