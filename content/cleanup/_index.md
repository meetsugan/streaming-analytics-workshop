---
title: "Cleanup"
chapter: true
weight: 80
---

# Congratulations!

You have not only built a reliable, scalable, and highly available streaming application based on Apache Flink and Kinesis Data Analytics for Java Applications. You also scaled the different components while ingesting and analyzing up to 25k events per second in near-real time. In large parts, this scenario was enabled by using managed services, so you didn’t need to spend time on provisioning and configuring the underlying infrastructure.


#### Be frugal!

If you are running the workshop on your own and have completed all steps, make sure you delete the resources you have created to avoid causing unnecessary costs.

First, delete the Kinesis data analytics application. Once the application has been deleted, also delete the Kinesis data stream, the CloudWatch dashboard, and the CloudFromation template (you need to manually delete or empty the S3 bucket created by the template).
