# 大模型安全论文周报 (2026-03-15)

> 由 OpenClaw 自动生成，每周精选论文深入解读

---

## 论文 1: Safety and Security Analysis of Large Language Models
**arXiv: 2509.10655**

### 核心观点
- LLMs 面临对抗性操纵和利用的漏洞
- 提出 **RSI (风险严重指数)** 量化评估 LLMs 安全态势
- 发现测试的 LLMs **安全过滤器存在广泛漏洞**

### 评估的 9 个模型
| 模型 | 发布者 | 日期 |
|------|--------|------|
| Claude Opus 4 | Anthropic | May 2025 |
| DeepSeek V3 | DeepSeek | Dec 2024 |
| GPT-4o | OpenAI | May 2024 |
| Gemini 2.5 Flash | Google | June 2025 |
| Grok 3 | xAI | Feb 2025 |
| Llama 4 Scout | Meta | Apr 2025 |
| Mistral 7B | MistralAI | Sep 2023 |
| Qwen 3 1.7B | Alibaba | Apr 2025 |

### 评估方法
- 对抗 24 个安全类别测试：暴力犯罪、非法活动、网络安全威胁等
- 使用 Risk Severity Index (RSI) 评估

### 实验数据
- **Defect Rate**: DeepSeek V3 达到 0.840 (最高风险)
- **Claude Opus 4** 和 **GPT-4o** 相对最强
- **开源模型**（Llama、Mistral、Qwen）更容易被攻击

### 主要发现
1. 测试的 LLMs 安全过滤器存在**广泛漏洞**
2. 呼吁需要**更强的对齐和负责任的部署**
3. 对开源和快速迭代的模型需要特别关注
4. 需要对 LLMs 潜在危害进行**彻底评估**

---

## 论文 2: LLM Security - Vulnerabilities, Attacks, and Defenses
**arXiv: 2505.01177**

### 核心观点
- AI 领域出现大型语言模型 (LLMs)，基于 Transformer 架构
- LLMs 在教育、医疗、客户支持等领域有广泛应用

### 安全威胁类型
1. **Prompt Injection** - 对输入的微小修改会大幅改变输出
2. **Privacy Breaches** - 隐私泄露
3. **Training Phase Attacks** - 训练阶段攻击
4. **Post-deployment Attacks** - 部署后攻击

### 研究问题
- 对 LLMs 漏洞的全面调查仍然不足
- 需要系统性的防御策略

---

*每周一自动更新*
