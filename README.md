Trader Behavior Insights

Project Overview
This project analyzes the relationship between cryptocurrency trading volumes and the Fear & Greed Index to uncover potential trading signals.
The objective is to understand how market sentiment influences trader behavior and to hypothesize possible strategies based on observed patterns.

------------------------------------------------------------

Table of Contents
1. Load and Prepare Data
2. Analyze Trading Behavior
3. Analyze Market Sentiment
4. Combine and Align Data
5. Identify Correlations and Trends
6. Identify Hidden Signals
7. Summary
8. Outputs

------------------------------------------------------------

1. Load and Prepare Data
- Imported trading volume data and Fear & Greed Index data
- Aligned time periods and ensured consistent formatting
- Checked for missing values (none found)

------------------------------------------------------------

2. Analyze Trading Behavior
- Visualized daily trading volumes
- Observed variability in trading activity across time

------------------------------------------------------------

3. Analyze Market Sentiment
- Classified sentiment into categories: Extreme Fear, Fear, Neutral, Greed, Extreme Greed
- Visualized distribution of sentiment across the dataset

------------------------------------------------------------

4. Combine and Align Data
- Merged both datasets on Date
- Final dataset contained aligned volume and sentiment classification per day

------------------------------------------------------------

5. Identify Correlations and Trends
- Computed correlation between trading volume and sentiment values
- Generated visualizations:
  * Correlation heatmap
  * Boxplot of trading volume by sentiment classification
  * Violin plot of trading volume by sentiment classification

------------------------------------------------------------

6. Identify Hidden Signals
Key hypotheses:
1. High trading volume during Fear suggests capitulation, potentially creating contrarian buying opportunities
2. Low trading volume during Extreme Greed suggests reduced activity at peaks, possibly signaling caution or selling opportunities
3. Large variance and outliers in volumes during fear states indicate that large individual trades may provide stronger signals than averages

------------------------------------------------------------

7. Summary
- Trading volume responds to sentiment extremes
- Extreme emotional states (fear and greed) provide the strongest observable signals
- This framework can be extended into signal generation and trading strategy design

------------------------------------------------------------

8. Outputs
All results are saved in the /outputs folder:
- correlation_matrix.csv
- average_volume_by_sentiment.csv
- correlation_heatmap.png
- volume_by_sentiment_boxplot.png
- volume_by_sentiment_violinplot.png
- trading_signals_summary.pdf

------------------------------------------------------------

How to Run
1. Clone the repository:
   git clone (https://github.com/Aparna200504/ds_aparna_prasad.git)
2. Open the notebook in Google Colab or Jupyter
3. Run all cells to reproduce analysis and outputs


