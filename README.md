# 哪都通桌面客户端

哪都通（NaDouTong）AI 网关平台的官方桌面客户端。一站式管理 Claude Code、Claude Desktop、Codex 等 AI 编程工具的接入配置，并随时掌握用量与费用。

## 下载安装

前往 [Releases](https://github.com/NaDouTongToken/client-releases/releases/latest) 下载对应平台的安装包：

| 平台 | 安装包 |
|---|---|
| Windows | `Nadoutong_windows_x.y.z_x64-setup.exe` |
| macOS（Intel / Apple Silicon 通用） | `Nadoutong_macos_x.y.z_universal.dmg` |
| Linux | `Nadoutong_linux_x.y.z_amd64.AppImage` |

安装后应用会**自动检查更新**，有新稳定版时应用内提示，一键升级、自动重启，无需手动重装。

## 核心功能

### 一键接入 AI 编程工具
- 自动为 **Claude Code / Claude Desktop / Codex** 写入哪都通接入配置（API 地址、密钥、模型），无需手动改配置文件
- 多套供应商配置随时切换，切换即生效
- 内置接入文档，配置细节一目了然

### 密钥管理
- 创建、吊销 API 密钥，设置密钥限额
- 密钥一键轮换：新建密钥 → 自动更新本机所有相关工具配置 → 吊销旧密钥，一步完成

### 用量与费用
- 主页速览：可用余额、本月费用与 token 用量、各供应商服务状态
- 余额账单、模型定价、用量明细、请求日志、消费报表
- 预算与告警：余额告急、用量突增、服务异常等自动通知

### 环境诊断
- 本机体检：检测工具配置与实际生效文件是否一致，漂移可一键修复
- 连通性诊断：网络 → 平台健康 → 鉴权/模型可用性/首字节时延，逐步定位接入问题

### 组织管理（管理员）
- 成员邀请（支持角色分配）、组织部门管理
- 成员模型权限配置、审计日志、工单支持

## 说明

- 本仓库仅用于**安装包分发与自动更新**，不包含源代码
- 遇到问题请在应用内「治理 → 工单」反馈
