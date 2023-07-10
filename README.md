# Comparative Analysis of Streaming Numbers and YouTube Viewership

This project aims to analyze and compare various factors related to streaming numbers and YouTube viewership in the music industry. The analysis focuses on four main categories:

1. **Comparing Streaming Numbers and YouTube Viewership:** The project examines the relationship between the streaming numbers on Spotify and the viewership of official music videos on YouTube for individual songs. By comparing these metrics, insights can be gained into the popularity and consumption patterns of music across the two platforms.

2. **Comparing Numbers between Albums and Singles:** The analysis delves into the differences in streaming numbers and YouTube viewership between albums and singles. This comparison allows for an understanding of the varying preferences and consumption patterns of listeners and viewers for different types of music releases.

3. **Comparing Numbers between Major and Minor Keys:** The project explores the impact of musical key (represented using standard Pitch Class notation) on streaming numbers and YouTube viewership. By analyzing the differences between songs in major keys and songs in minor keys, insights can be gained into the potential influence of musical tonality on audience engagement.

4. **Comparing Numbers between Music Artists:** The analysis extends to comparing streaming numbers and YouTube viewership across different music artists. By examining the variations in popularity and viewership between artists, it becomes possible to identify trends and factors contributing to their respective levels of success.

<!-- ## Project Overview

The project is organized into the following steps:

1. **Importing the Required Libraries:** The necessary Python libraries such as pandas, numpy, matplotlib, and scipy.stats are imported. These libraries provide the required functionalities for data analysis, manipulation, visualization, and statistical testing.

2. **Collecting and Preparing the Data:** The dataset containing information on streaming numbers, YouTube views, album types, music keys, and music artists is collected and read into a pandas DataFrame. Data preprocessing steps, such as handling missing values and data formatting, are performed.

3. **Comparing Streaming Numbers and YouTube Viewership:** The streaming numbers and YouTube viewership for each song are compared using statistical analysis techniques such as hypothesis testing (paired t-test) and data visualization (histograms).

4. **Comparing Numbers between Albums and Singles:** The analysis is expanded to compare streaming numbers and YouTube viewership between albums and singles. The data is filtered based on the album type, and the statistical analysis and visualization are performed for each category.

5. **Comparing Numbers between Major and Minor Keys:** The streaming numbers and YouTube viewership are further compared between songs in major keys and songs in minor keys. The data is filtered based on the music key, and the statistical analysis and visualization are performed.

6. **Comparing Numbers between Music Artists:** The analysis is extended to compare streaming numbers and YouTube viewership across different music artists. The data is grouped by artist, and statistical analysis and visualizations are performed to identify variations and insights.

7. **Documentation and Sharing:** The code is thoroughly documented with comments explaining each step and the purpose of the code. Markdown files and README.md are created to provide detailed descriptions, explanations, and visualizations of the analysis. The code and analysis results can be shared via GitHub or other platforms. -->

## Summary of Analysis

### 1. Streaming Numbers vs. YouTube Viewership:

* In this category, we compared the streaming numbers on Spotify with the viewership of official music videos on YouTube. The analysis involved applying the Central Limit Theorem to obtain sampling distributions and performing statistical tests.
* The results of the statistical test on the original data indicated a significant difference between Spotify streaming and YouTube views, as the p-value was below the chosen significance level. This suggests that there is a significant variation between the two platforms in terms of streaming numbers and YouTube viewership.
* A statistical analysis was performed using a paired t-test to compare the sample means of streaming numbers and YouTube views. The resulting p-value indicated whether there was a significant difference between the two metrics.
* The distributions of the sample means were visualized using histograms to understand their distributions and compare them between streaming numbers and YouTube views.

