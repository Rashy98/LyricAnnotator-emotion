# Hybrid Human-LLM Annotation Framework for Lyric Emotion Recognition

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the official dataset, codebase, and annotation interface for the paper: **"A Hybrid Framework for Song Lyric Annotation Based on Human-LLM Alignment"** (Currently under review at *IEEE Transactions on Affective Computing*).

## 📌 Overview
This project introduces a hybrid framework that optimizes Music Emotion Recognition (MER) annotation by routing lyric segments to either human experts or Large Language Models (LLMs) based on linguistic complexity and annotator agreement. 

By open-sourcing this repository, we aim to support reproducibility and facilitate further advancements in the MER community.

## 🗂 Repository Structure
```text
├── data/
│   ├── Annotated_lyrics_652_H.csv    # The 652-segment ground-truth dataset annotated manually
│   └── data_dictionary.md          # Explanation of columns and metrics
├── interface/
│   ├── annotator.html              # Source code for the annotation interface
└── README.md
