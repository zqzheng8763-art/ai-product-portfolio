# AI Product Manager Portfolio

> **B2B / AI Product · Agent · Data-driven Product Design**

This repository is my product portfolio, documenting how I frame business problems, define product strategy, design AI capabilities, and translate ideas into prototypes and executable product requirements.

## Featured Projects

### 01 · 向由心生｜智能特价机票发现与决策平台

**AI decision support for flight discovery, price comparison and purchase timing**

**Role:** Product Manager  
**Type:** AI Product / Consumer Product  
**Focus:** AI Decision Support · Recommendation · TCO · Price Monitoring · Monetization

**Core question:**

> 用户不是缺一个“能买机票”的地方，而是缺一个能回答“去哪更划算、现在买还是等、真实总价是多少”的决策工具。

**Key product capabilities**

- 泛意图搜索：支持“任何目的地”“一个月内”“3 天”等模糊条件
- AI 决策建议：输出“购买 / 观望”结论、信心指数与关键依据
- TCO 精算：穿透行李、选座等附加费用，计算真实总价
- 智能监控：关注航线、涨跌追踪、红黄绿决策标签
- AI 种草：结合目的地 POI 与用户偏好生成推荐理由
- 商业化：VIP + CPS 导流 + B2B 数据订阅 / DaaS

[🚀 View Live Demo](https://ticket-venture-space.nocode.host) · [📖 View Case Study](./projects/01-xiang-you-xin-sheng/README.md)

## Product Thinking Highlights

### 1. From transaction to decision

Instead of competing with OTA platforms on booking fulfillment, the product occupies the **pre-purchase decision layer** and uses CPS to route users back to OTA / airline channels for final transactions.

### 2. From “cheap ticket” to real cost

The product treats the displayed fare as only one part of the decision. For complex airline rules, especially low-cost carriers, the design converts unstructured fee rules into structured inputs and calculates total cost of ownership (TCO).

### 3. From chatbot to evidence-based AI

The AI assistant “小太阳” does not directly invent price facts. Structured price data, inventory signals, promotion calendars and algorithmic forecasts are prepared first; the LLM is then used to generate an interpretable recommendation.

## Portfolio Roadmap

| Project | Primary capability | Status |
| --- | --- | --- |
| 01 · 向由心生 | AI decision support / TCO / recommendation | ✅ Available |
| 02 · Data Analysis Agent | B2B / Agent / business intelligence | Planned |
| 03 · AI Investment Product | Complex-domain AI / financial product design | Planned |

## Project Documentation

- [01 · 向由心生 Case Study](./projects/01-xiang-you-xin-sheng/README.md)
- [PRD](./docs/01-PRD.md)
- [Product Analysis](./docs/02-Product-Analysis.md)
- [AI Product Design](./docs/03-AI-Product-Design.md)
- [Metrics & Roadmap](./docs/04-Metrics-and-Roadmap.md)

## About This Repository

This is a product portfolio rather than a production software repository. It focuses on product reasoning, PRD, AI solution design, metrics and iteration strategy.

> Product demos and documents are portfolio materials. They do not represent production integrations with real airline / OTA supply chains or payment systems.
