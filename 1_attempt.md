# Pre-AI Referee's Note & Metric Selection (Before AI)

## 1. Metric Selection Strategy
- **Skewed Items (with Flagged Outliers):** I will report the **Median** because extreme flagged values pull the mean upward, making the average look artificially high.
- **Stable Items (without Outliers):** I will report the **Mean** because prices are symmetrically distributed without extreme spikes.
- **Trend Over Time:** I will report the **First-to-Last Percentage Change** alongside the median to show overall price movement from the start to the end of the period.

## 2. Draft Referee's Note (Labelled with O, E, C)
# Pre-AI Referee's Note & Metric Selection (Before AI)

## 1. Metric Selection Strategy
- **Skewed Items (with Flagged Outliers):** I will report the **Median** because extreme flagged values pull the mean upward, making the average look artificially high.
- **Stable Items (without Outliers):** I will report the **Mean** because prices are symmetrically distributed without extreme spikes.
- **Trend Over Time:** I will report the **First-to-Last Percentage Change** alongside the median to show overall price movement from the start to the end of the period.

## 2. Draft Referee's Note (Labelled with O, E, C)
**[O]** Across the observed ledger period, the median price of staple items remained relatively stable compared to the mean, which was pulled upward by a few extreme price entries. 
**[O]** When flagged outlier rows are removed from the dataset, the mean drops significantly and aligns much closer to the median. **[O]** Calculating the first-to-last percentage change shows an overall upward drift in retail prices between the earliest and latest recorded dates. **[E]** A possible explanation for the gap between the mean and median is isolated supply chain disruptions or bulk-entry errors recorded on specific dates.
**[C]** These isolated price spikes directly caused the arithmetic mean to overstate the typical daily cost paid by consumers. **[O]** Therefore, quoting the median provides a more accurate representation of the typical price than the mean.
