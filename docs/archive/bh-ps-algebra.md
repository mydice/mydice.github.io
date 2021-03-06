
_玻海同人本《无解》习题集_

***高等代数***

有多项式的那些题我是对着某本高等代数与解析几何教材（哪本我忘了，随便网上找的）的课后习题编的，其它的题我应该是对着目录诌的或者从记忆里搜索出来的。

第3题的灵感来源于一道课后习题：证明圆上或者有无穷多个有理点或者至多两个有理点。

第40题我一开始就打算要放特殊日期之类的，然后凑着凑着凑出一个答案，大概可以算彩蛋。凑了第40题之后，当然要凑一个CP题，于是有了第41题。凑数的时候很高兴，凑完了之后怀疑这样是不是有点俗。

51题和52题，为了能共用矩阵，并且让答案都落在那300个数里，我很是花了一些功夫。

---

3. 我们称二维直角坐标系$XOY$中的一个点为有理点当且仅当该点的横坐标和纵坐标均为有理数。已知直角坐标系$XOY$中的圆$C$圆心为$(9+19\sqrt{41},101+19\sqrt{41})$且$(1922,999)$是圆上的点，试求该圆上除点$(1922,999)$外所有有理点的横纵坐标之和。<!--2921-->


35. 设实系数多项式$f(x)=\sum_{i=0}^{n} a_i x^i$，且$f'(x)|f(x)$。已知$n=50$，$a_n=1$，$a_0=1$，求$a_{n-2}$的值。
<!--n=(26,41,48,50,59,64,67), 答案=(325,820,1128,1225,1711,2016,2211); hint: n次多项式有n重根的充要条件是多项式能被其导数整除。-->

36. 设$f(x)=x^3+1$，$g(x)=x^2+1$。已知$u(x)$，$v(x)$是满足$u(x)f(x)+v(x)g(x) = 1$的次数最小的多项式。求$u(x)-v(x)$在$x=34$时的值。
<!--x=(20,34,42,44,64),答案(220,612,924,1012,2112) hint: 辗转相除法
$u(x) = (x+1)/2$,$v(x) = -(x^2+x-1)/2$-->

37. 已知$8$次实系数多项式$L(x)=\sum_{n=0}^{8} a_n x^n$满足$L(i) = 2*i^{8}+(-1)^{1+i} 9!, \,i=1,2,\cdots,9.$
求$a_{8}$的值。<!--2306-->

38. 设$A$, $B$, $C$是二维直角坐标系中的三个点，它们的坐标分别为$(0,0)$, $(19,32)$和$(22,70)$。求以这三个点为顶点的三角形的面积。<!--313-->

39. 设$A$, $B$, $C$, $D$是三维直角坐标系中的四个点，它们的坐标分别为$(0,0,0)$, $(19,0,19)$, $(0,30,0)$和$(22,0,41)$。求以这四个点为顶点的四面体的体积。<!--1805-->

40. 试求以下行列式的值：<!--520-->
    $$
    \left|
    \begin{array}{cccc}
        1 & 0 & 0 & 7 \\
        0 & 8 & 0 & 0 \\
        0 & 0 & 8 & 5 \\
        0 & 0 & -5 & 5
    \end{array}
    \right|
    $$

41. 试求以下行列式的值：<!--1314-->
    $$
    \left|
    \begin{array}{cccc}
        1 & 2 & 0 & 5 \\
        0 & 9 & 0 & 0 \\
        0 & 0 & 0 & -2 \\
        0 & 0 & 73 & 1
    \end{array}
    \right|
    $$
    
42. 试求以下行列式的值。<!--1008--><!--Vandermonde determinant-->
$$
        \left|\begin{array}{cccc}
        1 & 1 & 1 & 1 \\[9pt]
        \dfrac{1922}{2 \times 19} & \dfrac{1941}{2 \times 19} & \dfrac{1962}{2 \times 19} & \dfrac{1976}{2 \times 19} \\[9pt]
       \Big(\dfrac{1922}{3\times 5\times 7}\Big)^2 & \Big(\dfrac{1941}{3\times 5\times 7}\Big)^2 & \Big(\dfrac{1962}{3\times 5\times 7}\Big)^2 & \Big(\dfrac{1976}{3\times 5\times 7}\Big)^2 \\[9pt]
        1922^3 & 1941^3 & 1962^3 & 1976^3
    \end{array}\right|
$$




44. 向量组的秩指向量组中的任一极大线性无关组所含有的向量个数。设$a_1,a_2,\cdots,a_{2917}$是互不相同的数，求向量组
$$\alpha_i= (1,a_i,a_i^2,\cdots,a_i^{2918}),\quad i=1,2,\cdots,2917$$
的秩。<!--2917-->

45. 设$a_1,a_2,\cdots,a_{2918}$是互不相同的数，求向量组
$$\alpha_i= (1,a_i,a_i^2,\cdots,a_i^{2917}),\quad i=1,2,\cdots,2918$$
的秩。<!--2918-->

