# nosql-challenge
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

Part 1: Database and Jupyter Notebook Set Up
Use NoSQL_setup_starter.ipynb for this section of the challenge.

List the databases you have in MongoDB. Confirm that uk_food is listed.
List the collection(s) in the database to ensure that establishments is there.
Find and display one document in the establishments collection using find_one and display with pprint.
Assign the establishments collection to a variable to prepare the collection for use.

Part 2: Update the Database
Use NoSQL_setup_starter.ipynb for this section of the challenge.

Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.

Update the new restaurant with the BusinessTypeID you found.

Use update_many to convert latitude and longitude to decimal numbers.
Use update_many to convert RatingValue to integer numbers.

Part 3: Exploratory Analysis
Eat Safe, Love has specific questions they want you to answer, which will help them find the locations they wish to visit and avoid.

Use NoSQL_analysis_starter.ipynb for this section of the challenge.

Which establishments have a hygiene score equal to 20?

Which establishments in London have a RatingValue greater than or equal to 4?

Hint: The London Local Authority has a longer name than "London" so you will need to use $regex as part of your search.

What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
