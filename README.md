# Collective-intelligence
This repository contains a Python script that uses BERTopic to analyze research abstracts from arXiv related to collective intelligence and similar fields.

# arXiv Topic Modeling with BERTopic

This repository contains a Python script that uses BERTopic to analyze research abstracts from arXiv related to collective intelligence and similar fields.

The script performs the following steps:

1. **Fetches data from the arXiv API**: It queries the arXiv API for abstracts related to terms like collective intelligence, social brain, group intelligence, etc.
2. **Cleans the data**: It removes stop words from the abstracts to improve topic modeling.
3. **Generates embeddings**: Uses the SentenceTransformer model ('all-MiniLM-L6-v2') to generate embeddings for each abstract.
4. **Performs topic modeling with BERTopic**: Applies BERTopic to cluster the abstracts into topics and identify the top words for each topic.
5. **Visualizes the results**: Creates interactive visualizations of the topics, hierarchy, and topic evolution over time using Plotly and other libraries.
6. **Saves results**: Saves the topics, topic names, and paper assignments to an HTML file for easy browsing.


## Requirements

- Python 3.7 or higher
- bertopic
- sentence-transformers
- nltk
- sklearn
- matplotlib
- plotly
- umap
- hdbscan
- pandas
- requests
- xml.etree.ElementTree

To install all the required packages, you can use pip:

## Usage

1. Run the script.
2. The script will download the data from arXiv, perform topic modeling, and generate interactive visualizations.
3. The visualizations and results will be saved as HTML files.

## Files

- **arxiv_topic_modeling.py**: The main Python script for topic modeling.
- **arxiv_collective_intelligence.csv**: A CSV file containing the downloaded arXiv abstracts.
- **topic_visualization.html**: An HTML file containing the interactive topic visualization.
- **hierarchy_visualization.html**: An HTML file containing the interactive topic hierarchy visualization.
- **heatmap_visualization.html**: An HTML file containing the interactive topic heatmap visualization.
- **barchart_visualization.html**: An HTML file containing the interactive topic bar chart visualization.
- **topic_scatter_2d_plot_with_lines.html**: An HTML file containing the interactive topic scatter plot visualization.
- **temporal_visualization.html**: An HTML file containing the interactive temporal topic visualization.
- **papers_with_topics.html**: An HTML file containing the table of papers with their assigned topics.

## Acknowledgements

This script utilizes the following open-source libraries:

- BERTopic: [https://maartengr.github.io/BERTopic/](https://maartengr.github.io/BERTopic/)
- Sentence Transformers: [https://www.sks.ai/sentence-transformers/](https://www.sks.ai/sentence-transformers/)
- NLTK: [https://www.nltk.org/](https://www.nltk.org/)
- scikit-learn: [https://scikit-learn.org/](https://scikit-learn.org/)
- matplotlib: [https://matplotlib.org/](https://matplotlib.org/)
- Plotly: [https://plotly.com/](https://plotly.com/)
- UMAP: [https://umap-learn.readthedocs.io/en/latest/](https://umap-learn.readthedocs.io/en/latest/)
- HDBSCAN: [https://hdbscan.readthedocs.io/en/latest/](https://hdbscan.readthedocs.io/en/latest/)
- pandas: [https://pandas.pydata.org/](https://pandas.pydata.org/)
- requests: [https://requests.readthedocs.io/en/latest/](https://requests.readthedocs.io/en/latest/)
- xml.etree.ElementTree: [https://docs.python.org/3/library/xml.etree.elementtree.html](https://docs.python.org/3/library/xml.etree.elementtree.html)

## License

MIT License
