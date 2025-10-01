
# kitab-postgres-id
Kitab postgres bahasa indonesia
Author: @gibrain, @100%Linux

## Engineering Wisdom
* Data Valuation vs Backup 
* Don't start production without backup
* Mirror is not backup (Mirror vs BaseBackup)
* Design Principle: Keep it simple. STUPID !.
* Centralized vs Distributed
* TERABYTE Mirroring Best Practices
* In Memory Processing. DuckDB. 
* Hardware Design (SSD, Cloud, Isolation B/P)
* Data Type Vs Data Volume

## Server Architecture 
* Connection Process ( Thread Vs Process )
* Background process: Postmaster, Postgres, Autovacuum, Stats collector, Background writer, Wal Writer,  Logger Process, Checkpointer process, Replication Process
* Memory: Shared Buffers, Work memory, Wal Buffers, Maintenance Work Memory, etc
* Logical Structure: Cluster, Database, Schema (tables, indexes, view, functions, rules, tablespaces, etc), users
* Physical Files: Base, Global pg_xlog, pg_log, pg_xact, folders, etc

## Installation & Configuration
* Source Code Exploration 
* Compiling
* Cluster Initialization & Running
* Server Configuration (Parameter, File Locations, Connections & Authentication, Resource Consumption, Wal settings, etc) 

## Database Backup Rules
* Do not start production without a backup
* 3-2-1 Backup Rules.
* Retention Policy
* Backup Frequency
* Backup Validation

## Administration 
* Managing Databases
* Routine Database Maintenance Tasks
* Backup and Restore
* High Availability, Load Balancing, and Replication
* Monitoring Database Activity
* Reliability and the Write-Ahead Log
* Logical Replication
* Tools : Linux shell scripting for task automations, psql, pg_* tools: pg_createcluster, pg_basebackup, pg_dump, pg_backupcluster, pg_restore, pg_config, etc


## Node Architectures
* Classics: ( Master, Archive ) -> Standby 1, Standby 2, …
* Advance Architecture: 
- Distributed based on problem domain
- Distributed based on geography location
- Combination Of Two

## Performance Monitoring and Tuning
* Monitoring Slow Queries
* SQL Tuning
* Table Partitioning
* Operating System Best Practices
* Parameter Tuning
* Extensions
* Benchmarking
* Monitoring Best Practices 

## Database Backups and Restores
* Logical or SQL Dump Backups
* Restoring SQL Dumps
* Physical Backups - Offline
* Restoring Offline Backups
* Physical Backups - Online
* Write Ahead Log(WAL) Archiving
* Recovery configuration
* Point in Time Recovery using WAL Archives
 
## High Availability
* Transaction Log Archiving 
* Streaming Replication
* Connection Pooling and HA setup using pgpool-II
* Installation
* Configuration
* pgpool Setup
* HA Setup
 
## Database Security
* Users and Groups
* Access Control
* Row Level Security 
* Host Based Access Control
* Data Encryption using pgcrypto
 
## Database Upgrades
* PostgreSQL Versioning
* Plan for Upgrade
* Upgrade using pg_dump
* Upgrade using pg_upgrade
* In Place or Not-in Place Upgrade
* Post Upgrade Tasks

## Postgres & LLM's
* Query Design Automation
* Use LLM effectively
* Visualization Automation

## Integrasi DuckDB
* in memory processing
* big data
 
## Data Science With Postgres
* (buku terpisah)
  
## Case studies 
* ERP Complexities
* Heterogeneous Business Problems
* Heterogeneous Software
* Heterogeneous 3rd Party Vendor 



## Epilogue
* Management Wisdom
* Engineering Wisdom 

