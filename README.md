# Conspiracy vs Social Theory Analysis

This project analyzes the differences between conspiracy theory discourse and social theory discourse using Reddit data and text analysis methods.

## Research Question
Can conspiracy theories be systematically distinguished from social theories based on measurable linguistic and argumentative features?

## Data
- Data collected using the Reddit API (PRAW)
- 100 posts each from:
  - r/conspiracy
  - r/AskSocialScience
- Total dataset: ~19,000 words

## Methods
- Text data collection via Python (Reddit API)
- Data cleaning and preprocessing
- Feature extraction, including:
  - Citation frequency
  - Emotional/moral language
  - Named entity recognition (agent specificity)
  - Causal complexity scoring
- Statistical testing (Welch’s t-tests)

## Key Findings
- Social theory posts are significantly longer and more detailed
- Conspiracy posts rely more on single-cause explanations
- Social theory discourse shows higher causal complexity and agent specificity
- Emotional language and citation frequency were not statistically significant differences

## Significance
This project highlights how different communities construct knowledge and explanations, showing that conspiracy and social theory discourse differ not just in content, but in structure and reasoning.

## Files
- report.pdf: full paper and analysis
