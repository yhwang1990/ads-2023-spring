# 数据科学与工程算法 (Algorithms for Data Science and Engineering)

## ---  2023-24学年第二学期  ---

### 课程简介

Data scientists, that peculiar mix of software engineer and statistician. The purpose of this course is to introduce some commonly used algorithms for data scientists and engineers. In particular, this class is meant to introduce randomized, statistical, algebraic, and optimized algorithms, with an emphasis on applications in real life.

### 任课老师: 王延昊 (Yanhao Wang)

- 华东师范大学数据科学与工程学院副教授
- 办公室: 数学馆东115室
- 电子邮件: <yhwang@dase.ecnu.edu.cn>

### 课程助教

- 姓名: 周逸 (Yi Zhou) & 腾龙 (Long Teng)
- 办公室: 数学馆东102室
- 电子邮件: <yzhou@stu.ecnu.edu.cn> & <lteng@stu.ecnu.edu.cn>

### 课程时间地点

- 文史楼211教室
- 每周二 14:50 -- 16:25 (1-17周理论课)
- 每周五 13:00 -- 14:35 (1-4周理论课，5-17周实验课)

### 课程计划

- 1: 课程简介 (Introduction) [[ppt1](https://pan.baidu.com/s/15bQZnAO31ibKrU7MKtzZhA)] (提取码: 97iv) [[ppt2](https://pan.baidu.com/s/1VLa67MzdBYvXHInEdJXXKg)] (提取码: anqx)
- 2: 概率不等式 (Probability Inequality) [[ppt](https://pan.baidu.com/s/1Vb6fvesEEsrvHiWzEQQahg)] (提取码：gsp9) [[习题答案](https://pan.baidu.com/s/13D5AIB-kRhaBvViYClVoPA)] (提取码：zhue)
- 3: 哈希算法 (Hashing) [[ppt](https://pan.baidu.com/s/1G0IA0IA9EVAujCr9f4GYIQ)] (提取码：3lmg) [[lsh](https://pan.baidu.com/s/1TjC9ts5vRVfTOAn56ruHkA)] (提取码：qdbs) [[习题答案](https://pan.baidu.com/s/119pgWTauhCdI85NYyA-xvw)] (提取码：vj6m)
- 4: 概要数据结构 (Sketch) [[ppt](https://pan.baidu.com/s/1Kisz8IQPL-MMzKNu6lVB6Q)] (提取码：hzf8) [[习题答案](https://pan.baidu.com/s/1Q8Xc5DTzSz_OH26gXyzKrQ)] (提取码：8vee)
- 5: 采样算法 (Sampling) [[ppt](https://pan.baidu.com/s/1-I7Vz0SvXl_Zf4PGN6eLNw)] (提取码：iwaa) [[stream1](https://pan.baidu.com/s/1j52C2yLwu1IxXgDc4-dIDA)] (提取码：ibz7) [[stream2](https://pan.baidu.com/s/1WSrf3_ik1uCxngjYvSDm3A)] (提取码：lh2i) [[习题答案](https://pan.baidu.com/s/1pJfrIyujutq9AnmkUyVX3w)] (提取码：gisa)
- 6: 马尔可夫链与随机游走 (Markov Chain and Random Walk) [[ppt](https://pan.baidu.com/s/1KfkwEcy7VeJhb0vWkYxORA)] (提取码：k754)
- 期中总结 (Mid-Term Summary)
- 7: 特征值分解 (Eigenvalue Computation) [[ppt](https://pan.baidu.com/s/1wkBRWeikzyFc10C6G8yYeA)] (提取码：6hen)
- 8: 奇异值分解与主成分分析 (SVD and PCA) [[ppt](https://pan.baidu.com/s/1YLUV7Q6HvWW1GjayNDuFcg)] (提取码：47qs)
- 9: 矩阵因式分解 (Matrix Decomposition)
- 10: 线性与整数规划 (Linear & Integer Programming)
- 11: 次模函数 (Submodular Function)
- 12: 社区发现 (Community)
- 期末总结 (Summary)

### 课程项目

- **项目一: 数据流统计算法**
  1. **任务描述:** 数据集中包含带时间戳的用户对电影的评分信息，我们假设其以数据流的形式随时间增量式获取。 你需要设计并实现空间占用尽量小的数据结构实现如下功能:（1）成员查询：对给定查询时间戳和电影id，查询该电影在该时间戳及之前是否曾被评分过；（2）频度查询：对于给定查询时间戳和电影id，查询该电影在该时间戳及之前被评分的总次数；（3）Top-k查询：对给定正整数k和查询时间戳，查询在该时间戳及之前被评分次数最多的前k个电影。在实验报告中, 请展示所实现数据结构的关键性能指标，例如查询精度，构建与更新时间，查询时间和空间占用等。
  2. **数据集** [[Download](https://pan.baidu.com/s/1vuplpiEpZOTF_pjvj9_AeA)] (提取码: 1766)
  3. **实验报告模板** [[Template](https://pan.baidu.com/s/19a0QswPr710R18bHXxxpYw)] (提取码: mtk4)
- **项目二: 图像压缩**
  1. **任务描述:** 主成分分析可以降低矩阵数据（例如图像）的维度，从而将它们映射到更低维度的空间以重构并保留关键信息。你需要从给定的数据集中选取至少100张图片，使用基于主成分分析的方法压缩它们。在实验报告中, 请展示所实现图像压缩算法的关键性能指标，例如重构误差，空间节省，压缩比例，运行时间和实际视觉效果等。
  2. **数据集** [[Download](https://pan.baidu.com/s/1ZybljyQ32gdmsrXSqSafMw)] (提取码: gpez)
  3. **实验报告模板** [[Template](https://pan.baidu.com/s/19a0QswPr710R18bHXxxpYw)] (提取码: mtk4)

### 参考教材

- 高明, 胡卉芪著: 数据科学与工程算法基础 [[京东]](https://item.jd.com/12863803.html) [[当当]](http://product.dangdang.com/29253772.html)
- Jure Leskovec, Anand Rajaraman, and Jeff Ullman: [Mining of Massive Datasets](http://mmds.org)
- Avrim Blum, John Hopcroft, and Ravindran Kannan: [Foundations of Data Science](https://home.ttic.edu/~avrim/book.pdf)

### 在线课程

- CS246 @ Stanford University by Jure Leskovec: [Mining Massive Data Sets](http://web.stanford.edu/class/cs246/)
- D&K @ Université Paris-Saclay by Albert Bifet: [IoT Stream Data Mining](https://albertbifet.com/dk-iot-stream-data-mining-2019-2020/)
- MTH 417 @ IIT Kanpur by Shalabh: [Sampling Theory](http://home.iitk.ac.in/~shalab/course1.htm)
- MATP6620 @ Rensselaer Polytechnic Institute by John E. Mitchell: [Integer and Combinatorial Optimization](https://homepages.rpi.edu/~mitchj/matp6620/)
