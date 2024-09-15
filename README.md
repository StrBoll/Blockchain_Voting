Blockchain Project 

By Phillip Boll

-------------------------------



This readme file contains information regarding many aspects of the project, 
one of the first things you must do before attempting to run it is to install the openssl library. 
This library is used for the encryption in the blockchain. I am using SHA256, the most up-to-date 512 bit encryption










Transactions (timestamps):
---------------------------

1. Transactions follow ISO8601 Format which is YYYY-MM-DD followed by the time 
2. An example of the format is: 2024-09-11T15:30:00Z
3. The "T" separates the date from the time 
4. The "Z" at the end of the time is to denote what time zone it is. We are using UTC (Universal Timezone Coordinates)
5. The purpose of timestamps is to keep track of transactions which is why each block in the blockchain contains a list of transactional timestamps