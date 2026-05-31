# prophet-ops

**super-prophet 运营调控工具** — 多账号自动下单，维持目标赔率。

> 📘 详细使用说明（含截图）：[docs/usage.md](docs/usage.md)

---

## 📥 下载

前往 **[Releases](https://github.com/jiusanzhou/prophet-ops/releases/latest)** 下载对应平台版本：

| 平台 | 文件 | 说明 |
|------|------|------|
| **macOS** (Intel + Apple Silicon) | `prophet-ops-darwin.zip` | 解压后拖到「应用程序」 |
| **Windows** (x64) | `prophet-ops-windows-amd64.zip` | 解压后双击 `Prophet Ops.exe` |
| **Windows** (ARM64) | `prophet-ops-windows-arm64.zip` | ARM 架构的 Windows 设备 |
| **Linux** (x64) | `prophet-ops-linux-amd64` | 命令行运行 |
| **Linux** (ARM64) | `prophet-ops-linux-arm64` | ARM 架构服务器 |

---

## 🚀 快速启动

### macOS

1. 下载 `prophet-ops-darwin.zip` → 解压
2. 把 `Prophet Ops.app` 拖到 **应用程序** 文件夹
3. **首次启动**：右键点击 → 选择「打开」（绕过 Gatekeeper）
4. 浏览器会自动打开 `http://127.0.0.1:8080`

### Windows

1. 下载 `prophet-ops-windows-amd64.zip` → 解压到任意目录
2. 双击 `Prophet Ops.exe`
3. SmartScreen 拦截时：点「更多信息」→「仍要运行」
4. 浏览器会自动打开 `http://127.0.0.1:8080`

### 数据 / 配置 / 日志位置

- **Windows**: `%APPDATA%\prophet-ops\`
- **macOS**: `~/Library/Application Support/prophet-ops/`
- **Linux**: `~/.config/prophet-ops/`

---

## ✨ 主要功能

- 📊 **事件列表**：拉取 super-prophet 全部事件，一眼看清当前赔率分布
- 🎯 **目标赔率调控**：为任意事件 / 选项设置目标概率 + 容差 + 频率 + 上限
- 👥 **账号池**：批量导入 cookie 账号，自动轮换下单
- ⏱️ **定时巡检**：内置调度器，按设定频率维持目标赔率
- 📈 **实时面板**：仪表盘 + 委托记录 + 订单详情
- 🔔 **通知**：可接 Telegram / Stdout（可扩展 webhook/Slack/Discord）

---

## 📖 使用文档

完整图文教程：[docs/usage.md](docs/usage.md)

---

## ❓ 反馈

使用问题、bug 反馈、功能建议：联系内部对接同学。
