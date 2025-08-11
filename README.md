# LLM Personality Evolution Analysis

## Overview

This project investigates context-dependent personality evolution in Large Language Models (LLMs) through systematic analysis of conversational tone and topic effects on Big Five personality traits. The study provides the first comprehensive empirical analysis of how LLMs adapt their personality expression based on interpersonal context.

## 🔬 Research Objectives

- **Primary Goal:** Understand how conversational tone and topic influence personality trait expression in major LLMs
- **Key Questions:**
  - Do LLMs exhibit measurable, context-dependent personality changes?
  - Which contextual factors affect the personality the most?
  - Which LLMs show the greatest sensitivity to contextual variations?

## 📊 Experimental Design

### Participants

- **GPT-4o** (OpenAI)
- **Gemini 2.5 Flash** (Google)
- **Claude Sonnet 4** (Anthropic)

### Factors

- **Conversational Tones:** Friendly, Formal, Passive-Aggressive, Critical
- **Topics:** Coffee Brewing, REST API Development, Ethics of AI in Warfare
- **Personality Traits:** Big Five dimensions (Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism)

### Design

- **3×4×3 factorial design** with 5 replicates per condition
- **180 total observations** across all combinations
- **Balanced design** ensuring statistical power
- **Independent evaluation** using Claude Sonnet 4 as personality assessor

## Quick Start

```bash
git clone https://github.com/your-username/llm-personality-evolution.git
cd llm-personality-evolution
jupyter lab
```

### 📓 Notebook Guide

#### 1. Analysis (`analysis.ipynb`)

- Provides a step-by-step guide to analyze how different tones and topics affect personality trait ratings across LLms.
- We'll go from basic data exploration to advanced statistical tests.

#### 2.Visualizations (`visualizations.ipynb`)

- LLM personality profile radar charts
- Tone effect line plots
- Interaction visualizations
- Statistical significance summaries

## 📊 Data Description

### Dataset: `results_dataset.csv`

- **Rows:** 180 observations
- **Columns:** 8 variables
  - `llm`: Model name (3 levels)
  - `tone`: Conversational tone (4 levels)
  - `topic`: Conversation topic (3 levels)
  - `openness`: Personality rating (1-5 scale)
  - `conscientiousness`: Personality rating (1-5 scale)
  - `extraversion`: Personality rating (1-5 scale)
  - `agreeableness`: Personality rating (1-5 scale)
  - `neuroticism`: Personality rating (1-5 scale)

## 📜 License & Usage

This project contains original research intended for academic publication.
The work is protected under an MIT + Academic Research Addendum [License](LICENSE).

### For Academic Use:

- ✅ Citation and reference permitted
- ✅ Educational use encouraged
- ✅ Methodology replication allowed

### Citation Required:

> _NOTE: Will be added once the paper is published._

## 🙏 Acknowledgments

- Special thanks to my supervisor [Dr. Umair Rehman](https://www.linkedin.com/in/umair-rehman-phd-42aa2854) for supporting and encouraging this research.
