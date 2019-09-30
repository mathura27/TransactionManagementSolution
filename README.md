# TransactionManagementSolution
Solution for code challenge Financial transaction analyzer
@author : Mathura

****************Instructions for running **********************

1. Extract TransactionManager.zip
2. Open command prompt and navigate to the folder location
3. Place the input CSV file within the same folder
4. And run the command java -jar transactionManager-0.0.1-SNAPSHOT.jar to execute the jar
5. When asked for file name provide a valid file name.(case-sensitive)
6. Similarly provide a valid accountId 
7. Then provide both from date and to date in "dd/MM/yyyy HH:mm:ss"



**************Design********************************************

Implementation : Based on java and maven as build tool, this application describes a simple transactionManager.Maven is used here for all the packaging needs.
		
		Unit Tests are written using Junit and Mockito.Unit tests here are used to test if the application is working as expected.
		
		Comments have been added inside the source code to make it easily understandable as possible. To make it easyily maintainable , the application is divided into smaller components and packages.
		
		The data read from the csv input file is mapped using the pojo class. And the data is manged through getters and setters, so the file is only read once.

		Apache commons-csv is used to read the csv file in the application. Scanner is used here receive user inputs.


Assumsptions : 1. It is assumed that all the inputs provided by the user are valid and in the expected format
	       2. It is assumed that the records have valid entries in the file 
		
