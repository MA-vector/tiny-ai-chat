# 🚀 Tiny AI Chat

极简AI聊天助手 - 单文件支持Claude/OpenAI API

## ✨ 特性

- 🎯 **双API支持**: Claude + OpenAI
- ⚡ **极简设计**: 单HTML文件，无需依赖
- 🔧 **灵活配置**: 自定义Base URL和API Key
- 💾 **本地存储**: 配置自动保存
- 📱 **响应式**: 完美适配移动端
- 🎨 **现代化UI**: 简洁美观的界面

## 🚀 快速开始

### 方法1: 直接使用
1. 下载 `index.html`
2. 用浏览器打开
3. 配置API信息
4. 开始聊天

### 方法2: 在线部署
- GitHub Pages
- Netlify
- Vercel
- 任何静态托管服务

## ⚙️ 配置说明

### 1. 选择API类型
- **Claude API**: 使用Anthropic的Claude模型
- **OpenAI API**: 使用OpenAI的GPT模型

### 2. 填写配置
- **Base URL**: API服务地址
- **API Key**: 您的API密钥
- **模型**: 选择对应的AI模型

### 3. 保存并连接
点击"保存配置并开始聊天"，系统会自动测试连接。

## 🎮 使用界面

### 配置页面 (`⚙️ 配置`)
- 选择API类型 (Claude/OpenAI)
- 填写Base URL和API Key
- 选择模型
- 保存配置

### 聊天页面 (`💬 聊天`)
- 实时对话界面
- 消息历史记录
- 连接状态显示
- 支持Enter发送

## 🔧 技术细节

### 文件结构
```
tiny-ai-chat/
└── index.html    # 所有代码都在这个文件里
```

### 技术栈
- **HTML5**: 语义化标签
- **CSS3**: Flexbox布局，响应式设计
- **JavaScript ES6+**: 模块化代码，Fetch API
- **localStorage**: 配置持久化

### API支持
- **Claude API**: `/v1/messages` 端点
- **OpenAI API**: `/v1/chat/completions` 端点
- 支持自定义代理URL

## 🔒 安全特性

- 🔐 API Key仅存储在浏览器本地
- 🔐 不会上传到任何服务器
- 🔐 使用HTTPS进行API调用
- ⚠️ 不要在公共设备保存敏感API Key

## 📱 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+
- 移动端浏览器

## 🐛 故障排除

### 连接失败
1. 检查Base URL是否正确
2. 验证API Key是否有效
3. 确认网络连接正常
4. 检查CORS设置（如使用代理）

### 消息发送失败
1. 检查API配额
2. 确认模型名称正确
3. 查看浏览器控制台错误

### 重置配置
清除浏览器localStorage中的 `tinyAIChatConfig` 数据

## 📄 许可证

MIT License - 详见文件内许可证声明

## 🤝 贡献

欢迎反馈和建议！这个项目保持极简设计，专注于核心功能。

---

**版本**: v1.0
**发布日期**: 2026年3月10日
**文件大小**: ~15KB
**代码行数**: ~500行

💡 **提示**: 这是一个极简版本，专注于核心聊天功能。所有代码都在单个HTML文件中，便于部署和维护。