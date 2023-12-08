# nosql_challenge
nosql-challenge_ Mongo DB

The assignment is for a fictional magazine to evaluate the rating data provided by UK Food Standard Agency regarding the various establishments.

Part 1: Database and Jupyter Notebook Set Up


1.	Import the data provided in json file using Mongo import.

2.	Create an instance of the Mongo Client.

3.	List the databases you have in MongoDB. Confirm that uk_food is listed.

4.	List the collection(s) in the database to ensure that establishments is there.

5.	Find and display one document in the establishments collection using find_one and display with pprint.

Part 2: Update the Database


1.	Insert the data provided regarding one new restaurant in to the database. 

2.	Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.

3.	Update the new restaurant with the BusinessTypeID you found.

4.	Delete all the documents of establishments within the Dover Local Authority from the database

5.	Use update_many to convert latitude and longitude to decimal numbers.

6.	Use update_many to convert RatingValue to integer numbers.

Part 3: Exploratory Analysis


Use the following questions to explore the database, and find the answers, so you can provide them to the magazine editors.

•	Which establishments have a hygiene score equal to 20?

•	Which establishments in London have a RatingValue greater than or equal to 4?

•	What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

•	How many establishments in each Local Authority area have a hygiene score of 0?
