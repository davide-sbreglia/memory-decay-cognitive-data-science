# Moral Drift in Large Language Models

This repository contains the code and analysis for a Cognitive Data Science project investigating **moral drift** in GPT-3.5 Turbo. The study explores how moral judgments evolve over the course of multiple interactions, especially when ethical dilemmas are framed differently.

## 🎯 Project Goal

The goal is to measure and visualize changes in moral acceptability ratings over time using:

- 📊 **Likert trajectory analysis** (acceptability 1–7)
- 🔥 **Spreading Activation** in the moral foundation network
- 🌐 **Network Metrics** (density, clustering) to assess coherence

## 🧪 Experimental Design

- **Model**: GPT-3.5 Turbo (temperature = 0.3)
- **Conditions**: Neutral vs Framed
- **Stimuli**: 6 sequential moral dilemmas per thread
- **Threads**: 50 per condition (N = 100 total)

## 🗂 Folder Structure


## 📌 Analyses

- **Likert Drift**: Acceptability scores plotted across steps (D1–D6) for each condition
- **Spreading Activation**: Top moral foundation activations per step using cosine distance
- **Moral Network Analysis**: Density and average clustering of semantic connections

## 🖼 Sample Visuals

- Drift plot with 95% CI
- Barplot of top-activated foundations
- Comparison of network density across conditions
