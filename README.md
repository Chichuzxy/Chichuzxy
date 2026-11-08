# Chichu

区块链技术应用专业 · 2027 届 · 找软件测试 / Java 开发实习

**能把乱代码理出结构，再用测试证明它真能跑。**

---

## 三个能自己跑的项目

### [student-scholarship](https://github.com/Chichuzxy/student-scholarship) · Java 分层重构

把 277 行的单文件课程作业拆成实体、规则、业务、入口四个类，修掉三处逻辑缺陷：
每个等级只评一人就 break、名为冒泡实为选择排序、数据硬编码在方法体里。

**21 条自测用例，全部通过。** `javac` + `java` 直跑，零外部依赖。

### [student-info-system](https://github.com/Chichuzxy/student-info-system) · Python + SQLite + Tkinter

数据层、业务层、命令行、图形界面四层分离。原版依赖 MySQL，界面在连接不稳时会卡住，
换成 SQLite 单文件后彻底解决；业务层不碰输入输出，所以能直接单测。

**31 条单元测试，全部通过。** 覆盖加权规则、越界输入、重复约束、级联删除、排名统计。

### [AgentGuard402](https://github.com/Chichuzxy/AgentGuard402) · 链上支付策略预检

给 AI Agent 的链上支付做前置护栏：单笔上限、收款方白名单、日额度、nonce 防重放、
策略冻结。跑通 16 个端到端场景，其中 12 类非法请求全部在预检阶段拦下、交易未发出、**0 gas**。

**17 个 Foundry 用例，全部通过**；6 笔真实交易可在 [Fuji 浏览器](https://testnet.snowtrace.io/address/0xA79b564BcB53fab8B218C6707d815585338b6E6C) 复核。

---

## 其他项目

- [avaxguard](https://github.com/Chichuzxy/avaxguard) — ERC20 授权风险扫描 + 一键 revoke
- [privacy-ai-helper](https://github.com/Chichuzxy/privacy-ai-helper) — Aleo ZK 隐私顾问（Leo 电路）
- [ai-monad-explorer](https://github.com/Chichuzxy/ai-monad-explorer) — AI 分析结果上链可复算
- [codex-notify](https://github.com/Chichuzxy/codex-notify) — 多 AI 任务完成通知（Python unittest 覆盖日志轮转边界）
- 毕业设计：数字版权存证与授权交易系统，FISCO BCOS + WeBASE，三合约真机部署

## 技术栈

Java · Python · SQL · Linux · Git · Docker · Solidity · Foundry · SQLite · Tkinter

---

## 我的代码习惯

- 写之前先理清数据流和表结构，接口先对齐约定再动手
- 交付前必须自测跑通，配 README 说明怎么跑、怎么复现
- 用 AI 工具提效，但产出逐条核对，不把「能跑」当「正确」

## 联系

- 国内：3046132635@qq.com
- 海外 / 长期：zxy2004sss@outlook.com
- 作品集：[chichuzxy.github.io](https://chichuzxy.github.io/)

中文沟通，测试网优先，不碰私钥。

目前找软件测试 / Java 开发实习；也接小额合约开发单，测试网优先，源码全交付。