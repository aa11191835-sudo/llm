# Agent 如何運作？

教學用循環：**接收目標 → 規劃 → 行動 → 觀察結果 → 調整或停止**。

1. 確認目標和限制。
2. 拆成小步驟，決定是否需要工具或額外資料。
3. 呼叫工具或與環境互動。
4. 檢查結果成功與否、是否完整。
5. 修正計畫，或在完成、失敗、資訊不足、達到步數上限時停止。

ReAct 研究讓語言模型交替產生推理文字和行動，使環境回饋可影響後續步驟。它是研究範式之一，並非所有 Agent 的固定標準；工具結果也仍需檢查。

**來源：**[Yao et al., ReAct](https://arxiv.org/abs/2210.03629)；[Weng, LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/)。