![Compare Avg Streaming:Viewing](https://github.com/CBrownTech/Data-Analysis-Science/assets/99114801/94234ced-476c-42fb-aea5-aff871c48f7b) 

![Sampling Dist  of Difference (Streaming and YT Views) ](https://github.com/CBrownTech/Data-Analysis-Science/assets/99114801/b2871866-8325-4349-b6c1-6c66a3f09558)

![Dist  Sample Means Streams:Views](https://github.com/CBrownTech/Data-Analysis-Science/assets/99114801/361e6edd-4d9a-4304-87c1-51becec7068b)

### Conclusion:

Based on the analysis, it can be concluded that there is a significant difference between Spotify streaming numbers and YouTube viewership. Spotify and YouTube have distinct patterns in terms of popularity and viewership, suggesting that these platforms attract different audiences and have different levels of engagement.

The bar chart comparing the average streaming numbers and YouTube views further emphasizes the differences between the two platforms. Spotify streaming numbers tend to be higher on average compared to YouTube views.

Overall, this analysis provides insights into the contrasting popularity and viewership patterns of music between Spotify and YouTube. It can assist in understanding audience behavior and preferences, as well as inform strategic decisions related to music distribution and promotion on these platforms.

### 2. Albums vs. Singles:

* The statistical analysis indicated a significant difference between album streaming and single streaming on Spotify, as well as between album views and single views on YouTube. This suggests that albums and singles have distinct patterns of popularity and viewership on these platforms.
* The additional analysis revealed the mean streaming numbers and YouTube views for albums and singles, allowing for a direct comparison. The bar plots visually demonstrated the differences in average streaming numbers and YouTube views between the two categories.
* The sampling distribution of the difference in sample means was visualized through a histogram, showcasing the distribution of differences obtained by randomly sampling from the data. The observed difference in sample means was indicated by a vertical line in the histogram.

![Compare Avg Numbers of Albums and Singles](https://github.com/CBrownTech/Data-Analysis-Science/assets/99114801/9f8f5e61-eefb-48d5-8023-558a4d704978)

![Sampling Dist  of Albums and Singles](https://github.com/CBrownTech/Data-Analysis-Science/assets/99114801/9473c755-6f0f-4aa0-87eb-c511fca7e035)

### Conclusion:

Based on the analysis, it can be concluded that there is a significant difference in streaming numbers and YouTube views between albums and singles. Albums tend to have higher streaming numbers and YouTube views compared to singles.

This analysis provides insights into the varying popularity and viewership patterns between albums and singles in the music industry. It can inform decision-making processes related to music production, marketing, and audience engagement strategies. Understanding the differences between albums and singles can help music artists and industry professionals tailor their approaches and maximize their impact.


### 3. Major Keys vs. Minor Keys

* The Central Limit Theorem is applied by generating random samples and calculating the sample means for major keys and minor keys.
* A statistical test (independent t-test) is performed to compare the means of streaming numbers between major keys and minor keys.
* The distributions of sample means for major keys and minor keys are visualized through histograms.

![Dist  Sample Means Music Keys](https://github.com/CBrownTech/Data-Analysis-Science/assets/99114801/ed618274-5007-4aae-9108-f91990472660)

### Conclusion:

Based on the analysis, we can confidently conclude that there is a significant disparity in streaming numbers between major keys and minor keys. The key of the music plays a crucial role in determining its popularity and listenership, as evidenced by the clear distinction in streaming patterns observed between major keys and minor keys. This finding highlights the importance of considering the musical key when analyzing and promoting music, as it significantly impacts its overall appeal and engagement among listeners. 

The mean streaming numbers and the distribution of sample means further support this conclusion, providing valuable insights into the average popularity of music in each key category. Musicians, producers, and industry professionals can leverage this knowledge to make informed decisions in music composition, selection, and marketing strategies, thereby optimizing their reach and impact in the industry.

### Streaming Numbers vs. YouTube Viewership Among Music Artists

* In this category, we explored the relationship between streaming numbers and YouTube views among music artists. The analysis aimed to determine if there is a correlation between these two metrics and provide insights into the connection between streaming popularity and YouTube engagement.
* We began by grouping the data by music artists and calculating the mean streaming numbers and YouTube views for each artist. This allowed us to identify the top artists with the highest streaming numbers and YouTube views.
* To assess the correlation between streaming numbers and YouTube views, we performed correlation analysis using the correlation coefficient. The analysis revealed a strong positive correlation of 0.9453, indicating that approximately 94.53% of the variability in streaming numbers can be attributed to the variability in YouTube views among the top music artists.
* The significance of this correlation implies that artists who achieve higher streaming numbers also tend to receive higher YouTube views. This finding emphasizes the interdependence of streaming platforms and YouTube as key indicators of music popularity and audience engagement.
* We further visualized the mean streaming numbers and YouTube views for the top artists using bar charts, providing a clear comparison of the metrics and highlighting the artists who excelled in terms of both streaming numbers and YouTube views.

![Top Artists by Streaming Numbers](https://github.com/CBrownTech/Data-Analysis-Science/assets/99114801/1db39166-a0a2-4c6a-859a-9a4d8c26d33c)

![Top Artists by YouTube Views](https://github.com/CBrownTech/Data-Analysis-Science/assets/99114801/f446f59e-567a-4ba6-b0a0-c867f3b4feb5)

![Dist  Sample Means Music Artists](https://github.com/CBrownTech/Data-Analysis-Science/assets/99114801/8476b36e-10f1-48ab-a2ba-ba0394ba754b)

### Conclusion:

The analysis of the correlation between streaming numbers and YouTube views among music artists demonstrates a significant and positive relationship between these metrics. Artists with higher streaming numbers are more likely to have higher YouTube views, indicating a strong connection between streaming popularity and YouTube engagement.

This correlation highlights the importance of considering both streaming numbers and YouTube views when evaluating the success and impact of music artists in the digital landscape. It suggests that a strong presence on streaming platforms can drive higher engagement on YouTube and vice versa.

By leveraging this correlation, music artists can strategically focus on optimizing their digital strategies, promotional efforts, and content creation to enhance visibility and capture the attention of their target audience effectively. It provides valuable insights for artists, producers, and industry professionals to make informed decisions and maximize their reach and impact in the digital music landscape.

Overall, the analysis underscores the interconnectedness of streaming platforms and YouTube in determining music popularity and emphasizes the need for a holistic approach to audience engagement and digital marketing strategies in the music industry.

## Instructions

To run the code and replicate the analysis:

1. Install the required libraries mentioned in the `requirements.txt` file.
2. Download the dataset in CSV format and save it as `your_dataset.csv`.
3. Update the file paths and names in the code as necessary.
4. Run the code step-by-step, following the instructions and comments provided in each section.
5. Examine the results, visualizations, and interpretations obtained at each step.
6. Customize the code, visualizations, and analysis as needed for your specific requirements.

Please note that the code provided is a guideline, and you may need to adapt it based on your dataset and analysis goals.

---

This README.md file provides an overview of the project and a step-by-step guide to replicate the analysis. Feel free to customize and expand upon it based on your specific project requirements, datasets, and analyses.

If you have any questions or need further assistance, please let me know!
