<div align="center">

# 👋 Hi there, I'm Nick

**Java 开源开发者 · 基础工具库 & 大模型 SDK 作者**

专注打造「**小而全 · 零依赖 · 开箱即用**」的 Java 基础设施：
所有开源项目均采用 **JDK 21 + Maven 多模块 + Apache-2.0**，核心域零第三方运行期依赖，已发布至 Maven Central。

[![JDK](https://img.shields.io/badge/JDK-21+-orange.svg)](https://openjdk.org/projects/jdk/21/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Maven Central](https://img.shields.io/badge/Maven%20Central-io.github.tasure-blueviolet.svg)](https://central.sonatype.com/)
[![GitHub](https://img.shields.io/badge/GitHub-TASure-181717.svg?logo=github&logoColor=white)](https://github.com/TASure)

</div>

---

## 🧑‍💻 关于我 About Me

- 🔭 正在持续迭代：**sureai**（大模型统一接入 SDK）与 **suretool**（Java 工具类库）
- 🌱 技术栈：Java 21 · Maven 多模块 · JUnit 5 · GitHub Actions · Maven Central 发布
- 🎯 设计理念：静态工具类开箱即用、模块级隔离按需引入、核心域**零第三方运行期依赖**
- ✍️ 代码风格：Tab 缩进 · 中文 JavaDoc · Apache-2.0 · Conventional Commits
- 📦 发布坐标：`io.github.tasure`（`sure-all` / `sure-ai-all` 一键引入全部能力）

---

## 🚀 开源项目 Featured Projects

### 🤖 sureai —— 零第三方依赖的大模型统一接入 SDK

> 每个主流 AI 平台一个独立模块与静态入口工具类，模块间互相隔离，按需引入。

- 平台全覆盖：OpenAI · Azure · Anthropic · Gemini · DeepSeek · 通义千问 · 智谱 · Kimi(Moonshot) · 豆包 · 百度千帆 · Ollama
- 零第三方运行期依赖：内置轻量 JSON 解析与 HTTP 客户端，不引入 OkHttp / Jackson / Netty
- 一行调用：`OpenAiUtil.chat(model, prompt)` 完成对话
- 统一能力：SSE 流式 · Function Calling · Embedding · 环境变量自动配置
- 15 个模块 · 最新版本 **1.1.0**

[![源码](https://img.shields.io/badge/源码-GitHub-181717?logo=github&logoColor=white)](https://github.com/TASure/sureai)
[![Release](https://img.shields.io/github/v/release/TASure/sureai)](https://github.com/TASure/sureai/releases)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://github.com/TASure/sureai/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/TASure/sureai)](https://github.com/TASure/sureai)

### 🧰 suretool —— 小而全的 Java 工具类库

> 参考 [Hutool](https://doc.hutool.cn/) 设计理念，通过静态方法封装常用 JDK API，减少重复造轮子、降低开发成本。

- 17 个模块：core · json · xml · crypto · http · cache · cron · captcha · jwt · dfa · poi · spring-boot-starter 等
- 核心域零第三方运行期依赖（Office 域基于 Apache POI 5.5.1）
- 测试 625+ 全绿 · 覆盖率全模块 ≥ 85% · CI(JVM 21/25) 全绿 · SpotBugs/Checkstyle 零告警
- 已发布 Maven Central：`sure-all` 一键引入，最新版本 **1.0.0**

[![源码](https://img.shields.io/badge/源码-GitHub-181717?logo=github&logoColor=white)](https://github.com/TASure/suretool)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.tasure/sure-all.svg)](https://central.sonatype.com/artifact/io.github.tasure/sure-all)
[![CI](https://img.shields.io/github/actions/workflow/status/TASure/suretool/ci.yml?branch=main&label=CI)](https://github.com/TASure/suretool/actions)
[![Coverage](https://img.shields.io/codecov/c/github/TASure/suretool)](https://codecov.io/gh/TASure/suretool)
[![Stars](https://img.shields.io/github/stars/TASure/suretool)](https://github.com/TASure/suretool)

### 📦 全部项目一览 All Repositories

| 仓库 | 说明 | 语言 | Stars | 最近更新 |
|------|------|------|:----:|---------|
| [sureai](https://github.com/TASure/sureai) | 零第三方依赖的 Java 大模型统一接入工具库（11 平台 · 15 模块） | Java | 0 | 2026-09-24 |
| [suretool](https://github.com/TASure/suretool) | 小而全的 Java 工具类库（17 模块 · 已发布 Maven Central） | Java | 0 | 2026-09-24 |
| [TASure](https://github.com/TASure/TASure) | GitHub 主页（本仓库） | - | 0 | 2026-09-23 |

---

## 🛠️ 技术栈 Tech Stack

| 领域 | 技术 |
|------|------|
| 语言 | Java 21（record · pattern matching · switch 模式） |
| 构建 | Maven 多模块 · Maven Wrapper · BOM 统一版本管理 |
| 测试 | JUnit 5 · Jacoco 覆盖率门禁 · SpotBugs / Checkstyle 零告警 |
| 质量 | GitHub Actions CI（JVM 21/25）· CodeQL 安全扫描 · 发布级 `clean verify` 门禁 |
| 发布 | Maven Central（`io.github.tasure`）· GPG 签名 · GitHub Releases |
| 自研 | 轻量 JSON 解析 · HTTP 客户端 · SSE 流式 · 加密 / JWT / DFA 等 |

---

## 📈 GitHub 统计 Stats

| 指标 | 数值 |
|------|------|
| 公开仓库 | 3 |
| 总 Star | 0 |
| 总 Fork | 0 |
| 关注者 | 0 |
| 数据同步于 | 2026-09-25 03:23 (UTC+8) |

---

## 📅 最近动态 Recent Activity

- 2026-09-24 · **sureai**：docs: 记录 v1.1.0 发布 DNS 规避方案
- 2026-09-24 · **sureai**：chore: bump version to 1.2.0-SNAPSHOT
- 2026-09-24 · **suretool**：feat(extra): 新增 sure-extra 扩展模块（P5 v1.1.0）
- 2026-09-24 · **suretool**：feat(thread): ThreadUtil 虚拟线程升级（P5 v1.1.0）
- 2026-09-23 · **TASure**：chore: auto-sync profile README (2026-09-24 03:24 UTC+8)
- 2026-09-22 · **TASure**：chore: auto-sync profile README (2026-09-23 03:23 UTC+8)

---

## 📫 联系我 Contact

- GitHub：[TASure](https://github.com/TASure)
- Maven Central：搜索 groupId `io.github.tasure` 即可找到全部已发布构件
- 📬 欢迎提交 Issue / PR，或为开源项目点个 ⭐ 支持

---

<div align="center">

⭐ 感谢来访！如果我的项目对你有帮助，欢迎 **Star** ⭐

<sub>本主页 README 由脚本每日自动同步 GitHub 数据</sub>

</div>
