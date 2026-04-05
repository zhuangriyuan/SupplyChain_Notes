# Supply Chain Management

### Course3 Module 1
### Supply Chain Planning

__Naive Forecast（朴素预测）__
> A naive forecast assumes that the future demand will be the same as the most recent actual demand. It does not use complex statistical models or trends.
> 朴素预测假设未来的需求与最近一期的实际需求相同，不依赖复杂的统计模型或趋势分析。
> 例子 / Example：
> 本月销量（Actual demand） = 1200 个
> 下月预测（Naive Forecast） = 1200 个

__The Cumulative Mean(累积均值)__
> The cumulative mean (also called the running mean or progressive mean) is the mean of all values in a sequence up to a certain point. It is calculated iteratively by including each new data point into the average.
> 累积均值（Cumulative Mean），也称为运行均值或渐进均值，是指对一个序列中从开始到某一位置的所有数值计算平均值。它可以通过每加入一个新数据点迭代更新。

\[
\bar{x}_n = \frac{x_1 + x_2 + \cdots + x_n}{n}
\]

__Mean Error__
> \[
\text{ME} = \frac{\sum (D_t - F_t)}{n}
\]

> 实际需求 − 预测需求 
> 如果结果 > 0 → 预测偏低
> 如果结果 < 0 → 预测偏高
> 把所有 period 的误差直接相加 除以数据期数
> ME = 3.33 表示 平均来说，每一期预测低估了 3.33 个单位。


__Mean Absolute Error__
> \[
\text{MAPE} = \frac{\sum \left| \frac{D_t - F_t}{D_t} \right|}{n}
\]

> 计算每期误差
> 除以实际值，得到相对误差
> 取绝对值
> 求所有相对误差的平均
> MAPE = 8.89% 表示预测值和实际值之间的平均偏差约为 8.89%。
> 越接近 0%，说明预测越准确。

__Mean Squared Error__
> \[
\text{MSE} = \frac{\sum (D_t - F_t)^2}{n}
\]

> MSE = 200
> 表示预测值与实际值之间的平均平方误差为 200。
> 平方的特点：
> 放大了大误差的影响（比 MAE 更敏感）
> 越小 → 预测越准确
> 越大 → 出现了较大偏差，需要优化预测模型

__Moving Average__
> 窗口越大，移动平均越平滑，但反应慢
> 窗口越小，移动平均更贴近原始数据，但波动大

__Exponential Smoothing(指数平滑法)__
> 加权预测方法 它给“最近的数据”更高权重，给“较早的数据”较低权重。
权重是指数递减的。
> $F_{t+1} = F_t + \alpha (D_t - F_t)$
> 新预测=旧预测+修正量
> α 决定“改多少”。
> α 大 → 改很多 → 反应快
> α 小 → 改很少 → 很稳定

__MRP System(Material Requirements Planning)物料需求规划系统__
> It breaks down the final product into its subcomponents, the value of materials, and then we get to manage each raw material or input by ensuring adequate足够的 inventory is available when it goes into production
> MRP（物料需求计划）**是一种基于需求驱动的计算系统，用来回答三个核心问题：
> 需要什么物料？
> 需要多少？
> 什么时候需要？
> For production planning

__DRP Distribution Requirements Planning分销需求计划__
> DRP解决的问题
> 在多级仓储网络中：
> 各区域仓库需要多少库存？
> 什么时候补货？
> 总仓什么时候发货？