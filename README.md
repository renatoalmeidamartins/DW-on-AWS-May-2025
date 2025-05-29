# Data warehousing on AWS - class links

## Access to the class and course materials

- [Class meeting link](https://awsvirtual.webex.com/awsvirtual/j.php?MTID=m56c471205ec47002f0182c982b6e9210)
- [Access to labs and course materials](https://us-east-1.student.classrooms.aws.training/class/ilt%23d7oZD4UhZeVv187TRRKiTr)

## Supporting materials
- [List of all instructor-led training, along with their versions](https://releases.awstc.com/)
- [List of classroom-training, by role](https://aws.amazon.com/training/classroom/?nc2=sb_tr_ct)
- [Skills builder - Site with lots of materials from AWS, courses, videos, learning paths. Most with free access](https://skillbuilder.aws/)

## Day 1 links
- [Hitchhiker's guide to the data lake](https://azure.github.io/Storage/docs/analytics/hitchhikers-guide-to-the-datalake/)
- [Medallion architecture](https://www.databricks.com/glossary/medallion-architecture)
- [Database normalization](en.wikipedia.org/wiki/Database_normalization)
- [Star schema](https://en.wikipedia.org/wiki/Star_schema)
- [The data ware toolkit book](https://www.amazon.com/Data-Warehouse-Toolkit-Definitive-Dimensional/)
- [Data management at scale book](https://www.amazon.com/Data-Management-Scale-Modern-Architecture/)
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/?wa-lens-whitepapers.sort-by=item.additionalFields.sortDate&wa-lens-whitepapers.sort-order=desc&wa-guidance-whitepapers.sort-by=item.additionalFields.sortDate&wa-guidance-whitepapers.sort-order=desc)
- [Nodes and slices size table](https://docs.aws.amazon.com/redshift/latest/mgmt/working-with-clusters.html)
- [Serverless Reservations, a way to save on costs for Redshift serverless](https://aws.amazon.com/about-aws/whats-new/2025/04/serverless-reservations-discounted-pricing-option-amazon-redshift-serverless/)
- [CREATE TABLE statement](https://docs.aws.amazon.com/en_us/redshift/latest/dg/r_CREATE_TABLE_NEW.html) - pay attention to the supported types on sortkey (SUPER is not supported)
- [Primary and foreign key constraints are informationaly only](https://docs.aws.amazon.com/redshift/latest/dg/c_best-practices-defining-constraints.html)
- [SUPER data type supports up to 16 MBs of data](https://docs.aws.amazon.com/redshift/latest/dg/r_SUPER_type.html)
- [Analyze compression command](https://docs.aws.amazon.com/redshift/latest/dg/t_Verifying_data_compression.html) - this can indicate the most optimal encoding for the current data, and estimate space savings
- [System-defined roles](https://docs.aws.amazon.com/redshift/latest/dg/r_roles-default.html)
- [Auto table optimization](https://docs.aws.amazon.com/redshift/latest/dg/t_Creating_tables.html)
- [Feature support across PostgreSQL and Redshift](https://docs.aws.amazon.com/redshift/latest/dg/c_redshift-and-postgres-sql.html)
- [Step-by-step database migrations using DMS](https://docs.aws.amazon.com/dms/latest/sbs/dms-sbs-welcome.html)
- [S3 directory buckets](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-express-differences.html)
- [Jobs with the COPY command](https://docs.aws.amazon.com/redshift/latest/dg/r_COPY-JOB.html) - detects changes on the S3 bucket
- [COPY command](https://docs.aws.amazon.com/redshift/latest/dg/r_COPY.html) - client side encryption is not supported anymore
- [Redshift Spectrum](https://docs.aws.amazon.com/en_us/redshift/latest/dg/c-getting-started-using-spectrum.html)
- [Kinesis Firehose supporting zero-seconds buffering](https://aws.amazon.com/about-aws/whats-new/2023/12/amazon-kinesis-data-firehose-zero-buffering/)
- [Redshift materialized views](https://docs.aws.amazon.com/redshift/latest/dg/materialized-view-overview.html)
- [Setting up zero-ETL cross-account](https://repost.aws/articles/AR5c_j088bT76j2v5hAWaljw/set-up-cross-account-zero-etl-integration-in-the-same-region)

## Day 2 links
- [Row level security end-to-end example](https://docs.aws.amazon.com/redshift/latest/dg/t_rls-example.html)
- [Dynamic data masking](https://docs.aws.amazon.com/redshift/latest/dg/r_ddm-procedures.html)
- [Step by step to load data from EMR into Redshift](https://docs.aws.amazon.com/redshift/latest/dg/loading-data-from-emr.html)
- [Step by step to load data from a host - SSH-based](https://docs.aws.amazon.com/redshift/latest/dg/loading-data-from-remote-hosts.html)
- [Get temporary credentials - must have the Redshift:GetClusterCredentials right](https://docs.aws.amazon.com/redshift/latest/mgmt/generating-iam-credentials-steps.html)
- [Connecting from the Query editor to the glue data catalog](https://docs.aws.amazon.com/redshift/latest/mgmt/query-editor-v2-glue.html)
- [Materialized views in Redshift](https://docs.aws.amazon.com/redshift/latest/dg/materialized-view-overview.html)
- [Auto refresh for materialized views](https://docs.aws.amazon.com/redshift/latest/dg/materialized-view-refresh.html)
- [Explain command operators](https://docs.aws.amazon.com/redshift/latest/dg/c-the-query-plan.html)
- [Automatic materialized views](https://docs.aws.amazon.com/redshift/latest/dg/materialized-view-auto-mv.html)
- [Advanced design patterns for DynamoDB](https://www.youtube.com/watch?v=xfxBhvGpoa0) - no direct relation to the class, just to highlight the pivotal shift we have when we go non-relational. Start with the access patterns, and build the table based on them
