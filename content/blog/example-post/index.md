---
title: "Example Post"
date: 2026-04-21
# draft: true
summary: "A template post showing the frontmatter and markdown features the blog supports."
---

A short intro paragraph. This appears in the summary preview if you omit the
`summary` frontmatter field. With the field set, this paragraph is only shown
on the detail page.

<!--more-->

## Heading level 2

Regular prose with a [link](https://example.com), some **bold**, and some
*italic* text. Inline code looks like `const x = 42`.

### Heading level 3

A bulleted list:

- First item
- Second item with more text to show line-height
- Third item

A numbered list:

1. Step one
2. Step two
3. Step three

> A blockquote for pull quotes or callouts. The accent-colored left border
> comes from `.blog-post__content blockquote`.

```js
// A fenced code block
function greet(name) {
  return `Hello, ${name}`;
}
```

---

That horizontal rule above is styled. Images, when you add them, get rounded
corners automatically.
