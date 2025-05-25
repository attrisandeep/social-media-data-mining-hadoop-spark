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

  ## Power BI dashboard
  ![image](https://github.com/user-attachments/assets/b895ad7c-59c9-4bc2-ba65-bcd0b9cdc027)


## 📁 Project Structure

The project is organized as follows:

```social-media-data-mining/
├── .gitignore
├── LICENSE
├── Notebook.ipynb                         # Combined notebook for preprocessing, analysis
├── Outputdataset.csv                      # Final output with user, total tweets, sentiment
├── powerBI.pbix                           # Power BI dashboard file
├── README.md                              # Project overview and documentation
├── requirements.txt                       # Python dependencies for PySpark and NLP

