# 智析 BizInsight · Interactive Demo

> **销售异常分析闭环｜可运行 MVP**

这是「智析 BizInsight」的可运行 Demo。它不是为了证明模型“会聊天”，而是让你亲手体验一次完整的经营分析任务：

**问题输入 → 数据确认 → 确定性计算 → 贡献拆解 → Evidence Gate → 假设验证 → 复盘摘要**

## 快速体验

当前 Demo 代码位于作品集构建目录，包含：

- `app.py`：Streamlit 应用
- `demo_sales_data.csv`：示例销售数据
- `demo_inventory_data.csv`：示例库存数据
- `requirements.txt`：运行依赖

本地运行：

```bash
pip install -r requirements.txt
streamlit run app.py
```

## 推荐体验路径

1. 选择「一键体验案例」
2. 输入 / 选择“看一下最近两周销售为什么下降”
3. 确认字段映射
4. 查看 GMV 异常与商品贡献拆解
5. 进入 Evidence Gate
6. 补充库存数据
7. 验证“缺货导致下滑”假设
8. 生成复盘摘要

## 这个 Demo 想证明什么？

### 1. LLM 不负责算数

关键指标、趋势、环比和贡献拆解由确定性计算完成；AI 层负责理解问题、组织分析路径和解释结果。

### 2. Contribution ≠ Causality

商品贡献只能说明“谁贡献了变化”，不能直接证明“谁导致了变化”。

### 3. Evidence Gate

当证据不足时，Demo 会显式暴露证据缺口，而不是自动生成一个听起来合理的原因。

### 4. Human-in-the-loop

人工只在字段映射、证据缺口和最终经营判断等关键节点介入。

## 产品边界

这是作品集中的 MVP / 概念验证，不代表已经接入真实企业生产环境。当前 Demo 使用 **Python + pandas 确定性计算 + 规则化流程模拟 Agent**，后续可以替换为真实 LLM、Schema 校验和工具路由。

[← 返回智析 Case Study](../README.md)
