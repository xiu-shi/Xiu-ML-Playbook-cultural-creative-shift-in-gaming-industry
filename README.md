Xiu-ML-Playbook-cultural-creative-shift-in-gaming-industry
The cultural and creative shift in gaming industry analysis

# 🎮 The Cultural and Creative Shift in the Gaming Industry: A Data Analysis

This repository contains the data analysis and Jupyter Notebook for my Medium article, **[From Yellow Cartridges to Creative Fatigue: A Gamer's Journey Through the Shifting Sands of the Industry](<LINK_TO_YOUR_MEDIUM_ARTICLE_HERE>)**.

## 🕹️ The Story Behind This Analysis

This project was born from a personal observation: after a long and joyful history with gaming—from the simple fun of Nintendo in the 90s to the strategic depth of *Ingress* I found my passion waning. Upon returning to console gaming with the highly anticipated *Black Myth: Wu Kong*, I realized I was more captivated by the story's nostalgia than the gameplay itself. This led me to question whether my experience was unique or part of a broader trend.

This analysis uses a video game sales dataset spanning 1980 to 2016 to objectively investigate this feeling, exploring the statistical evidence of a cultural and creative shift in the gaming industry.

## 🤔 Key Question & Hypothesis

**Did the gaming industry's creative and commercial direction over the years impact overall player satisfaction?**

My hypothesis was that my personal loss of interest was not an isolated event but reflected a wider trend of declining player satisfaction as games became more commercially complex and perhaps less focused on pure, accessible fun.

## 📊 Key Findings

To test this, I segmented the dataset into two eras and performed an independent two-sample t-test on their `User_Score`.

-   **Era 1** 🏛️: Games released in or before 2005
-   **Era 2** 🚀: Games released after 2005

The results confirmed a statistically significant decline in average player satisfaction.

| Metric | Era 1 (≤2005) | Era 2 (>2005) |
| :--- | :--- | :--- |
| **Mean User Score** | 7.68 ⭐ | 6.84 📉 |
| **T-statistic** | 24.64 | - |
| **P-value** | ~0.000 ✅ | - |

> 💡 **What does this mean?** The p-value of virtually zero indicates that the observed difference in user scores between the two eras is highly unlikely to have occurred by random chance. This provides strong statistical support for the idea that the collective player experience has indeed shifted over time.

This analysis validates the core theme of the article: the feeling of a lost "golden era" of gaming isn't just nostalgia, but a sentiment supported by data. 📈

## 📁 Dataset

The analysis is based on the **Video Game Sales with Ratings** dataset, which includes over 16,000 games with information on sales, genre, platform, publisher, and critic/user scores. The data spans from 1980 to 2016.

## 🗂️ Repository Structure

-   `data-visualisation-techniques-ca1-xiu-shi.ipynb`: The main Jupyter Notebook containing all the data cleaning, analysis, statistical testing, and visualizations.
-   `Video_Games_Sales_as_at_22_Dec_2016.csv`: The raw dataset used for the analysis.
-   `README.md`: This file, providing an overview of the project.

## 🚀 Running the Analysis

To run the analysis yourself, you will need Python and the following libraries installed:

-   `pandas`
-   `numpy`
-   `seaborn`
-   `matplotlib`
-   `plotly`
-   `scipy`

You can then open and run the `data-visualisation-techniques-ca1-xiu-shi.ipynb` notebook in a Jupyter environment.

## 🤝 Connect & Discuss

Found this analysis interesting? Have thoughts on the gaming industry's evolution? I'd love to hear from you! Feel free to open an issue or reach out via the Medium article comments.

---

**Made with 💻 and 🎮 nostalgia**

