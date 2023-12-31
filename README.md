# HandsOn on Mongo DB

Load Atlas Sample Dataset - https://www.mongodb.com/docs/atlas/sample-data/#load-sample-data-1

Build the following queries -
1. In db sample_mflix, collection movies, find the unique countries.
2. In db sample_mflix, collection movies, find the unique genres for country France
3. In db sample_mflix, collection movies, find all movies having imdb rating more than 7 and at least 10 reviews and tomatoes rating more than 8 with at least 50 reviews.
4. In db sample_mflix, collection movies, find the decade (1960, 1970, 1980, etc...) in which the most movies were released...
5. In db sample_mflix, collections movies and comments, find the name/title of the movie having the most comments...
6. In db sample_airbnb, collection listingsAndReviews, find the average price of all properties in Porto market (address.market)
7. In db sample_airbnb, collection listingsAndReviews, find the number of properties in 10km range of the coordinates - [-8.61308, 41.1413] (This is long first, then lat) (Hint: check geo stages and operators in MongoDB)
8. In db sample_restaurants, collection restaurants, find the top 5 restaurants with highest average grade score -- (grades.score)