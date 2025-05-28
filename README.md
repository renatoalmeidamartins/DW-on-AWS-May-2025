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
