# Hi, I'm Jun 👋

**English** · [中文](README.zh-CN.md)

I'm an AI engineer and creator based in Hong Kong. I build Agent workflows and the harness around them: reviewable plans, explicit approval, evidence, validation, and usable artifacts.

My public projects focus on spoken media and document workflows, where planning, evidence and validation turn Agent output into something people can review and use.

[LinkedIn](https://www.linkedin.com/in/huzujun/) · [X](https://x.com/poet_coder) · [Xiaohongshu · 诗人程序员 Jun.AI](https://www.xiaohongshu.com/user/profile/5b40fe744eacab72c9f480ef) · [PoetCut](https://poetcut.online/)

## Inspect the projects

### [MotionTalk](https://github.com/PoetCoderJun/MotionTalk)

Edited video + final SRT → a director plan → one approval → a packaged motion-graphics video.

**Engineering evidence:** [Harness case study](https://github.com/PoetCoderJun/MotionTalk/blob/main/docs/harness-case-study.en.md), [plan validator](https://github.com/PoetCoderJun/MotionTalk/blob/main/scripts/validate_plan.py), [final validator](https://github.com/PoetCoderJun/MotionTalk/blob/main/scripts/validate_master.mjs), and [tests](https://github.com/PoetCoderJun/MotionTalk/tree/main/tests). Deterministic checks validate structure and recorded evidence; the Agent still judges visual meaning. Original repository material is non-commercial under CC BY-NC-SA 4.0; commercial use requires prior written permission.

### [clean-talking-video](https://github.com/PoetCoderJun/clean-talking-video)

Raw talking-head video → subtitle review → edited MP4 + SRT aligned to the new timeline. Preserves meaningful emphasis while removing failed takes, filler and dead time.

**Engineering evidence:** [subtitle approval and rendering workflow](https://github.com/PoetCoderJun/clean-talking-video/blob/main/clean-talking-video/SKILL.md) and [tests](https://github.com/PoetCoderJun/clean-talking-video/tree/main/tests). ASR uses DashScope cloud audio upload; it is not a fully local workflow.

### [DingTalk-style Minutes](https://github.com/PoetCoderJun/dingtalk-style-minutes)

Recording or existing transcript → overview, editable Feishu graphic minutes, evidence-linked notes, and complete timestamped transcript.

**Engineering evidence:** [workflow and dependency contract](https://github.com/PoetCoderJun/dingtalk-style-minutes/blob/master/skill/dingtalk-style-minutes/SKILL.md), [visual samples](https://github.com/PoetCoderJun/dingtalk-style-minutes/tree/master/examples/sections), and [tests](https://github.com/PoetCoderJun/dingtalk-style-minutes/tree/master/tests). Local ASR does not make Feishu delivery fully local.