46. 一个矩阵$A$的列秩是$A$的线性独立的纵列的极大数目；行秩是$A$的线性独立的横行的极大数目。矩阵的列秩与行秩总相等，因此它们可以简单地称作矩阵的秩，我们用符号${\rm rank(A)}$表示这个数。用$A(i,j)$表示矩阵$A$的第$i$行第$j$列的元素，假设一个$3020\times 3020$的方阵$A$满足
    $$A(2k-1,2k) = k,\quad A(2k,2k-1) = \dfrac{1}{k},\quad k = 1,2,\cdots, 1510,$$
    而$A$的其他元素均为$0$。我们用$I_{3020}$表示$3020\times 3020$的单位矩阵，试求${\rm rank}(A+I_{3020})+{\rm rank}(A-I_{3020})$。<!--3020-->
<!--hint: A^2 = I-->

47. 一个$n\times n$的矩阵$A$的迹，是指$A$的主对角线上各个元素的总和。现有$3\times 3$的矩阵$A$，其第$i$行第$j$列的元素为
$$a_{ij} = i+2*j+5,\, i=1,2,3, \, j = 1,2,3$$
求$AA^T$(这里$A^T$表示$A$的转置)的迹。
<!--1119-->

48. 一个$n \times n$的矩阵$A$具有如下形式：
    $$
        \left(\begin{array}{ccccc}
        1941 & 19 & 19 & \cdots & 19 \\
        19 & 1941 & 0 & \cdots & 0 \\
        19 & 0 & 1941 & \cdots & 0 \\
        \vdots &\vdots & \vdots & \vdots &\vdots \\
        19 & 0 & 0 & \cdots & 1941
    \end{array}\right),
    $$
    即：对角线全为$1941$，第一行和第一列除去第一个元素全为$19$，其余元素均为零。当$n=17$时，求矩阵$A$的最大特征值。<!--2017 Solution:
\det(A-\lambda I) = (a-\lambda)^{n-2}*((a-\lambda)^2-(n-1)bc)-->

49. 已知$A$和$B$都是$2\times 3017$的矩阵：
    $$
    \begin{aligned}
       A&=\left(\begin{array}{ccccc}
            1 & 2 & 3 & \cdots & 3017 \\
            3017 & 3016 & 3015 & \cdots & 1
        \end{array}\right),\\[9pt]
       B&=\left(\begin{array}{ccccc}
            1 & 1 & 1 & \cdots & 1 \\
            2 & 2 & 2 & \cdots & 2
        \end{array}\right).
    \end{aligned}
    $$
    请问$0$是矩阵$A^T B$的几重特征值？<!--3016-->


50. 给定$1941 \times 1941$的矩阵如下，试求矩阵$A^{19}$上三角部分（含对角线）所有元素的和。<!--1922-->
$$
        A=\left(\begin{array}{ccccc}
        0 & 1 & 0 & \cdots & 0 \\
        0 & 0 & 1 & \cdots & 0 \\
        \vdots & \vdots & \vdots & \vdots & \vdots \\
        0 & 0 & 0 & \cdots & 1 \\
        1 & 0 & 0 & \cdots & 0
    \end{array}\right).
$$

51. 给定矩阵$A$如下：
    $$
        A=\left(\begin{array}{cc}
        -1/3 & 8/3  \\
        -2/3 & 7/3 
    \end{array}\right).
    $$
    试求$A^{1007}$的全部四个元素之和。<!--2016-->
    <!--hint: A = P*L*Pinv}-->

52. $A$同上题，试求$A^{1205}$的全部四个元素之和。<!--2412-->

53. 试求矩阵
    $$
        A=\left(\begin{array}{ccc}
    19  &  0  &   1\\
    0 &  41  & 0 \\
     0   & 0  &  22
     \end{array}\right)
    $$
    的全部奇异值的平方和。<!--2527-->

54. 给定矩阵$A$和向量$b$如下：
    $$
        A=\left(\begin{array}{cccc}
        1 & 9 & 2 & 2\\
        1 & 9 & 4 & 1\\
        0 & 0 & 1 & 0
        \end{array}\right),
        b=\left(\begin{array}{r}
        41 \\
        41 \\
        60 \\
        10
        \end{array}\right).
    $$
    对$n$维实数空间中的向量$x=(x_1,x_2,\cdots,x_n)^T$，我们定义它的长度为$$\|x\| = \sqrt{x_1^2+x_2^2+\cdots+x_n^2}.$$
    试求使得$\|A^T x-b\|$最小的$x$，写下$\|x\|^2$。<!--2525-->
    
---

[题目合集](archive/bh-ps)
[上一页](archive/bh-ps-probability-and-statistics)
[下一页](archive/bh-ps-computational-mathematics)