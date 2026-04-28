# PM Interview Question Bank and Defense Patterns

Use this bank selectively. Do not dump all questions; choose what the JD and resume imply.

## Universal Must-Ask Questions

### 请做一个自我介绍

Interviewer wants:

- Who this candidate is.
- Whether experience matches the role.
- Whether expression is structured.
- What to ask next.

Answer structure:

> 背景 → 最相关经历 → 能力标签 → 岗位匹配

Avoid:

- Chronological life story.
- Too many unrelated experiences.
- Empty adjectives without proof.

### 介绍一个你最有代表性的项目

Interviewer wants:

- Problem definition ability.
- Real contribution.
- PM thinking.
- Result and reflection.

Answer structure:

> 项目背景 → 目标指标/用户问题 → 你的判断 → 关键动作 → 结果 → 复盘

Must include:

- Why the problem mattered.
- What tradeoffs were made.
- How success was measured.

### 为什么投这个岗位/公司

Interviewer wants:

- Whether the candidate understands the role.
- Whether motivation is specific.
- Whether there is long-term fit.

Answer structure:

> 业务兴趣 → 岗位职责匹配 → 过往经历连接 → 未来成长动机

Avoid:

- “平台大”.
- “我很喜欢产品”.
- “想学习”.

### 为什么你适合这个岗位

Answer structure:

> 岗位最需要A/B/C → 我分别有证据1/2/3 → 所以我能更快上手

## PM Core Capability Questions

### 如何判断需求优先级?

Strong structure:

1. Clarify objective and target metric.
2. Estimate user/business value.
3. Estimate effort and dependency.
4. Consider urgency and strategic importance.
5. Use MVP or experiment for uncertain high-potential ideas.

Sample wording:

> 我不会只按谁声音大来排优先级。我会先看这个需求服务哪个业务目标，再看影响用户规模、问题严重程度、预期收益、实现成本和依赖。如果收益高但不确定性也高，我会优先设计低成本验证，而不是直接做完整版。

### 指标下降怎么分析?

Strong structure:

1. Confirm data reliability.
2. Decompose metric formula and funnel.
3. Segment by user, channel, version, device, region, time.
4. Check recent changes and external factors.
5. Form hypotheses.
6. Validate with data and user feedback.
7. Implement and monitor.

### 如何做用户研究?

Strong structure:

1. Define research question.
2. Select target users.
3. Combine qualitative and quantitative methods.
4. Distinguish stated wants from real behavior.
5. Translate insights into requirements.
6. Validate after launch.

### 如何推动跨团队协作?

Strong structure:

1. Align on common objective.
2. Clarify responsibility and timeline.
3. Make tradeoffs visible.
4. Communicate risks early.
5. Use data/user value to resolve disagreement.
6. Document decisions and follow up.

## Risk Defense Patterns

### “你这个项目是不是更偏运营，不像产品?”

Defense:

> 这个项目确实有运营执行部分，但我在里面做的不只是执行。我主要参与了三个产品相关动作：第一是拆用户路径，找到关键流失/转化问题；第二是设计机制或流程，而不是只做活动；第三是看数据和反馈复盘效果。所以我会把它理解为一个产品运营结合的项目，但里面有比较明确的产品思考。

Upgrade if evidence exists:

- Mention user journey.
- Mention mechanism design.
- Mention metrics.
- Mention iteration.

### “你没有完整产品实习，为什么能胜任PM?”

Defense:

> 我确实还没有完整独立负责一个商业产品的经历，所以我不会夸大自己。但我过去的经历已经覆盖了产品新人最关键的几个底层能力：用户问题拆解、数据意识、方案表达和跨角色推进。这个岗位如果是实习/校招，我认为核心不是立刻独当一面，而是能不能快速理解业务、把问题讲清楚并推动执行。这些能力我有具体项目可以证明。

### “这个数据怎么归因?”

Defense:

> 这个数据不能完全归因于我个人或单一方案。当时我们主要通过上线前后对比/分渠道观察/用户反馈来判断效果。严格来说，如果重新做，我会设计实验组和对照组，并提前定义主指标、副指标和观察周期。这个项目给我的一个反思也是，产品结果要尽量用更严谨的实验方式验证。

### “你在项目里到底负责什么?”

Defense:

> 我负责的部分主要是三块：第一，前期问题拆解和信息整理；第二，方案设计中的{specific part}; 第三，上线/执行后的数据观察和复盘。不是所有事情都是我一个人完成的，但这些环节是我实际推动或深度参与的。

### “为什么从原方向转产品?”

Defense:

> 我不是突然转向，而是在过去{experience}中发现自己更感兴趣的是“为什么用户会这样做、怎么设计机制让问题被更好解决”。相比单纯执行，我更喜欢把用户、业务和方案连接起来。后来我也通过{project/course/tool/internship}补了产品方法和实践，所以这次投递是基于已有经历后的明确选择。

### “你的缺点是什么?”

Defense structure:

> 真实但不致命的问题 → 具体场景 → 改进动作 → 已有改善

Avoid:

- “太追求完美”.
- “工作太投入”.
- Fatal PM weaknesses like no communication, no logic, no ownership.

## Product Case Opening Templates

### Optimize a metric

> 我会先明确这个指标的定义和业务目标，再把它拆成用户路径或公式，定位影响最大的环节。接着结合用户分层和场景判断原因，优先选择影响大、成本低、可验证的方案，最后用主指标、副指标和负向指标一起评估。

### Design a feature

> 我会先确认目标用户和核心场景，判断这个需求解决的是真问题还是表层诉求。然后拆当前路径的痛点，给出MVP方案，并说明它如何影响目标指标。最后考虑异常情况、上线验证和后续迭代。

### Analyze a product

> 我会从用户、场景、需求、路径、商业目标和指标六个角度看。先判断它服务谁、解决什么问题，再看当前体验中哪些环节影响转化或留存，最后提出可以验证的优化假设。

## Smart Interviewer Questions

Choose 3-5:

- 这个岗位入职后最核心的业务目标是什么?
- 目前团队最希望这个角色解决的问题是什么?
- 如果我加入，前三个月最期待我在哪些方面产生价值?
- 这个岗位更偏策略探索、需求落地，还是跨团队项目推进?
- 团队现在判断一个PM表现好的核心标准是什么?
- 这个方向当前最大的产品挑战是用户理解、增长、商业化，还是内部协作?
- 对这个岗位来说，您觉得最容易做错的一点是什么?