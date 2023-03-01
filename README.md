# kafka-stock-market-project-data-engineering

- This project fetch real-time stock market data using Python and stores it on S3 bucket and query via AWS Athena.
- The data is processed with Apache Kafka on AWS EC2 and then stored in s3 bucket.

# Key Features
- Data Engineering: Implement a data pipeline to process real-time data streams.
- Tech Stack: Utilize Python, AWS EC2, Apache Kafka, AWS Glue Crawler, AWS Data Catalog, AWS Athena.
- Future Enhancements: Room for adding data visualization, machine learning predictions, real-time alerts, and scalability.

# Architecture
![kafkaArchitecture](https://drive.google.com/uc?export=view&id=1v3cUGDaArAryU9Uc-etFdDNX8EHJdsS8)

# Project Implementation
1. Launch EC2 instance and install Apache Kafka.
2. Create a Python script to retrieve real-time stock market data.
3. Use Apache Kafka to produce the data to a topic.
4. Create a new Python script to consume topic data and store it in AWS S3 bucket.
5. Create Crawler and Query in AWS Athena.

# Execution
1. Launch an EC2 instance as well as Apache Kafka.
2. Start Apache Kafka producer to produce data to a topic.
3. Run the Python script to send stock market data in real-time.
4. Start Python consumer script to consume and store data in s3 bucket.

# Future Enhancements
- Adding a data visualization layer using tools such as Matplotlib or Seaborn to visualize the stock market data stored in AWS S3.
- Adding a machine learning model to predict stock prices based on the stored data.
- Scaling the pipeline to handle larger amounts of data by adding more EC2 instances.

## **Technologies used**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## **Tools used**
![VSCode](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
## Contact

- linkedin - https://www.linkedin.com/in/mahima-jain-41b540191/
- gmail - mahimaj25@gmail.com
