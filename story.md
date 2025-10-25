---
layout: page
title: Story
permalink: /story/
---

<style>
/* —— 仅本页用的轻量样式 —— */
.story-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 16px;
  margin-top: 14px;
}

.story-card {
  border: 1px solid #eaecef;
  border-radius: 14px;
  background: #fff;
  overflow: hidden;
}

.story-figure {
  position: relative;
  width: 100%;
  aspect-ratio: 3 / 2; /* 保持3:2横幅 */
  overflow: hidden;
  background: #f6f8fa;
}

.story-figure img {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover; /* 居中裁切，适配任意原始比例 */
}

.story-body {
  padding: 14px 16px 16px 16px;
}

.story-title {
  margin: 0 0 6px 0;
  font-size: 18px;
  line-height: 1.35;
}

.story-meta {
  margin: 0 0 10px 0;
  color: #586069;
  font-size: 13.5px;
}

.story-links a {
  display: inline-block;
  margin-right: 10px;
  text-decoration: none;
  font-weight: 600;
  font-size: 14px;
}

.story-badges {
  margin-top: 8px;
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
}

.badge {
  font-size: 12px;
  padding: 4px 8px;
  border-radius: 999px;
  background: #f1f8ff;
  border: 1px solid #d1e7ff;
  color: #0366d6;
}

/* 移动端优化：让图片与文字有呼吸感 */
@media (max-width: 420px) {
  .story-body { padding: 12px; }
}
</style>

# Selected Works

> Selected Works

<div class="story-grid">

  <!-- Paper 1 -->
  <article class="story-card">
    <figure class="story-figure">
      <img src="{{ '/assets/paper-1.png' | relative_url }}" alt="Paper 1 teaser">
    </figure>
    <div class="story-body">
      <h3 class="story-title">LLMs for bioinformatics.</h3>
      <p class="story-meta">
         Yanjun Lyu, Ruan, Wei,Jing Zhang, Jiazhang Cai, Peng Shu, Yang Ge, Yao Lu et al. "Large language models for bioinformatics." Quantitative Biology 14, no. 1 (2026): e70014.
      </p>
      <p>
        The applications of the methodology of large language models (LLMs) in bioinformatics tasks. The levels of life‐science factors in bioinformatics can be divided into five levels, from micro to macro. e.g., the mammal model organisms as a template, the
