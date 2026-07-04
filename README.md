# Single Note Breakdown Skill

Break down one Xiaohongshu / RedNote / Douyin post into the reasons it gets
clicked, watched, saved, commented on, and adapted.

这个开源 Skill 只做一件事：

> 把一条内容拆开看清楚：它为什么被点、为什么被看完、为什么被收藏，以及普通创作者下一条内容能学什么。

It is not a crawler, not a traffic-growth promise, and not a viral-copy tool.
It is a lightweight content-analysis workflow for creators, operators, and AI
agents.

## Search Keywords

English keywords:

`Xiaohongshu note breakdown`, `RedNote post analysis`, `XHS viral post`,
`viral content breakdown`, `creator content strategy`, `short video analysis`,
`social media content analysis`, `post structure analysis`, `AI skill for creators`,
`content repurposing`.

中文关键词：

`小红书笔记拆解`, `爆款笔记拆解`, `单篇笔记分析`, `小红书运营`,
`内容拆解`, `爆款内容分析`, `标题封面拆解`, `评论区需求`, `内容复用`,
`创作者工具`, `短视频拆解`.

## Why This Exists

很多人看到爆款，只会说“这个数据好”。但真正有用的问题是：

- 这条为什么会被点进来？
- 用户为什么愿意继续看？
- 它为什么有收藏价值？
- 评论区暴露了什么需求？
- 普通人能学习哪个动作，而不是照抄整条？

This Skill turns one public post, screenshot, transcript, or copied content into
a structured breakdown that can guide the creator's next piece.

## What It Can Do

- identify the first-click reason
- judge the opening and retention mechanism
- explain the save/share/comment reason
- extract title, cover, structure, and hook patterns
- separate learnable structure from non-copyable resources
- turn the breakdown into a next-post direction
- produce a compact knowledge-base card if needed

## Open-Source Boundary

This open version includes:

- a reusable one-post breakdown framework
- input checklist
- output contract
- safety rules against copying
- sample output
- adaptation prompts

This open version does not include:

- private API keys
- platform crawling logic
- bulk export
- private sample libraries
- guaranteed growth claims
- copied post rewriting for plagiarism

If a public-content connector is available, an Agent may use it to fetch public
post details, comments, or transcript text. If no connector is available, the
user can paste a post link, screenshot, title, body text, transcript, metrics,
or comments manually.

## Best Inputs

Any one of these is enough for a first pass:

- Xiaohongshu / RedNote / Douyin post link
- post title and cover text
- screenshots of the post
- copied post body text
- transcript or spoken script
- top comments
- visible metrics
- short context about the creator's own account

Better input produces better diagnosis. If only a topic is given, the Skill can
still explain what to look for, but should not pretend it analyzed real data.

## Output Contract

Default output:

1. One-sentence diagnosis
2. Click reason
3. Watch/read-through reason
4. Save/share reason
5. Comment-demand signal
6. Title and cover mechanism
7. Structure map
8. Learnable parts
9. Non-copyable parts
10. Next-post adaptation

## Example Prompts

```text
帮我完整拆解这条小红书笔记：为什么有人点、为什么有人收藏、下一条我能学什么？
```

```text
这是一个短视频逐字稿，帮我拆它的开头、节奏、看完理由和可复用结构。
```

```text
我只有截图和标题，先做一个轻量单篇笔记拆解，不要假装有完整数据。
```

## Repository Map

- `SKILL.md`: Agent entrypoint and workflow rules
- `agents/openai.yaml`: OpenAI Agent display metadata
- `references/breakdown-framework.md`: detailed breakdown framework
- `examples/sample-breakdown.md`: sample output

## Recommended GitHub Description

> Open Skill for breaking down one Xiaohongshu / RedNote / Douyin post into click, retention, save, comment, and adaptation signals.

## Suggested GitHub Topics

`xiaohongshu`, `rednote`, `xhs`, `douyin`, `creator-tools`,
`content-strategy`, `social-media`, `viral-content`, `ai-skill`,
`post-analysis`, `content-marketing`

## License

MIT
