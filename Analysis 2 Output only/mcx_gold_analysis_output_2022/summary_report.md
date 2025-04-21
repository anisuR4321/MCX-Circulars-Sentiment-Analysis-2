
# MCX Gold Circular Sentiment Analysis - Summary Report

## Overview
This report analyzes the relationship between MCX circular sentiment regarding gold commodity and *gold price changes* using multiple time windows for analysis.

## Key Findings

### Time Window: T±3 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: nan
   - Statistical significance: p-value = nan (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=212): 0.34% ± 1.19%
   - Neutral sentiment circulars (n=2): 0.97% ± 1.09%
   - Negative sentiment circulars (n=52): 0.37% ± 1.24%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: nan
   - p-value: nan (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: nan
   - Statistical significance: p-value = nan (Not Significant at α=0.05)
   - The standard sentiment algorithm performs better than the enhanced algorithm for this time window.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=92): 0.34% ± 1.19%
     - hereby notified as under: (n=66): 0.30% ± 1.17%
     - hereby  notified as under: (n=27): 0.38% ± 1.15%

### Time Window: T±7 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: 0.067
   - Statistical significance: p-value = 0.2761 (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=213): 0.55% ± 2.12%
   - Neutral sentiment circulars (n=2): 1.63% ± 2.48%
   - Negative sentiment circulars (n=52): 0.21% ± 2.13%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: 1.037
   - p-value: 0.3030 (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: 0.063
   - Statistical significance: p-value = 0.3021 (Not Significant at α=0.05)
   - The standard sentiment algorithm performs better than the enhanced algorithm for this time window.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=92): 0.42% ± 2.10%
     - hereby notified as under: (n=66): 0.44% ± 2.05%
     - hereby  notified as under: (n=27): 0.42% ± 2.19%

### Time Window: T±15 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: 0.011
   - Statistical significance: p-value = 0.8620 (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=213): 1.22% ± 2.59%
   - Neutral sentiment circulars (n=2): 2.76% ± 0.45%
   - Negative sentiment circulars (n=52): 1.25% ± 3.01%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -0.058
   - p-value: 0.9541 (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: 0.008
   - Statistical significance: p-value = 0.9029 (Not Significant at α=0.05)
   - The standard sentiment algorithm performs better than the enhanced algorithm for this time window.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=92): 1.38% ± 2.76%
     - hereby notified as under: (n=66): 1.28% ± 2.59%
     - hereby  notified as under: (n=27): 1.36% ± 2.70%

## Overall Conclusions

1. **Time Window Analysis**: None of the analyzed time windows showed a statistically significant relationship between circular sentiment and price changes at the α=0.05 level.

2. **Sentiment Group Differences**: No statistically significant differences were found between price changes following positive versus negative sentiment circulars, suggesting that sentiment polarity alone may not be a strong predictor of subsequent price movements.

3. **Sentiment Algorithm Comparison**: The standard sentiment algorithm generally performed better in capturing the relationship between circular sentiment and price changes. This suggests that standard sentiment analysis is more effective for this application.

## Limitations and Recommendations

1. **Multiple Factors**: Gold prices are influenced by numerous global factors beyond MCX circulars, including macroeconomic indicators, geopolitical events, and market sentiment from other sources.

2. **Sample Size**: The analysis is based on a limited set of circulars, which may affect the robustness of the findings.

3. **Time Lag**: The optimal time window for measuring price changes after circular issuance may vary depending on market conditions and the nature of the circular.

4. **Sentiment Algorithms**: Standard sentiment analysis may not fully capture the nuanced and technical language used in MCX circulars.

### Recommendations for Further Research

1. **Combine with Other Indicators**: Integrate circular sentiment with other technical and fundamental indicators for a more comprehensive analysis framework.

2. **Develop Domain-Specific Sentiment Models**: Create sentiment algorithms specifically trained on financial and commodity market terminology.

3. **Categorize Circulars**: Further analyze the relationship between circular categories and price changes to identify which types of circulars have the strongest price impact.

4. **Varying Time Windows**: Experiment with additional time windows to identify the optimal lag between circular issuance and price reactions.
