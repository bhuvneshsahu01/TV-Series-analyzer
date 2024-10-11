# Series Analysis with NLP and LLMs

Welcome to the **Series Analysis with NLP and LLMs** project! In this project, we aim to analyze a series using advanced Natural Language Processing (NLP) techniques and Large Language Models (LLMs). Our goal is to scrape relevant data, implement various classification models, and build an interactive character chatbot. This project is designed to enhance your understanding of NLP and provide you with hands-on experience in real-world applications.

## Project Overview

This project is organized into five main components, each focusing on a different aspect of the analysis. Below is a brief description of each component:

### 1. Data Scraper
- **Description**: This folder contains code that employs the Scrapy framework to scrape data from the web. The goal is to build a comprehensive dataset about the chosen series, ensuring that the dataset is rich and informative.
- **Key Features**:
  - Web scraping techniques using Scrapy
  - Data cleaning and preprocessing
  - Customizable scraping rules to target specific data sources

### 2. Character Network Visualization
- **Description**: This folder includes code to create an intricate character network using SpaCy's Named Entity Recognition (NER) model, NetworkX, and PyViz. The character network visualizes the relationships between different characters within the series.
- **Key Features**:
  - NER implementation to identify character entities
  - NetworkX for constructing and visualizing the character graph
  - PyViz for enhanced data visualization techniques

### 3. Text Classification Model
- **Description**: This directory contains the implementation of a text classifier that can categorize text into multiple classes. This component can be tailored to suit various classification tasks relevant to the series.
- **Key Features**:
  - Training and evaluation of classification models
  - Support for multiple classification algorithms (e.g., Naive Bayes, SVM)
  - Hyperparameter tuning for optimal performance

### 4. Theme Extraction
- **Description**: This folder features code that extracts the main themes of the series using zero-shot classifiers. Understanding the themes enhances the analysis of the narrative structure.
- **Key Features**:
  - Utilization of zero-shot learning techniques for theme extraction
  - Ability to identify and categorize various narrative themes
  - Integration with the text classifier for comprehensive analysis

### 5. Character Chatbot
- **Description**: This folder contains the code for building an interactive character chatbot powered by LLMs. Users can engage in conversations with characters from the series, providing a unique and immersive experience.
- **Key Features**:
  - Implementation of a chatbot using transformer-based LLMs
  - Customization options for character personality and dialogue
  - Integration with the Gradio library for an interactive web interface
