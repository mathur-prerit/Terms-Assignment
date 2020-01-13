## 10 popular commands

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

## 10 Network commands

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

## 10 OS commands

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

## 10 GIT commands

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

## DataBase
Database is a collection of data, which can be managed and manipulated easily. These are generally saved in the forms of tables.

## SQL Database
SQL database can be called as Relational databases which means that is stores realtionship in form of tables. And "Structured Query Langauge" is used to peform operations on the SQL. IT is consistent, Available But not partition tolerant.
ex- MySQL, MS SQL etc.

## NoSQl Database
To handle very big database,if we userelational database gets slows a database increase. So we distribute database in various partition calling the operation "scaling out". So it stands for "Non Relational Database". It is partition-tolerant,but not still are either inconsistent or unavailable.
ex- MongoDB, Cassandra

## 10 Popular Databases

1. MongoDB - It is cross platform NoSQL database with high performance and scalability.
2. MySQl - It is one of the most commonly used type of database.
3. MariaDB - It is a forked open-source version of MySQL.
4. DynmoDB - It is a NoSQl database developed by Amazon.
5. Orcale - It is the most commonly used type of enterprise database. 
6. MS SQL Server - It is a relational database developed by Microsoft.
7. Postgre SQL - It is open source relational database.
8. Elastic Search - It is used for text search and analytics.
9. DB2 - It is developed by IBM.
10. Cassandra - It is distributed database use for storing a large data.

## ACID Properties:-
These are properties for a transactional type of database query.
a). **A**tomicity - Either transaction should complete or not at all.
b). **C**onsistency - Database should maintain consistency before and after transaction.
c). **I**solation - All transactions should occur independently without any interference.
d). **D**urability - Transaction should be complete even the system fails.

## Aggregations:-
It is treating two different entities as a single entity. 
ex- A apple and mango can be sold with the label of fruit.

## Joins:-
Joins are property of SQl to display data from different tables and create a combined view of them for the user.

## CAP Theorm:-
It is a theorm which stats a databases can have only two properties at a time.
These three properties are Availability, Consistency, Partition-Tolerance.

![CAP Theorm](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQWoiFAsoIvk5gfcgazC6--5ekn48jvz0nTs_qkmp-57TfAPhmG)

## Normalization:-
Normalization is a process of removing data redundancy and maintaining data integrity.

![Normalization steps](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTTmvNTVOHx61ARTTnzByGSE8gTO8idlwhvkeGMorZLxsYIL03y)

## DataBase Sharding:-
It is method to maintain large database in pieces into different tables, by using a method called as *horizontal scaling*, in which instead of breaking parts of tables into different tables, we break the table in various parts.

## 7 Network Layers:-
These layers called as Open System Interconnection layers. There are 7 layers each having a specific task and passing control to each other.

