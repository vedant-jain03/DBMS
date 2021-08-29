# What is Database System
Comprise of two things:

### 1.Database

Collection of related data
Two types:
- Structured Data(ex. IRCTC, University): Stored in RDBMS(Relational DBMS) format(tabular formate).
- Not Structured Data(ex. webpage)

### 2.DBMS

System to perform operation (CRUD) on the database.
Example: SQL,MySQL, Oracle etc.

# File System vs DBMS

File System in which data stored in file format like heirarchical but DBMS is much better then file system because:

- Searching: Suppose in file system you want to access 1kb of data so for that you first have to get all data suppose of 1gb and then you will get your 1kb data from that 1gb but in dbms data is stored in server so you can access 1kb of data from their. 
- Attributes: In FS, for getting data from file you first have to get metadata(C:/Drivename) of file but in dbms , data is accessed from server.
- Concurrency: Thier is not protocols for multiple user accessing a file in FS, but thier is a solid protocol in DBMS.
- Redundancy: In fs it is easy to make duplicate files, but in dbms thier is a protocols like primary key, foreign key.
- Security: In FS, user can access any file but in DBMS we can provide role based data or auth. data.

# DBA and its function

DBA(Database Administration) is used for specialized software to store and organize data. The role may include capacity planning, installation, configuration, database design, migration, performance monitoring, security, troubleshooting, as well as backup and data recovery.

Function of DBA:

- Schema deﬁnition.The DBA creates the original database schema by executing a set of data deﬁnition statements in the DDL.
- Storage structure and access-method deﬁnition.
- Schema and physical-organization modiﬁcation.The DBA carries out changes to the schema and physical organization to reﬂect the changing needs of the organization, or to alter the physical organization to improve performance
- Granting of authorization for data access.
- Routine maintenance:
  Examples of the database administrator’s routine maintenance activities are:
  - Periodically backing up the database, either onto tapes or onto remote servers, to prevent loss of data in case of disasters such as ﬂooding.
  - Ensuring that enough free disk space is available for normal operations, and upgrading disk space as required.
  - Monitoring jobs running on the database and ensuring that performance is not degraded by very expensive tasks submitted by some users

# Two-Tier And Three-Tier database architecture

## 1.Two-Tier:

The two-tier architecture is based on the Client-Server model. It consists of Client-Application tier and Database tier. The Client-Application server communicates directly with the Database server. Data or information transfer between the two components is fast due to the absence of a middleware.
Example: Rails, .NET, C++ etc.

## 2.Three-Tier: 

In three-tier, the application logic or process lives in the middle-tier, it is separated from the data and the user interface. Three-tier systems are more scalable, robust and flexible. In addition, they can integrate data from multiple sources. In the three-tier architecture, a middle tier was added between the user system interface client environment and the database management server environment. There are a variety of ways of implementing this middle tier, such as transaction processing monitors, message servers, or application servers.

[Difference](https://www.geeksforgeeks.org/difference-between-two-tier-and-three-tier-database-architecture/)
