# spring-microservices-eureka-demo

* Clone the repository:
```bash
git clone https://github.com/KondratovIvan/spring-microservices-eureka-demo
```

* Create a few instances of any client app in IDE Run/Debug configuration (for greater clarity):
  
![image](https://github.com/KondratovIvan/spring-microservices-eureka-demo/assets/94958641/2e6b8fd3-1dc8-4cc1-890d-0f042dc78219)

* Run applications in this order: EurekaServerApplication, ApiGatewayApplication, EurekaClientApplications and their instances
  
![image](https://github.com/KondratovIvan/spring-microservices-eureka-demo/assets/94958641/8b148ef0-efdf-48df-bae1-8f3c286ad663)

* Open browser and browse at: http://localhost:8081/ to see registered services info
  
![image](https://github.com/KondratovIvan/spring-microservices-eureka-demo/assets/94958641/27b875b9-c5b2-4199-834d-7ffdd93fb89f)

* Open browser and browse at: http://localhost:8082/main/test or http://localhost:8082/main2/test2 to see Api Gateway routing:
  
![image](https://github.com/KondratovIvan/spring-microservices-eureka-demo/assets/94958641/e27b3118-b088-4b4a-bb3f-96df891e0ea2)
![image](https://github.com/KondratovIvan/spring-microservices-eureka-demo/assets/94958641/1b45387c-8b50-4742-8881-7eb3bc9f2c2d)
