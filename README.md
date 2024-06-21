# 前言 
这是关于《计算机程序的构造和解释》第二版中提到的例子和习题对应的python代码。在ipynb上面实现，所有代码都经过了测试，确保正确。  
# 第1章：构造过程抽象 
## 1.1 程序设计的基本元素 
### 1.1.1 表达式 
### 1.1.2 命名和环境 
### 1.1.3 组合式的求值 
### 1.1.5 过程应用的代换模型 
### 1.1.6 条件表达式和谓词 
#### [练习1.3](chapter1/1.1.ipynb#13-输入三个数为参数返回其中较大的两个数之和) 
#### [练习1.5](chapter1/1.1.ipynb#15-检测解释器采用哪种序求值) 
### 1.1.7 实例：采用牛顿法求平方根 
#### [牛顿法求平方根](chapter1/1.1.ipynb#eg-采用牛顿法求平方根) 
#### [练习1.6](chapter1/1.1.ipynb#16-把if通过cond将它定义为一个常规过程) 
#### [练习1.7](chapter1/1.1.ipynb#17-good_enough函数对于非常大或者非常小的数会失效) 
#### [练习1.8](chapter1/1.1.ipynb#18-求立方根的牛顿法) 
### 1.1.8 过程作为黑箱抽象 
## 1.2 过程与他们所产生的计算 
### 1.2.1 线性的递归和迭代 
#### [利用递归和迭代计算阶乘](chapter1/1.2.ipynb/#eg-利用递归和迭代计算阶乘)
#### [练习1.9](chapter1/1.2.ipynb/#19-两个正整数相加的方法)
#### [练习1.10](chapter1/1.2.ipynb/#110-Ackermann函数)
### 1.2.2 树形递归 
### [斐波那契数列](chapter1/1.2.ipynb/#eg-斐波那契数列)
### [换零钱方式的统计](chapter1/1.2.ipynb/#eg-换零钱方式的统计)
### [练习1.11](chapter1/1.2.ipynb/#111)
### [练习1.12](chapter1/1.2.ipynb/#112-帕斯卡三角形)
### 1.2.3 增长的阶 
### [练习1.14](chapter1/1.2.ipynb/#114-零钱换现)
### [练习1.15](chapter1/1.2.ipynb/#115-弦求值)
### 1.2.4 求幂 
### [求幂](chapter1/1.2.ipynb/#求幂)
### [练习1.16](chapter1/1.2.ipynb/#116-连续求平方迭代快速求幂)
### [练习1.17](chapter1/1.2.ipynb/#117-递归求乘算法)
### [练习1.18](chapter1/1.2.ipynb/#118-迭代求乘算法)
### [练习1.19](chapter1/1.2.ipynb/#119-对数步骤求出斐波那契数列)
### 1.2.5 最大公约数
### [练习1.20](chapter1/1.2.ipynb/#120-最大公约数)
### 1.2.6 实例：素数检测
### [素数检测](chapter1/1.2.ipynb/#素数检测)
### [练习1.21](chapter1/1.2.ipynb/#121-smallest-divisor)
### [练习1.22](chapter1/1.2.ipynb/#122-runtime)
### [练习1.23](chapter1/1.2.ipynb/#123-fast-smallest-divisor)
### [练习1.24](chapter1/1.2.ipynb/#124-runtime-fermat-tet)
### [练习1.25](chapter1/1.2.ipynb/#125)
### [练习1.26](chapter1/1.2.ipynb/#126)
### [练习1.27](chapter1/1.2.ipynb/#127-carmichael-test)
### [练习1.28](chapter1/1.2.ipynb/#128-miller-rabin-test)
## 1.3 用高阶函数做抽象
### 1.3.1 过程作为参数
### [过程作为参数](chapter1/1.3.ipynb/#过程作为参数)
### [练习1.29](chapter1/1.3.ipynb/#129-simpson-rule)
### [练习1.30](chapter1/1.3.ipynb/#130-sum-iteration)
### [练习1.31](chapter1/1.3.ipynb/#131-product)
### [练习1.32](chapter1/1.3.ipynb/#132-accumulate)
### [练习1.33](chapter1/1.3.ipynb/#133-filter)
### 1.3.2 用lambda构造过程
### [练习1.34](chapter1/1.3.ipynb/#134)
### 1.3.3 过程作为一般性的方法
### [通过区间折半寻找方程的根](chapter1/1.3.ipynb/#通过区间折半寻找方程的根)
### [找出函数的不动点](chapter1/1.3.ipynb/#找出函数的不动点)
### [练习1.35](chapter1/1.3.ipynb/#135)
### [练习1.36](chapter1/1.3.ipynb/#136)
### [练习1.37](chapter1/1.3.ipynb/#137)
### [练习1.38](chapter1/1.3.ipynb/#138)
### [练习1.39](chapter1/1.3.ipynb/#139)
### 1.3.4 过程作为返回值
### [牛顿法](chapter1/1.3.ipynb/#牛顿法)
### [练习1.40](chapter1/1.3.ipynb/#140)
### [练习1.40](chapter1/1.3.ipynb/#140)
### [练习1.41](chapter1/1.3.ipynb/#141)
### [练习1.42](chapter1/1.3.ipynb/#142)
### [练习1.43](chapter1/1.3.ipynb/#143)
### [练习1.44](chapter1/1.3.ipynb/#144)
### [练习1.45](chapter1/1.3.ipynb/#145)
### [练习1.46](chapter1/1.3.ipynb/#146)
# 第2章 构造数据抽象
## 2.1 数据抽象导引
### 2.1.1 实例：有理数的算术运算
### [练习2.1](chapter2/2.1.ipynb/#21)
### 2.1.2 抽象屏障
### [练习2.2](chapter2/2.1.ipynb/#22)
### [练习2.3](chapter2/2.1.ipynb/#23)
### 2.1.3 数据意味着什么
### [练习2.4](chapter2/2.1.ipynb/#24)
### [练习2.5](chapter2/2.1.ipynb/#25)
### [练习2.6](chapter2/2.1.ipynb/#26)
### 2.1.4 扩展练习：区间算术
### [练习2.7](chapter2/2.1.ipynb/#27)
### [练习2.8](chapter2/2.1.ipynb/#28)
### [练习2.9](chapter2/2.1.ipynb/#29)
### [练习2.10](chapter2/2.1.ipynb/#210)
### [练习2.11](chapter2/2.1.ipynb/#211)
### [练习2.12](chapter2/2.1.ipynb/#212)
## 2.2 层次性数据和闭包性质
### 2.2.1 序列的表示
### [练习2.17](chapter2/2.2.ipynb/#217)
### [练习2.18](chapter2/2.2.ipynb/#218)
### [练习2.19](chapter2/2.2.ipynb/#219)
### [练习2.20](chapter2/2.2.ipynb/#220)
### [对表的映射](chapter2/2.2.ipynb/#对表的映射)
### [练习2.21](chapter2/2.2.ipynb/#221)
### [练习2.22](chapter2/2.2.ipynb/#222)
### [练习2.23](chapter2/2.2.ipynb/#223)
### 2.2.2 层次性结构
### [层次性结构](chapter2/2.2.ipynb/#层次性结构)
### [练习2.24](chapter2/2.2.ipynb/#224)
### [练习2.25](chapter2/2.2.ipynb/#225)
### [练习2.26](chapter2/2.2.ipynb/#226)
### [练习2.27](chapter2/2.2.ipynb/#227)
### [练习2.28](chapter2/2.2.ipynb/#228)
### [练习2.29](chapter2/2.2.ipynb/#229)
### [对树的映射](chapter2/2.2.ipynb/#对树的映射)
### [练习2.30](chapter2/2.2.ipynb/#230)
### [练习2.31](chapter2/2.2.ipynb/#231)
### [练习2.32](chapter2/2.2.ipynb/#232)
### 2.2.3 序列作为一种约定的界面
### [示例代码](chapter2/2.2.ipynb/#示例代码)
### [练习2.33](chapter2/2.2.ipynb/#233)
### [练习2.34](chapter2/2.2.ipynb/#234)
### [练习2.35](chapter2/2.2.ipynb/#235)
### [练习2.36](chapter2/2.2.ipynb/#236)
### [练习2.37](chapter2/2.2.ipynb/#237)
### [练习2.38](chapter2/2.2.ipynb/#238)
### [练习2.39](chapter2/2.2.ipynb/#239)
### [嵌套映射](chapter2/2.2.ipynb/#嵌套映射)
### [练习2.40](chapter2/2.2.ipynb/#240)
### [练习2.41](chapter2/2.2.ipynb/#241)
### 2.2.4 实例：一个图形语言
## 2.3 符号数据
### 2.3.1 引号
### [练习2.53](chapter2/2.2.ipynb/#253)
### [练习2.54](chapter2/2.2.ipynb/#254)
### 2.3.2 实例：符号求异

