# Anomaly Detection  Amazon Reviews

> A machine learning project that detects anomalous Amazon beauty product reviews using statistical analysis and data visualization to identify potentially fake or suspicious reviews.

## 🎯 Project Overview

This project implements an **anomaly detection pipeline** for Amazon product reviews, specifically targeting beauty products. By leveraging statistical methods and machine learning algorithms, we identify outlier reviews that may indicate fake, spam, or suspicious content.

### Key Features
- 📊 **Statistical Analysis**: Advanced anomaly scoring algorithms
- 🔍 **Data Visualization**: Interactive plots for pattern recognition
- 🤖 **Machine Learning**: Optimized detection models
- 📈 **Performance Metrics**: Comprehensive evaluation framework

## 📁 Repository Structure

```
Anomaly_Detection_AmazonReviews/
├── 📊 analysis.py                      # Main analysis script
├── 📁 output/                          # Generated results
├── 📁 images/                          # Visualization outputs
├── 📋 Report.pdf                       # Technical documentation
└── 📖 README.md                        # Project documentation
```

## 🔍 Data Analysis & Insights

### Price vs Anomaly Relationship

Our analysis reveals interesting patterns between product pricing and anomaly detection:



**Key Findings:**
- Most anomalous reviews concentrate at **lower price points** ($0-$500)
- Higher-priced products show **fewer anomalous patterns**
- Clear inverse relationship between price and anomaly likelihood

### Sentiment Distribution Analysis

The sentiment analysis provides crucial insights into review authenticity:



**Observations:**
- **Sharp central peak** around neutral sentiment (0.0)
- Over **500K reviews** clustered near neutral sentiment
- **Symmetric distribution** with moderate positive/negative tails

### Feature Correlation Matrix

Understanding relationships between key variables:



**Correlation Insights:**
- **Weak correlations** across all features (< 0.10)
- Rating and sentiment show **minimal correlation** (0.01)
- Price demonstrates **slight negative correlation** with anomaly scores (-0.01)

### Rating vs Sentiment Analysis

Boxplot analysis reveals sentiment patterns across rating levels:



**Pattern Analysis:**
- **Consistent sentiment distribution** across all rating levels (1-5 stars)
- Similar **median values** (~0.15) for all ratings
- Extensive **outliers** present in every rating category

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Quick Start

```bash
# Clone the repository
git clone https://github.com/DiwakarP0/Anomaly_Detection_AmazonReviews.git
cd Anomaly_Detection_AmazonReviews

# Run the analysis
python analysis.py
```

## 🛠️ Methodology

### 1. Data Preprocessing
- **Data Cleaning**: Remove noise and standardize formats
- **Feature Engineering**: Extract sentiment, ratings, and price features
- **Normalization**: Scale features for optimal algorithm performance

### 2. Anomaly Detection Pipeline
- **Statistical Methods**: Z-score and IQR-based detection
- **Machine Learning**: Isolation Forest and Local Outlier Factor
- **Optimization**: Threshold tuning for balanced precision/recall

### 3. Validation & Analysis
- **Visual Analytics**: Multi-dimensional plotting and correlation analysis
- **Performance Metrics**: Precision, recall, and F1-score evaluation
- **Statistical Testing**: Significance testing for pattern validation

## 📊 Results Summary

| Metric | Value |
|--------|-------|
| **Dataset Size** | 1.4GB+ processed reviews |
| **Features Analyzed** | Price, Rating, Sentiment, Anomaly Score |
| **Visualization Types** | 4 comprehensive plot types |
| **Key Correlation** | Price-Anomaly: -0.01 (weak negative) |

## 🔬 Technical Specifications

- **Programming Language**: Python 3.6+
- **Core Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Visualization**: High-resolution statistical plots
- **Performance**: Optimized for large-scale data processing

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

## 📧 Contact

**Diwakar** - [@DiwakarP0](https://github.com/DiwakarP0)

Project Link: [https://github.com/DiwakarP0/Anomaly_Detection_AmazonReviews](https://github.com/DiwakarP0/Anomaly_Detection_AmazonReviews)

***

⭐ **Star this repository** if you find it helpful!

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/images/84903779/1c0bfebf-a196-453d-bbf4-defc3d9da4ff/scatter_price_anomaly.jpg)
[2](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/images/84903779/d9c1e28b-0ef0-4276-9603-7a3e14af09b1/histogram_sentiment.jpg)
[3](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/images/84903779/13e6b954-e1c7-46bb-8320-92c3bc96bcfd/correlation_heatmap.jpg)
[4](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/images/84903779/49cdeade-b772-42ce-a655-bdb2b599774f/boxplot_sentiment_rating.jpg)
