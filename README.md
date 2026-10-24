# Codex Skills

这里收录可复用的 Codex Skill。目前公开的是一项试卷反馈流程；以后会逐项审核并加入更多 Skill。

## Exam Feedback Coach

[查看 Skill](skills/exam-feedback-coach/SKILL.md) · [下载压缩包](https://github.com/Gianda-Wang/codex-skills/releases)

把试卷、参考答案和小题得分整理成可核对的教学反馈。它会分阶段询问老师希望达到的成果程度、实际可用的学习材料和特殊要求，再决定分析深度与输出形式。默认可以生成四类内容：

1. 试卷与逐题分析
2. 整班学情和后续教学重点
3. 教师用的逐人分析与重点跟进依据
4. 面向家长的逐人建议

有多次可比考试时，也可以分析同一能力点的变化。Skill 要求核对学生与分数的对应关系，区分已观察到的得分事实、由题目表现支持的推测，以及需要答卷或教师观察才能确认的错因。

### 使用

将 `skills/exam-feedback-coach` 整个文件夹放入本机的 `~/.codex/skills/`，然后在 Codex 中使用 `$exam-feedback-coach`，提供本次考试材料和希望得到的成果。也可以先只提供现有材料，让 Skill 帮你判断还缺什么。

本仓库只包含通用 Skill 指令，不包含学生姓名、成绩、试卷或课堂资料。生成的教师逐人分析属于教师资料；向家长发布时应单独核对可见范围。

---

**English summary:** Exam Feedback Coach is a configurable Codex skill for evidence-based exam and item-score analysis. It helps teachers produce exam, class, teacher-only student, and family-facing feedback, with explicit data checks and cautious interpretation of error causes.
