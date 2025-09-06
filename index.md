---
layout: default
title: Home
---

<!-- 顶部横幅图（可选），直接丢一张图到 /assets/ 并替换文件名 -->
<p align="center">
  <img src="{{ '/assets/banner.jpg' | relative_url }}" alt="banner" width="880">
</p>

# {{ site.title }}
_{{ site.description }}_

Hi! I am **{{ site.author.name | default: site.title }}** from
**{{ site.author.affiliation | default: 'Your Institution' }}**.
My work focuses on **[fill your research focus]**.

**Quick links:**  
[About](/about/) · [Projects](/projects/) · [Publications](/publications/)

---

## Highlights
- 📄 New: _[Your paper title]_ — [arXiv](#)
- 🧪 Project: _[Project name]_ — [Code](#)

## Insert an image (simple)
Markdown（推荐）：
```markdown
![caption text](/assets/example.jpg)