### 2.3.3 实例：集合的表示
### [集合作为未排序的表](chapter2/2.2.ipynb/#集合作为未排序的表)
### [练习2.59](chapter2/2.2.ipynb/#259)
### [练习2.60](chapter2/2.2.ipynb/#260)
### [集合作为排序的表](chapter2/2.2.ipynb/#集合作为排序的表)
### [练习2.61](chapter2/2.2.ipynb/#261)
### [练习2.62](chapter2/2.2.ipynb/#262)
### [集合作为二叉树 ](chapter2/2.2.ipynb/#集合作为二叉树 )
### [练习2.63](chapter2/2.2.ipynb/#263)
### [练习2.64](chapter2/2.2.ipynb/#264)
### [练习2.65](chapter2/2.2.ipynb/#265)
### [练习2.66](chapter2/2.2.ipynb/#266)
### 2.3.4 实例：Huffman编码树 
### [huffman树](chapter2/2.2.ipynb/#huffman树)
### [练习2.67](chapter2/2.2.ipynb/#267)
### [练习2.68](chapter2/2.2.ipynb/#268)
### [练习2.69](chapter2/2.2.ipynb/#269)
### [练习2.70](chapter2/2.2.ipynb/#270)
### [练习2.71](chapter2/2.2.ipynb/#271)
### [练习2.72](chapter2/2.2.ipynb/#272)
## 2.4 抽象数据的多重表示
### 2.4.1 复数的表示
### 2.4.2 带标志数据
### 2.4.3 数据导向的程序设计和可加性
## 2.5 带有通用型操作的系统
### 2.5.1 通用型算术运算
### 2.5.2 不同类型数据的组合
### 2.5.3 实例：符号代数  




