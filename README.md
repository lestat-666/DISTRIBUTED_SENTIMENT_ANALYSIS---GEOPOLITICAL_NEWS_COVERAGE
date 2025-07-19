# DISTRIBUTED-SENTIMENT-ANALYSIS-GEOPOLITICAL-NEWS-COVERAGE
## Large-scale sentiment analysis of YouTube video transcripts, focusing on geopolitical content analysis across multiple news channels.

### Project Overview
This project implements a scalable distributed computing pipeline for extracting, transcribing, and analyzing sentiment from YouTube news videos. The system processes geopolitical content across multiple international news channels (BBC, CNN, SABC News, Al Jazeera English) to identify editorial patterns and correlate sentiment shifts with real-world events.

### Key Findings 
- **Performance Optimization**: Achieved 66% reduction in processing time (96s → 32.56s) through distributed computing with Apache Spark
- **High Transcription Accuracy**: 88.74% accuracy for single-reporter news videos using Google Cloud Speech-to-Text API
- **Editorial Variations**: Identified significant sentiment differences between BBC and Al Jazeera coverage of Israel-Iran conflict
- **Event Correlation**: Successfully correlated sentiment drops with real-time events (Gaza aid incident: -0.09, Iranian attacks: -0.14)
- **Coverage Patterns**: Conflict coverage consistently 0.1-0.2 points more negative than general news sentiment

### Technical Stack
Distributed Computing: Apache Spark, PySpark
Cloud Platform: Google Cloud Platform (GCP)
APIs: YouTube Data API v3, Google Cloud Speech-to-Text API
NLP Libraries: TextBlob, NLTK
Data Processing: Python, pandas
Visualization: matplotlib, seaborn
Audio Processing: pytube, pydub
