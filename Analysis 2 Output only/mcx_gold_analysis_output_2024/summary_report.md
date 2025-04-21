
# MCX Gold Circular Sentiment Analysis - Summary Report

## Overview
This report analyzes the relationship between MCX circular sentiment regarding gold commodity and *gold price changes* using multiple time windows for analysis.

## Key Findings

### Time Window: T±3 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: nan
   - Statistical significance: p-value = nan (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=154): 0.45% ± 1.51%
   - Neutral sentiment circulars (n=1): 1.77% ± nan%
   - Negative sentiment circulars (n=47): 0.00% ± 1.98%

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
     - hereby notified as under: (n=76): 0.91% ± 1.05%
     - notified as under: (n=56): 0.04% ± 1.91%
     - informed as under: (n=10): 0.45% ± 0.93%

### Time Window: T±7 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: 0.021
   - Statistical significance: p-value = 0.7634 (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=163): 0.96% ± 2.58%
   - Neutral sentiment circulars (n=1): 1.85% ± nan%
   - Negative sentiment circulars (n=47): 0.73% ± 3.07%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: 0.464
   - p-value: 0.6438 (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: 0.021
   - Statistical significance: p-value = 0.7655 (Not Significant at α=0.05)
   - The standard sentiment algorithm performs better than the enhanced algorithm for this time window.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - hereby notified as under: (n=76): 1.19% ± 2.20%
     - notified as under: (n=56): 0.62% ± 2.98%
     - informed as under: (n=10): 0.45% ± 3.50%

### Time Window: T±15 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: -0.029
   - Statistical significance: p-value = 0.6749 (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=163): 1.94% ± 3.79%
   - Neutral sentiment circulars (n=1): -5.61% ± nan%
   - Negative sentiment circulars (n=47): 2.12% ± 3.77%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -0.291
   - p-value: 0.7720 (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: -0.033
   - Statistical significance: p-value = 0.6362 (Not Significant at α=0.05)
   - The enhanced sentiment algorithm shows stronger correlation with price changes compared to the standard algorithm.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - hereby notified as under: (n=76): 1.94% ± 3.65%
     - notified as under: (n=56): 2.08% ± 4.31%
     - informed as under: (n=10): 2.25% ± 3.78%

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
