# Sql2

Problem 1 : Rank Scores		(https://leetcode.com/problems/rank-scores/ )
Solution:

Select score, DENSE_RANK()
OVER (ORDER BY score DESC) AS 'rank'
from Scores

Problem 2 : Exchange Seats	(https://leetcode.com/problems/exchange-seats/ )

Problem 3 : Tree Node		(https://leetcode.com/problems/tree-node/ )

Problem 4 : Deparment Top 3 Salaries		(https://leetcode.com/problems/department-top-three-salaries/ )
