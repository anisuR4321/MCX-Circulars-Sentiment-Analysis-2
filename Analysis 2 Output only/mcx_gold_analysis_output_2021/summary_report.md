
# MCX Gold Circular Sentiment Analysis - Summary Report

## Overview
This report analyzes the relationship between MCX circular sentiment regarding gold commodity and *gold price changes* using multiple time windows for analysis.

## Key Findings

### Time Window: T±3 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: -0.120
   - Statistical significance: p-value = 0.0490 (Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=222): -0.15% ± 1.54%
   - Neutral sentiment circulars (n=0): nan% ± nan%
   - Negative sentiment circulars (n=47): 0.28% ± 1.22%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -2.106
   - p-value: 0.0384 (Significant at α=0.05)
   - This suggests there is a statistically significant difference between price changes following positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: -0.117
   - Statistical significance: p-value = 0.0555 (Not Significant at α=0.05)
   - The standard sentiment algorithm performs better than the enhanced algorithm for this time window.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=129): -0.23% ± 1.41%
     - hereby notified as under: (n=46): 0.37% ± 1.26%
     - hereby  notified as under: (n=19): 0.24% ± 1.30%

### Time Window: T±7 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: -0.060
   - Statistical significance: p-value = 0.3249 (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=222): -0.26% ± 2.33%
   - Neutral sentiment circulars (n=0): nan% ± nan%
   - Negative sentiment circulars (n=47): 0.08% ± 1.94%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -1.074
   - p-value: 0.2862 (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: -0.063
   - Statistical significance: p-value = 0.3055 (Not Significant at α=0.05)
   - The enhanced sentiment algorithm shows stronger correlation with price changes compared to the standard algorithm.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=129): -0.37% ± 2.10%
     - hereby notified as under: (n=46): 0.32% ± 1.77%
     - hereby  notified as under: (n=19): -0.17% ± 2.51%

### Time Window: T±15 days

1. **Sentiment-Price Change Correlation**:
   - Correlation coefficient: -0.025
   - Statistical significance: p-value = 0.6841 (Not Significant at α=0.05)

2. **Price Change % by Sentiment Category**:
   - Positive sentiment circulars (n=222): -0.56% ± 3.25%
   - Neutral sentiment circulars (n=0): nan% ± nan%
   - Negative sentiment circulars (n=47): -0.41% ± 3.19%

3. **Statistical Test Between Positive and Negative Sentiment Groups**:
   - t-statistic: -0.300
   - p-value: 0.7651 (Not Significant at α=0.05)
   - There is not enough evidence to conclude that price changes differ significantly between positive and negative sentiment circulars.

4. **Enhanced Sentiment Analysis**:
   - Alternative sentiment algorithm correlation: -0.026
   - Statistical significance: p-value = 0.6712 (Not Significant at α=0.05)
   - The enhanced sentiment algorithm shows stronger correlation with price changes compared to the standard algorithm.

5. **Circular Category Analysis**:
   - Top circular categories and their associated price changes:
     - notified as under: (n=129): -0.59% ± 3.25%
     - hereby notified as under: (n=46): 0.23% ± 2.99%
     - hereby  notified as under: (n=19): -1.26% ± 3.77%

## Overall Conclusions

1. **Time Window Analysis**: The relationship between circular sentiment and price changes was statistically significant for the following time windows: T±3 days.

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
