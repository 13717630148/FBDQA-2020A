# 第五周学习小结

1. A股：反转因子更有效；美股，趋势因子更有效
2. 股票池选取：
   - 剔除总市值<10%的股票
   - 剔除PE<0 >100的股票
   - 剔除ST股
   - 25日跌幅前10%的股票
3. 择时信号设计
   - 买入：20min K线， MA3上穿MA200
   - 卖出：20min K线，MA3下穿MA200

4. 趋势策略入场信号不如出场信号重要

5. 财务多因子
   - 评分计算方法：根据数值（eg资产负债率）直接打分；根据排序（盈利率）分段打分
6. 择时信号优化
   - 在更小的范围上定义均线（小周期）
   - 大均线：eg小时线穿过年线

#### 均值回复型策略

趋势跟随or均值回复取决于观察尺度

短期市场的反转逻辑：

- 过去3个月表现最差的N只股票的组合（N不能太小）

长期：过去1年/3年/5年表现最差 （适当加长再平衡周期）
-- 跳空缺口：非交易时段市场情绪累积造成的价格空缺

缺口方式的交易策略（日内策略）：

- 选择“缺口型”股票
- 缩小范围：开盘价高于20日收盘均价



#### SQL

关系数据模型

