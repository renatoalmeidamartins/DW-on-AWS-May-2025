# Data warehousing on AWS - class links

## Class evaluation
- Go to [aws.training])aws.training)
- Click sign in, log in with the same account you used to access the lab and course materials
- Then go on the top right to My Account, then transcript, click on the Archived section (direct link [https://www.aws.training/Account/Transcript/Archived](https://www.aws.training/Account/Transcript/Archived)
- You should see the class, with a button to evaluate

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
- [Common-table expressions](https://docs.aws.amazon.com/redshift/latest/dg/r_WITH_clause.html)
- [Exploits of a mom on XKCD](https://xkcd.com/327/)
- [PL/pgSQL reference - used inside procedures](https://docs.aws.amazon.com/redshift/latest/dg/c_pl_pgSQL_reference.html)
- [Window functions in Redshift](https://docs.aws.amazon.com/redshift/latest/dg/c_Window_functions.html)
- [Aggregation extensions - rollup, cube, grouping_sets](https://docs.aws.amazon.com/redshift/latest/dg/r_GROUP_BY_aggregation-extensions.html)
- [Redshift Serverless is supported on AWS backup since April 2025](https://aws.amazon.com/about-aws/whats-new/2025/04/aws-backup-amazon-redshift-serverless/)
- [Cross-region snapshots](https://docs.aws.amazon.com/redshift/latest/mgmt/snapshot-crossregioncopy-configure.html)
- [Converting a recovery point (similar to a transaction log backup, taken every 30 minutes to reduce the RPO) to a snapshot](https://docs.aws.amazon.com/redshift/latest/mgmt/serverless-recovery-point-convert.html)
- [VACUUM command](https://docs.aws.amazon.com/redshift/latest/dg/r_VACUUM_command.html)
- [System tables and views reference - STV has "snapshots" of system state, and STL has logging](https://docs.aws.amazon.com/redshift/latest/dg/cm_chap_system-tables.html)
- [Diagnostic queries to identify queries that should be tuned](https://docs.aws.amazon.com/redshift/latest/dg/diagnostic-queries-for-query-tuning.html)
- [Concurrency scaling mode](https://docs.aws.amazon.com/redshift/latest/dg/concurrency-scaling.html)
- [Query monitoring rules](https://docs.aws.amazon.com/redshift/latest/dg/cm-c-wlm-query-monitoring-rules.html)
- [AWS Config conformance pack definitions](https://github.com/awslabs/aws-config-rules/tree/master/aws-config-conformance-packs)
## Day 3 links
- [get iam role by user function](https://docs.aws.amazon.com/redshift/latest/dg/PG_GET_IAM_ROLE_BY_USER.html) - this, along with other functions, allows some introspection into the identity presented by a user
- [Granting permissions to federated users](https://docs.aws.amazon.com/redshift/latest/mgmt/redshift-iam-access-federated-db-roles.html) - pay attention to the session mentioning tags, specifically the RedshiftDbRoles
- [Example of using tag-based roles from IAM to assume different Redshift roles](https://repost.aws/articles/AR1m7iVsf1REyIsPpsU7p0fw/use-iam-tags-to-enable-fine-grained-federated-authentication-to-redshift-serverless)
- [Attribute-based access control through identity center](https://docs.aws.amazon.com/singlesignon/latest/userguide/attributesforaccesscontrol.html)
- [Redshift IAM policy conditions and resources](https://docs.aws.amazon.com/singlesignon/latest/userguide/attributesforaccesscontrol.html)
- [DynamoDB fine-grained access control](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/specifying-conditions.html)
- [Redshift data API conditions and resources](https://docs.aws.amazon.com/service-authorization/latest/reference/list_amazonredshiftdataapi.html)
- [Lake formation permissions and Redshift Spectrum](https://docs.aws.amazon.com/redshift/latest/dg/spectrum-lake-formation.html)
- [Step function activity example](https://docs.aws.amazon.com/step-functions/latest/dg/tutorial-creating-activity-state-machine.html)
- [Activities in step functions](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-activities.html)
- [All types of tasks supported in step functions](https://docs.aws.amazon.com/step-functions/latest/dg/state-task.html#state-task-activity)
- [Example for ETL with dbt - data build tool](https://aws.amazon.com/blogs/big-data/implement-data-warehousing-solution-using-dbt-on-amazon-redshift/)
- [Another example of using dbt](https://aws.amazon.com/blogs/big-data/create-a-modern-data-platform-using-the-data-build-tool-dbt-in-the-aws-cloud/)
- [Eventbridge partner integrations](https://aws.amazon.com/blogs/aws/amazon-eventbridge-event-driven-aws-integration-for-your-saas-applications/)
- [Sagemaker built-in models](https://docs.aws.amazon.com/sagemaker/latest/dg/algos.html)
- [Dynamodb ingestion of streaming data into Redshift](https://aws.amazon.com/blogs/big-data/near-real-time-analytics-using-amazon-redshift-streaming-ingestion-with-amazon-kinesis-data-streams-and-amazon-dynamodb/)
- [Cluster relocation](https://docs.aws.amazon.com/redshift/latest/mgmt/managing-cluster-recovery.html)
- [Cluster resize](https://docs.aws.amazon.com/redshift/latest/mgmt/resizing-cluster.html)
