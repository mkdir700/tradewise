# TradeWise

TradeWise 是一个 TradingView 交易工具集合，包含了各种交易指标和策略。

## 项目结构

```
src/
├── indicators/        # 交易指标
│   ├── btc-trend-indicator.pine    # BTC 趋势指标
│   ├── slope.pine                  # 斜率指标
│   ├── trend-indicator-a.pine      # 趋势指标 A
│   └── volume-alert.pine           # 成交量提醒指标
└── strategies/        # 交易策略
    └── ma-cross-strategy.pine      # 均线交叉策略
```

## 使用说明

1. 复制需要使用的指标或策略代码
2. 在 TradingView 中打开 Pine Editor
3. 粘贴代码并点击"添加到图表"
4. 根据需要调整参数

## 指标说明

- **BTC趋势指标**: 用于显示比特币价格趋势
- **斜率指标**: 计算价格变化斜率
- **趋势指标A**: 综合趋势分析指标
- **成交量提醒**: 监控异常成交量

## 策略说明

- **均线交叉策略**: 基于快慢均线交叉产生交易信号，包含止损和止盈设置