# Exploring Fan Sentiments: Unsupervised Learning and Sentiment Analysis in Formula 1

This project explores fan sentiments regarding Formula 1 by performing sentiment analysis on YouTube comments using unsupervised learning techniques. The main focus is to analyze the overall fan sentiment toward Formula 1 races and related content, as expressed in YouTube comments.

## Project Overview

The project utilizes data collected from YouTube videos to analyze and cluster fan sentiments. The workflow involves extracting comments, performing preprocessing, and applying unsupervised learning techniques like clustering to understand different sentiment groups.

### Key Steps:
1. **Data Collection**:
   - Comments are extracted from several YouTube videos using the YouTube Data API.
   - The comments include metadata such as the author's name, the time of publication, and the number of likes the comment received.

2. **Data Preprocessing**:
   - The collected comments are cleaned, which includes removing special characters, stopwords, and applying other preprocessing techniques to prepare the data for analysis.

3. **Sentiment Analysis**:
   - Sentiment analysis is applied to the comments to determine whether the overall sentiment is positive, negative, or neutral.

4. **Unsupervised Learning**:
   - Unsupervised learning techniques such as clustering are used to group comments based on their sentiment and content.
   - This helps in identifying common themes and opinions among fans.

5. **Results and Insights**:
   - The clustering results provide insights into how Formula 1 fans feel about specific aspects of the sport.
   - Sentiment analysis results are visualized to show the distribution of sentiments (positive, negative, neutral).

## Project Structure

- `F1_Fan_Sentiment_Analysis_Unsupervised_Learning.ipynb`: Jupyter notebook containing all the code for extracting, processing, and analyzing YouTube comments.
- `README.md`: This file, providing an overview of the project.

## Installation

To run the project, ensure you have Python installed along with the necessary libraries:

```bash
pip install pandas numpy sklearn google-api-python-client nltk
```

## Usage

To run the project, follow these steps:

1. Obtain a YouTube Data API key and replace it in the notebook.
2. Set up the video IDs you want to analyze (already provided in the notebook as an example).
3. Run the Jupyter notebook to extract comments and perform the analysis.

```bash
jupyter notebook F1_Fan_Sentiment_Analysis_Unsupervised_Learning.ipynb
```

## Example Output

After running the notebook, the output will include:
- A DataFrame of YouTube comments.
- Visualization of sentiment distributions (positive, negative, neutral).
- Clustering results of fan sentiments using unsupervised learning techniques.

## Future Improvements

- Enhance data collection by increasing the number of videos analyzed.
- Apply more advanced sentiment analysis techniques, such as fine-tuned models.
- Explore other unsupervised learning algorithms to improve the clustering process.
