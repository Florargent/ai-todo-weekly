# AI智能任务管理与周报生成器

基于 Vue3 + Vite + Pinia + 火山Deepseek大模型 的智能任务管理系统，支持自然语言输入生成任务、SSE实时响应、自动周报生成。

**在线体验**：https://floraragent.github.io/ai-todo-weekly/

## 技术栈
- Vue3 + Vite + Pinia + TypeScript
- 火山Deepseek R1 大模型API + Prompt工程
- SSE 流式响应
- Axios 请求处理

## 主要功能
- 自然语言转结构化任务列表
- SSE 实时响应与异常数据降级处理
- 自动生成周报
- GitHub Pages SPA路由404问题解决

## 核心亮点
- 自主实现SSE流式解析逻辑，处理大模型不稳定返回
- 项目从需求拆解到部署上线全流程独立完成
