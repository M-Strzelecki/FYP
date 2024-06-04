# A Machine Learning Approach to Nutritional Analysis

## Project Overview

This project aims to provide an automated solution for nutritional analysis using machine learning techniques. It features a mobile application that uses barcode scanning to retrieve and analyze nutritional data, categorizing food products into health-conscious clusters. The application leverages machine learning models to simplify nutritional information, making it accessible and understandable for users.

## Features

- **Barcode Scanning:** Instantly retrieve detailed product information from Open Food Facts.
- **Nutritional Clustering:** Categorize products into clusters to help users make healthier food choices.
- **User-Friendly Interface:** Designed with Flutter for compatibility with both Android and iOS devices.
- **Data Visualization:** Includes various visual tools such as word clouds, bar graphs, and PCA heatmaps for better understanding.

## Goals and Objectives

### Simplify Access to Nutritional Information
- Use barcode scanning for quick data retrieval.
- Provide detailed product information instantly.

### Deliver Dietary Recommendations
- Implement clustering models to analyze and categorize nutritional data.
- Aid users in making healthier food choices.

### Enhance User Experience
- Ensure the app operates efficiently across multiple devices.
- Provide an intuitive and user-friendly interface.

## Technical Details

### Mobile Application Development
- **Framework:** Flutter for cross-platform compatibility.
- **Barcode Scanning:** Integration with a high-performance barcode scanning library.
- **API:** Uses Open Food Facts API for product data retrieval.

### Machine Learning Model
- **Data Analysis:** Initially developed in Python for data preprocessing.
- **Model Development:** Uses K-Means clustering, PCA for dimensionality reduction.
- **On-Device Execution:** Converted to PyTorch for integration into the mobile app.

### Data Visualization
- **Clusters Visualization:** PCA to visualize clusters.
- **Word Clouds:** Generated from NLP results to identify common words from product names.
- **Heatmaps:** Show feature contributions to principal components.

## Demo Video

Watch the [demo video](https://drive.google.com/file/d/1bwGZ9xquwQcMDWz5YkeGE9hXrn83u55z/view?usp=drive_link) to see the application in action.

## Future Enhancements

### Advanced Machine Learning Techniques
- Explore integration of more sophisticated models for better accuracy and predictive capabilities.

### Personalization Features
- Develop user-profile systems for personalized dietary recommendations based on individual health goals and dietary restrictions.

### Real-Time Feedback System
- Implement a feedback mechanism for users to rate and provide suggestions on dietary recommendations.

## Acknowledgments

Special thanks to my supervisors, Oonagh O’Brien and Brian Murphy, for their invaluable guidance and unwavering support throughout this project. Thanks also to my wife and child for their patience and support.
