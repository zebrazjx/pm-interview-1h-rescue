---
name: pm-interview-1h-rescue
description: "This skill should be used when a user needs a last-hour product manager interview rescue pack from a resume and target JD. It creates a customized PM interview battle plan, including JD intent decoding, resume-JD fit diagnosis, strongest experience selection, self-introduction scripts, high-probability questions, risk defenses, product case frameworks, interviewer questions, and 60/30/15-minute cram plans. Trigger keywords include 产品经理面试, PM面试, 面试前1小时, 简历和JD, 面试急救包, JD拆解, 自我介绍, 高频面试题, product manager interview, resume JD interview prep."
---

# PM Interview 1h Rescue

## Purpose

Create a high-conversion, last-hour interview rescue pack for product manager candidates. Optimize for interview performance, not generic preparation: translate the JD into hiring intent, extract the strongest proof from the resume, predict the interviewer’s questions, and generate concise scripts the candidate can say aloud.

Treat the output as a **PM interview battle plan**. The goal is to raise the candidate’s probability of passing by improving fit expression, answer readiness, risk defense, and interviewer recall.

## Required Inputs

Ask for missing required inputs only when absent:

1. Resume or structured experience summary.
2. Target job description/JD.

Proceed without blocking when optional inputs are missing:

- Company name and product/business line.
- Interview round: HR,业务一面,主管面,终面,群面,case面.
- Candidate seniority: 实习,校招,社招,转岗.
- Time left: 60min, 30min, 15min, or custom.
- Biggest worry: no PM experience, weak data, project sounds operational, career switch, low company knowledge, case interview, English interview, pressure interview.

If resume or JD content is too thin, explicitly state the limitation and produce a best-effort rescue pack with assumptions.

## Core Principle

Do not produce generic interview advice. Every recommendation must connect to at least one of:

- A JD signal.
- A resume proof point.
- A PM interview evaluation dimension.
- A likely interviewer concern.
- A time-boxed action the candidate can complete before the interview.

Prioritize what can be used in the room. Prefer scripts, answer structures, risk defenses, and one-page cram notes over long explanations.

## Workflow

### 1. Decode the JD Hiring Intent

Infer the real hiring problem behind the JD, not just the listed responsibilities.

Identify:

- Product role type: growth, C-side, B-side, AI product, commercial, strategy, platform, data, community/content, e-commerce/transaction, international, tool/SaaS, marketplace, product operations hybrid.
- Business stage: 0-1 exploration, 1-10 growth, mature optimization, internal platform construction, commercialization, retention/activation, efficiency improvement.
- Core PM capabilities ranked by importance.
- Hidden concerns implied by wording.
- Likely interview evaluation criteria.
- Questions likely to be asked from each JD line.

Use `references/role-archetypes.md` for role-specific interview priorities.

### 2. Diagnose Resume-JD Fit

Create a matching matrix. Do not merely summarize the resume.

For each major JD requirement:

- Extract the strongest corresponding resume evidence.
- Rate fit as 高/中/低.
- Explain why the evidence is or is not convincing.
- Convert the evidence into interview language.
- Flag missing evidence and propose a compensation strategy.

Find the candidate’s top 3 strongest experiences for this interview. Choose experiences by JD relevance and story density, not by chronological importance.

### 3. Define the Candidate Positioning

Create one memorable interviewer takeaway:

> 把候选人定位成：{X型产品候选人}

Examples:

- 数据驱动型增长产品候选人
- 有用户洞察的C端产品新人
- 懂业务流程的B端产品候选人
- 有AI工具实践经验的产品候选人
- 执行力强、能推动落地的0-1产品实习生
- 内容生态理解强的社区产品候选人

Then define three narrative pillars the candidate should repeatedly return to during the interview.

### 4. Build the Interview Answer Arsenal

Generate practical answer assets:

- 30-second self-introduction.
- 90-second self-introduction.
- “Why this role/company” answer.
- Three flagship experience stories using a PM-oriented STAR+R structure.
- High-probability question predictions with answer strategy and sample wording.
- Risk questions with defensive scripts.
- Product case framework adapted to the JD role type.
- Three to five smart questions to ask the interviewer.

Use `references/question-bank.md` for question prediction and `references/output-template.md` for final packaging.

### 5. Create Time-Boxed Cram Plan

Adapt the rescue pack to the time left:

- 60-minute mode: complete battle plan.
- 30-minute mode: compress to positioning, top 3 experiences, top 5 questions, top 3 risks, 30-second intro.
- 15-minute mode: produce only one-page emergency notes.

Always include a final “last 10 minutes only read this” page.

Use `references/time-modes.md` for prioritization rules.

## Output Requirements

Use Chinese by default unless the user requests another language.

Produce output in this order:

1. **面试胜率判断**: one blunt paragraph on current fit and the highest-leverage improvement.
2. **本岗位真实招聘意图**: what the team likely wants and fears.
3. **你的面试定位**: one-line positioning and three narrative pillars.
4. **JD-简历匹配矩阵**: requirement, evidence, fit, interview expression, risk.
5. **三张王牌经历**: question coverage, STAR+R story, must-say details, avoid-saying details, likely follow-ups.
6. **高频问题预测与答案**: 必考题, 高概率题, 风险题, case题.
7. **自我介绍与动机话术**: 30-second intro, 90-second intro, why role/company.
8. **PM专属临场框架**: role-specific case/product analysis framework.
9. **反问面试官问题**: high-signal questions tied to the role.
10. **最后10分钟速记页**: one compact checklist.

For long outputs, start with a one-page emergency summary, then provide detailed sections.

## Quality Bar

Before finalizing, check:

- Does every major claim tie back to resume, JD, or PM evaluation logic?
- Are the top 3 experiences truly the best fit for this JD?
- Are the sample answers speakable in an interview, not essay-like?
- Are weak points handled honestly instead of disguised with empty praise?
- Does the candidate know what to stop reading in the last 10 minutes?
- Would an interviewer remember the candidate as one clear type of PM?

## Failure Modes to Avoid

Avoid:

- Generic “了解公司、熟悉岗位、调整心态” advice without customization.
- Long theoretical PM frameworks with no connection to the JD.
- Overclaiming candidate achievements or inventing metrics.
- Encouraging candidates to memorize too many answers.
- Treating all PM roles the same.
- Rewriting the resume instead of preparing interview behavior.
- Ignoring red flags because the user wants encouragement.

## References

Load references only as needed:

- `references/output-template.md`: detailed rescue pack structure and reusable answer format.
- `references/role-archetypes.md`: PM role archetypes and interview priorities.
- `references/question-bank.md`: question prediction bank and risk defense patterns.
- `references/time-modes.md`: 60/30/15-minute prioritization rules.
