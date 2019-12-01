## Documentation 


This section presents the documentation about the process solution [assigment](https://github.com/sentialabs/public-cloud-recruitment/blob/master/ASSIGNEMENT.md)


## 1. Current infrastructure and issues.

The customer is currently hosting ten wordpress sites using wordpress multisite in a private datacenter.
- *10 wordpress instances*
- They achieve HA  by using 2 servers and having 2 copies of their multisite
- For the database they are using 2 MySQL servers behind HA proxy to achieve HA
- The past few months, they have been having a lot of issues because some of their websites have increased in popularity, especially during certain timeframes.
- So, the customer has decided to move away from wordpress multisites and have independent Wordpress applications.
- They have also pointed out that they have 5 more sites in the making that will reach Production in the next 12 months.

The client is only interested in developing the WordPress sites from an application perspective. They work using GIT repositories, and they have agreed to provide access to the application source code in one or more repositories.


We have undertaken the task to design the future state of this environment in the public cloud. The solution needs to:

- Be scalable and flexible.
- Be futureproof and expandable with new WordPress sites with minimal effort.

### 1.1 Part 1 - Transformation and Migration to the Public Cloud
- Use control version system to IaC templates. 
- Provide a design for the designated Azure architecture.
- Provide Azure ARM templates.

### 1.2 Part 2 - CI/CD
- Provide a design for the CI/CD pipeline that you will use to deliver the changes to the environment,every time the client updates any of their WordPress applications in GIT

### 1.3. Deliverables
- For Part 1, an architectural design and IaC templates for deploying the components.
- For Part 2, a complete architectural design of the CI/CD process.
- Please include a simple time log of the activities you have performed.
- Please document any assumptions and decisions you have made.
- Please include a presentation of the results within slides, ready to be presented to our client.



## 2.0 An architectural design and IaC templates for deploying the components


### 2. Azure service components . 

 MySQL database Wordpress site for wordpress backend DB.
 One instance of Azure Container Registry
 WebApp for Docker Containers.
 
 architectural design: 
 
 <TO Filled>
 
 ARM Templetes:
 
 Azure mysql 
 Container Registry
 WebApp for Docker Containers
 
 ### For Part 2, a complete architectural design of the CI/CD process.
 
 architectural design of the CI/CD process
 
 ### Please include a simple time log of the activities you have performed.
 
 ### Please document any assumptions and decisions you have made.
