# nosql-challenge
assignment 12

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

Part 1: Database and Jupyter Notebook Set Up

the evaluation and analysis of the UK Food Standards Agency data for Eat Safe, Love magazine have been successfully set up and executed. The database, named uk_food, was established, and the collection, establishments, was loaded with relevant data. The Jupyter Notebook, NoSQL_setup_starter.ipynb, was employed to import the data, confirm the database and collection creation, and make necessary updates.

In Part 2, modifications were made to the database, including the addition of a new halal restaurant, Penang Flavours, in Greenwich. The BusinessTypeID for "Restaurant/Cafe/Canteen" was found and applied to the new restaurant. Establishments in the Dover Local Authority were removed as per the magazine's request, and numeric values were appropriately converted using update_many.

Moving on to Part 3, exploratory analysis was conducted using NoSQL_analysis_starter.ipynb. Specific questions posed by Eat Safe, Love were addressed, including identifying establishments with a hygiene score equal to 20, those in London with a RatingValue greater than or equal to 4, and the top 5 establishments with a RatingValue of 5 sorted by the lowest hygiene score, nearest to the newly added restaurant, Penang Flavours. Additionally, the number of establishments in each Local Authority area with a hygiene score of 0 was determined, sorted from highest to lowest, with the top ten local authority areas displayed.

Overall, the comprehensive evaluation and analysis of the data have equipped Eat Safe, Love magazine with valuable insights to guide their future articles and recommendations for their audience.
