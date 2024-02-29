# Palestine_News_Analysis

This project focuses on analyzing and visualizing Palestine news articles to gain insights into the content, themes, and trends in the coverage related to Palestine. The analysis employs various techniques such as word cloud visualization, text clustering using TF-IDF, and text visualization using t-SNE to provide a comprehensive understanding of the dataset.

## Task Explanation

The task involves analyzing a dataset of Palestine news articles sourced from various sources to extract meaningful insights and patterns. The key objectives of the analysis are:

1. **Word Cloud Visualization**: The word cloud visualization technique is utilized to visually represent the most frequent words in the Palestine news articles. By generating word clouds, common themes, topics, and prominent keywords in the articles can be identified at a glance, providing an overview of the content.

2. **Text Clustering using TF-IDF**: TF-IDF (Term Frequency-Inverse Document Frequency) is employed to cluster similar news articles based on their textual content. This unsupervised learning technique calculates the importance of each word in the dataset and identifies clusters of articles with similar content. Clustering helps in organizing and categorizing the articles, facilitating better exploration and understanding of the dataset.

3. **Text Visualization using SentenceTransformer('thenlper/gte-small)**: thenlper/gte-small embedding is applied to the textual data and UMAP is employed for visualizing the text in a lower dimensional space. By reducing the dimensionality of the text data, UMAP preserves the relationships between articles and reveals underlying patterns or structures in the dataset. The resulting visualization aids in understanding the distribution of articles and identifying any clusters or groups present in the data.

## Files Included
1. **Israeli Palestine News Data preprocessing.ipynb**: Jupyter Notebook containing code for cleaning and data preprocessing

2. **WordCloud_Visualization.ipynb**: Jupyter Notebook containing code for generating word cloud visualizations of Palestine news text data.

3. **Text_Clustering_TFIDF.ipynb**: Jupyter Notebook containing code for performing text clustering using TF-IDF on Palestine news articles.

4. **Text visualisation_LLM.ipynb**: Jupyter Notebook containing code for visualizing text data using t-SNE on Palestine news articles.

5. **Palestine_News_Data.csv**: CSV file containing the Palestine news text data used for analysis.
