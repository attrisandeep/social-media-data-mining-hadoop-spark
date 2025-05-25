# social-media-data-mining-hadoop-spark
Sentiment analysis and user engagement mining on 1.6M tweets using Hadoop, Spark, and Power BI.
# social-media-data-mining-hadoop-spark

Sentiment analysis and user engagement mining on 1.6M tweets using Hadoop, Spark, and Power BI.

##  Features

- Hadoop HDFS for distributed data storage  
- Apache Spark for fast data processing  
- Sentiment analysis using NLP techniques (VADER)  
- User engagement metrics (queries per user)  
- Interactive Power BI dashboard for data visualization  

## Dataset

**Source:** [Kaggle - Sentiment140 Dataset](https://www.kaggle.com/kazanova/sentiment140)  
**Records:** 1.6 million labeled tweets  
**Fields:** polarity, tweet text, user ID, date, query  

## Technologies Used

- Apache Hadoop  
- Apache Spark (PySpark)  
- Python (VADER, Pandas)  
- Power BI  
- Jupyter Notebook  

## 📁 Project Structure

The project is organized as follows:

```social-media-data-mining/
│
├── data/
│ ├── raw/ # Original dataset files (e.g., sentiment140.csv)
│ ├── processed/ # Cleaned or transformed data ready for analysis
│
├── notebooks/
│ ├── data_preprocessing.ipynb
│ ├── sentiment_analysis.ipynb
│ ├── user_engagement_analysis.ipynb
│
├── scripts/
│ ├── hadoop_setup.sh
│ ├── spark_job.py
│ ├── data_cleaning.py
│
├── powerbi/
│ ├── dashboard.pbix
│ ├── data_exports/
│
├── requirements.txt # Python dependencies
├── README.md ```
