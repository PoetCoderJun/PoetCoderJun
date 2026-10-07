# 你好，我是 Jun 👋

[English](README.md) · **中文**

我是在香港工作的 AI 工程师与创作者。我构建 Agent 工作流，以及让它可交付的 Harness：可审查的计划、明确审批、证据、验证与可继续使用的成品。

我的公开作品主要围绕口述媒体与文档工作流：通过规划、证据与验证，把 Agent 的输出变成可以审阅、可以使用的成品。

[LinkedIn](https://www.linkedin.com/in/huzujun/) · [X](https://x.com/poet_coder) · [小红书 · 诗人程序员 Jun.AI](https://www.xiaohongshu.com/user/profile/5b40fe744eacab72c9f480ef) · [PoetCut](https://poetcut.online/)

## 从作品检查实现

### [MotionTalk](https://github.com/PoetCoderJun/MotionTalk)

精剪视频 + 最终 SRT → 导演计划 → 一次批准 → MG 包装成片。

**工程证据：**[Harness 案例](https://github.com/PoetCoderJun/MotionTalk/blob/main/docs/harness-case-study.md)、[计划验证器](https://github.com/PoetCoderJun/MotionTalk/blob/main/scripts/validate_plan.py)、[成片验证器](https://github.com/PoetCoderJun/MotionTalk/blob/main/scripts/validate_master.mjs)与[测试](https://github.com/PoetCoderJun/MotionTalk/tree/main/tests)。确定性检查验证结构与已记录证据，画面语义仍由 Agent 判断。仓库原创内容采用 CC BY-NC-SA 4.0，仅限非商业使用；商业使用需事先获得书面许可。

### [clean-talking-video](https://github.com/PoetCoderJun/clean-talking-video)

原始口播 → 字幕审阅 → 精剪 MP4 + 与新时间线匹配的 SRT。删除失败重说、口头禅与无意义停顿，同时保留正常强调。

**工程证据：**[字幕审批与渲染流程](https://github.com/PoetCoderJun/clean-talking-video/blob/main/clean-talking-video/SKILL.md)及[测试](https://github.com/PoetCoderJun/clean-talking-video/tree/main/tests)。ASR 会上传音频到 DashScope，不是全本地流程。

### [DingTalk-style Minutes](https://github.com/PoetCoderJun/dingtalk-style-minutes)

录音或现成转写 → 内容概览、可编辑飞书画板、带证据的纪要，以及完整时间戳转写。

**工程证据：**[工作流与依赖契约](https://github.com/PoetCoderJun/dingtalk-style-minutes/blob/master/skill/dingtalk-style-minutes/SKILL.md)、[视觉样例](https://github.com/PoetCoderJun/dingtalk-style-minutes/tree/master/examples/sections)及[测试](https://github.com/PoetCoderJun/dingtalk-style-minutes/tree/master/tests)。本地 ASR 不等于飞书交付全本地。
