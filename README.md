# HackerRank_SQL
Solutions for all HackerRank problems, define problems, and execute the syntax to resolve it

## Problem List

### Basic
1. **Vowels starting City Name**: Query the list of CITY names starting with vowels (i.e., a, e, i, o, or u) from STATION. Your result cannot contain duplicates.
   - **Solution SQL**:    ```sql SELECT DISTINCT city FROM station WHERE city REGEXP '^[aeiou]';```
   - **Description**:
     - Use the regular expression REGXP to resolve it 
     - Another query to resolve this problem, but it will make the query longer and not approach the main purpose of this practice: [vowels_start_city.sql](SQL/Basic/vowels_start_city.sql)

### Intermediate
1. **Shortest_Longtest City Name**: Query the two cities in STATION with the shortest and longest CITY names.
   - **Solution File:** [SubQuery_MAX_LENGTH.sql](SQL/Intermediate/SubQuery_MAX_LENGTH.sql)
   - **Description:**
     - Retrieve the city with the shortest & longest name length.
     - If there are multiple cities with the same length, return the one that comes first alphabetically.
     - Write two separate queries, to get desired output. It need not be a single query.

2. **The second problem**: Updating

### Advanced
- (Add content for hard-level problems)
