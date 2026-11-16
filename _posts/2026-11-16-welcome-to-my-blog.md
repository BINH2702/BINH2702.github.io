---
title: Welcome to my blog
---

This is my first post. It also works as a small guide for writing the next one.

## How to write a new post

1. Open the `_posts` folder in this repository.
2. Add a new file named like `2026-12-01-my-post-title.md`.
   The date at the start and the `.md` ending are required.
3. Put this at the very top of the file:

   ```
   ---
   title: My post title
   ---
   ```

4. Write the post below it in Markdown and commit. The site updates by itself in a minute or two.

## Markdown in thirty seconds

- `**bold**` gives **bold**, and `*italic*` gives *italic*.
- `[a link](https://example.com)` gives [a link](https://example.com).
- A line starting with `## ` is a heading.
- Lines starting with `- ` make a list, like this one.
- Put an image in `assets/` and show it with `![description](/assets/picture.jpg)`.

Code works too:

```python
def hello():
    print("Hello from my blog!")
```

> And a line starting with `>` becomes a quote.

The first paragraph of each post is shown as the preview on the [blog page](/blog/).
