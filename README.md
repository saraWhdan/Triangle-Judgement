# Triangle-Judgement

Problem Link:(https://leetcode.com/problems/triangle-judgement/description/?envType=study-plan-v2&envId=top-sql-50)

## Solution

```sql
select x,y,z
,case 
    when x+y>z AND x+z>y AND y+z>x then 'Yes'
    ELSE 'No'
END AS triangle    
from Triangle

```
