# 阿浩_Learn 工具箱【视频配套】

「阿浩_Learn」视频里用到的提示词和 Skill。

## 已更新

| 期数 | 视频 | 内容 |
|---|---|---|
| 第 2 期 | 习惯让 AI 总结，正在毁掉你的学习 | [让 AI 考你](prompts/02-让AI考你.md)：别让 AI 替你总结，让它出题考你<br>[思维教练](skills/thinking-coach/SKILL.md)：一次问你一个问题，直到你能用自己的话讲清楚 |
| 第 5 期 | 半小时的事，为什么能拖延一整天？ | [拖延检视](prompts/05-拖延检视.md)：先问你卡在哪，再把第一步缩到最小<br>[拖延检视 Skill](skills/procrastination-coach/SKILL.md)：同样的引导，装进 AI agent 里随时用<br>[回收站实验 Skill](skills/recycle-bin-draft/SKILL.md)：写不出来是因为怕被评价时用。每天写半小时放进回收站，只收不评，攒够了再还原、再检查（[提示词版](prompts/05-回收站实验.md)给没法装 Skill 的人） |
| 第 6 期 | 不知道以后想干什么，怕学了被AI取代，还错不起 | [人生设计](prompts/06-人生设计.md)：用《斯坦福大学人生设计课》的方法想清楚以后怎么过（四个仪表、美好时光日志、三个五年计划、去试、做选择）<br>[人生设计 Skill](skills/life-design/SKILL.md)：完整版，每个练习有做法和模板，记录存在你电脑上 |

## 提示词

在 `prompts/` 里，按期数命名。每个文件里写了什么时候用、怎么用。

## 安装 Skill

把下面这段发给你的 AI agent（Claude Code、Codex、Cursor 等），让它帮你装：

<!-- install-prompt -->
```text
帮我安装这个仓库里的 Skill：https://github.com/ahao-learn/ahao-learn-toolkit
把 skills/ 下的 thinking-coach、procrastination-coach 和 recycle-bin-draft 文件夹装到你的 Skill 目录（Claude Code 是 ~/.claude/skills/），装好后告诉我怎么用。
```
<!-- /install-prompt -->

装好后，跟 AI 说“用思维教练考考我”“我又在拖延了”，或者“开始回收站实验”，就会开始。

用 Obsidian 的话，插件 [FLOWnote](https://github.com/1095327780/FLOWnote) 已经内置了思维教练。

## 仓库地址

- GitHub：https://github.com/ahao-learn/ahao-learn-toolkit
- 国内镜像（CNB）：https://cnb.cool/ahao-learn/ahao-learn-toolkit

两边内容一样，GitHub 更新后会自动同步到 CNB。

## 许可

MIT
