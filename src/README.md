# AWS Data Pipeline

This repository contains the implementation for a scalable data processing pipeline. The system is designed to manage data transitions between various storage zones on AWS.

## Configuration

The config.cfg file in the src folder contains the following parameters:

```
[AWS]  
KEY=<AWS-KEY>
SECRET=<AWS-SECRET-KEY>
  
[BUCKET]  
LANDING_ZONE=<Landing zone bucket name>
WORKING_ZONE=<working zone bucket name>  
PROCESSED_ZONE=<processed zone bucket name>  
  
[FILES]  
NAME=author.csv,book.csv,reviews.csv,user.csv
```

## Maintainer

Pardhu Mattupalli
AI Engineer
Email: pmattupalli26@gmail.com
LinkedIn: https://www.linkedin.com/in/pardhu--mattupalli

### About the Developer

Pardhu Mattupalli is an AI/ML Engineer with over 3 years of experience designing, developing, and deploying scalable Artificial Intelligence and Machine Learning solutions. He is proficient in Python, PySpark, SQL, and AWS, with a focus on building production-ready AI systems and real-time predictive analytics pipelines. His expertise includes implementing MLOps practices, model monitoring, and ensuring regulatory compliance within complex data environments.