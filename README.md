# Senti_ - Sentiment Analysis Web App

**Version**: 1.0.0  
**Last Updated**: September 28, 2025, 06:03 PM IST  
**Author**: GeoEgnn  
**Repository**: [https://github.com/GeoEngnn/Senti_.git](https://github.com/GeoEngnn/Senti_.git)

This is a robust web-based sentiment analysis application developed using Streamlit. The application leverages two advanced sentiment analysis techniques: VADER (Valence Aware Dictionary and sEntiment Reasoner), a rule-based model, and Roberta, a transformer-based model from Hugging Face Transformers. Designed for ease of use, it provides an interactive interface to analyze text sentiment and compare results from both models.

## Overview

The Senti_ Sentiment Analysis Web Application allows users to input text and obtain sentiment predictions using VADER and Roberta models. VADER provides a compound score along with individual scores for negative, neutral, and positive sentiments, while Roberta offers probability distributions across these categories. The app includes a comparative analysis feature, making it a valuable tool for researchers, developers, and enthusiasts interested in natural language processing (NLP).

## Features

- **Dual Sentiment Analysis**: Implements VADER (rule-based) and Roberta (transformer-based) for comprehensive sentiment evaluation.
- **Interactive Interface**: Built with Streamlit, offering a user-friendly web interface for text input, method selection, and result visualization.
- **Comparative Analysis**: Enables side-by-side comparison of sentiment scores from both models.
- **Error Handling**: Includes robust error management for invalid inputs and model-related issues.
- **Real-Time Processing**: Delivers instant sentiment analysis results with detailed score breakdowns.


## Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)
- ngrok (for public access, optional)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/GeoEngnn/Senti_.git
   cd Senti_
