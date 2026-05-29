# Adding Blog Posts

Add each new blog post as a Markdown file in `posts/`.

1. Create a new file, for example `posts/my-new-post.md`.
2. Copy this starter format:

```md
---
title: "My New Post"
slug: "my-new-post"
date: "June 2026"
category: "thought"
excerpt: "One short sentence about the post."
---

Write your post here.

## Section heading

More writing here.
```

3. Open `data/posts.json`.
4. Add your new filename to the list.

Example:

```json
[
  "my-new-post.md",
  "small-tools-slow-internet.md",
  "quiet-interfaces.md",
  "wandering-systems.md"
]
```

GitHub Pages will read the files and show them on the Blog page.
