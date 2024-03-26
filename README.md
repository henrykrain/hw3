# Here is the code I used for the first query and its output. 
{ runtime: { $gt: 200 }, year: 1983 } this first argument filters throught the collection to find the documents where the runtime is greater than 200 and the year values is 1983
{ _id: 0, runtime: 1, title: 1, year: 1 } this arguemnt creates the output. It hides the id field and displays the runtime,k title, and year

![image](https://github.com/henrykrain/hw3/assets/120867004/38d56972-1d0d-401d-903b-885a8429131c)
![image](https://github.com/henrykrain/hw3/assets/120867004/f33c43b9-030e-471c-ba10-71e69f185700)


# Here is the code I used for the second query and its output.
db.movies refers to the movies collection
{ year: { $gt: 2014 }, "imdb.rating": { $gt: 9 } } this arguement filters throught the collection to find documents where the year field is greater than the 2014 and the imdb rating is greater than 9
{ _id: 0, title: 1, year: 1, "imdb.rating": 1 } this argument creates the output. It hides the id field and displays the title, year and imdb rating

![image](https://github.com/henrykrain/hw3/assets/120867004/6da6b6cf-3c0b-4d70-8279-09d00dcc55d9)
![image](https://github.com/henrykrain/hw3/assets/120867004/0839e109-43d4-4d6b-a0b9-f12e0389bd90)
