## 📊 YouTube Comments Analysis
**Author**: Daanan Dasilva  
**Date**: September 2024

### Project Overview
This project aims to explore and analyze YouTube comments to gain insights into viewer sentiment, engagement patterns, and category performance. By leveraging sentiment analysis, word cloud visualizations, and engagement metrics, this project uncovers valuable feedback trends across different types of video content. The analysis includes text preprocessing, natural language processing (NLP) techniques, and detailed visualizations to communicate findings effectively.

### Objectives
- **Sentiment Analysis**: Determine the overall sentiment (positive, negative, or neutral) of comments and identify the categories with the most positive or negative feedback.
- **Word Cloud Analysis**: Visualize the most frequently occurring words in positive and negative comments to understand common themes and topics.
- **Emoji Analysis**: Analyze emoji usage in comments to assess how viewers express their emotions.
- **Engagement Metrics Analysis**: Calculate engagement metrics such as like rate, dislike rate, and comment rate across different categories.
- **Correlation Analysis**: Explore the relationships between views, likes, and other engagement metrics to identify patterns in viewer interaction.

### Dataset
The dataset used in this project is a collection of YouTube comments that includes the following fields:
- `video_id`: Unique identifier for each YouTube video.
- `comment_text`: Text content of the comment.
- `likes`: Number of likes the comment received.
- `replies`: Number of replies to the comment.

### Project Workflow
1. **Extract, Transform, Load (ETL)**:
   - Loaded the YouTube comments dataset and additional metadata files.
   - Cleaned and transformed the data by removing duplicates, handling missing values, and converting data types.

2. **Exploratory Data Analysis (EDA)**:
   - Performed sentiment analysis using TextBlob and VADER.
   - Visualized the distribution of sentiment across categories and created word clouds for positive and negative comments.

3. **Emoji Analysis**:
   - Extracted and analyzed emoji usage to identify common emoji patterns in the comments.

4. **Engagement Analysis**:
   - Calculated and visualized like rate, dislike rate, and comment rate for each video category.

5. **Correlation Analysis**:
   - Explored correlations between views, likes, and dislikes, and created scatter plots with regression lines to show the strength of these relationships.

6. **Conclusion and Key Insights**:
   - Summarized findings and provided insights into category performance and viewer engagement.

### Results and Insights
- **Sentiment Analysis**: Most comments had neutral to positive sentiment. Categories like Entertainment and Music had the highest levels of positivity.
- **Emoji Analysis**: The most commonly used emojis were indicative of support and appreciation, such as the clapping hands emoji and the fire emoji.
- **Engagement Analysis**: Categories like Music and Entertainment had the highest average likes and comment engagement rates.
- **Correlation Analysis**: There was a strong positive correlation between views and likes, suggesting that videos with higher views also tend to have more likes.

### Technical Skills Demonstrated
- **Data Cleaning and Transformation**:
  - Handled missing values and converted data types.
  - Created new columns for engagement metrics.

- **Natural Language Processing**:
  - Used `TextBlob` and `VADER` to conduct sentiment analysis.
  - Processed and cleaned text data to extract meaningful insights.

- **Data Visualization**:
  - Created visualizations using `matplotlib`, `seaborn`, and `plotly`.
  - Used word clouds to highlight frequently occurring words in comments.

- **Statistical Analysis**:
  - Calculated and visualized engagement metrics and correlation matrices.
  - Used box plots and scatter plots to display engagement trends across categories.

### Dependencies
The following libraries are required to run this project:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `wordcloud`
- `nltk`
- `plotly`

### Future Work
- **Predictive Analysis**: Develop a model to predict video performance based on engagement metrics.
- **Viewer Demographics**: Analyze how engagement varies based on viewer demographics (if data is available).
- **Temporal Analysis**: Study engagement trends over time to identify seasonal or event-driven patterns.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Contact
If you have any questions or feedback, feel free to reach out:
- **Email**: daanandasilva@gmail.com
- **LinkedIn**: [Daanan Dasilva](https://www.linkedin.com/in/daanan-dasilva-784b10211/)
