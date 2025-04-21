
# MCX Gold Circular Sentiment Analysis - Summary Report

## Overview
This report analyzes the relationship between MCX circular sentiment regarding gold commodity and *gold price changes* using multiple time windows for analysis.

## Key Findings

### Time Window: T±3 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: -0.152
   - Statistical significance: p-value = 0.0030 (Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=293): -0.06% ± 2.34%
   - Neutral sentiment circulars (n=1): 0.64% ± nan%
   - Negative sentiment circulars (n=87): 0.80% ± 2.23%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -3.113
   - p-value: 0.0022 (Significant at α=0.05)
   - This suggests there is a statistically significant difference between price changes following positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: -0.145
   - Statistical significance: p-value = 0.0045 (Significant at α=0.05)
   - The standard sentiment algorithm performs better than the enhanced algorithm for this time window.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=195): 0.10% ± 2.42%
     - hereby notified as under: (n=52): 0.24% ± 2.20%
     - hereby  notified as under: (n=28): 0.65% ± 1.84%

### Time Window: T±7 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: -0.158
   - Statistical significance: p-value = 0.0020 (Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=293): 0.47% ± 3.68%
   - Neutral sentiment circulars (n=1): -0.13% ± nan%
   - Negative sentiment circulars (n=87): 1.79% ± 3.70%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -2.918
   - p-value: 0.0041 (Significant at α=0.05)
   - This suggests there is a statistically significant difference between price changes following positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: -0.165
   - Statistical significance: p-value = 0.0013 (Significant at α=0.05)
   - The enhanced sentiment algorithm shows stronger correlation with price changes compared to the standard algorithm.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=195): 0.54% ± 3.80%
     - hereby notified as under: (n=52): 0.95% ± 3.42%
     - hereby  notified as under: (n=28): 1.08% ± 3.18%

### Time Window: T±15 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: -0.086
   - Statistical significance: p-value = 0.0919 (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=293): 2.08% ± 5.25%
   - Neutral sentiment circulars (n=1): 2.38% ± nan%
   - Negative sentiment circulars (n=87): 3.15% ± 5.35%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -1.652
   - p-value: 0.1007 (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: -0.093
   - Statistical significance: p-value = 0.0704 (Not Significant at α=0.05)
   - The enhanced sentiment algorithm shows stronger correlation with price changes compared to the standard algorithm.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=195): 2.05% ± 4.99%
     - hereby notified as under: (n=52): 2.44% ± 5.21%
     - hereby  notified as under: (n=28): 2.85% ± 5.70%

## Overall Conclusions

1. **Time Window Analysis**: The relationship between circular sentiment and price changes was statistically significant for the following time windows: T±3 days, T±7 days.

2. **Sentiment Group Differences**: Statistical tests revealed significant differences in price changes between positive and negative sentiment circulars for at least one time window, suggesting that sentiment polarity in MCX circulars may be a useful factor for predicting subsequent price movements.

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
