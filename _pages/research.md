---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Overview

Currently, I am working under the guidance of [Professor Christian Wallraven](https://scholar.google.com/citations?hl=tr&user=VJuuzLwAAAAJ&view_op=list_works&sortby=pubdate) in the [Cognitive Systems Lab](https://cogsyslab.notion.site/) at Korea University, where I am investigating [the role of internal and external cues in fine-grained ethnicity recognition; whether Koreans can distinguish between Korean, Chinese, and Japanese faces](https://osf.io/gxky7/). Later, this research led to a follow-up study comparing human and machine learning performance in fine-grained ethnicity recognition. My work aims to deepen our understanding of human perception and its implications for intelligent systems, bridging cognitive science with computational approaches.

---

## Projects (click to expand)

<div class="cm-accordion">

  <div class="cm-item">
    <button class="cm-header" type="button">
      External vs. Internal Facial Features in Fine-Grained Ethnicity Categorization
      <span class="cm-tag">Behavioral · Face perception</span>
    </button>
    <div class="cm-body">
      <p>
        I examine how Korean observers use <strong>internal features</strong> (e.g., eyes/nose)
        versus <strong>external cues</strong> (e.g., hair/face outline) when categorizing
        Korean, Japanese, and Chinese faces, and how background/context modulates this process.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> 3AFC categorization · feature manipulations · confidence measures</p>
      <p class="cm-links">
        <a href="https://osf.io/gxky7/" target="_blank" rel="noopener">Preprint / OSF</a>
      </p>
    </div>
  </div>

  <div class="cm-item">
    <button class="cm-header" type="button">
      Humans vs. Machines: Comparing Strategies in Fine-Grained Face Categorization
      <span class="cm-tag">Computational · Human–AI</span>
    </button>
    <div class="cm-body">
      <p>
        Building on the behavioral findings, I compare human performance with deep learning models
        to understand <strong>where humans struggle</strong>, <strong>where machines excel</strong>,
        and whether they rely on different facial information.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> embeddings/classifiers · cross-validation · error analysis</p>
      <p class="cm-links">
        <!-- link eklemek istersen buraya -->
        <!-- <a href="..." target="_blank" rel="noopener">Paper / Preprint</a> -->
      </p>
    </div>
  </div>

  <div class="cm-item">
    <button class="cm-header" type="button">
      Gaze Direction × Face Mask Effects on Emotion Recognition (Eye-Tracking)
      <span class="cm-tag">Eye-tracking · Social vision</span>
    </button>
    <div class="cm-body">
      <p>
        My senior bachelor project investigated how perceived gaze direction and face masks shape
        emotion recognition, and how attention is allocated to diagnostic facial regions.
      </p>
      <p class="cm-meta"><strong>Funding:</strong> TUBITAK</p>
      <p class="cm-links">
        <a href="https://osf.io/3fd5h/" target="_blank" rel="noopener">Project / OSF</a>
      </p>
    </div>
  </div>

  <div class="cm-item">
    <button class="cm-header" type="button">
      Audio-visual Mechanisms of the Uncanny Valley Effect (HRI)
      <span class="cm-tag">Multisensory · HRI</span>
    </button>
    <div class="cm-body">
      <p>
        As an undergraduate research assistant in the
        <a href="https://cnvplab.com/" target="_blank" rel="noopener">CNVP Lab</a>,
        I worked on how levels of naturality in visual–auditory stimuli influence human–robot interaction
        and uncanny valley perception across generations.
      </p>
      <p class="cm-links">
        <a href="https://cnvplab.com/https-cnvplab-com-projects-short-term-plasticity-in-bistable-phonetic-word-processing-visual-crowding-in-holistic-configurations/projects-short-term-plasticity-in-bistable-phonetic-word-processing-186-2/"
           target="_blank" rel="noopener">Project page</a>
      </p>
    </div>
  </div>

</div>

<style>
/* --- Cansu Malak: Research accordion --- */
.cm-accordion { max-width: 900px; }

.cm-item {
  border: 1px solid #e3e3e3;
  border-radius: 12px;
  margin: 14px 0;
  overflow: hidden;
  background: #fff;
}

.cm-header {
  width: 100%;
  text-align: left;
  border: 0;
  cursor: pointer;
  padding: 16px 16px;
  font-size: 1.05rem;
  font-weight: 650;
  background: #f7f7f7;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
}

.cm-header:hover { background: #efefef; }

.cm-tag {
  font-size: 0.85rem;
  font-weight: 600;
  padding: 6px 10px;
  border-radius: 999px;
  background: #ffffff;
  border: 1px solid #e6e6e6;
  white-space: nowrap;
}

.cm-body {
  display: none;
  padding: 14px 16px 16px 16px;
  line-height: 1.6;
}

.cm-meta { margin-top: 10px; opacity: 0.9; }
.cm-links a { font-weight: 600; }
</style>

<script>
  // Simple accordion toggle (no dependencies)
  document.querySelectorAll(".cm-header").forEach(btn => {
    btn.addEventListener("click", () => {
      const body = btn.nextElementSibling;
      const isOpen = body.style.display === "block";
      body.style.display = isOpen ? "none" : "block";
    });
  });
</script>
