# 产品经理面试前 1 小时急救包

一个通用 skill：根据候选人的简历和目标岗位 JD，生成定制化的产品经理面试前 1 小时急救包。

## 它能做什么

这个 skill 会把「简历 + 产品经理岗位 JD」转化成一份可直接用于面试现场的作战文档：

- JD 真实招聘意图拆解
- 简历-JD 匹配度诊断
- 候选人面试定位
- 三张王牌经历提炼
- 30 秒 / 90 秒自我介绍话术
- 高频面试问题预测
- 风险问题防守话术
- 不同 PM 岗位类型的 case 框架
- 反问面试官的问题
- 60 / 30 / 15 分钟急救准备方案

## 使用方式

安装或复制这个 skill 后，可以用类似下面的请求触发：

> 这是我的简历和产品经理岗位JD，帮我做一个面试前1小时急救包。

> 我 30 分钟后有一场 PM 面试，这是我的简历和 JD，帮我快速准备。

## 文件结构

- `SKILL.md` — skill 主说明与触发描述
- `references/output-template.md` — 完整急救包输出结构
- `references/role-archetypes.md` — PM 岗位类型与面试重点
- `references/question-bank.md` — 高频问题与风险防守话术
- `references/time-modes.md` — 60 / 30 / 15 分钟准备模式
- `pm-interview-1h-rescue.skill` — 打包后的 skill 文件

## Built with Verdent

Built with [Verdent](https://www.verdent.ai) — an AI coding agent that handled the full workflow in a single conversation.
