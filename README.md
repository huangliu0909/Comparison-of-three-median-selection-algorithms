# Comparison-of-three-median-selection-algorithms

概述  
分别三种算法求解如下计算问题。方法1：先排序后直接抽取；方法2：《算法设计与分析》第3章讲授的线性时间中位数选取算法；方法3：本课程第2章讲授的lazySelect随机算法。  
输入：实数集合R={r1,r2,…,rn},正整数k{1,2,…,n}  
输出：min(R,k)—R中第k小的元素  
整个工程应包含数据生成、排序选择方法、线性时间选取算法，lazySelect方法，实验在Main函数中通过调用相应方法进行。各模块应该独立实现在源代码文件中  

阐述  
1.实现先排序后直接抽取算法  
2.实现线性时间选取算法  
3.lazySelect随机算法  
4.随机产生服从均匀分布、正态分布、Zipff分布的数据和均匀选取的k，开展实验，比较三种算法的性能和扩展性  

数据：  
随机产生服从均匀分布、正态分布、Zipff分布的数据  
查找中位数
