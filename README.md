# TRADEMARKIA_SQL_TASK_ASHWANI

 <h2> Name: Ashwani Chaudhary </h2>
<h4>
Ques: Design a data model to store users, posts and comments where comments could be nested; similar to reddit. Posts will have an associated "poster" (the user who posted that post) and associated comments. comments will also have an associated score which is calculated by the number of users who upvoted minus the number of users that downvoted. Each user should only be able to vote (upvote or downvote) once on a comment.
Then, write a query to fetch the post along with its poster and all comments. Remember that comments can be nested up to multiple levels. The comments should be sorted by the product of the square of their score and their time of posting in descending order. The query should run fast and should have as little overhead as possible. You may use appropriate indexes to achieve the same.
Also write a mutation to insert comments at any level belonging to a post, and mutations for a user to upvote or downvote a comment (which must recalculate the comment score).
</h4>

Sol: 


<h5> The following are the some of the queries to fetch an score of the comments are :

 SELECT count(Score) FROM score_tbl WHERE (like = 1); </h5>

 </p>
