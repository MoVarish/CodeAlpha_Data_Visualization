# Task 4: Sentiment Analysis

## Project Overview
This project demonstrates Sentiment Analysis using Natural Language Processing (NLP).

It analyzes sample customer reviews and classifies them into:
- Positive
- Negative
- Neutral

It also detects possible emotion signals using keywords and visualizes sentiment and emotion patterns through graphs.

## Objectives
- Classify text into sentiment categories.
- Detect possible emotions using keyword matching.
- Visualize sentiment and emotion results.
- Understand customer feedback and identify possible business improvements.

## Technologies Used
- Python
- Google Colab
- Pandas
- Matplotlib
- VADER Sentiment
- NLP (Natural Language Processing)

## Project Workflow
1. Create a sample review dataset.
2. Analyze reviews using VADER.
3. Classify sentiment as Positive, Negative, or Neutral.
4. Detect emotion keywords.
5. Generate sentiment and emotion graphs.
6. Display insights and conclusion.

## Sentiment Classification
VADER compound score rules:
- Positive: Score >= 0.05
- Negative: Score <= -0.05
- Neutral: Otherwise

## Sample Results
Total sample reviews: 10

| Sentiment | Count |
|---|---:|
| Negative | 5 |
| Positive | 4 |
| Neutral | 1 |

**Most Common Sentiment:** Negative

## Emotion Summary
| Emotion | Count |
|---|---:|
| No keyword match | 4 |
| Joy | 3 |
| Disgust | 2 |
| Sadness | 1 |

## Business Insights
- Negative reviews may help identify product issues.
- Positive reviews may highlight customer satisfaction.
- Neutral reviews may provide useful feedback.

## Visualizations
- Sentiment Graph
- Emotion Graph

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. If required, install VADER:

   `!pip install vaderSentiment`

4. View the classification results, emotion results, graphs, and conclusion.

## Limitations
- This project uses a small sample dataset.
- VADER may not fully understand sarcasm or context.
- Keyword-based emotion detection can miss emotions.
- Results are not representative of the whole market.

## Conclusion
This project demonstrates how sentiment analysis can help businesses understand customer opinions and improve products and services.

**Project File:** `Task_4_Sentiment_Analysis.ipynb`
