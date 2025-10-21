# BSC交易分析工具

--------------------
一个简单但功能强大的BSC（币安智能链）交易分析工具，支持多钱包地址分析，可以帮助您追踪和分析BSC上的交易活动。

## 🌟 特点

- 💼 支持多钱包地址分析
- 📊 详细的交易统计（买入/卖出/Gas费用）
- 💰 实时BNB价格转换
- 📅 自定义时间范围分析（默认统计当天8:00到次日8:00）
- 🔄 自动重试机制，确保数据获取的可靠性
- 📱 响应式设计，支持移动端访问

## 🚀 在线使用

访问 [https://sincitysh.github.io/bscalpha/analyzer.html](https://sincitysh.github.io/bscalpha/analyzer.html) 即可开始使用。

USDT统计的，可以访问这个
[https://sincitysh.github.io/bscalpha/usdt-analyzer.html](https://sincitysh.github.io/bscalpha/usdt-analyzer.html) 


## 📝 使用说明

1. 输入钱包地址（支持多个地址，每行一个）
   ```
   名称1 0x...地址1
   名称2 0x...地址2
   ```

2. 选择日期（可选）
   - 不选择日期时默认分析当天8:00到次日8:00的数据
   - 选择日期后将分析该日8:00到次日8:00的数据

3. 点击"分析"按钮开始分析

4. 查看分析结果
   - 交易统计（总次数、成功、失败）
   - 交易金额（买入总额、卖出总额、Gas消耗）
   - 收益分析（交易盈亏、净盈亏、当前余额）
   - 详细交易记录（可折叠展示）

## 🛠️ 技术特点

- 纯前端实现，无需后端服务器
- 使用BSCScan API获取交易数据
- Web3.js 集成获取实时数据
- Bootstrap 5 响应式界面
- 内置错误重试机制
- 支持并发请求控制

## 📋 数据说明

- 交易数据来源：BSCScan API
- BNB价格来源：Binance API
- 所有数据实时获取，确保准确性
- 支持查看交易详情链接到BSCScan

## 👨‍💻 作者

- 东东 [@lumaodaren](https://x.com/lumaodaren)

## 📄 开源协议

MIT License

## ⚠️ 免责声明

- 本工具仅供学习和研究使用
- 交易数据来自第三方API，可能存在延迟
- 请勿用于任何非法用途
- 作者不对使用本工具造成的任何损失负责

## 🤝 贡献

欢迎提交 Issues 和 Pull Requests 来改进这个工具。

## 🙏 致谢

- BSCScan API
- Web3.js
- Bootstrap
- 所有贡献者和用户 
