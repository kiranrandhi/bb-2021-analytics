# Streaming Ingest and Stream Processing

Processing real-time streaming data requires throughput scalability, reliability, high availability, and low latency to
support a variety of applications and workloads. Some examples include: streaming ETL, real-time analytics, fraud detection,
API microservices integration, fraud detection activity tracking, real-time inventory and recommendations,
and click-stream, log file, and IoT device analysis.

Streaming data architectures are built on five core constructs: data sources, stream ingestion, stream storage, stream
processing, and destinations. Each of these components can be created and launched using AWS Managed Services
and deployed and managed as a purpose-built solution on Amazon EC2, Amazon Elastic Container Service (Amazon
ECS), or Amazon Elastic Kubernetes Service (Amazon EKS).

Examples of each of these components include:

Data sources: Application and click stream logs, mobile apps, existing transactional relational and NoSQL databases,
IoT sensors, and metering devices.
Stream ingestion and producers: Both open source and proprietary toolkits, libraries, and SDKs for Kinesis Data
Streams and Apache Kafka to create custom stream producers, AWS service integrations such as AWS IoT Core,
CloudWatch Logs and Events, Amazon Kinesis Data Firehose, AWS Data Migration Service (DMS), and third-party
integrations

Stream storage: Kinesis Data Streams, Amazon Managed Streaming for Apache Kafka (Amazon MSK), and Apache
Kafka

Stream processing and consumers: Amazon EMR (Spark Structured Streaming, Apache Flink), AWS Glue ETL
Streaming, Kinesis Data Analytics for Apache Flink, third-party integrations, and build-your-own custom applications
using AWS and open source community SDKs and libraries.

Downstream destinations: Databases, data warehouses, purpose-built systems such as OpenSearch services, data
lakes, and various third-party integrations.

With these five components in mind, next let’s consider the characteristics as you design your stream processing
pipeline for real-time ingestion and nearly continuous stream processing.

# Workshops to Help You Get Started 

https://github.com/aws-samples/streaming-analytics-workshop
https://github.com/aws-samples/amazon-kinesis-analytics-streaming-etl
https://streaming-analytics.workshop.aws/beam-on-kda/


# Additional Resources

AWS Samples: https://github.com/aws-samples

AWS Workshops: https://workshops.aws/

AWS QuickStarts: https://aws.amazon.com/quickstart

AWS QuickStarts Repos: https://github.com/orgs/aws-quickstart/repositories

AWS CF Templates: https://github.com/awslabs/aws-cloudformation-templates/tree/master/aws/solutions

AWS Architecture Center: https://aws.amazon.com/architecture/





