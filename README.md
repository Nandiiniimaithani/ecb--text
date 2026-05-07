# ecb--text

This repository contains a conda environment definition for text processing and analysis.

## Analysis report

### 1) ECB page chosen

I used a press conference page from the official European Central Bank website ( dataset source:
[https://www.ecb.europa.eu/press/pr/date/2026/html/ecb.mp260430~81b7179e6f.en.html](https://www.ecb.europa.eu/press/pr/date/2026/html/ecb.mp260430~81b7179e6f.en.html)).

This page contains '11 structured paragraphs', including policy decisions, inflation outlook, and risk assessments.

---

### 2) Sentiment package used and why

I used 'TextBlob' for sentiment analysis. It was chosen because it provides:

'Polarity scores (-1 to +1)' for each paragraph
'Subjectivity scores (0 to 1)'
Simple paragraph-level processing without needing training data

From your results, the sentiment statistics show:

 Polarity range: approximately =-0.2 to +0.29.
 Subjectivity range: approximately =0.10 to 0.56

This makes it suitable for quick quantitative analysis of ECB communication tone.

---

### 3) What the paragraph-level results suggest (based on your data)

Your dataset shows:

#### Sentiment distribution (11 paragraphs total)

6 positive paragraphs
4 neutral paragraphs
1 negative paragraph

#### Tone pattern

Most paragraphs are labeled 'positive (6/11)', but this does NOT mean optimistic language—it reflects institutional wording like stability, resilience, and policy readiness.
'Neutral paragraphs (4/11' are mainly structural content (headings, technical descriptions, announcements).
'Only 1 negative paragraph' appears, related to **asset purchase programme reduction (APP/PEPP decline)**.

#### Key thematic insights

'Inflation risk and energy prices' increase polarity variability (your highest subjectivity up to ~0.56).
ECB emphasizes:

inflation targeting (2% goal)
economic resilience
data-dependent policy decisions
Despite geopolitical pressure (energy shock), language remains "controlled and technical", not emotionally negative.

---
