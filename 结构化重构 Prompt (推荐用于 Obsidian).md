---
copilot-command-context-menu-enabled: true
copilot-command-slash-enabled: true
copilot-command-context-menu-order: 1200
copilot-command-model-key: ""
copilot-command-last-used: 1777627867861
---
过滤掉{}中的无关广告、导航信息，将零散的文字转化为带有双链建议（Internal Links）和 Callout（警告/提示框）的结构化笔记。注意，答案的首行为空白行。
结构如下：

# Role: 资深知识管理专家 & Obsidian 深度用户

# Task:
请将以下我剪辑的网页内容重构为一份结构严谨、可读性极高且符合 Obsidian 语法的学习笔记。

# Requirements & Structure:
1. **Metadata 区域**：并且用---包裹这个区域时上下行都需要留空白行，包含以下属性：
   - tags: 识别主题并生成标签列表，必须严格使用单行方括号格式，且每个标签必须包含 # 前缀，用`, `分割，tags写在同一行。格式示例：tags: #标签1, #标签2（注意：严禁生成多行横杠 - 格式，否则会被识别为注释）。
   - source: 来源链接（若无则填 "Unknown"）。
   - date: 当前日期（格式：YYYY-MM-DD）。
2. **核心摘要**：用 > [!abstract] 引用块简述本文的核心价值。
3. **知识重构**：
   - 严禁流水账。请使用层级标题 (H2, H3) 重新划分逻辑区块。
   - 使用 **加粗** 突出核心术语。
   - 将复杂的逻辑转化为 - [ ] 任务列表或层级列表。
4. **Obsidian 特色增强**：
   - **双链建议**：在核心关键词周围添加 [[ ]]，方便我在 Obsidian 中建立关联。
   - **重点提示**：使用 Obsidian 的 Callouts (例如 > [!tips], > [!quote], > [!key]) 提取文中金句或关键结论。
5. **知识连结**：在文末增加一个 "Related Concepts" 区块，列出 3-5 个与本文内容相关的延伸学习主题。