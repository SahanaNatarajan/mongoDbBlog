This application is a basic project of integrationg MongoDB is a spark framework based web application.
This project is part of the MongoDB for Java developer certification (M101J) course provided by the University of MongoDB.

This project is build onto of the maven build system.

This application is about users signing in for a blog page and create posts.
The user will be able to create new blog posts, read posts made by other users and add comments on them. The blogs can be categories by tagging them into different user-defined categories.

To run this project:
- Maven dependencies has to be loaded by building the project
	>mvn clean install
- Start the Mongo DB server using the following command in mongo bin
	> mongod
- Before running the application, a set of mongo collections has to be created inside a database called 'blog'
- The collections to be created are
	- posts
	- users
	- sessions
- To run the application, point your command prompt to project folder location having the pom.xml file. And run the following command.
	>mvn compile exec:java -Dexec.mainClass=course.BlogController

The application server will be initialed in the localhost with port 8082.