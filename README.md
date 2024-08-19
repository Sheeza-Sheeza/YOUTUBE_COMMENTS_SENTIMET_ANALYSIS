# YouTube Comment Sentiment Analysis

This project involves analyzing the sentiment of comments on a YouTube video using the VADER sentiment analysis tool. The project fetches comments from a specified YouTube video, filters out irrelevant comments, performs sentiment analysis, and visualizes the results.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Visualization](#visualization)
- [License](#license)

## Introduction

The purpose of this project is to analyze the sentiments of comments on YouTube videos to determine whether the overall response is positive, negative, or neutral. The analysis is performed using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool, which is particularly effective for social media texts.

## Features

- **Fetching Comments**: Fetches comments from a YouTube video using the YouTube Data API.
- **Comment Filtering**: Filters out irrelevant comments, such as those containing hyperlinks or excessive emojis.
- **Sentiment Analysis**: Analyzes the sentiment of each comment using VADER.
- **Result Visualization**: Displays the results in both bar chart and pie chart formats.

## Technologies Used

- **Python**: Programming language used for the entire project.
- **YouTube Data API**: Used to fetch comments from a YouTube video.
- **VADER Sentiment Analysis**: A tool used for performing sentiment analysis.
- **Matplotlib**: Used for visualizing the results in bar and pie charts.
- **Regex**: Used for filtering comments.

## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/youtube-comment-sentiment-analysis.git
