"# nosql-challenge"

The solution of the set up is in the file named 'NoSQL_setup_starter_CZ'.
The solution of the analysis can be found in the file labeled 'NoSQL_analysis_starter_CZ'.

In Part 1, I made some changes in the order of the recommended steps. Particularly by moving the "# assign the collection to a variable" step before reviewing the documents in the collection (count).

In Part 2.1, I introduced additional code lines to prevent the new restaurant from being added more than once to the database. These steps include querying to find and remove existing documents with the same BusinessName and confirming the document count after insertion.

For 2.5, I'm assuming that the step # Set non 1-5 Rating Values to Null means that we need to change the ratings that are originally words to blanks so they can be converted to integers. 

in the Analysis part, point 2: Which establishments in London have a RatingValue greater than or equal to 4?, I have to add a piece of code to see how 'London' was defined.  I found that it was included as 'City of London Corporation'.  That was a sneaky move!!