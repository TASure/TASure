<div align="center">

# 👋 Hi there, I'm Nick

**Java 开源开发者 · 基础工具库 & 大模型 SDK 作者**

专注打造「**小而全 · 零依赖 · 开箱即用**」的 Java 基础设施：
所有开源项目均采用 **JDK 21/25 + Maven 多模块 + Apache-2.0**，核心域零第三方运行期依赖，已发布至 Maven Central。

[![JDK](https://img.shields.io/badge/JDK-21%2F25-orange.svg)](https://openjdk.org/projects/jdk/25/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Maven Central](https://img.shields.io/badge/Maven%20Central-io.github.tasure-blueviolet.svg)](https://central.sonatype.com/)
[![GitHub](https://img.shields.io/badge/GitHub-TASure-181717.svg?logo=github&logoColor=white)](https://github.com/TASure)

</div>

---

## 🧑‍💻 关于我 About Me

- 🔭 正在持续迭代：**sureai**（大模型统一接入 SDK）与 **suretool**（Java 工具类库）
- 🌱 技术栈：Java 21/25 · Maven 多模块 · JUnit 5 · GitHub Actions · Maven Central 发布
- 🎯 设计理念：静态工具类开箱即用、模块级隔离按需引入、核心域**零第三方运行期依赖**
- ✍️ 代码风格：Tab 缩进 · 中文 JavaDoc · Apache-2.0 · Conventional Commits
- 📦 发布坐标：`io.github.tasure`（`sure-all` / `sure-ai-all` 一键引入全部能力）

---

## 🚀 开源项目 Featured Projects

### 🤖 sureai —— 零第三方依赖的大模型统一接入 SDK

> 每个主流 AI 平台一个独立模块与静态入口工具类，模块间互相隔离，按需引入。

- 平台全覆盖：**23 个平台**（OpenAI · Azure · Anthropic · Gemini · DeepSeek · 通义千问 · 智谱 · Kimi · 豆包 · 百度千帆 · Ollama · Grok · Mistral · Cohere · llama.cpp · AWS Bedrock · MiniMax · 阶跃星辰 · 百川 · 01.AI · 硅基流动 · 腾讯混元 · 讯飞星火）
- 零第三方运行期依赖：内置轻量 JSON 解析与 HTTP 客户端，不引入 OkHttp / Jackson / Netty
- 一行调用：`OpenAiUtil.chat(model, prompt)` 完成对话
- 统一能力：SSE 流式 · Function Calling · Embedding · 图像/视频生成 · TTS/STT · Rerank · 结构化输出 · 多模态 · PDF 理解 · Realtime · Batches · Grounding · 微调
- 生态模块：MCP 客户端与服务端 · Agent(ReAct) · RAG · CLI 命令行 · Maven 脚手架 · GraalVM native-image · OTel 可观测 · Spring Boot Starter · Quarkus 扩展
- 41 个模块 · 最新版本 **2.5.0**

[![源码](https://img.shields.io/badge/源码-GitHub-181717?logo=github&logoColor=white)](https://github.com/TASure/sureai)
[![Release](https://img.shields.io/github/v/release/TASure/sureai)](https://github.com/TASure/sureai/releases)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://github.com/TASure/sureai/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/TASure/sureai)](https://github.com/TASure/sureai)

### 🧰 suretool —— 小而全的 Java 工具类库

> 参考 [Hutool](https://doc.hutool.cn/) 设计理念，通过静态方法封装常用 JDK API，减少重复造轮子、降低开发成本。

- 28 个模块：core · json · xml · crypto · http · cache · cron · captcha · jwt · dfa · poi · pdf · db · aop · log · event · math · process · script · socket · template · compress · extra · spring-boot-starter 等
- 核心域零第三方运行期依赖（Office 域基于 Apache POI 5.5.1；DB 域内置零依赖最小连接池）
- 测试全绿 · 覆盖率门禁 · CI 全绿 · CodeQL + Dependabot 自动依赖升级 · SpotBugs/Checkstyle 零告警
- 已发布 Maven Central：`sure-all` 一键引入，最新版本 **1.16.0**（JDK 25 基线 · Spring Boot 4.1.1）

[![源码](https://img.shields.io/badge/源码-GitHub-181717?logo=github&logoColor=white)](https://github.com/TASure/suretool)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.tasure/sure-all.svg)](https://central.sonatype.com/artifact/io.github.tasure/sure-all)
[![CI](https://img.shields.io/github/actions/workflow/status/TASure/suretool/ci.yml?branch=main&label=CI)](https://github.com/TASure/suretool/actions)
[![Coverage](https://img.shields.io/codecov/c/github/TASure/suretool)](https://codecov.io/gh/TASure/suretool)
[![Stars](https://img.shields.io/github/stars/TASure/suretool)](https://github.com/TASure/suretool)

### 📦 全部项目一览 All Repositories

| 仓库 | 说明 | 语言 | Stars | 最近更新 |
|------|------|------|:----:|---------|
| [sureai](https://github.com/TASure/sureai) | 零第三方依赖的 Java 大模型统一接入工具库（23 平台 · 41 模块） | Java | 1 | 2026-10-10 |
| [suretool](https://github.com/TASure/suretool) | 小而全的 Java 工具类库（28 模块 · 已发布 Maven Central） | Java | 1 | 2026-10-10 |
| [TASure](https://github.com/TASure/TASure) | GitHub 主页（本仓库） | - | 0 | 2026-10-08 |

---

## 🛠️ 技术栈 Tech Stack

| 领域 | 技术 |
|------|------|
| 语言 | Java 21 / 25（record · pattern matching · switch 模式 · 虚拟线程） |
| 构建 | Maven 多模块 · Maven Wrapper · BOM 统一版本管理 |
| 测试 | JUnit 5 · Jacoco 覆盖率门禁 · SpotBugs / Checkstyle 零告警 |
| 质量 | GitHub Actions CI · CodeQL 安全扫描 · Dependabot 自动依赖升级 · 发布级 `clean verify` 门禁 |
| 发布 | Maven Central（`io.github.tasure`）· GPG 签名 · GitHub Releases |
| 自研 | 轻量 JSON / HTTP · SSE 流式 · 加密 / JWT / DFA · MCP · Agent / RAG · GraalVM native-image · OTel 可观测 |

---

## 📈 GitHub 统计 Stats

| 指标 | 数值 |
|------|------|
| 公开仓库 | 3 |
| 总 Star | 2 |
| 总 Fork | 1 |
| 关注者 | 0 |
| 数据同步于 | 2026-10-11 03:23 (UTC+8) |

---

## 📅 最近动态 Recent Activity

- 2026-10-10 · **sureai**：test(coverage): agent 干净单轮 97.85%→98.29%（miss 34→27，确定性补 Error/中断/maxIterations 分支）
- 2026-10-10 · **sureai**：test(coverage): 修复干净单轮下时序竞争并补测防御分支，mcp/mcp-server 稳定 ≥98%
- 2026-10-10 · **suretool**：feat(core): 批36 新建 SetUtil 20 方法（对标 Guava Sets 高频，v1.17.0）
- 2026-10-10 · **suretool**：release: bump to 1.16.1-SNAPSHOT after v1.16.0
- 2026-10-08 · **TASure**：chore: auto-sync profile README (2026-10-09 03:24 UTC+8)
- 2026-10-08 · **TASure**：chore: auto-sync profile README (2026-10-08 09:20 UTC+8)

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
