# Tamil lyrics corpus Based on previous researchers source Dataset(Dhivya Chinnappa and Praveenraj Dhandapani) below research is conducted and addiing new dataset with additional columns.

 Official release, Sep 02,2023

## Paper:  THE INFLUENCE OF ENGLISH LANGUAGE WORDS IN TAMIL FILM SONG LYRICS CORPUS: A MACHINE LEARNING APPROACH    <br/>
# Sabananthan Vijayarangan: 
Msc DataScience, LJMU UK

# Contact: v.sabananthan@gmail.com,
The file Tamil-lyrics-Updated-POS-IOB-tag.csv provides lyrics and other feature columns like POS and IOB tag label also words extracted based on language (English/ Tamil codemix Suffix / Tamil & other words)

Summary of the Thesis:

The research focuses on the intricate linguistic pattern created by the interweaving of English and Tamil in song lyrics. Utilizing Exploratory Data Analysis (EDA) and models like Conditional Random Field (CRF) & K-Means clustering, the study examines a corpus of Tamil lyrics to reveal complex language relationships. The methodology included preprocessing steps like tokenization, special character removal, POS tagging, and IOB labeling.Lyricists like Kannadasan, Vairamuthu, and Vali have significantly contributed to maintaining the purity of Tamil.A strong positive correlation (0.74) between the count of English and Tamil connect codemix words, indicating a significant blending of languages. T-Test and Z-Test revealed a significant shift in code-mixing trends before and after 1990. CRF focused on identifying English words within Tamil lyrics. Used techniques like L-BFGS or SGD and evaluated with metrics such as precision, recall, F1-score (all 0.99). Consistently high performance across different folds in cross-validation with a mean F1 score of 0.99. The central focus was to develop preprocessing method aimed at identifying English words within Tamil lyrics. This will be achieved using various Python packages, allowing for a computational approach to what is a complex and nuanced linguistic task.  However, despite the python package performance, the method encountered difficulties with certain words that have the same alphabetic representation in both English and Tamil. For example, words such as 'nee' or 'நீ' , 'naan'  or 'நான்' and 'mama' or 'மாமா' are represented identically in the scripts of both languages. This created a challenge for the preprocessing method, as it struggled to distinguish between the Tamil and English instances of these words.
K-means algorithm Extreme values were capped, and features were scaled for clustering. Clustering was performed, focusing on specific features like counts of unique code-mix suffix words, English words, and Tamil words. The silhouette score was used to evaluate the clusters, measuring how well-clustered the objects are. The study provides a systematic analysis of the vibrant linguistic interplay between English and Tamil. It combines computational techniques with humanistic appreciation, reflecting cultural, artistic, and linguistic insights. The utilization of CRF, K-Means, and various statistical tools has enabled a deep understanding of trends, patterns, and anomalies in the code-mixing of English and Tamil words. 

