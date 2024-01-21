# Spring cloud demo for beginners - service discovery, API gateway, service to service API calls using feign client<br>

### Links   
  Refer guides here <https://Spring.io> <br>
  Tool to generate spring projects <https://start.spring.io>  
   <br>
   
## Clone below projects and import as existing maven projects in to STS/eclipse and Run projects in the below order  
1) Discovery(Serviceregistry) - <https://github.com/sunilsp54/discovery>  
2) Gateway - <https://github.com/sunilsp54/gateway>  
3) user-management - <https://github.com/sunilsp54/user-management>   
4) merchant-management - <https://github.com/sunilsp54/merchant-management>    

  
## Access service registry  

 Service registry  <http://localhost:8761/eureka>  
  

## Access users API via gateway  

Get user with merchant info <http://localhost:8090/users/id1>  
Get user with merchant info <http://localhost:8090/users/id2>  

user-management internally calls merchants-management service API to get merchant details and returns the merchant info as part of 
the response of GET <http://localhost:8090/users/id1>  

## Access merchants API via gateway<br>
 Merchants APIs<br>
 <http://localhost:8090/merchants/m1>  
 <http://localhost:8090/merchants/m1> 
 
 
 
  

