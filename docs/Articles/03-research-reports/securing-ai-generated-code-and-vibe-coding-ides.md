---
title: "保护 AI 生成代码与 Vibe Coding IDE 的安全"
---

# Securing AI-Generated Code and Vibe Coding IDEs

<div style="font-size: 16px; color: var(--vp-c-text-2); font-weight: 400; margin-top: 8px; margin-bottom: 24px;">保护 AI 生成代码与 Vibe Coding IDE 的安全</div>

<div class="article-meta" style="margin-bottom: 24px;">
  <span class="article-date">2025-05-27</span>
  <span style="margin: 0 12px; color: var(--vp-c-text-2);">•</span>
  <span style="color: var(--vp-c-text-2);">Backslash Security / 安全白皮书</span>
</div>

## 摘要

这份白皮书聚焦“vibe coding 对软件供应链安全意味着什么”，核心关键词包括 AI-generated code security、vibe coding IDEs、supply chain risk、secure SDLC、threat modeling。 报告先从 Karpathy 的定义切入，指出当开发者通过自然语言让 IDE 自动生成和修改代码时，传统代码审查与依赖治理流程很容易被绕过，从而引入难以察觉的脆弱性与合规风险。 创新点在于提出了一整套“安全 vibe coding”实践框架：包括要求 IDE 提供可追踪的变更日志、为 AI 生成代码设置额外审核关卡、结合 SAST/DAST 与 SBOM 工具，以及在提示工程阶段就嵌入安全约束。 报告并引用了若干来自客户环境的匿名事件和业界公开事故（如 AI 脚本误删数据、引入弱密码逻辑等），指出企业若完全跟随“忘记代码存在”的叙事，会在审计、责任划分和事件响应上付出高昂代价，因此建议将 vibe coding 纳入现有 DevSecOps 与治理体系。​

## 原文链接

[Securing AI-Generated Code and Vibe Coding IDEs](https://www.backslash.security/resources/vibe-coding-security-whitepaper)

---

**返回：** [优质文章篇](/Articles/) > [研究报告](./)
