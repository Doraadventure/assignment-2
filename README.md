# Column family

![cassandra](https://user-images.githubusercontent.com/122898714/227750508-b3241687-6c73-4749-9a80-3cd8e73f4454.png)

Database used: cassandra

• Cassandra is one of the popular column-family databases

`Created a Application of banking System `

There are some kind of safe for which Cassandra could be appropriate.

Those kinds of safe:

For transactional information, safety means a consistent view of the data regardless of access path. Eventual           consistency is no good when we're dealing with bank balances. Or the other hand, Cassandra would be fine for           logging the transaction details in an audit trail.

# Requreiments
- Java >= 1.8 (OpenJDK and Oracle JVMS have been tested)

  [java jdk1.8](https://www.oracle.com/webapps/redirect/signon?nexturl=https://download.oracle.com/otn/java/jdk/8u40-b26/jdk-8u40-windows-x64.exe)

* Python 3.6+ (for cqlsh)

  [python](https://www.python.org/ftp/python/2.7/python-2.7.amd64.msi)


# Getting Started

Database on Casandra and that includes the entity like

 > customer,branch,account,transaction
 
 attributes for the corresponding entity

 - [x] CUSTOMERS Custid,Name,City,Occupation,Dob
 - [x] BRANCH  Bid,bcity 
 - [x] ACCOUNT  Acnum,custid,bid,opbalance,atype, acstatus 
 - [x] TANSACTION DETAIL tnum,acnum,,transtype,transmedium




