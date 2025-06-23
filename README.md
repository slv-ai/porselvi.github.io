# Machine Learning Engineer @ OMDENA

### PROJECTS
## Real time fraud detection

![Fraud Detection Architecture](./assets/AWS-stream-pipeline.png)

[Project Link](https://github.com/slv-ai/Real-Time-Fraud-Detection)

Designed and implemented a real-time fraud detection pipeline leveraging AWS Kinesis and Lambda to deliver scalable, low-latency predictions. Incoming transaction data streams into Kinesis Data Streams, triggering Lambda functions that run fraud detection models and generate predictions instantly. The predicted results are then sent to a separate Kinesis stream for downstream processing or alerting.

Infrastructure provisioning and deployment are automated using Terraform, ensuring reproducible and scalable environments. CI/CD pipelines built with GitHub Actions streamline code integration, testing, and deployment, promoting rapid and reliable updates.

Future plans include adding unit testing to improve code reliability and implementing model monitoring to track prediction accuracy and drift, ensuring ongoing model effectiveness and compliance

## Recommender systems

[Project Link](https://github.com/slv-ai/Recommender-system)

Built a scalable movie recommender system using PySpark ALS in Amazon SageMaker.
Trained models on MovieLens data stored in S3 and evaluated performance using RMSE.
Saved trained models to S3 and wrote personalized predictions to DynamoDB.
Designed the pipeline to support future integration with Step Functions for automated retraining.
