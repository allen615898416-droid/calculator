# IAA 游戏变现与 ROI 算账模型

一个用于计算IAA（In-App Advertising）游戏变现和ROI的交互式工具。

## 功能特点

- 📊 **核心指标速览**：DAU构成、单日流水、新增用户创收一目了然
- ⚙️ **灵活参数配置**：支持自定义留存率、广告eCPM、展示频次等关键参数
- 📈 **双衰减模型**：老用户eCPM和频次双衰减，更贴近实际
- 💰 **财务结算**：自动计算LTV、ROI，辅助买量决策
- 📋 **行业基准参考**：内置2025年最新行业数据，方便对齐校验

## 使用方法

直接在浏览器中打开 `iaa-game-revenue-model.html` 即可使用，无需安装任何依赖。

## 核心公式

- **日ARPU** = eCPM × 展示次数 / 1000
- **综合日ARPU** = (新增日ARPU × 新增用户数 + 留存日ARPU × 老用户数) / DAU
- **LTV** = 新增日ARPU + (LT-1) × 留存日ARPU
- **ROI** = LTV × 新增用户数 / (CPA × 新增用户数)

## 数据来源

行业基准数据来自：
- Tenjin《Ad Monetization in Mobile Games Benchmark Report 2025》
- Business of Apps《Mobile Advertising Rates 2025》
- Playwire《AdMob eCPM Benchmarks 2025》

## License

MIT
