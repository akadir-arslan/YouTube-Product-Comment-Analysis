# Sentiment Analysis and Key Theme Identification in YouTube Comments for "GoPro HERO12" Product Reviews Using TextBlob and LLM"

## **Overview**

This project involves analyzing YouTube video comments related to the GoPro Hero 12 camera. The analysis aims to evaluate sentiment using various models, visualize sentiment trends, and identify key themes (topics) from user feedback. The dataset consists of English-language comments from top-viewed videos, with a focus on extracting actionable insights for marketing, product development, and customer engagement.

## **Project Tasks**

### **1. Sentiment Analysis**

- **Sentiment Labeling:** Manual sentiment labeling for the first 21 comments to evaluate model performance.
- **Models Used:**
  - **VADER:** Valence Aware Dictionary and sEntiment Reasoner
  - **TextBlob:** A library for processing textual data.

### **2. Visualization**

- **Sentiment Distribution by Video:** Visualization of sentiment distribution across different videos using TextBlob.
- **General Sentiment Distribution:** Analysis of positive, neutral, and negative sentiments in comments about the product.
- **Temporal Sentiment Trends:** Visualization of sentiment trends over time to understand changes in customer feedback.

### **3. Key Theme Identification**

- **Model Used:** Meta-LLama-3-70B-Instruct LLM from Replicate.
- **Purpose:** Identifying main topics from positive and negative comments to understand user feedback and areas for improvement.

## **Data**

- **Source:** Comments extracted from top-viewed YouTube videos related to GoPro Hero 12 product.
-  The data is collectected and preprocessed for the further analysis in the **data_engineering.ipynb** file.

## **Requirements**

- Python packages: `pandas`, `vaderSentiment`, `textblob`, `scikit-learn`, `matplotlib`, `replicate`
- API Token for Replicate

## **How to Run**

1. **Download the Dataset:**
   - Obtain the dataset from the source mentioned above and save it as `processed_comments.csv`.

2. **Install Required Packages**


"Sentiment Analysis and Key Theme Identification in YouTube Comments for GoPro HERO12 Reviews Using TextBlob and LLM"


