# # Fake Review Detector

A Natural Language Processing (NLP) project that detects potentially fake online reviews using a hybrid approach combining:

* NLTK VADER Sentiment Analysis
* Rule-Based Classification
* Text Feature Extraction
* Linguistic Pattern Detection

Developed by **Dionis**.

---
<img width="604" height="565" alt="image" src="https://github.com/user-attachments/assets/1f61dcf3-5dd4-4db5-9c11-518da951842c" />

---
## Overview

Online platforms are increasingly affected by fake reviews that can manipulate customer decisions. This project analyzes review text and classifies it as:

* ✅ GENUINE
* 🚨 SUSPICIOUS

The detector uses sentiment analysis and handcrafted NLP features to identify common characteristics of deceptive reviews.

---

## Features

### NLP Analysis

* Sentiment scoring using VADER
* Positive, Negative and Neutral sentiment detection
* Compound sentiment score evaluation

### Text Analysis

* Review length analysis
* Capital letter detection
* Exclamation mark frequency
* Vocabulary diversity measurement
* Exaggerated language detection
* Specific detail identification

### Classification System

The final decision is based on a weighted scoring mechanism that evaluates multiple indicators of authenticity and deception.

---

## Technologies Used

* Python 3
* NLTK
* VADER Sentiment Analyzer
* Regular Expressions (Regex)
* Rule-Based Classification

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Dionis-bit/fake-review-detector.git
cd fake-review-detector
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python detector.py
```

---

## Example

### Input

```text
This product is absolutely amazing!
Best product ever!
Highly recommend!
```

### Output

```text
Classification: SUSPICIOUS
Score: 72/100
```

---

## Project Structure

```text
fake-review-detector/
│
├── detector.py
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
└── examples/
```

---

## Detection Criteria

The detector evaluates:

* Extreme positive sentiment
* Exaggerated marketing language
* Excessive punctuation
* High capitalization usage
* Repetitive vocabulary
* Lack of specific product details

Indicators that increase authenticity:

* Product-specific information
* Balanced opinions
* Real user experiences
* Concrete details

---

## Future Improvements

* Machine Learning Model (Random Forest / XGBoost)
* Dataset-Based Training
* Web Interface
* REST API
* Multilingual Review Detection
* Confidence Probability Score

---

## Author

**Dionis-bit**

---

## License

This project is licensed under the MIT License.
