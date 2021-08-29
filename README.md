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









