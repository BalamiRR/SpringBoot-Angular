# User Directory

## Spring Boot + JPA + MySQL + Thymeleaf + JUnit (Test Driven Development)

The project is about inserting, deleting, updating and selecting users from the directory. 


### Interface of User Directory

![alt text](./EmployeeDirectory.png)
 
### Inserting and Updating User
 
When the user wants to update the person who exists on the list will be placed in the box after clicking on the update button.

![alt text](./Insert.png)  ![alt text](./Update.png)
 

![alt text](./Delete.png)



## Test Driven Development

In this project, Test Driven Development was implemented for @Service Layer and @Controller.

@Controller :

Totally, 6 methods were constituted for @Controller. Those methods are about the testing the @Get, @Delete, @Post and @Put annotations to check whether returning HTTP: 200 or HTTP: 404 errors etc.

Passed : 6     Failed : 0

 ![alt text](./Controller.png)


@Service :

Totaly, 3 methods were constituted for @Service. Those methods were about to check by id, creating person and getting all person whether returning correctly or not.

Passed : 3     Failed : 0

 ![alt text](./ServiceLayer.png)




This project was done by Fuat Kara


# ~THE END ~
