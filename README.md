# Math-01-Convex-Optimization
Notes for USTC course 'Convex Optimization' by 凌青

## Video of course

https://www.bilibili.com/video/av40868517?p=1



1-2：推荐书目，引言，常见例子，优化问题分类，发展史
3-4：仿射/凸/凸锥 + 集/组合/包
5-6：几种重要的凸集:超平面与半空间/球和椭球/多面体/单纯形/对称(半)(正定)矩阵
7-8：凸集的交集，保凸运算：仿射函数/缩放和移位/透视函数/线性分段函数
9-10：（9缺）凸函数的定义1/定义2/定义3，凸函数的扩展
11-12：凸函数定义2补充/定义4，常见例函数的凸性：二次函数/仿射函数/指数函数/幂函数/绝对值的幂函数/对数函数/负熵/范数/零范数/极大值函数/log-sum-up函数
13-14：函数凸性：极大值函数/log-sum-up函数/几何平均/行列式对数；保持函数凸性：非负加权和/仿射映射/两函数的极大值函数/无像个凸函数的极大值
15-16：复合函数保凸的条件，函数的透视：欧几里得范数的平方/负对数/K-L散度，函数的共轭
17-18：复合函数保凸条件，函数的共轭，α-sublevel set，拟凸函数
19-20：（课堂小测1），向量零范数的松弛形式，可微拟凸函数的一阶条件和二阶条件，对数凹函数/对数凸函数
21-22：可微拟凸函数的一阶条件的充分性证明，凸问题：域/可行解集/最优值/最优解(集)/ε次优解集/局部最优解/可行性优化问题，凸问题的等价形式（举例）
23-24：凸优化问题，凸优化约束的降维和升维（松弛变量），拟凸优化问题，凸问题局部最优等于全局最优，可微目标函数情况下的最优解（画图举例），三个名人的故事
25-26：凸问题的等价变换，营养食谱问题，线性分数规划，二次规划，QCQP，回归问题下x稀疏时的LASSO（引入X=X+ + X-）
27-28：投资组合问题的形式，半正定规划问题，谱范数，多目标优化问题：pareto最优面，多目标问题①的转化（单目标问题②和带约束的单目标问题③）
29-30：对偶性，Lagrange函数，Lagrange函数的凹性，对偶函数与函数共轭的关系，(P)对偶函数的对偶函数仍未(P)
学角度解释
33-34：线性代数知识：Byod的《Convex Optimization》附录C的内容
35-36：P*=d*经济学角度解释的补充，鞍点解释的补充，鞍点定理，KKT条件，KKT条件充要性证明
37-38：线性约束的QP问题的KKT条件，Water-filling问题的KKT条件，约束仅为非负约束时互补条件和KKT条件的关系，更多的凸问题等价转换例子。。，带框约束的LP问题
39-40：敏感性分析：P*(u,w)/局部敏感性，Boolen LP问题的LP松弛和Lagrange松弛的等价性（两种松弛形式互为对偶）
41-42：带等式约束的可微凸优化问题的罚函数形式，带线性不等式约束的可微凸优化问题的log-barrier法，算法：Line Search：exact(黄金分割法)/inexact(Amijo Rule)
43-44：（课堂小测2），函数的强凸性，Hassien矩阵的上界下界，f(x)-P*的上界和下界，梯度下降法
45-46：强凸性等价不等式及其相反性质的等价不等式，梯度下降法，算法的收敛性，(亚/超)线性收敛，Amijo Rule解的上下界，矩阵的条件数
47-48：最速下降法：二模/一模/无穷模，坐标轮换***************/拟牛顿法
49-50：无约束优化问题算法选择建议，有约束优化问题（关心只含等式约束的问题）：构造KKT条件，拉格朗日法/增广拉格朗日法
51-52：增广拉格朗日法，其常用技巧（分布式计算）
53-54：NLP专题讲座，NLP下的KKT条件，（互补松弛条件讲的太好啦！）
55：总复习
