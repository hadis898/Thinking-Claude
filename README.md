快速提醒：思维 Claude 并非针对基准测试或数学等领域的重大突破，因为这些都由基础模型（新的 Claude-3.5 Sonnet）预先决定。我只是想探索我们能在 Claude 的"深度思维模式"下达到什么程度。话虽如此，当您在日常任务中使用它时，您会发现 Claude 的内部独白（思维过程）非常有趣。

本项目包含两个主要组件：

1. **思维协议**：指导 Claude 在回应前进行深入系统思考的全面指令集
2. **浏览器扩展**：让 Claude 的思维过程在浏览器界面中更易读和管理的工具

思维协议 思维协议指导 Claude 在提供回应前遵循自然、全面的思考过程。

浏览器扩展 浏览器扩展通过使思维过程更易管理来增强 Claude 界面：

功能特点

- 🔄 可折叠的思维过程区块
- 📋 便捷的复制功能
- 🎯 清晰直观的界面
- ⚡ 自动处理新消息

安装方法 Chrome

1. 克隆此代码仓库
2. 打开 Chrome 并访问 `chrome://extensions/`
3. 启用"开发者模式"
4. 点击"加载已解压的扩展程序"并选择 `extension/chrome` 文件夹

Firefox

1. 克隆此代码仓库
2. 打开 Firefox 并访问 `about:debugging#/runtime/this-firefox`
3. 点击"临时载入附加组件"
4. 导航到代码仓库并选择 `extension/firefox/manifest.json` 文件

使用方法 应用思维协议

1. 复制 `model_instructions` 文件夹中的最新版本
2. 在 Claude.ai 中启动新项目
3. 将指令粘贴到自定义指令部分
4. Claude 现在将在所有后续交互中遵循思维协议

使用扩展程序 安装后，扩展程序会自动：

- 检测 Claude 的思维过程块
- 添加折叠/展开功能
- 为每个块提供复制按钮

为什么使用 Thinking Claude？

- **更好的推理**：获得更全面、深思熟虑的回应
- **透明度**：了解 Claude 如何得出结论
- **改进的组织**：更有效地管理长对话
- **质量控制**：受益于内置的验证步骤

### 项目地址：[https://github.com/richards199999/Thinking-Claude](https://www.upx8.com/go/aHR0cHM6Ly9naXRodWIuY29tL3JpY2hhcmRzMTk5OTk5L1RoaW5raW5nLUNsYXVkZQ)