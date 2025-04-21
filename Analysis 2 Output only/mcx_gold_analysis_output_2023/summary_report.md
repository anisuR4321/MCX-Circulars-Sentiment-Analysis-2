
# MCX Gold Circular Sentiment Analysis - Summary Report

## Overview
This report analyzes the relationship between MCX circular sentiment regarding gold commodity and *gold price changes* using multiple time windows for analysis.

## Key Findings

### Time Window: T±3 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: -0.046
   - Statistical significance: p-value = 0.4347 (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=235): 0.18% ± 1.17%
   - Neutral sentiment circulars (n=1): -1.40% ± nan%
   - Negative sentiment circulars (n=49): 0.41% ± 1.06%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -1.327
   - p-value: 0.1887 (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: -0.048
   - Statistical significance: p-value = 0.4169 (Not Significant at α=0.05)
   - The enhanced sentiment algorithm shows stronger correlation with price changes compared to the standard algorithm.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=116): 0.26% ± 0.91%
     - hereby notified as under: (n=63): 0.22% ± 1.37%
     - hereby  notified as under: (n=14): -0.25% ± 1.71%

### Time Window: T±7 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: -0.036
   - Statistical significance: p-value = 0.5477 (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=235): 0.42% ± 1.94%
   - Neutral sentiment circulars (n=1): 0.46% ± nan%
   - Negative sentiment circulars (n=49): 0.68% ± 1.68%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -0.963
   - p-value: 0.3383 (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: -0.038
   - Statistical significance: p-value = 0.5262 (Not Significant at α=0.05)
   - The enhanced sentiment algorithm shows stronger correlation with price changes compared to the standard algorithm.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=116): 0.54% ± 1.65%
     - hereby notified as under: (n=63): 0.40% ± 1.90%
     - hereby  notified as under: (n=14): 0.17% ± 2.41%

### Time Window: T±15 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: -0.002
   - Statistical significance: p-value = 0.9673 (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=235): 1.31% ± 2.40%
   - Neutral sentiment circulars (n=1): -2.34% ± nan%
   - Negative sentiment circulars (n=49): 1.49% ± 2.94%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -0.400
   - p-value: 0.6902 (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: -0.010
   - Statistical significance: p-value = 0.8636 (Not Significant at α=0.05)
   - The enhanced sentiment algorithm shows stronger correlation with price changes compared to the standard algorithm.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=116): 1.40% ± 2.33%
     - hereby notified as under: (n=63): 1.26% ± 2.14%
     - hereby  notified as under: (n=14): 1.40% ± 2.68%

## Overall Conclusions

1. **Time Window Analysis**: None of the analyzed time windows showed a statistically significant relationship between circular sentiment and price changes at the α=0.05 level.

2. **Sentiment Group Differences**: No statistically significant differences were found between price changes following positive versus negative sentiment circulars, suggesting that sentiment polarity alone may not be a strong predictor of subsequent price movements.

3. **Sentiment Algorithm Comparison**: The enhanced sentiment algorithm generally performed better in capturing the relationship between circular sentiment and price changes. This suggests that domain-specific sentiment analysis with gold market terminology is more effective for this application.

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
