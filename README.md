# YouTube Sentiment Analysis Project

This project demonstrates a YouTube comment analysis pipeline, including sentiment scoring, sentiment distribution visualization, and word cloud generation. The analysis is focused on extracting user comments, categorizing them by sentiment, and visualizing insights for actionable decision-making.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Visualization Outputs](#visualization-outputs)
- [Future Enhancements](#future-enhancements)
- [License](#license)

---

## Project Overview

The YouTube Sentiment Analysis project extracts comments from YouTube videos using the YouTube Data API and processes them to analyze sentiment. The outputs include sentiment scores, sentiment categorization (positive, neutral, negative), and graphical insights like:
- A bar chart showing sentiment counts.
- A word cloud visualization of common terms in comments.

### Objectives
1. Automate comment extraction from a YouTube video.
2. Perform sentiment analysis to categorize comments.
3. Visualize sentiment distribution and key themes from user feedback.

---

## Features

- **YouTube Comment Extraction**: Fetch comments from a YouTube video using the YouTube Data API.
- **Sentiment Analysis**: 
  - Scores comments based on sentiment polarity (negative, neutral, or positive).
  - Visualizes the count of each sentiment category.
- **Word Cloud Generation**: Highlights frequently used words in the comments.
- **Interactive Dashboard**: (If applicable) Export data to Excel for further analysis.

---

## Installation

### Prerequisites
- Python 3.8 or later
- Required libraries: `pandas`, `numpy`, `google-api-python-client`, `textblob`, `matplotlib`, `wordcloud`

### Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
