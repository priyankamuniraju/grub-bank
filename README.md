GrubBank is a standalone java application to store your favourite food recipes, update or delete them. It can also be used to search recipes based on some search criteria. 

Tech or architecture stack - the project is developed using java 11, spring boot, REST API and H2 persistent DB on a high level.
### Pre-requisite to run the application : 
`Java 11`, a REST client such as [`POSTMAN`](https://www.postman.com/downloads/) or [`Advanced Rest client`](https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo) to hit the REST API end points.

### Step by step guide to run the application - 
Steps :

1. Open your terminal and navigate to a desired location on your machine, where you want to place the project (eg : cd Documents)
2. Here execute the command : git clone https://github.com/priyankamuniraju/grubbank.git
3. Navigate to the project(`grubbank`) folder (eg: cd grubbank)
4. Run the command : `./gradlew bootrun`
5. The application starts on port 8080 by default.
6. Optional Step if you currently have another application running on port 8080. The default port of grubbank can be changed to any desired port number.

>- Go to the file - grubbank/src/main/resources/application.properties  
>- And add the following line :server.port=8081 . Now the grubbank uses port 8081.
>- Save the changes and repeat step 5

7. Alternately you can kill the current process running on 8080 and repeat step 5
8. Now that the application is up and running, the application can be used through clients such as [`POSTMAN`](https://www.postman.com/downloads/) or [`Advanced Rest client`](https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo) by hitting the REST endpoints described here : https://github.com/priyankamuniraju/grubbank/wiki
