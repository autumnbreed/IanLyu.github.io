---
layout: default
title: Home
---

<!-- 顶部横幅图（可选），直接丢一张图到 /assets/ 并替换文件名 -->
<div style="max-width:960px; margin:0 auto;">
  <div style="position:relative; width:100%; aspect-ratio:4/3; overflow:hidden; border-radius:12px;">
    <img src="{{ '/assets/banner.jpg' | relative_url }}"
         alt="banner"
         style="position:absolute; inset:0; width:100%; height:100%; object-fit:cover;">
  </div>
</div>

<!-- ===== Hero Section（带头像与按钮） ===== -->
<div style="display:flex; flex-direction:column; align-items:center; gap:14px; text-align:center; margin: 32px 0;">
<!--   <img src="{{ site.brand.hero_image | default: '/assets/avatar.jpg' }}"
       alt="profile"
       style="width:120px;height:120px;border-radius:50%;object-fit:cover;box-shadow:0 10px 30px rgba(0,0,0,0.15);" /> -->

  <h1 style="margin:10px 0 6px 0; font-size:28px; line-height:1.2;">
    {{ site.title }}
  </h1>

  <p style="margin:0; color:#586069; font-size:16px;">
    {{ site.description }}
  </p>

  <div style="display:flex; gap:10px; margin-top:12px; flex-wrap:wrap; justify-content:center;">
    <a href="https://scholar.google.com/citations?user=4xW30NMAAAAJ" 
       style="padding:10px 16px; border-radius:10px; text-decoration:none; background:#0366d6; color:white; font-weight:600;">
      {{ site.brand.cta_primary_text | default: "Publications" }}
    </a>
    <a href="{{ site.brand.cta_secondary_link | default: './about.md' }}" 
       style="padding:10px 16px; border-radius:10px; text-decoration:none; background:#eaecef; color:#24292e; font-weight:600;">
      {{ site.brand.cta_secondary_text | default: "About Me" }}
    </a>
    <a href="{{ site.brand.cta_secondary_link | default: './story.md' }}" 
       style="padding:10px 16px; border-radius:10px; text-decoration:none; background:#eaecef; color:#24292e; font-weight:600;">
      {{ site.brand.cta_secondary_text | default: "Research story" }}
    </a>
  </div>

  <!-- 社交/外链（按需增减） -->
  <p style="margin-top:10px; font-size:14px;">
    <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a> ·
    <a href="https://huggingface.co/IanL10/datasets">Data</a> ·
    <a href="https://orcid.org/0009-0009-5646-326X">ORCID</a>
  </p>
</div>

<!-- ===== Intro ===== -->
<div style="max-width:900px;margin:0 auto;">
  <h2>About My Research</h2>
  <p>
    I work at the intersection of <strong>machine learning</strong>, <strong>bioinformatics</strong>, <strong>neuroimaging</strong>, and <strong>genomics</strong>, building AI to understand multi-omics and multi-layered principles of life science. I am especially interested in representation learning, multi-modality AI and interpretable biomedical/bioinformatic AI.
  </p>

  <!-- ===== Cards: Research Topics / News ===== -->
  <div style="display:grid; grid-template-columns:repeat(auto-fit,minmax(260px,1fr)); gap:14px; margin-top:18px;">
    <div style="background:#ffffff;border:1px solid #eaecef;border-radius:14px;padding:16px;">
      <h3 style="margin-top:0;">Current Topics</h3>
      <ul style="margin:0; padding-left:18px;">
        <li>Multi-modality models and interpretable deep learning in studying brain disorders</li>
        <li>Representation learning in exploring brain fundamental organization</li>
        <li>Foundation models for life science and bioinformatics</li>
        <li>Foundation language model for healthcare</li>
      </ul>
    </div>
    <div style="background:#ffffff;border:1px solid #eaecef;border-radius:14px;padding:16px;">
      <h3 style="margin-top:0;">News</h3>
      <ul style="margin:0; padding-left:18px;">
        <li>[Latest paper] Lyu, Yanjun, et al. "Oblique Genomics Mixture of Experts: Prediction of Brain Disorder with Aging-Related Changes of Brain’s Structural Connectivity Under Genomic Influences." MICCAI, 2025. — <a href="#">arXiv</a></li>
        <li>[Latest paper] Lyu, Y., Ruan, W., Zhang, J., Cai, J., Shu, P., Ge, Y., ... & Liu, T. (2026). Large language models for bioinformatics. Quantitative Biology, 14(1), e70014. — <a href="#">GitHub</a></li>
        <li>[About banner picture] Cedar Hill State Park, TX, "Evening after a rain" — <a href="#">Slides</a></li>
      </ul>
    </div>
    <div style="background:#ffffff;border:1px solid #eaecef;border-radius:14px;padding:16px;">
      <h3 style="margin-top:0;">Quick Links</h3>
      <ul style="margin:0; padding-left:18px;">
        <li><a href="https://scholar.google.com/citations?user=4xW30NMAAAAJ">Publications</a></li>
        <li><a href="/story.md/">Story</a></li>
        <li><a href="/about.md">About</a></li>
        <li><a href="/cv.md">CV</a></li>
      </ul>
    </div>
  </div>
</div>

<!-- ===== Footer small note ===== -->
<p style="text-align:center; color:#6a737d; font-size:12px; margin-top:28px;">
  Built with Jekyll & GitHub Pages · © {{ site.time | date: "%Y" }} {{ site.author.name | default: site.title }}
</p>

{% seo %}

