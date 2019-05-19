##NAME:

Black_Friday_R


## OBJECTIVE:

This open source project / package is created specifically for an assignment for the Advanced R class of the Master in Big Data and Business Analytics at IE School of Human Sciences and Technology (Madrid). The objective is to predict the purchase amount on Black friday.

## CONTEXT:

The dataset here is a sample of the transactions made in a retail store. The store wants to know better the customer purchase behaviour against different products. Specifically, here the problem is a regression problem where we are trying to predict the dependent variable (the amount of purchase) with the help of the information contained in the other variables.

Classification problem can also be settled in this dataset since several variables are categorical, and some other approaches could be "Predicting the age of the consumer" or even "Predict the category of goods bought". This dataset is also particularly convenient for clustering and maybe find different clusters of consumers within it.

## CONTENT:

Both Dataset have the following fields, except Purchase - which is not available in BlackFriday_test.csv.

1. User_ID: Unique ID of the customer
2. Product_ID: Unique ID of the product sold/bought
3. Gender: Gender of the Customer
4. Age: Age group of the customer
5. Occupation: Customer occupation category
6. City_Category: Category of the city
7. Stay_In_Current_City_Years: Number of years the Customer has been staying in the city
8. Marital_Status: Customer's marital status
9. Product_Category_1: Parent category of the product
10. Product_Category_2: Sub-category on the Product_Category_1
11. Product_Category_3: Sub-category on the Product_Category_2
12. Purchase: Target variable. Monitary amount of purchase

##SUPPORT:

For questions or any other remarks, please find below the email adresses of the creator of this library:

	- Pravat Pasayat : pasayat.pravat@student.ie.edu, pasayat.pravat@gmail.com


##CONTRIBUTING:

How to contribute to our project: 

	* Either the repository is public. If the repository is private, then you need to be a collaborator of this project.
	
	* Fork the master repository (https://github.com/pasayatpravat/Black_Friday_R.git) to your github remote account
 
	* Clone the master repository to your local machine.
		git clone https://github.com/pasayatpravat/Black_Friday_R.git
	
	* Go to the local github directory.
		cd <directoryPath>
		
	* Add your fork as a remote
		git remote add <GitHub_UserName> <Forked_repository_URL>
		
	* Initialize the repository
		git init
		
	* Create a new branch 
		git checkout -b <branchName>
		
	* Add/Modify/Remove files in the repository.
	
	* Commit your changes.
		git add <filePath/fileName>
		git commit -m <"comment">
		
	* Push up your changes/branch to your forked repository. 
		git push <GitHub_UserName> <branchName>
		
	* Go to your GitHub remote repository and create a pull request.
	
	* Wait for another collaborator to approve your changes.


##AUTHOR:

	- Pravat Pasayat
	

##ACKNOWLEDGMENTS:

We would like to thank our 'Advance R' Professor, *Mr. Sirio Sobrino Uranga*, for his coaching.
