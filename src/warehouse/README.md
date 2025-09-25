# Warehouse Configuration

The warehouse_config.cfg file in the warehouse folder contains:

```ini
[AWS]  
KEY=<AWS-KEY>
SECRET=<AWS-SECRET-KEY>
  
[CLUSTER]  
HOST='<Redshift Cluster Endpoint>'  
DB_NAME='<db-name>'  
DB_USER='<db-user-name>'  
DB_PASSWORD='<db-password>'  
DB_PORT=<db-port, default 5439>  
  
[IAM_ROLE]  
ARN=<Redshift ARN role>
  
[STAGING]  
SCHEMA=<Warehouse-staging-schema>  
  
[WAREHOUSE]  
SCHEMA=<Warehouse-schema>  
  
[BUCKET]  
LANDING_ZONE=<landing-zone-bucket>  
WORKING_ZONE=<working-zone-bucket>
PROCESSED_ZONE=<processed-zone-bucket>
```

## Maintainer

Pardhu Mattupalli
AI Engineer
Email: pmattupalli26@gmail.com
LinkedIn: https://www.linkedin.com/in/pardhu--mattupalli?utm_source=share_via&utm_content=profile&utm_medium=member_ios

## About the Developer

Pardhu Mattupalli is an AI Engineer with over 3 years of experience designing, developing, and deploying scalable Artificial Intelligence and Machine Learning solutions across Healthcare and Financial domains. He is proficient in building production-ready AI systems, intelligent automation solutions, and real-time predictive analytics pipelines using Python, SQL, and AWS. His expertise includes implementing MLOps practices, model monitoring, and ensuring regulatory compliance within agile environments.