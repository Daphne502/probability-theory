# 1.1 随机试验与随机事件

## 随机试验
随机试验特点：
- 可重复性
- 多结果性
- 不确定性
  
类似于扔硬币这类**事件**，我们称作**随机试验**（experiment），用**E**来表示

## 样本空间
试验E的所有可能结果组成的<u>集合</u>成为E的**样本空间**
用**Ω**表示
每一种可能的结果记作**样本点**，用**ω**表示，是一个元素的概念

## 各类事件
==事件是一个集合的概念==
必然事件：样本空间Ω
基本事件：一个样本点组成的集合(不能再细分的，例如摇骰子事件里摇出1这个事件)
随机事件：是Ω的子集
不可能事件：空集$\emptyset$，e.g.摇骰子出现7点，不含任何样本点
事件A发生：属于A任一样本点出现
$\emptyset \subset A \subset \Omega$

## 事件的运算
1. 包含：$A \subset B$
   A发生必然导致B发生
2. 并(和)：$A \cup B$
   A，B至少有一个发生
3. 交(积)：$A \cap B$ 或 $AB$
   A，B同时发生
4. 事件的差：$A-B$ 或$A \setminus B$
   A发生而B不发生
5. 互不相容（互斥）：$AB = \emptyset$
   A,B不能同时发生
6. 对立事件：$A \cup B = \Omega$ 且 $A \cap B = \emptyset$
    把全集一分为二
    A的对立事件记作 $\overline{A}$

> 互不相容与对立之间的关系
>1. A，B对立 $\Rightarrow$ A，B互不相容，反之不然
>2. 对立，2个事件；互不相容，多个事件
>3. $\Omega = \{\omega_1,\omega_2\}$ 对立
>   $\Omega = \{\omega_1,\omega_2······\omega_n\}$ n>2 互不相容
>4. A，B互不相容 $\nRightarrow$  $\overline{A}$ 与 $\overline{B}$ 相容或不相容
>   A与B对立 $\Rightarrow$ $\overline{A}$ 与 $\overline{B}$对立
7. 完备事件组：
   （样本空间的划分）
   $$A_1,A_2······A_n
    \left\{
\begin{aligned}
A_i \cap A_j = \emptyset \\
\sum_{i=1}^{n} A_i = \Omega
\end{aligned}
\right.$$

## 运算律
1. 交换律：$$A \cup B = B \cup A
    \qquad A \cap B = B \cap A$$
2. 结合律：$$((A \cup B) \cup C) = A \cup (B \cup C) \quad
   ((A \cap B) \cap C) = A \cap (B \cap C)$$
3. 分配律：$$((A \cup B) \cap C) = (A \cap C) \cup (B \cap C) \quad
   ((A \cap B) \cup C) = (A \cup C) \cap (B \cup C)$$
4. 对偶律：$$\overline{A \cup B} = \overline{A} \cap \overline{B} \qquad \overline{A \cap B} = \overline{A} \cup \overline{B}$$