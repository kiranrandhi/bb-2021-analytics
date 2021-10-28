# Data Mesh

Organizations of all sizes have recognized that data is one of the key enablers to increase and sustain innovation,
and drive value for their customers and business units. They are modernizing traditional data platforms with cloud-
native technologies that are highly scalable, feature-rich, and cost-effective. As you look to make business decisions
driven by data, you can be agile and productive by adopting a mindset that delivers data products from specialized
teams, rather than through a centralized data management platform that provides generalized analytics.
A centralized model simplifies staffing and training by centralizing data and technical expertise in a single place. This
reduces technical debt since you are managing a single data platform, which reduces operational costs. Data platform
groups, often part of central IT, are divided into teams based on the technical functions they support. For instance,
one team might own the ingestion technologies used to collect data from numerous data sources managed by other
teams and lines of business (LOBs). A different team might own the data pipelines, the writing and debugging extract,
transform, and load (ETL) code, and orchestrating job runs, while validating and fixing data quality issues and
ensuring that data processing meets business SLAs. However, managing data through a central data platform can
create scaling, ownership, and accountability challenges. Central teams might not understand the specific needs of a
data domain, due to data types and storage, security, data catalog requirements, or the specific technologies needed
for data processing.

You can often reduce these challenges by giving ownership and autonomy to the team who owns the data. This
allows them to focus on building data products, rather than being limited to a common central data platform. For
example, make product teams responsible for ensuring that the product inventory is updated regularly with new
products and changes to existing ones. They’re the domain experts of the product inventory datasets, and if a
discrepancy occurs, they’re the ones who know how to fix it. Therefore, they’re best able to implement and operate a
technical solution to ingest, process, and produce the product inventory dataset. They own everything leading up to
the data being consumed: they choose the technology stack, operate in the mindset of data as a product, enforce
security and auditing, and provide a mechanism to expose the data to the organization in an easy-to-consume way.
This reduces overall friction for information flow in the organization, where the producer is responsible for the datasets
they produce and is accountable to the consumer based on the advertised SLAs.

This data-as-a-product paradigm is similar to the operating model that Amazon uses for building services. Service
teams build their services, expose APIs with advertised SLAs, operate their services, and own the end-to-end
customer experience. This is distinct from the model where one team builds the software, and a different team
operates it. The end-to-end ownership model has enabled us to implement faster, with higher efficiency, and to
quickly scale to meet customers’ use cases. We aren’t limited by centralized teams and their ability to scale to meet
the demands of the business. Each service we build relies on other services that provide the building blocks. At AWS,
we have been talking about the data-driven organization model for years. This model is similar to those used by some
of our customers and has been described by Zhamak Dehghani of Thoughtworks, who coined the term data mesh.

# Blog Post to Help You Get Started 

https://aws.amazon.com/blogs/big-data/design-a-data-mesh-architecture-using-aws-lake-formation-and-aws-glue/


# Dataset That Might Be Useful

https://github.com/awslabs/amazon-redshift-utils/tree/master/src/CloudDataWarehouseBenchmark/Cloud-DWB-Derived-from-TPCDS

# Additional Resources

AWS Samples: https://github.com/aws-samples

AWS Workshops: https://workshops.aws/

AWS QuickStarts: https://aws.amazon.com/quickstart
AWS QuickStarts Repos: https://github.com/orgs/aws-quickstart/repositories

AWS CF Templates: https://github.com/awslabs/aws-cloudformation-templates/tree/master/aws/solutions

AWS Architecture Center: https://aws.amazon.com/architecture/





