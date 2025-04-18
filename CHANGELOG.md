# 📋 更新日志

### v2.0.0 (2025-04-08)
- 🏗️ 完全重构 抛弃使用协议端API获取聊天记录的方式，改为基于Astrbot本身，支持了更多消息平台 [#21](https://github.com/23q3/astrbot_plugin_SpectreCore/issues/21) [#4](https://github.com/23q3/astrbot_plugin_SpectreCore/issues/4)
- 🔄 架构改进 采用高度模块化设计，每个功能封装在独立工具类中
- 📸 图片转述 支持图片转述功能 [#16](https://github.com/23q3/astrbot_plugin_SpectreCore/issues/16)

### v1.0.4 (2025-03-12)
- 🐛 修正处理大模型回复时的条件判断逻辑 [#15](https://github.com/23q3/astrbot_plugin_SpectreCore/issues/15)

### v1.0.3 (2025-03-11)
- 🐛 在处理大模型回复时增加了对角色的判断，避免调用函数工具时出错 [#15](https://github.com/23q3/astrbot_plugin_SpectreCore/issues/15)
- 🐛 在提示词增加了bot的昵称和qq号，避免大模型不知道聊天记录中哪个是自己 [#14](https://github.com/23q3/astrbot_plugin_SpectreCore/issues/14)

### v1.0.2 (2025-03-08)
- 🔒 添加了群组锁机制，防止并发调用大模型
- 🛠️ 优化了消息处理存储流程，极大提高了性能
- 🔍 添加了清除聊天记录的指令
- 🔍 添加了检测指令关键词不回复功能
- 📝 改进了代码结构

### v1.0.1 (2025-03-05)
- 🔍 增加了读空气功能
- 🔍 增加了函数工具开关配置
- 🔄 更换了request_llm方法调用大模型，提高兼容性
- 🛠️ 优化部分代码

### v1.0.0 (2025-03-04)
- 🎉 首次发布
- ✨ 实现基本的群聊互动功能 