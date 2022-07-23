
Spring Boot & Rest Calls Implemented

A retailer offers a rewards program to its customers, awarding points based on each recorded purchase.

 


A customer receives 2 points for every dollar spent over $100 in each transaction, plus 1 point for every dollar spent over $50 in each transaction

(e.g. a $120 purchase = 2x$20 + 1x$50 = 90 points).

 


Given a record of every transaction during a three month period, calculate the reward points earned for each customer per month and total.


Data set to tested locally to demonstrate that the outuput is working fine locally
 Attached along with the sample 10 results data set to your kind attention below


The Reward report for last 3 months is

 
 	Transaction id: 1                Price: $185    Reward points: 220

	Transaction id: 2                Price: $115    Reward points: 80
   
	Transaction id: 3                Price: $674    Reward points: 1198

	Transaction id: 4                Price: $322    Reward points: 494
      
	Transaction id: 5                Price: $1016  Reward points: 1882
                 
Transaction id: 6                Price: $16       Reward points: 0
	
Transaction id: 7                Price: $181     Reward points: 212            
	
Transaction id: 8                Price: $3         Reward points: 0    
                 Transaction id: 9                Price: $120      Reward points: 90       
	Transaction id: 10                       Price: $558                   Reward points: 966

	Transaction id: 11                        Price: $797                   Reward points: 1444
	
Transaction id: 12                        Price: $469                   Reward points: 788

	Transaction id: 13                        Price: $124                   Reward points: 98

	Transaction id: 14                        Price: $234                   Reward points: 318

	Transaction id: 15                        Price: $1081                  Reward points: 2012
T

       Reward points: 1960

Check solution into GitHub


  

---


###
To Run this project locally
```shell
$ git clone https://github.com/Vigneshwarathirumal/retailer-rewards-programme.git
$ mvn spring-boot: run

