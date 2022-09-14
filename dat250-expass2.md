# Lab Assignment 2

This is a lab report for lab assignment 2 in DAT250. In the report I am going to discuss and address the following:

* Technical problems that you encountered during installation and use of Java Persistence Architecture (JPA) and how you resolved

* A link to your code for experiment 2 above. Make sure the included test case passes!

* An explanation of how you inspected the database tables and what tables were created. For the latter, you may provide screenshots.

* Any pending issues with this assignment that you did not manage to solve


## Technical problems with JPA
Installing the Derby Database was a problem. Mostly because I understood it as optional to use for the inspection of the database tables. When I found no other way than to install it, it went fine. Using the Maven project as a starting point was very helpfull.

When filling in the entity classes I had a lot of problems with the assosiactions, but when I found good information on the internet. I had some problems with an entity relationship that was a Collection in the project, but actually was a Set. This change made my MainTest successfull.

## A link to the code for experiment 2
https://github.com/malinive/dat250-jpa-example-master

## Inspection of database tables 
I had a lot of problems with showing the database tables. The first problem was that I used the wrong version of Intellij. It was not possible to show these types of diagrams in the version I had downloaded. I feel that this could have been communicated to us when we were told to download an IDE. 
When switching to the Intellij Ultimate version it got a lot easier. I had some problems with the connection to the database, but when deleting the 
db directory and then refreshing the database, it showed the updated tables. 

Screenshots:

![image](https://user-images.githubusercontent.com/42604421/190159253-502e84e9-2337-4f76-9479-5fdd9a8cf5e5.png)

![image](https://user-images.githubusercontent.com/42604421/190159383-d82ab8a6-6378-44ff-88a0-2d32840ce736.png)


## Any pending issues
None that I'm aware of.
