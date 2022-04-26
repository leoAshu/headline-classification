<p align="center">
    <image src="images/cover.jpg">
</p>

# Headline Classification

This is a Machine Learning project related to Natural Language Processing(NLP). 
    
The objective of the project is to analyse a news article's headline and classify it as one of the following two classes: `clickbait`, `not clickbait`.

## Data:
- Source Paper: [Stop Clickbait: Detecting and Preventing Clickbaits in Online News Media](https://github.com/bhargaviparanjape/clickbait)
- 2 CSV files, one for each class label compressed separately named:
    - clickbait_data.gz
    - non_clickbait_data.gz
- The final dataset is constructed by combining both the files randomly followed by cleaning and preprocessing as necessary.
- There is only one column in the dataset initially:
    - `headline` &nbsp;&nbsp;- contains the headline statements
    - `clickbait` - this column is manually added before constructing the final dataset and represents if a particular headline is clickbait(1) or not(0).
    
