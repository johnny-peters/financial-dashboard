# 快速上手指南

欢迎使用金融仪表板！本指南将帮助您快速配置和使用应用。

## 📋 目录

- [快速开始](#快速开始)
- [API Key 配置](#api-key-配置)
- [Aktools 部署指南](#aktools-部署指南)
- [常见问题](#常见问题)

---

## 🚀 快速开始

### 1. 首次启动

1. 启动应用后，点击左侧导航栏的 **"设置"** 图标
2. 根据您要监控的资产类型，配置相应的 API Key（见下方详细说明）
3. 返回 **"价格"** 页面，点击 **"添加资产"** 按钮
4. 在搜索框中输入资产名称或代码（如：`BTC`、`AAPL`、`0700.HK`）
5. 从搜索结果中选择资产并点击 **"添加"**

### 2. 基本功能

- **实时价格监控**: 资产价格会自动更新（默认每 30 秒）
- **投资组合**: 在 **"投资"** 页面添加持仓，跟踪盈亏
- **主题切换**: 在设置中选择浅色/深色主题
- **多语言**: 支持中文和英文切换

---

## 🔑 API Key 配置

应用支持多种数据源，您可以根据需要配置相应的 API Key。**注意：某些数据源提供免费计划，无需 API Key 即可使用。**

### 加密货币数据源

#### CoinGecko（推荐，免费）

- **状态**: ✅ 无需 API Key
- **优先级**: 最高
- **限制**: 免费计划有速率限制
- **获取链接**: <https://www.coingecko.com/en/api>
- **说明**: 免费使用，无需注册

#### CryptowatchR（备用，免费）

- **状态**: ✅ 无需 API Key
- **优先级**: 备用
- **获取链接**: <https://cryptowat.ch/>

#### TwelveData（可选）

- **状态**: ⚠️ 需要 API Key
- **免费计划**: 每天 800 次请求
- **获取链接**: <https://twelvedata.com/>
- **注册步骤**:
  1. 访问 <https://twelvedata.com/>
  2. 点击 "Sign Up" 注册账号
  3. 在 Dashboard 中获取 API Key
  4. 在应用的 **设置 > API 密钥配置 > 加密货币数据源** 中填入

#### CoinMarketCap（可选）

- **状态**: ⚠️ 需要 API Key
- **免费计划**: 每月 10,000 次请求
- **获取链接**: <https://coinmarketcap.com/api/>
- **注册步骤**:
  1. 访问 <https://coinmarketcap.com/api/>
  2. 点击 "Get Your API Key Now"
  3. 注册并验证邮箱
  4. 在 Dashboard 中获取 API Key
  5. 在应用的 **设置 > API 密钥配置 > 加密货币数据源** 中填入

### 股票数据源

#### Finnhub（推荐）

- **状态**: ⚠️ 需要 API Key
- **免费计划**: 每分钟 60 次请求
- **获取链接**: <https://finnhub.io/>
- **注册步骤**:
  1. 访问 <https://finnhub.io/>
  2. 点击 "Get Free API Key"
  3. 注册账号（可使用 GitHub 登录）
  4. 在 Dashboard 中复制 API Key
  5. 在应用的 **设置 > API 密钥配置 > 股票数据源** 中填入

#### Alpha Vantage（备用）

- **状态**: ⚠️ 需要 API Key
- **免费计划**: 每天 25 次请求，每分钟 5 次
- **获取链接**: <https://www.alphavantage.co/support/#api-key>
- **注册步骤**:
  1. 访问 <https://www.alphavantage.co/support/#api-key>
  2. 填写邮箱获取免费 API Key
  3. 在应用的 **设置 > API 密钥配置 > 股票数据源** 中填入

#### TwelveData（备用）

- **状态**: ⚠️ 需要 API Key
- **免费计划**: 每天 800 次请求
- **获取链接**: <https://twelvedata.com/>
- **注册步骤**: 同加密货币数据源的 TwelveData

#### Marketstack（备用）

- **状态**: ⚠️ 需要 API Key
- **免费计划**: 每月 1,000 次请求
- **获取链接**: <https://marketstack.com/>
- **注册步骤**:
  1. 访问 <https://marketstack.com/>
  2. 注册账号
  3. 在 Dashboard 中获取 API Key
  4. 在应用的 **设置 > API 密钥配置 > 股票数据源** 中填入

### 指数数据源

#### Financial Modeling Prep（必需）

- **状态**: ⚠️ 需要 API Key
- **免费计划**: 每天 250 次请求
- **获取链接**: <https://site.financialmodelingprep.com/developer/docs/>
- **注册步骤**:
  1. 访问 <https://site.financialmodelingprep.com/developer/docs/>
  2. 点击 "Get Your Free API Key"
  3. 注册账号
  4. 在 Dashboard 中获取 API Key
  5. 在应用的 **设置 > API 密钥配置 > 指数数据源** 中填入
  6. **注意**: 这是获取指数数据的唯一数据源

### 汇率数据源

#### Alpha Vantage（推荐）

- **状态**: ⚠️ 需要 API Key
- **免费计划**: 每天 25 次请求，每分钟 5 次
- **获取链接**: <https://www.alphavantage.co/support/#api-key>
- **注册步骤**: 同股票数据源的 Alpha Vantage

#### Finnhub（备用）

- **状态**: ⚠️ 需要 API Key
- **免费计划**: 每分钟 60 次请求
- **获取链接**: <https://finnhub.io/>
- **注册步骤**: 同股票数据源的 Finnhub

#### TwelveData（备用）

- **状态**: ⚠️ 需要 API Key
- **免费计划**: 每天 800 次请求
- **获取链接**: <https://twelvedata.com/>
- **注册步骤**: 同加密货币数据源的 TwelveData

### 中国股票数据源（HK、SH、SZ、BJ）

#### Aktools（推荐，自部署）

- **状态**: ✅ 无需 API Key，但需要部署服务
- **说明**: 用于获取港股、A股等中国股票数据
- **部署指南**: 见下方 [Aktools 部署指南](#aktools-部署指南)

---

## 🛠️ Aktools 部署指南

Aktools 是基于 AKShare 的 HTTP 服务，用于获取中国股票（港股、A股）数据。应用会自动优先使用 Aktools 获取中国股票数据。

### 方式一：使用默认公共服务器（快速开始）

如果您只是想快速体验，可以使用默认的公共服务器：

1. 打开应用的 **设置** 页面
2. 找到 **"Aktools 数据源"** 卡片
3. 填入aktools服务url
4. 点击 **"测试"** 按钮验证连接
5. 如果测试成功，点击 **"保存"**

**注意**: 公共服务器可能不稳定，建议部署自己的服务。

### 方式二：自部署 Aktools 服务（推荐）

1. 详见官方文档：<https://aktools.akfamily.xyz/aktools/>

### 验证部署

1. 在浏览器中访问 `http://your-server:8080/`，应该看到 JSON 响应
2. 在应用的设置页面测试连接
3. 尝试搜索港股或A股（如：`0700.HK`、`600519.SH`）

---

## ❓ 常见问题

### Q1: 为什么添加资产时提示"验证失败"？

**A**: 可能的原因：

- API Key 未配置或无效
- 网络连接问题
- 数据源暂时不可用

**解决方案**:

1. 检查 API Key 是否正确配置
2. 在设置页面测试 API Key 连接
3. 如果资产在搜索结果中找到，即使验证失败也可以添加（价格稍后获取）

### Q2: 中国股票（HK、SH、SZ）需要配置 API Key 吗？

**A**: 不需要。中国股票会自动使用 Aktools 服务获取数据。您只需要：

- 使用默认的公共服务器，或
- 部署自己的 Aktools 服务

### Q3: 如何提高数据获取速度？

**A**:

1. 配置多个数据源的 API Key（提供故障转移）
2. 对于中国股票，部署自己的 Aktools 服务（比公共服务器更快）
3. 减少更新间隔（在设置中调整）

### Q4: 免费 API Key 有使用限制吗？

**A**: 是的，所有免费 API Key 都有速率限制：

- **Finnhub**: 每分钟 60 次请求
- **Alpha Vantage**: 每天 25 次请求，每分钟 5 次
- **TwelveData**: 每天 800 次请求
- **Financial Modeling Prep**: 每天 250 次请求

如果遇到速率限制，应用会自动切换到备用数据源。

### Q5: 如何部署 Aktools 到云服务器？

**A**:

1. 详见官方文档：<https://aktools.akfamily.xyz/aktools/#aktools-docker>

### Q6: 应用支持哪些资产类型？

**A**:

- **加密货币**: BTC, ETH 等（使用 CoinGecko，无需 API Key）
- **股票**: 美股、港股、A股等
- **指数**: S&P 500, NASDAQ 等（需要 Financial Modeling Prep API Key）
- **汇率**: USD/CNY, USD/EUR 等

### Q7: 如何查看资产的历史价格图表？

**A**:

暂不支持

---

## 📞 获取帮助

如果您遇到问题或需要帮助：

1. 查看应用的 **设置** 页面中的错误提示
2. 检查浏览器控制台（F12）中的错误信息
3. 访问项目 GitHub 仓库提交 Issue
4. 联系支持邮箱：<support@btc-reborn.com>

---

## 🎯 推荐配置（最小化设置）

如果您只想快速开始，最少需要配置：

1. **加密货币**: 无需配置（使用 CoinGecko 免费）
2. **中国股票**: 使用默认 Aktools 服务器或部署自己的服务
3. **国外股票**: 配置 Finnhub API Key（免费，推荐）
4. **指数**: 配置 Financial Modeling Prep API Key（免费，必需）

这样您就可以监控大部分资产类型了！

---

**祝您使用愉快！** 🎉
