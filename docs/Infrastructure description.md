# Infrastructure description

- **Frontend** is hosted on Amazon S3
- **Backend** is hosted on Amazon Elastic Beanstalk
- **Postgres Database** is hosted on Amazon RDS

## Infrastructure Diagram

![AWS_Infrastructure](screenshots/AWS_Infrastructure.png)

## Screenshots

### RDS

![RDS](screenshots/RDS.png)

### Elastic Beanstalk

![EB](screenshots/EB.png)

### S3

The production version should be accessible via this link
http://udagrambucket2023.s3-website-us-east-1.amazonaws.com

![S3_Bucket](screenshots/S3_Bucket.png)

### CircleCI Pipeline

![CircleCI_Env](screenshots/CircleCI_Env.png)
![CircleCI_Pipeline](screenshots/CircleCI_Pipeline.png)
![CircleCI_Build](screenshots/CircleCI_Build.png)
![CircleCI_Deploy](screenshots/CircleCI_Deploy.png)
