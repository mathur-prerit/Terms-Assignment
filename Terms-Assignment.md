#### 10 popular commands

1. mkdir- This command is used to create a new directory.
2. cd - It is used to move across the path. It can be used with ".",".." and "~".
3. pwd - It show the users' current working directory.
4. ls - To list all the files and directories in current directory. We can write it as "ls -al" for listing all files including the hidden ones.
5. touch - To create a new file.
6. rm - To remove the file from the directory. "rm -rf" to remove folders and files recursively.
7. mv -To move file or folder across the path. It could also be used to rename the file or folder.
8. cat- Display the content of the file.
9. history-list all the history of commands user entered in the system.
10. man-To show details for the entered command.

#### 10 Network commands

1. ping - To check the network connection with the host.
2. ipconfig - To help knowlegde about user local IP and MAC address of its various adapater in the device.
3. curl ipconfig.me - To know your public ip address.
4. Hostname -I - To know the ip address of public server.
5. w - To know summary of active users and other details like login time.
6. netstat - To know our connection info
7. host google.com- To know the host name and info of a website.
8. iwconfig - To know and stats about your wifi adapter.
9. wget google.com - For downloading the data for the given address.
10. nslookup google.com - To look for ip address for the given hostname.

#### 10 OS commands

1. grep - To search string in file or any result. And we can add or pipe it with any other command.
2. mount - To mount any kind of partition or drive on the system.
3. df - To view space available, filesystem stats.
4. free - TO know about RAM stats like free memory usage.
5. kill - It is paired process id and used for killing a process.
6. su - To switch user to another user. And default one is root.
7. top - To see the overview details about the process running in the system.
8. date - To view date and time in the system.
9. diff - To compare content of two files.
10. find - To search a file in the sepecified directory.
11. clear- To clear the console.

#### 10 GIT commands

1. git config - To store the git configurationthings like username and email address.
2. git init - To initiate the git in the repository.
3. git add * - To add all files in directory for git commit. We can also specify them by name.
4. git rm - To remove a file from the commit.
5. git commit - It initate a commit with tracked file. We can also pass a message with it by "-m" parameter.
6. git push - To push the recent commit to URL.
7. git status- To know the current status of git commit files.
8. git pull- To update and merges the local repository changes from the URL.
9. git clone - To copy the online repository to local system.
10. git log - To list the various versions of commits of the GIT respository.

#### DataBase
Database is a collection of data, which can be managed and manipulated easily. This are generally saved in the forms of tables.

#### SQL Database
SQL database can be called as Relational databases which means that is stores realtionship in form of tables. And "Structured Query Langauge" is used to peform operations on the SQL. IT is consistent, Available But not partition tolerant.
ex- MySQL, MS SQL etc.

#### NoSQl Database
To handle very big database,if we userelational database gets slows a database increase. So we distribute database in various partition calling the operation "scaling out". So it stands for "Non Relational Database". It is partition-tolerant,but not still are either inconsistent or unavailable.
ex- MongoDB, Cassandra

#### 10 Popular Databases

1. MongoDB - 
2. MySQl - 
3. MariaDB - 
4. DynmoDB - 
5. Orcale 12c - 
6. MS SQL Server - 
7. Postgre SQL - 
8. Elastic Search - 
9. DB2 - 
10. Cassandra - 

#### ACID Properties:-
These are properties for a transactional type of database query.
a). **A**tomicity - Either transaction should complete or not at all.
b). **C**onsistency - Database should maintain consistency before and after transaction.
c). **I**solation - All transactions should occur independently without any interference.
d). **D**Duarability - Transaction should be complete even the system fails.

#### Aggregations:-
It is treating two different entities as a single entity. 
ex- A apple and mango can be sold with the label of fruit.

#### Joins:-
Joins are property of SQl to display data from different tables and create a combined view of them for the user.

#### CAP Theorm:-
It is a theorm which stats a databases can have only two properties at a time.
These three properties are Availability, Consistency, Partition-Tolerance.
![CAP Theorm](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQWoiFAsoIvk5gfcgazC6--5ekn48jvz0nTs_qkmp-57TfAPhmG)

#### Normalization:-
Normalization is a process of removing data redundancy and maintaining data integrity.
![Normalization steps](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTTmvNTVOHx61ARTTnzByGSE8gTO8idlwhvkeGMorZLxsYIL03y)

#### DataBase Sharding:-
It is method to maintain large database in pieces into different tables, by using a method called as *horizontal scaling*, in which instead of breaking parts of tables into different tables, we break the table in various parts.

#### 7 Network Layers:-
These layers called as Open System Interconnection layers. There are 7 layers each having a specific task and passing control to each other.
![OSI model 7 layers](https://blogs.bmc.com/wp-content/uploads/2018/06/osi-model-7-layers-804x1024.png)

#### Request Response Protocol:-
It is a protocol generally used in *CLient Server Model* in which one on one request-response applies.
![Request Response Protocol](https://cdn.tutsplus.com/net/authors/jeremymcpeak/http1-request-response.png)

#### Web API:-
It is an Application Programing Interface which allows it user to interact with it, and use its functions and features. It is accessible from different kinds of devices
![Web API](https://www.tutorialsteacher.com/Content/images/webapi/webapi-overview.png)

#### REST API:-
REST stands for **RE**presentational **S**tate **T**ransfer, so it provide the user with resources which user can interact and do operations **CRUD** which are Create, Read, Update, Delete.
![REST API](https://vikramviknowledgesharing.files.wordpress.com/2017/01/rest-crud.png)

#### HTTP Status Codes:-
These are the response code which are send as responses of a request. So there are various types of status code some of them are as given.
![HTTP response code](https://i1.wp.com/csharpcorner.mindcrackerinc.netdna-cdn.com/article/create-api-with-asp-net-core-day-three-working-with-http-status-codes-in-asp/Images/image002.jpg)
