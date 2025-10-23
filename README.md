# SolarPunk-Protocol

demo:
https://little-green-ranger.vercel.app/


SolarPunk Protocol is a DePIN + ReFi infrastructure on Solana that turns LGRlight into on-chain truth. We capture solar energy data via IoT devices, mint kWh-backed tokens on Solana, and create a new paradigm for decentralized energy ownership. Our protocol enables anyone to tokenize their renewable energy production and participate in the green economy revolution.


# SolarPunk Protocol — 演示文稿（中文）

## 1 — 标题与愿景

**SolarPunk Protocol**
**去中心化能源，代币化阳光**

我们让阳光成为链上的真实。

这是一个基于 **Solana** 的 DePIN + ReFi 基础设施协议，
将现实世界的太阳能转化为可验证、可交易的数字资产。

---

## 2 — 问题

* 当今能源生产 **高度集中且不透明**
* 太阳能数据被 **封闭在企业或机构系统中**
* 可再生能源凭证（REC）**价格高、结算慢、难验证**
* 个体发电者 **无法证明或变现他们的发电贡献**

---

## 3 — 解决方案

**SolarPunk Protocol** 实现太阳能发电数据的去中心化验证与代币化：

1. **IoT + Solana 基础设施：** 数据记录器通过 MQTT/HTTP 上传发电数据 → Solana RPC → 链上能源生产证明（PoEP）。
2. **代币化层：** 每 1 千瓦时（kWh）发电量 = 1 枚 $LGR 代币（可自定义比例）。
3. **ReFi 模块：** $LGR 可用于质押、交易或兑换碳信用资产。
4. **开放协议：** 开发者与能源社区可直接调用 API / SDK 接入 SolarPunk 网络。

---

## 4 — 技术架构

```
[ 太阳能板 ]
     ↓
[ 数据记录器 / RS485 ]
     ↓ MQTT / Express API
     ↓
[ Solana 智能合约 (Anchor) ]
     ↓
[ 铸造 $LGR 代币 ]
     ↓
[ 仪表盘 + 钱包 + 区块浏览器 ]
```

**：**

* 后端：Node.js / Express / MQTT
* 链上：Solana + Anchor (Rust)
* 前端：React + Wallet Adapter
* 数据证明：IoT 签名负载 + 时间戳验证

---

## 5 — 代币经济（ReFi 层）

| 行为      | 链上效果      | 奖励    |
| ------- | --------- | ----- |
| 产生太阳能   | 铸造 $LGR   | 发电收益  |
| 质押 $LGR | 获得 $ECO   | 绿色激励  |
| 销毁 $LGR | 生成碳信用 NFT | 可持续证明 |

**目标：** 建立一个去中心化的绿色金融体系——*让可持续性本身也能产生收益。*

---

##  6 — 为什么选择 Solana

* 高吞吐量，适合 **实时 IoT 能源数据写入**
* 低 Gas 成本 → 支持 **微量能源交易**
* 活跃的 **DePIN 与 ReFi 生态**（Helium、Render、Hivemapper）
* 完善的基础设施（RPC 服务、索引器、钱包支持）

**能源上链需要速度、透明度与可组合性——Solana 拥有这三者。**

---

## 7 — 应用场景

* 家庭太阳能发电者赚取 $LGR 收益
* 企业 ESG 报告的链上绿色能源数据验证
* 碳信用市场基于 $LGR 的追踪与交易
* 政府/NGO 激励清洁能源生产

---

##  8 — 路线图

**2025 Q1：** MVP 原型 — 数据记录器 → Solana → 仪表盘
**2025 Q2：** 公测网络 + ReFi 流动性池集成
**2025 Q3：** 与太阳能硬件厂商达成合作
**2025 Q4：** 主网发布 + DAO 治理（SolarDAO）

---

## 9 — 加密朋克宣言

> 在一个能源被垄断、生态被摧毁的世界，
> 我们选择重写能源的所有权规则。
>
> 每一瓦电力，都应属于创造它的人。
> 无论是屋顶工人、戈壁板阵，还是追光的工程师。
>
> 我们不只是写代码，我们在设计能源自由的未来。
> **革命不会被中心化，它将由阳光引爆。**

---

## 幻灯片 10 — 行动呼吁

加入 SolarPunk 运动。
让开源能源属于每一个人。

🌞 官网：[solar.team](https://solar.team)
💻 GitHub：[github.com/SolarPunkProtocol](https://github.com/SolarPunkProtocol)
🐦 Twitter：[@SolarPunkXYZ](https://twitter.com/SolarPunkXYZ)

**打造太阳能经济，从一缕阳光开始。**
