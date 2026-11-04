---
title: This blog runs on markdown files
date: 2026-11-04
tag: Notes
summary: How writeups get posted here — drop a .md file in /posts, add it to index.json, ship.
---

# This blog runs on markdown files

No CMS, no build step. A post is a markdown file in `posts/`, listed in `posts/index.json`.

## Adding a post

1. Create `posts/my-post.md` with frontmatter:

```
---
title: My post
date: 2026-11-04
tag: Engineering
summary: One line that shows on the card.
---
```

2. Add `"my-post.md"` to `posts/index.json`.
3. Commit and push — Vercel does the rest.

Cards sort newest first by `date`. Everything below the frontmatter is normal markdown: headings, lists, code blocks, quotes, images.

> Longer essays go up on Substack. Build notes live here.
