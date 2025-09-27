## LAB 2 CST8915

## Video
https://www.awesomescreenshot.com/video/44678350?key=f38b11da3cf73c3636ea37855d55f07d

## Changes made
I firstly changed the old scripts with the new ones that have environment variables, afterwards I created .env file in each section and I added the variables we will need in our lab

## Importance of using environment variables
The environment variables are important because they make our apps more secure, flexible, and maintainable and more importantly the ease to deploy our app in any environment without touching the code. and lastly a cleaner code.

## Importance of separate repository for each service
Having separate repositories for each microservice is important because it enforces independence, scalability, and maintainability.
Each service will have its own lifecycle without waiting other teams, and can be deployed and scaled individually

## Repo Link
I created 2 Vms, one for Rabbit and the other for Backend/frontend
As Azure won't let me have 4 IPs.

Front & Back : https://github.com/SoufianeMouss/Algonquin_Pet_Store_Front_Back
RabbitMQ : https://github.com/SoufianeMouss/Algonquin_Pet_Store_Rabbit

## Challenges
I spent a lot of time trying to make it work because : 
1. I didn't open RabbitMQ port 5672 along with 15672
2. I was not using different terminals for each service when I want to run it
3. I was running the service and then run the other one on the same terminal, which means the previous one get closed

Thank you.