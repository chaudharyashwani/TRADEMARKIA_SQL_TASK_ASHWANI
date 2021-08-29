# TRADEMARKIA_SQL_TASK_ASHWANI

 <h2> Name: Ashwani Chaudhary </h2>
<h4>
Ques: Design a data model to store users, posts and comments where comments could be nested; similar to reddit. Posts will have an associated "poster" (the user who posted that post) and associated comments. comments will also have an associated score which is calculated by the number of users who upvoted minus the number of users that downvoted. Each user should only be able to vote (upvote or downvote) once on a comment.
Then, write a query to fetch the post along with its poster and all comments. Remember that comments can be nested up to multiple levels. The comments should be sorted by the product of the square of their score and their time of posting in descending order. The query should run fast and should have as little overhead as possible. You may use appropriate indexes to achieve the same.
Also write a mutation to insert comments at any level belonging to a post, and mutations for a user to upvote or downvote a comment (which must recalculate the comment score).
</h4>

Sol: 
<p>
Data model is used to organize the data elements and analysing how data elements are related to another data elements and the data model represents the real world things whic are living and non living example dogs can bite , human can drink water and house have an doors ,etc. this are the real world things whic your seeable

some of the requiremnets to satisfied the data model in the structure query language they are,

=>Finding the entity types

=>validating with attributes

=>making the relationship

=>assign the keys

=>apply the model for test

=>improve the performance with the effiency query

nested is an tabel which means one table of an data are embeded or merged to another table of an data is called an nested data for an example there is an retail store considering the two tables availabel nedd to access like stock
_table1 and bill_table2 in this both table are embeded together.

the followin are the some of the example are used to make an data model are

User data tbl: Post CHAR<<FK>> 0 Poster tbl: Comments VARCHAR <<FK>> Le check like and dislikes 1 0 score tbl: Score int: Lik


The following are the some of the queries to fetch an score of the comments are :

<h5> SELECT count(Score) FROM score_tbl WHERE (like = 1); <h5>

 </p>
