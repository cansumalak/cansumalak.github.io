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


## Projects

<div class="cm-accordion">

  <details class="cm-item project-pink">
    <summary class="cm-header">
      <span>What Do We Look At When We Decide Someone’s Ethnicity?</span>
      <span class="cm-tag">Behavioral · Face perception</span>
    </summary>
    <div class="cm-body">
      <p>
        How do Korean observers use <strong>internal</strong> (eyes, nose) versus
        <strong>external</strong> (hair, face outline) facial cues when categorizing
        Korean, Japanese, and Chinese faces?
      </p>
      <p class="cm-meta"><strong>Methods:</strong> 3AFC categorization · stimulus manipulations · confidence measures</p>
      <p class="cm-links">
        <a href="https://osf.io/gxky7/" target="_blank" rel="noopener">Preprint / OSF</a>
      </p>
    </div>
  </details>

  <details class="cm-item project-lpink">
    <summary class="cm-header">
      <span>When Humans Struggle and Machines Succeed at Face Categorization</span>
      <span class="cm-tag">Computational · Human–AI</span>
    </summary>
    <div class="cm-body">
      <p>
        A follow-up study comparing human categorization patterns with deep learning models,
        asking where humans and machines converge—and where their error profiles diverge.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> face embeddings · supervised classifiers · cross-validation</p>
    </div>
  </details>

  <details class="cm-item project-lblue">
    <summary class="cm-header">
      <span>Attractive Strangers Look Korean: How Social Traits Bias Ethnicity Perception</span>
      <span class="cm-tag">Social cognition · Trait bias</span>
    </summary>
    <div class="cm-body">
      <p>
        Examines how rapid social trait impressions such as <strong>attractiveness</strong>
        and <strong>trustworthiness</strong> bias fine-grained ethnicity categorization,
        including asymmetric in-group effects.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> trait ratings · mixed-effects analyses</p>
    </div>
  </details>

  <details class="cm-item project-blue">
    <summary class="cm-header">
      <span>Reading Emotions When Faces Are Partly Hidden</span>
      <span class="cm-tag">Eye-tracking · Social vision</span>
    </summary>
    <div class="cm-body">
      <p>
        Investigates how gaze direction and face masks shape emotion recognition and
        visual attention to diagnostic facial regions.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> eye-tracking · emotion recognition · ROI analyses</p>
      <p class="cm-links">
        <a href="https://osf.io/3fd5h/" target="_blank" rel="noopener">Project / OSF</a>
      </p>
    </div>
  </details>

  <details class="cm-item project-purple">
    <summary class="cm-header">
      <span>Why Some Robots Feel Uncanny: Audio-Visual Cues in Human–Robot Interaction</span>
      <span class="cm-tag">Multisensory · HRI</span>
    </summary>
    <div class="cm-body">
      <p>
        Explores how naturality in audio–visual signals influences human–robot interaction
        and the perception of the uncanny valley.
      </p>
      <p class="cm-meta"><strong>Methods:</strong> multisensory stimuli · behavioral judgments</p>
    </div>
  </details>

</div>

<style>
.cm-accordion { max-width: 900px; }

/* Card */
.cm-accordion details.cm-item {
  border: 1px solid #e3e3e3;
  border-left-width: 6px;
  border-radius: 12px;
  margin: 14px 0;
  background: #fff;
  transition: transform 140ms ease, box-shadow 140ms ease;
}

.cm-accordion details.cm-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.06);
}

/* Header — GRID FIX (tag hizalama) */
.cm-accordion details.cm-item > summary.cm-header {
  list-style: none;
  cursor: pointer;
  padding: 16px;
  background: #f7f7f7;

  display: grid;
  grid-template-columns: 1fr auto;
  align-items: center;
  column-gap: 12px;

  font-size: 1.05rem;
  font-weight: 650;
  border-radius: 12px;
}

.cm-accordion summary::-webkit-details-marker { display: none; }
.cm-accordion summary::marker { content: ""; }

.cm-accordion details.cm-item > summary.cm-header::after {
  content: "▾";
  opacity: 0.6;
  margin-left: 10px;
}

.cm-accordion details.cm-item[open] > summary.cm-header::after {
  content: "▴";
}

/* Tag */
.cm-tag {
  justify-self: end;
  align-self: center;
  font-size: 0.85rem;
  font-weight: 600;
  padding: 6px 10px;
  border-radius: 999px;
  background: #ffffff;
  border: 1px solid #e6e6e6;
  white-space: nowrap;
}

/* Body */
.cm-body {
  padding: 14px 16px 16px;
  line-height: 1.6;
}

.cm-meta { margin-top: 10px; opacity: 0.9; }
.cm-links a { font-weight: 600; }

/* Color themes */
.project-pink   { border-left-color: #e87aa4 !important; }
.project-lpink  { border-left-color: #f2a6c1 !important; }
.project-lblue  { border-left-color: #9ecae1 !important; }
.project-blue   { border-left-color: #6baed6 !important; }
.project-purple { border-left-color: #b39ddb !important; }

/* Hover */
.project-pink:hover   > summary { background: #fdeaf1 !important; }
.project-lpink:hover  > summary { background: #fff0f6 !important; }
.project-lblue:hover  > summary { background: #eef6fb !important; }
.project-blue:hover   > summary { background: #e8f2fa !important; }
.project-purple:hover > summary { background: #f3eefc !important; }

/* Open */
.project-pink[open]   > summary { background: #fdeaf1 !important; }
.project-lpink[open]  > summary { background: #fff0f6 !important; }
.project-lblue[open]  > summary { background: #eef6fb !important; }
.project-blue[open]   > summary { background: #e8f2fa !important; }
.project-purple[open] > summary { background: #f3eefc !important; }
</style>
