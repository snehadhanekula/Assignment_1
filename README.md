# Assignment_1
Assignment demonstrating loading large datasets using postgreSQL

Created Tables:

Tables for authors, subreddits, submissions, and comments were created with appropriate data types and primary keys.
Added Foreign Key Constraints:

Foreign keys were added to maintain relationships between authors, subreddits, submissions, and comments tables.
Executed Queries:

5 queries were executed:
Query 1: Count of comments by author xymemez.
Query 2: Count of subreddits by type.
Query 3: Top 10 subreddits based on comment count and average score.
Query 4: Label authors with higher link karma than comment karma.
Query 5: Count of comments by type for [deleted_user].
Bash Script:

setup.sh script created for automating the setup process, including table creation, data insertion, and query execution.