![OSI model 7 layers](https://blogs.bmc.com/wp-content/uploads/2018/06/osi-model-7-layers-804x1024.png)

## Request Response Protocol:-
It is a protocol generally used in *Client Server Model* in which one on one request-response applies.

![Request Response Protocol](https://i0.wp.com/blogs.innovationm.com/wp-content/uploads/2016/10/HTTP-Protocol.png?resize=624%2C248)

## Web API:-
It is an Application Programing Interface which allows it user to interact with it, and use its functions and features. It is accessible from different kinds of devices

![Web API](https://www.tutorialsteacher.com/Content/images/webapi/webapi-overview.png)

## REST API:-
REST stands for **RE**presentational **S**tate **T**ransfer, so it provide the user with resources which user can interact and do operations **CRUD** which are Create, Read, Update, Delete.

![REST API](https://vikramviknowledgesharing.files.wordpress.com/2017/01/rest-crud.png)

## HTTP Status Codes:-
These are the response code which are send as responses of a request. So there are various types of status code some of them are as given.

![HTTP response code](https://i1.wp.com/csharpcorner.mindcrackerinc.netdna-cdn.com/article/create-api-with-asp-net-core-day-three-working-with-http-status-codes-in-asp/Images/image002.jpg)

## HTML:-
HTML stands for **Hy**per **T**ext **M**arkup **L**anguage which are designed for displaying in browser. Its parent is XML. It contains tags which are used to render different kinds of effects on multimedia page.

## Box Model:-
It is a part of CSS. When a browser render any HTML element, each element is treated in rectangular box. The box model is structural property of the HTML element. The box model is made of margin, padding, border, and content properties.

![Box model](https://www.topalovich.com/wp-content/uploads/2017/09/Box_Model.png)

## Margin:-
Margin provide us control the space around the content, outside of defined border. Basically it pushes content outside the box.

## Padding:-
Padding help us to control space around the content, inside of defined border. It pushes content inside the box.

## CSS Selectors:-
These are the options for selecting and html element and applying CSS properties on this. It could be done by defining universal, ID, class or on tags by grouping.

![CSS Selectors](https://studyopedia.com/wp-content/uploads/2017/07/CSS-Selectors.png)

CSS Specificity:-
There are certain rules for specifying the CSS properties to an HTML element. Each one of them have there own precendence order and points, so by it we can calculate their specificity of an element. They are Inline style, ID, classes and tags.

![CSS Specificity](https://cdn.rawgit.com/MakeSchool-Tutorials/sa-2018-landing-page/master/P06-CSS-Inheritance-And-Specificity/assets/css_specificity_magnitudes.png)

## Flexbox:-
It is a CSS property used to design layout for responsive sites. It works on container and its element principle. Generally flex works in 1 dimension. It contains various properties like flex-flow, flex-basis, etc.

## Grid:-
It is also a CSS property used to design layout for responsive sites. It works on *grid*(rows and columns) principle. It works for 2 dimension. It contains properites like grid-gap, grid-template-areas etc.

## GIT:-
GIT is a version control system. It was designed for managing and keeping track of the source code developed by programmers. It even tracks the changes occurs by others making it easy the code for coders to manage their code with others. 

## HTTP:-
HTTP stands for **H**yper **T**ext **T**ransfer **P**rotocol which is used to browse across *World Wide Web*. It create the user request to server, and the server response accordingly.

## TCP:-
TCP is **T**ransmission **C**ontrol **P**rotocol, which is used in www,ftp etc. It has more layers which make it slow but provie more secure and better network. 

## UDP:-
UDP is **U**ser **D**atagram **P**rotocol, which is used for video streaming,DNS etc. It is fast because has less layer but data transimmision is unreliable. We use it generally when we don't data surely.

## Web server:-
A web server is a server which stores HTML, CSS, multimedia content and scripts which render the data to user on request. It can be interacted with HTTP request.

## Static server:-
It is a kind of server in which genrate files everytime it requested. Generally it easy, cheap, fast to create a static server.

## Application server:-
Application server is server which is used to run web application or a desktop application. It may have business logics, databases and various components connected to it.

## DNS server:-
DNS server stands for **D**omain **N**ame **S**ystem. It is a server which keep table for ip address and hostname. So when we request a ip address for a hostname, it first goes to DNS server to resolve the name thing.

## Database Server:-
Database server is a server which keep data. It are generally not connected directly with internet. The request first goes to web server and then web server process the server request and then passes it to database server and it retieve the result and response it.

## Standalone Application:-
It a kind of portable application, which can executed independently. They are not dependent on any other component.

## MVC:-
The MVC stands for **M**odel **V**iew **C**ontroller. It is architectural that seperate these components from each other.
a). Model - It includes the data and logic part.
b). Controller - It works a controller between model and view which is triggered by users' action.
c). View - Render the view to the user.

![MVC](https://www.guru99.com/images/1/122118_0445_MVCTutorial1.png)

## Operating System:-
The OS is interaction between user and hardware. It is build of various applications and filesystem. There are various types of architecture for OS.
ex:- Windows, Ubuntu, MacOS etc.

![OS](https://www.tutorialspoint.com/operating_system/images/conceptual_view.jpg)

## Kernel:-
Kernel are the sub part of a OS which interacts and create a link betwwen hardware components in the system like CPU, RAM, hard drives, devices etc. with applications and softwares. 
ex:- Monolithic kernel, Micro kernel etc. 

## Process:-
A process is a program under execution. It may be further threads for execution. A process could be in ready, waiting, running, completed or terminated state. These process register themselves in call stack.

## Thread:-
A thread is a sub process in sytem. A process could have multiple threads. The threads share their memory among another thread if they are executing for  same process. 

## SOLID:-
The SOLID stands as:-
**S** - Single responsibility principle
**O** - Open/closed principle
**L** - Liskov substitution principle
**I** - Interface segregation principle
**D** - Dependency inversion principle

![SOLID principles](https://howtodoinjava.com/wp-content/uploads/solid_class_design_principles.png)

## Apache Web Server:-
Apache is open source web server. Apache uses a process-driven approach and creates a new thread for each request.

## Nginx Web Server:-
Nginx web server is mostly used for static files. It uses an event-driven architecture to handle multiple requests within one thread.

## Messaging Queue:-
It is kind of storage for message when it doesn't reach its destination. It insert the message in a queue and provide asynchronous communication.

## Enterprise Message Bus:-
It is a kind of middleware application used for distributing and communicationg among the components of applications. Though their no standard in this, but it is majorly used by organisation. 

## RabbitMQ:-
It is an open-source message broker, used fot asynchronous messaging.

## Kafka:-
Kafka is open-source stream-processing application. It is used because it provides low latency TCP based protocol.

## Zookeeper:-
It is a service for distributed system which stores a hierarchical key-value pair.

## Service Oriented Architecture:-
It is a type of architecture where various components of application communicate through a communication protocol.

![SOA](https://e8c5h7a9.stackpathcdn.com/wp-content/uploads/2017/09/Service-oriented-architecture.jpg)

## Microservices Architecture:-
It is based on *single responsibility principle* , in which each of service have single job and coupled together to create a microservice architecture.

![Microservice](https://docs.microsoft.com/en-us/azure/architecture/includes/images/microservices-logical.png)

## Redis? Why?:-
Redis is an open source where in-memory key value pair are used.It is fast and NoSQL type of database.

## Solr? Why?:-
Solr is open source Apache search server. It is used because it can index and can search multiple sites. 

## ElasticSearch? Why?:-
It is an open source text-search and analytics server. It provides a vast range of searching options like website search, application search etc. It can search, index, store data very quickly.

## Celery? Why?:-
Celery is open source asynchronous task queue based on distributed message passing. It have scheduling, monitoring etc.

## Node JS:-
Node JS is open-source environment which can executes Javascript code outside of a browser. It is used to write javascript script.

## MongoDB? Why?:-
It is a cross-platform database. It can classified NoSQL database. It is dynamic, high performance database.

## Progressive Web Apps (PWA):-
PWA is those web apps which gurantee the output even when their is no network. They stores some components on the device so that it can be accesssible without internet connectivity.

## Session Based Authentication:-
Session based authentication is a kind of authentication where keys are stored it server side. So for each request you need to authenticate the client to use the services.

## Token Based Authentication:-
Token based authentication is a kind of authentication where keys are stored in client side. For this we generally used local storage. So user doesn't to authenticate for each request. It is preferred method for REST API.

## Authorization:-
Authorization is access privileges provided to the client. For example A user can add, delete, edit, get its data for its own page, but might not save type of permission for other client.

## Docker:-
Docker is an open-source virtualization platform to provide other application their required environment. It provide PaaS (*Platform as a Service*).

## IaaS:-
The IaaS or *Infrastructure as a Service* provides API which can interact with physical hardware resources, so we could control and manages them.
ex- VMware, VirtualBox, Hyper-V etc.

## AWS:-
AWS stands for **A**mazon **W**eb **S**ervices. It is a cluster of different kinds of applications provided by Amazon.
ex:- DynamoDB, S3 bucket, etc.

## PaaS:-
PaaS or *Platform as a Service* is a cloud computing services by developing or deploying their application and serivces on cloud platform.
ex- Google App Engine, Heroku.

## Heroku:- 
Heroku is a PaaS which provide facility of deploying ither applications on cloud platform.

## Hoisting:-
Hoisting is declaring functions and variables and defining them before it, So the language first execute the declaration part and then define them.  

## Pass by Reference/Pass By Value:-

#### Pass by Value-
In this we create two independent variables with the same value.

#### Pass by Reference-
In this we use the same variable for the parameter.

![difference](https://www.mathwarehouse.com/programming/images/pass-by-reference-vs-pass-by-value-animation.gif)

## Closures:-
It is feature in which we use global defined variables are used in local scope function to get the output.

## Prototypal Inheritance:-
It is kind of inheritance in which we create prototypes and then inheritance using prototypes

## Mutable Methods in JS:-
The method which are subject to be changed/altered the objects.

## Immutable Methods in JS:-
The method which are to meant to mutable the objects.

## React:-
React is javascript library which was created by Facebook. It is used for creating the UI interface for the user. It build the UI in the form of components.

## Why React?:-
It create virtual DOM, which only refresh the components which are modified, which make it fast.

## Redux:-
Redux is an open-source javascript library used for managing the state. It is generally used  React or Angular with user interfaces.

## Why Redux?:-
It is easy to maintain and it is easy to predict the outcome of state. 

## State:-
State is an object which stores the property values of the components. And on change the state value the components re-render.

## Props:-	
Props are like function arguments in JavaScript and attributes in HTML.