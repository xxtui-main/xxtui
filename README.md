<p align="center">
  <a href="https://xxtui.com" target="_blank">
    <img align="center" alt="xxtui" width="180" style="border-radius: 15px;" src="Images/logo.png" />
  </a>
</p>

<p align="center">xxtui，仅需一个url，轻松实现推送提醒。支持将消息发送至微信公众号、企业微信群、钉钉群、Bark ~</p>

<!-- 顶部统计徽章行 -->
<p align="center">
  <a href="https://github.com/vladelaina/Catime/stargazers">
    <img src="https://img.shields.io/github/stars/xxtui-main/xxtui?style=flat-square&logo=github&color=yellow&label=Stars" alt="Stars" />
  </a>
  <a href="https://github.com/vladelaina/Catime/issues">
    <img src="https://img.shields.io/github/issues/xxtui-main/xxtui?style=flat-square&label=open%20issues&color=orange" alt="Open Issues" />
  </a>
</p>

<p align="center">
  <a href="https://www.xxtui.com" target="_blank">
    <img src="https://img.shields.io/badge/KEY-专属安全-FF6E40?style=for-the-badge" alt="api_key"/>
  </a>
  <a href="https://www.xxtui.com/channelManage" target="_blank">
    <img src="https://img.shields.io/badge/扩展-自定义通道-BA68C8?style=for-the-badge" alt="custom_http"/>
  </a>
  <a href="https://www.xxtui.com/channelGroup" target="_blank">
    <img src="https://img.shields.io/badge/聚合-多渠道推送-26A69A?style=for-the-badge&logoColor=3949ab" alt="渠道组合" />
  </a>
  <a href="https://www.xxtui.com/uplinkMessage" target="_blank">
    <img src="https://img.shields.io/badge/消息-支持上行-4FC3F7?style=for-the-badge" alt="channel"/>
  </a>
  <a href="https://www.xxtui.com/command" target="_blank">
    <img src="https://img.shields.io/badge/指令-简单易用-42A5F5?style=for-the-badge" alt="xxtui" />
  </a>
</p>
<div align="center">

[![Uptime](https://status.xxtui.com/api/badge/1/uptime?style=flat-square)](https://status.xxtui.com/status/api)
[![Avg-Response](https://status.xxtui.com/api/badge/1/avg-response?style=flat-square)](https://status.xxtui.com/status/api)

</div>

## 🌟特点

- **简单**：一个url，仅需切换`专属KEY`，轻松实现各种渠道的通知
- **高效**：服务器接收即处理，无需等待，渠道组内包含多个渠道时采用多线程同时推送
- **专属KEY**：除主`KEY`默认用法，每个渠道、渠道组都有独立的`API_KEY`
- **聚合**：选择渠道生成组合，使用渠道组`API_KEY`可以同时推送消息到组合里的每个渠道
- **上行消息**：不仅能`发`，还能`收`，支持公众号收到指定消息回调指定接口
- **指令系统**：简单易用的指令系统，操作便捷不区分大小写，通过help/h查看所有指令或具体指令帮助

## 📡 支持渠道

- 📱 **微信公众号**

  通过公众号模板快速推送消息，直达用户微信端。

- 📞 **短信 | 语音电话**

  支持通过短信或语音电话方式，将重要通知直接发送到用户手机，适用于紧急提醒、重要事件推送等场景。

- 📧 **电子邮箱**

  通过邮件方式，将通知或告警信息发送到用户邮箱。

- 📨 **企业微信群**

  企业微信群机器人，消息可定向发送到指定群聊。

- 📩 **钉钉群**

  钉钉群机器人

- 🔔 **Bark**

  iOS 平台本地推送工具，配合 Bark APP 实时唤醒手机通知，适合个人任务提醒和轻量级消息推送。

- ⚙️ **自定义 HTTP 渠道**

  用户可按需配置任意 HTTP 接口，携带变量和自定义头部，自由扩展到更多系统或服务。

## 💡使用场景

- 👔 **工作协同**

  接收需求更新、审批完成等提醒，一键推送到团队群，及时跟进，不错过任何变动。

- 🍅 **番茄专注**

  每个 25 分钟工作／学习时段结束后，自动推送“休息开始”“休息结束”提醒，告别分心。

- 🎮 **监控告警**

  服务异常时，立即将报警发送到微信、钉钉等多个群组，运维团队秒响应，减少故障损失。

- ⏰ **定时提醒**

  设定日常打卡、吃药、账单到期等定时任务，让 xxtui 成为你的贴身小助手。

## 🤖 MCP 支持

MCP (Model Context Protocol) 协议，为 AI 提供了类似"万能接口"的能力，让模型能够安全、灵活地接入外部资源。

### 核心优势

- **即时推送**：AI 完成操作即可触发消息发送
- **无需等待**：大多数情况下，用户无需关注 AI 执行过程
- **多渠道支持**：兼容 xxtui 所有渠道，只需配置 API-KEY
- **上下文感知**：AI 会根据任务上下文发送合适的消息

### 支持的 MCP 客户端

- **Claude Code**：通过终端命令快速配置
- **Cherry Studio**：图形界面配置
- **通义灵码**：IDEA 插件配置

### 配置示例（Claude Code）

```bash
claude mcp add --transport http xxtui https://mcp.xxtui.com --header "API-KEY:你的key"
```

配置完成后，Claude Code 即可通过 xxtui 发送推送消息。

## 🧩 小技巧

- **移动的139邮箱可免费开启新邮件短信通知，收到新邮件时自动短信提醒。**

## 💭社区

火速赶来中~

## 💖支持

如果您喜欢本项目，欢迎star。您的支持是我持续更新的动力 ദ്ദി˶>𖥦<)✧Thanks!

## ⭐Star History

[![Star History Chart](https://api.star-history.com/svg?repos=xxtui-main/xxtui&type=Date)](https://www.star-history.com/#xxtui-main/xxtui&Date)

---

<div align="center">

Made with ❤️ & ⌨️

</div>

