[Site Home](../../../../index) | [SQL PASS Summit Home](../../../index) | [Pass Summit 2018 Home](../../index) | [November 7th Sessions](./index)

Legend:

- ? = Question needing answering

- T = Tool to examine

- I = Information for follow up

- ! = ToDo at work

- \* Exciting item

## SQL Server Database Admisitration for the Non-DBA

### Speaker: Denny Cherry

### Abstract
> *Are you a developer or a systems admin and you've just been handed a SQL Server database and you've got no idea what to do with it?  I've got some of the answers for you in this session. During this session, we will cover a variety of topics including backup and restore, recovery models, database maintenance, compression, data corruption, database compatibility levels, and indexing.*
>
> *While this session won't teach you everything you need to know, it will give you some insights into the SQL Server database engine and give you the ability to better know what to look for.*

\- Keep at least two full backups based on your SLA. For example:
If you do daily backups you should have two days of backups, likewise weekly backups should have two weeks of backups, and so on...

\- The starting size of your backups is determined by the size of the largest object being backed up

\- SQL Server has no option to turn off logging, it does however allow you to determine the level of logging being captured (Yay repudiation)
* ? Does Aurora allow logging to be disabled?

\- Line of business databases should be in Full Recovery

\- Differential Backup and Restore: The backup is the difference between initiation and the last full backup. Likewise, the restore is the difference between initiation and the last full restore

? What is page level restore?

\- Database Maintenence: Index Rebuild or Index Defrag
* ? I thought there was something about Index Restore which needed to also have an Index Defrag

T Ola SQL: Scripts to create jobs which will do the Database Maintenence

? What kind of maintenence does Aurora support? Does it allow us to perform our own maintenence?

\- Index stat updates in the background

\- Whenver we make an index, we store a copy of the indexed data. So every index on a singular field, or group of fields, will create a copy on the database.
* This is by intention because you are trading disk space for speed of data access.
* ? Again does Aurora do this?

\- Non clustered indexies are 99% of the problems which need to be fixed on databases

\- ? If you filter on a column, create a key. If you If you are selecting on a colum only it's an include?

\- Filtering on an index? When an application is always looking for data based on a filter, and the column being is a literal, you can add a 'WHERE' clause to the key