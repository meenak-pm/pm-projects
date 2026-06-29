1. Identified problem statement from a personal experience using an UPI app
2. Used AI tools to conduct research, document PRD and create prototype

User pain points while using UPI app:		
	- User is unable to see the UPI transaction limit set by the bank	
	- The user needs to check it through another app (bank's app) or use net banking (defies UNIFIED notion of UPI)	
	- If the transaction fails for exceeding the limit, there is no option to modify the limit from the UPI app itself or transact through other methods like NEFT/IMPS	
		
Proposed solution:		
	- Similar to 'check balance', there should be link for 'check limits' against each bank ac linked to the UPI id	
	- When transaction fails due to exceeding limit, 	
		 - the message should be clear if daily or per transaction limit is exceeded
		 - there should be a link to modify limits, which takes user to the bank's site (bank site/app opens up separately)
		 - the 'try again in x hrs' message should calculate the exact time & date after which the limit will be reset & user will         be able to transact successfully
	   - once the limit is successfully modified, user can come back to the UPI app and attempt the transaction again
