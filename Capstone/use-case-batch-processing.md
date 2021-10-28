# Batch Processing

Most analytics applications require frequent batch processing, which allows them to process data in batches at
varying interval. For example, processing daily sales aggregations by individual store and then writing that data to the
data warehouse on a nightly basis can enable business intelligence (BI) reporting queries to run faster. Batch systems
must be built to scale for all sizes of data and scale seamlessly to the size of the dataset being processed at various
job runs.

It is important for the batch processing system to be able to support disparate source and target systems, process
various data formats, seamlessly scale out to process peak data volumes, ability to orchestrate jobs using workflow,
provide a simple way to monitor the jobs and most importantly offer an ease of use development framework that
accelerates job development. Business requirements might dictate that batch data processing jobs be bound by an
SLA, or have certain budget thresholds. Use these requirements to determine the characteristics of the batch
processing architecture.

On AWS, analytic services, such as Amazon EMR, Amazon Redshift, Lake Formation Blueprints, and AWS
Glue enable you to run batch data processing jobs at scale for all batch data processing use cases and for various
personas, such as data engineer, data analyst, and data scientists. While there are some overlapping capabilities
between these services, knowing the core competencies and when to use which service or services enable you to
accomplish your objectives in the most effective way.

# Workshops to Help You Get Started 

https://analytics-101-workshop.by.awsome.builders/01-introduction/02-labs-overview/


# Additional Resources

AWS Samples: https://github.com/aws-samples

AWS Workshops: https://workshops.aws/

AWS QuickStarts: https://aws.amazon.com/quickstart

AWS QuickStarts Repos: https://github.com/orgs/aws-quickstart/repositories

AWS CF Templates: https://github.com/awslabs/aws-cloudformation-templates/tree/master/aws/solutions

AWS Architecture Center: https://aws.amazon.com/architecture/





