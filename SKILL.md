---
name: single-note-breakdown
description: Break down one Xiaohongshu / RedNote / Douyin post into click reason, read-through reason, save/share reason, comment demand, title/cover mechanism, learnable structure, non-copyable resources, and next-post adaptation. Use when the user asks to analyze one viral post, note, short video, screenshot, transcript, or copied post.
---

# Single Note Breakdown

Use this Skill when the user wants to understand why one piece of social content
works.

It is intentionally a lightweight open Skill. It does not do bulk monitoring,
traffic prediction, copying, or private platform access. It turns one supplied
post or one public-post dataset into a useful creator-facing breakdown.

## Best Fit

Use this for:

- Xiaohongshu / RedNote post breakdown
- Douyin short-video breakdown
- viral note analysis
- title and cover mechanism review
- transcript or script analysis
- comment-demand reading
- adapting one post structure into the user's next post

Do not use it for:

- guaranteed growth advice
- copying another creator's post
- scraping or bulk exporting platform data
- full account diagnosis
- campaign strategy across many posts

## Input Handling

Accept any of these:

- post link
- screenshot
- copied title / cover text / body text
- transcript
- visible metrics
- top comments
- user's own account context

If the user only gives a link and no connector is available, ask them to paste
the visible content or screenshots. If only partial data is available, say the
output is a first-pass breakdown based on supplied material.

## Core Rule

Do not say "this went viral because the title is good" without explaining the
specific mechanism.

Always separate:

- what made users click
- what made users continue
- what made users save or share
- what made users comment
- what an ordinary creator can learn
- what should not be copied

## Workflow

1. Identify the post type: image note, long graphic note, video, talking-head
   video, product note, tutorial, emotional story, list, comparison, or
   interaction post.
2. Read `references/breakdown-framework.md`.
3. Build a compact evidence list from the supplied material.
4. Diagnose the four user actions:
   - click
   - continue
   - save/share
   - comment
5. Map the content structure.
6. Extract learnable parts and non-copyable parts.
7. Give one next-post adaptation for the user.

## Output Contract

Default output:

```markdown
## One-Sentence Diagnosis
...

## Click Reason
...

## Read-Through Reason
...

## Save / Share Reason
...

## Comment Demand
...

## Title And Cover Mechanism
...

## Structure Map
...

## Learnable Parts
...

## Do Not Copy
...

## Next Post Adaptation
...
```

## Tone

Write in Chinese unless the user asks otherwise.

Be direct, concrete, and creator-friendly. Avoid vague phrases like "high
quality content", "strong positioning", or "good engagement" unless immediately
explained through observable details.

## Safety Boundary

Never help the user copy another creator's full post. The useful output is an
adaptable mechanism, not a clone.

Good:

> 学它的开头动作：先抛出一个具体反差，再给出一个可验证结果。

Bad:

> 把这个标题和结构照着改成你的版本。
