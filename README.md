# Seaborn可视化

> author: wikke
> email: wikkefly [at] gmail.com
> ref: [blueliberty/Seaborn](https://github.com/blueliberty/Seaborn)

## 一、单变量

- 连续:distplot
- 离散:countplot

## 二、多变量（连续-连续）

- lmplot:简化FacetGrid
- pairplot:简化PairGrid
- jointplot:简化JointGrid

## 三、多变量（离散-连续）

- factorplot: 综合所有下面函数，通过kind实现不同绘图

### 分布散点

- swarmplot
- stripplot:有jitter参数，实现和swarmplot类似效果

### 分布统计

- boxplot
- violinplot

### 均值统计

- pointplot: factorplot默认kind
- barplot

## 四、网格

- FacetGrid: Subplot grid for plotting conditional relationships.
- PairGrid: Subplot grid for plotting pairwise relationships in a dataset.
- JointGrid: Grid for drawing a bivariate plot with marginal univariate plots.
