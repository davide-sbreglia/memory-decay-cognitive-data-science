# Moral Drift in Large Language Models

This repository contains the code and analysis for a Cognitive Data Science project investigating **moral drift** in GPT-3.5 Turbo. 

## Overview

Large Language Models (LLMs) are used in many domains where ethical reasoning is important. However, they can show **moral drift** defined as gradual changes in judgment when answering similar questions over time. This project tests whether an **empathy-based framing** can reduce that drift.

We compared two conditions:
- **Neutral**: dilemmas presented with standard wording
- **Framed**: dilemmas preceded by a short emotional or empathic sentence

GPT-3.5 was asked to rate each dilemma on a scale from 1 (morally wrong) to 7 (morally right), followed by a short justification.

## Key Findings

- Moral scores decreased significantly across dilemmas in the **neutral** condition, but was different in the **framed** condition (26% reduction).
- Semantic networks built from GPT’s justifications showed **higher conceptual diversity** in the empathy condition.

## Experimental Design

- 100 conversation threads (50 per condition)
- 6 classic moral dilemmas (from trolley problem to terrorism scenario, impersonal to personal)
- Sentence embeddings via MiniLM to analyze justification structure
- Drift analysis: Mann-Whitney U test, Cohen’s d, mixed-effects model
- Graph metrics: density, clustering, average path length

The full write-up, including visualizations and references, is available in the section "paper" (paper/Moral_Trajectory_in_LLMs_.pdf).
---
*Project by Davide Sbreglia – MSc Data Science – University of Trento*
