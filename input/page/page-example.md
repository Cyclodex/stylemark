---
name: Page example
category: Page
type: template
version: 1.0.0
---

# Examples template of filtered component loading from external file

```register.html
<div class="test">
  {{{test1:/components/image.md template=test-1}}}
  {{{test2:/components/image.md template=test-2}}}
  {{{test3:/components/image.md template=test-3}}}
</div>
```
