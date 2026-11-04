# posts/

A post is a markdown file in this folder, listed in `index.json`.

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
3. Commit and push.

Cards sort newest first by `date`. Everything below the frontmatter is normal
markdown: headings, lists, code blocks, quotes, images. `README.md` is not in
`index.json`, so it never shows up on the site.