levels can be divided into: the molecular level, the genome‐scale level, the cellular level, the tissue/organ system level, and the population/community/meta-genomics level.
      </p>
      <!-- <p class="story-links">
        <a href="#" target="_blank">PDF</a>
        <a href="#" target="_blank">Code</a>
        <a href="#" target="_blank">Project</a>
        <a href="#" target="_blank">arXiv</a>
      </p> -->
      <div class="story-badges">
        <span class="badge">LLMs</span>
        <span class="badge">Bioinformatics.</span>
        <span class="badge">Life‐science factors</span>
        <span class="badge">Multi-levels/Multi-layers</span>
      </div>
    </div>
  </article>

  <!-- Paper 2 -->
  <article class="story-card">
    <figure class="story-figure">
      <img src="{{ '/assets/paper-2.png' | relative_url }}" alt="Paper 2 teaser">
    </figure>
    <div class="story-body">
      <h3 class="story-title">Oblique Genomics Mixture of Experts.</h3>
      <p class="story-meta">
        Lyu, Yanjun, et al. "Oblique Genomics Mixture of Experts: Prediction of Brain Disorder with Aging-Related Changes of Brain’s Structural Connectivity Under Genomic Influences." International Conference on Medical Image Computing and Computer-Assisted Intervention. Cham: Springer Nature Switzerland, 2025.
      </p>
      <p>
        Inthiswork,we introduce a novel deep-learning diagram, an oblique genomics mixture of experts(OG-MoE), designed to address the prediction of brain disease diagnosis, with awareness of the structural connectivity changes over time, and coupled with the genomics influences. By integrating genomics features into the dynamic gating router system of MoE layers, the model specializes in representing the structural connectivity components in separate parameter spaces. 
        FrameworkoftheOG-MoE.ThemodelisbasedonBert-styletransformer encoders and the mixtures of sparse expert diagram with the special gating router, which combines genomics features.
      </p>
      <!-- <p class="story-links">
        <a href="#" target="_blank">PDF</a>
        <a href="#" target="_blank">Code</a>
        <a href="#" target="_blank">Dataset</a>
      </p> -->
      <div class="story-badges">
        <span class="badge">Oblique Genomics</span>
        <span class="badge">Mixture of Experts</span>
      </div>
    </div>
  </article>

  <!-- Paper 3 -->
  <article class="story-card">
    <figure class="story-figure">
      <img src="{{ '/assets/paper-3.png' | relative_url }}" alt="Paper 3 teaser">
    </figure>
    <div class="story-body">
      <h3 class="story-title">Large language model for gene-phenotype mapping.</h3>
      <p class="story-meta">
        Lyu, Yanjun, et al. "Gp-gpt: Large language model for gene-phenotype mapping." arXiv preprint arXiv:2409.09825 (2024).
      </p>
      <p>
        The build bio-text datasets in genomics, proteomics, and medical genetics have experienced significant growth in both scale and diversity. For the purpose of comprehensively incorporating and extracting the mapping between genes and associated phenotype/diseases, multiple data sources were integrated into the training dataset of this study. Data merged from NCBI, OMIM, dbGaP, UniPort, and DisGeNet.
      </p>
      <!-- <p class="story-links">
        <a href="#" target="_blank">PDF</a>
        <a href="#" target="_blank">Code</a>
        <a href="#" target="_blank">Poster</a>
      </p> -->
      <div class="story-badges">
        <span class="badge">Large language model</span>
        <span class="badge">Gene-phenotype</span>
        <span class="badge">Genomics</span>
        <span class="badge">Bio-text</span>
      </div>
    </div>
  </article>

  <!-- Paper 4 -->
  <article class="story-card">
    <figure class="story-figure">
      <img src="{{ '/assets/paper-4.png' | relative_url }}" alt="Paper 4 teaser">
    </figure>
    <div class="story-body">
      <h3 class="story-title">Finer-scale brain connectome</h3>
      <p class="story-meta">
        Lyu, Yanjun, et al. "Mild cognitive impairment classification using a novel finer-scale brain connectome." 2024 IEEE International Symposium on Biomedical Imaging (ISBI). IEEE, 2024.
      </p>
      <p>
        The objective is to construct a novel 3HG-based finer-scale brain connectome and comprehensively compare its performance with traditional region-based connectome in predicting MCI against Normal Controls (NC).
      </p>
      <!-- <p class="story-links">
        <a href="#" target="_blank">PDF</a>
        <a href="#" target="_blank">Code</a>
        <a href="#" target="_blank">Slides</a>
        <a href="#" target="_blank">Video</a>
      </p> -->
      <div class="story-badges">
        <span class="badge">Brain connectome</span>
        <span class="badge">Finer-scale brain landmark</span>
        <span class="badge">Brain cortical folding pattern</span>
      </div>
    </div>
  </article>

  <!-- Paper 5 -->
  <article class="story-card">
    <figure class="story-figure">
      <img src="{{ '/assets/paper-5.png' | relative_url }}" alt="Paper 4 teaser">
    </figure>
    <div class="story-body">
      <h3 class="story-title">Fusing neuroimaging and gene expression data</h3>
      <p class="story-meta">
        Lyu, Yanjun, et al. "Classification of mild cognitive impairment by fusing neuroimaging and gene expression data: classification of mild cognitive impairment by fusing neuroimaging and gene expression data." 2021.
      </p>
      <p>
        To incorporate both imaging and molecular biomarkers, we propose a new deep fusion model: by integrating a cross-model deep network working on multi-modal brain image data and a fully-connected neural network working on gene expression data. Two models are merged in the late-fusion manner.
      </p>
      <!-- <p class="story-links">
        <a href="#" target="_blank">PDF</a>
        <a href="#" target="_blank">Code</a>
        <a href="#" target="_blank">Slides</a>
        <a href="#" target="_blank">Video</a>
      </p> -->
      <div class="story-badges">
        <span class="badge">Multi-Omics</span>
        <span class="badge">Fusion model</span>
        <span class="badge">Gene expression</span>
      </div>
    </div>
  </article>

</div>

---

## How to update images & links
- 把配图放在：`/assets/` 目录（建议 3:2，如 `1500×1000`；任意比例也行，会被居中裁切）。  
- 替换 `<img src="{{ '/assets/paper-x.jpg' | relative_url }}">` 的路径与 alt。  
- 修改标题、作者、Venue、亮点描述与链接（PDF / Code / Project / arXiv 等）。  
- 想新增作品：按上方 `<article class="story-card"> ... </article>` 整块复制粘贴一份并替换内容即可。
