Major Challenges
The major challenge was to get started with the project, first of all since the project was built on
Php and SQL so it was difficult to add different services according to the client needs.
Since our client was asking for addition of different micro-services to the website there was a dilemma that whether to use NodeJS for backend or to use Spring Boot, 
but finally we decided go with Spring Boot as Spring Boot was the best choice that we had. It is the best framework to work with the micro-services. Also all the deployment 
of the project comes handy with all the cloud functions of the spring boot
The second major Issue was the security issue since the given website is an ecommerce website so the security was our main priority, so the final decision was to go with the 
spring boot i.e. to make the whole website again with the spring Boot which is considered best for security services.
While developing the API’s the biggest challenge came while developing the recent viewed API. The main problem was to make a API that use very less database hits and also we 
can make a proper API’s using only simple tools like triggers and methods. So we prepared a trigger in MySQL Workbench that enables us to store only 10 records at a moment and
remove automatically the previous record and add manually the new records. But this approach also had a major flaw that we can create and delete at the same time on a database
as the database locks itself while preforming an action so the final approach was to make a trigger that will sort by
