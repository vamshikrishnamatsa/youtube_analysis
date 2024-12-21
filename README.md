YouTube US Videos Dataset Analysis

Overview

This project involves exploratory data analysis (EDA) of a dataset containing information about trending YouTube videos in the US. The analysis uses Python and various libraries to generate insights and visualizations. Below is a description of the process, key components, and visualizations created.


Dependencies

The following Python libraries are required to run the analysis:

pandas

numpy

matplotlib

seaborn

wordcloud

collections

datetime

json

Install these libraries using pip if not already installed:

pip install pandas numpy matplotlib seaborn wordcloud

Steps in Analysis

1. Data Cleaning

Missing values in the description column are filled with an empty string ("").

2. Summary Statistics

Descriptive statistics of the dataset are generated using the df.describe() method.

3. Capitalized Words in Titles

A function checks if titles contain fully capitalized words.

A pie chart visualizes the proportion of titles with and without capitalized words.

4. Title Length Analysis

The length of video titles is calculated.

A histogram shows the distribution of title lengths.

5. Relationship Between Views and Title Length

A scatter plot illustrates the relationship between the number of views and the length of video titles.

6. Correlation Analysis

Correlations between numerical and boolean features are calculated.

A heatmap displays the correlation matrix with labeled axes for readability.

7. Word Cloud

A word cloud is generated from the words in video titles, providing a visual representation of frequently used words.

Visualizations

Pie Chart: Titles Containing Capitalized Words

Displays the proportion of video titles with and without fully capitalized words.

Histogram: Title Length Distribution

Shows the distribution of title lengths in the dataset.

Scatter Plot: Views vs. Title Length

Explores the relationship between video popularity (views) and the length of their titles.

Correlation Heatmap

Illustrates correlations between numerical and boolean features in the dataset.

Word Cloud

Visualizes the most common words in video titles.

Customizations

Plot Aesthetics

Colors, fonts, and gridlines are styled for consistency using matplotlib and seaborn configurations.

Custom color palettes (PLOT_COLORS) are defined to maintain visual appeal.

Code Modularization

Reusable functions like contains_capitalized_word improve code readability and modularity.

How to Run

Ensure Python is installed on your system.

Install the required libraries listed in the "Dependencies" section.

Place USvideos.csv in the same directory as the script.

Run the Python script using:

python script_name.py

View the generated visualizations and outputs.

Future Work

Analyze more features, such as likes, dislikes, or comment_count.

Incorporate time-based trends (e.g., publishing day or time).

Enhance interactivity using tools like Streamlit or Dash.

Acknowledgments

Dataset Source: Publicly available YouTube trending videos dataset.

Libraries and Tools: pandas, numpy, matplotlib, seaborn, and wordcloud.

