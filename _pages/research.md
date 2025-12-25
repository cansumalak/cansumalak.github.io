---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Overview

Currently, I am working under the guidance of [Professor Christian Wallraven](https://scholar.google.com/citations?hl=tr&user=VJuuzLwAAAAJ&view_op=list_works&sortby=pubdate) in the [Cognitive Systems Lab](https://cogsyslab.notion.site/) at Korea University. My research centers on fine-grained ethnicity recognition—specifically, how Korean observers distinguish between Korean, Chinese, and Japanese faces, a task that is often assumed to be intuitive but is perceptually challenging in practice.

Across a series of studies, I investigate this question from multiple complementary angles: how observers rely on different facial cues (internal features, external features, or their combination), how social trait impressions such as attractiveness and trustworthiness bias categorization decisions, and how human performance compares to that of machine learning models trained on the same task. Together, these projects aim to characterize the perceptual and social factors shaping fine-grained face categorization, and to clarify where human and artificial systems converge or diverge in solving this problem.

---
## Projects (click to expand)

<div class="cm-accordion">

  <details class="cm-item">
    <summary class="cm-header">
      <span>External vs. Internal Facial Features in Fine-Grained Ethnicity Categorization</span>
      <span class="cm-tag">Behavioral · Face perception</span>
    </summary>
    <div class="cm-body">
      <p>
        How do Korean observers use <strong>internal</strong> (eyes/nose) versus <strong>external</strong> (hair/face outline) facial cues when categorizing Korean, Japanese, and Chinese faces?
        This project tests feature reliance and contextual effects on accuracy and confidence.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> 3AFC categorization · stimulus manipulations · confidence</p>
      <p class="cm-links">
        <a href="https://osf.io/gxky7/" target="_blank" rel="noopener">Preprint / OSF</a>
      </p>
    </div>
  </details>

  <details class="cm-item">
    <summary class="cm-header">
      <span>Humans vs. Machines: Comparing Strategies in Fine-Grained Face Categorization</span>
      <span class="cm-tag">Computational · Human–AI</span>
    </summary>
    <div class="cm-body">
      <p>
        A follow-up study comparing human categorization patterns to deep learning models, asking whether humans and machines rely on the same facial information—and where their error profiles diverge.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> face embeddings · supervised classifiers · cross-validation · error analysis</p>
    </div>
  </details>

  <details class="cm-item">
    <summary class="cm-header">
      <span>Attractive Strangers Look Korean</span>
      <span class="cm-tag">Social cognition · Trait bias</span>
    </summary>
    <div class="cm-body">
      <p>
        Investigates how rapid social trait impressions (e.g., <strong>attractiveness</strong> and <strong>trustworthiness</strong>) bias fine-grained ethnicity categorization decisions, including asymmetric in-group effects.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> trait ratings · correlational / mixed-effects analyses · bias–accuracy links</p>
      <!-- varsa link ekle:
      <p class="cm-links"><a href="..." target="_blank" rel="noopener">Preprint</a></p>
      -->
    </div>
  </details>

  <details class="cm-item">
    <summary class="cm-header">
      <span>Gaze Direction × Face Mask Effects on Emotion Recognition (Eye-Tracking)</span>
      <span class="cm-tag">Eye-tracking · Social vision</span>
    </summary>
    <div class="cm-body">
      <p>
        Examines how gaze direction and face masks shape emotion recognition and visual attention to diagnostic facial regions, with implications for understanding social vision under occlusion.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> eye-tracking · emotion recognition · ROI-based attention analyses</p>
      <p class="cm-links">
        <a href="https://osf.io/3fd5h/" target="_blank" rel="noopener">Project / OSF</a>
      </p>
    </div>
  </details>

  <details class="cm-item">
    <summary class="cm-header">
      <span>Audio-visual Mechanisms of the Uncanny Valley Effect (HRI)</span>
      <span class="cm-tag">Multisensory · HRI</span>
    </summary>
    <div class="cm-body">
      <p>
        Explores how naturality in audio–visual signals influences human–robot interaction and the perception of the uncanny valley across generations.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> multisensory stimuli · behavioral judgments · individual differences</p>
      <!-- varsa link ekle:
      <p class="cm-links"><a href="..." target="_blank" rel="noopener">Project page</a></p>
      -->
    </div>
  </details>

</div>

<style>
.cm-accordion { max-width: 900px; }

.cm-accordion details.cm-item {
  border: 1px solid #e3e3e3 !important;
  border-radius: 12px !important;
  margin: 14px 0 !important;
  overflow: hidden !important;
  background: #fff !important;
}

.cm-accordion details.cm-item > summary.cm-header {
  list-style: none !important;
  cursor: pointer !important;
  padding: 16px 16px !important;
  background: #f7f7f7 !important;
  display: flex !important;
  align-items: center !important;
  justify-content: space-between !important;
  gap: 12px !important;
  font-size: 1.05rem !important;
  font-weight: 650 !important;
  border-radius: 12px !important;
}

.cm-accordion details.cm-item > summary.cm-header::-webkit-details-marker { display: none !important; }
.cm-accordion details.cm-item > summary.cm-header::marker { content: "" !important; }

.cm-accordion details.cm-item > summary.cm-header::after {
  content: "▾";
  font-size: 1.1rem;
  opacity: 0.65;
  margin-left: 10px;
}

.cm-accordion details.cm-item[open] > summary.cm-header::after {
  content: "▴";
}

.cm-accordion details.cm-item > summary.cm-header:hover {
  background: #efefef !important;
}

.cm-accordion .cm-tag {
  font-size: 0.85rem !important;
  font-weight: 600 !important;
  padding: 6px 10px !important;
  border-radius: 999px !important;
  background: #ffffff !important;
  border: 1px solid #e6e6e6 !important;
  white-space: nowrap !important;
}

.cm-accordion .cm-body {
  padding: 14px 16px 16px 16px !important;
  line-height: 1.6 !important;
}

.cm-accordion .cm-meta { margin-top: 10px; opacity: 0.9; }
.cm-accordion .cm-links a { font-weight: 600; }
</style>
