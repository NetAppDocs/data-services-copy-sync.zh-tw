# Claude instructions for NetApp Copy and Sync documentation

## Repository overview

**Product:** NetApp Copy and Sync

NetApp Copy and Sync is a data movement service that securely copies and synchronizes data between supported source and target systems across on-premises and cloud environments. Customers use it to support migration, ongoing replication, and operational data distribution between file and object storage endpoints. The documentation in this repository focuses on setup, relationship configuration, monitoring, and troubleshooting workflows that help users move data reliably at scale.

## Repository structure

* `_include` - Reusable text blocks referenced in .adoc files in the root. 
* `media` - Images and diagrams that are elements of articles in the root directory. This includes .png and source files. 
* `_whatsnew` - Release notes in .adoc form that are aggregated in the whats-new.adoc file.

## Product-specific context

* **Console agent** - NetApp component that ensures connectivity between on-premises storage systems and NetApp data services in the cloud.
* **Data broker** - The data transfer engine that performs scanning and copy/sync operations for relationships.
* **Data broker group** - A logical grouping of one or more data brokers that executes and scales relationship workloads.
* **Sync relationship** - A configured source-to-target data path with schedule, filters, and transfer behavior settings.
* **Continuous Sync** - A near-real-time synchronization mode for supported cloud-object relationship types.
* **Relationship settings** - Per-relationship controls such as schedule, retries, exclusions, ACL behavior, and notifications.

## Typical user workflows

* **Configure and deploy** - Set up prerequisites, deploy a data broker, and create a sync relationship between supported endpoints.
* **Operate and manage** - Monitor sync status, adjust relationship settings, manage data broker groups, and maintain credentials.
* **Optimize and troubleshoot** - Use reports and error details to improve performance, resolve failures, and refine filters and policies.
