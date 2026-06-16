# Sentiment and Emotion Mining of Anime Reviews from MyAnimeList
*Advanced NLP pipeline for understanding audience emotions in anime reviews*

## Overview

This project presents a comprehensive **sentiment analysis** and **fine-grained emotion mining** study on anime reviews from [MyAnimeList (MAL)](https://myanimelist.net/). 

We collected, annotated, and analyzed **1,592 reviews** spanning 1980–2026 using a combination of lexicon-based methods, classical ML, and state-of-the-art transformer models (BERT & RoBERTa). The study reveals strong positive bias in anime fandom, dominant emotions like **joy** and **anticipation**, and clear genre-specific affective patterns.

**Full Research Report**: [View HTML Report](anime_sentiment_linkedin_report.html)

---

## Key Features

- **Data Collection**: Automated scraping via Jikan MAL API (top + random anime)
- **Annotation**: Manually labeled 3-class sentiment + Plutchik's 8 emotions (κ = 0.78)
- **Analysis**:
  - Lexicon-based (VADER)
  - Classical ML (TF-IDF + Logistic Regression / SVM)
  - Deep Learning (fine-tuned BERT & RoBERTa)
- **Visualizations**: Word clouds, emotion heatmaps, genre comparisons, temporal trends
- **Reproducible Pipeline**: Complete Jupyter notebook with all steps

---

## Key Findings

- **68.3%** of reviews express **positive sentiment**
- Strong correlation between textual sentiment and official MAL scores
- Dominant emotions: **Joy** and **Anticipation**
- Negative reviews frequently cite pacing issues ("rushed", "boring", "generic")
- Significant differences in emotional profiles across genres (Action, Drama, Romance, Sci-Fi)

---
