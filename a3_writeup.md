# Assignment 3 - Writeup

Assignment 3 is all about creating this natural language query system.  In order to do so, you have to write a lot of functions to retrieve infomation.  You will also have to write a function to return answers from a pattern-action list.  There is a lot of work to accomplish in this assignment, but this portion is intended for you to write about what you accomplished.

## Reflection Questions
1. In your own words describe the `search_pa_list` function.
The search_pa_list main function is just to intake what the user is requestion. The the function iterates through the lists to find if there's a match in the source. If a match is found it appeneds it into the result list and then outputs the statement, if there is not a match it just retuns nothing (an empty list). 


2. What movie did you add to the `movies.py` file?  What year was it made? Any specific reason you added that movie?
I added Spider-Man Across The Spider Verse which was made in 2023. I added it because I love the movie, if you havn't watched it yo have to. 

3. What pattern / action did you add to the paList data structure?  Why do you think that is a useful pattern / action?
I added movie a function movie_by_actor which then allowed me to add what movies were acted by to the paList data structure. i think it's useful because it allows you to find out wha movies an actor has been in. This would be more useful in a bigger movie database. 

4. What is chatbot would you create that would be like this?  Describe why you would create it and what it would do.
I would create a chatbot that would be able to write parodies to songs because I think it would be really funny and would just use it to make popular songs goofy. 

5. What was the most difficult portion of this assignment?
Tracing the code back to see what's wrong when something doesn't work. 

6. Did you write a new assert for your pattern action?
Yes, assert isinstance(movie_by_actor(["Oscar Isaac"]),list), "movie_by_actor not returning a list"


