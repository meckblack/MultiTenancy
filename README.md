MULTITENACY
Multitenancy refers to a principle in software architecture where a single instance of the software runs on a server, serving multiple tenants. A tenant is a group of users sharing the same view on the software they use. - Wikipedia
This can be achieved in two ways:
Single Database – A single database is created, and all data is stored here. Each record is assigned a tenant key, and only data belonging to that tenant is accessible. Access is restricted by the application software.
Multiple Databases – Alternatively, a separate database can be used to store each customer’s data. Access to the database can then be restricted by using SQL login credentials.

ADVANTAGES OF THE MULTI DATABASE APPROACH
1. It is possible to back up and restore user’s data.
2. Easy to move data between servers.


