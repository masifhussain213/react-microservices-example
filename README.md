# react-microservices-example

### Introduction
In this project I will try to show some concepts and techonologies related to microservices. This is a example of a booking website with a react app,  some spring boot and NodeJs services.
My main motivation for this project is to have something in my portifolio to show to anyone interested in my job. Furthermore, I think it can be usefull for anyone interested in exchange some knoledge about microservice archtecture. I will try to show how to build a website based on microservices but let me know if you find something to improve in this code.

This project should run inside a docker.

My free time is scarce then I will try to improve this project a litle at a time. 


### Overview
Here is how this project is organized:
* /react-microservices-example
  * /accommodation-service     -> sprin boot service related to accommodation process. It show some basics (but nice) features of spring boot.
  * /file-service              -> utility service to handle images and files
  * /findmyplace_website       -> A website written in react to consume the other services
  * /reservation-service       -> spring boot service related to reserve process to show a case of eventual consistency. It will be used to make a reservation and inform the schedule about that event.
  * /schedule-service          -> spring boot service related to schedule that will work together with the reservation. It shows a schedule of some accommodation.
  * /findmyplace-config-server -> It is a config server for my services. I will show a example of how to use it in my cloud.
  * docker-compose.yml         -> Docker config for a dev enviroment
        
    
### Where do I start?
You can start wherever you want. Every project is supposed to be independent from each other.
I would recommend to take a look into the /accommodation-service first, but every project/service has his own README.md file.
I will use it to describe the service. 


### References

* https://12factor.net
* https://www.martinfowler.com/microservices
