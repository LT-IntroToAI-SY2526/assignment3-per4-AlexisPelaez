# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
One of the key programming concepts was experiments with loops-and-a-half and using a tracker variable to loop through a database. I had previous experience in Java but some of the aspects from converting that into python was troubling for me.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
The movie chatbot system takes a prompt(source) from the user and if it matches with one of the patterns, then it will run the function that correlates to that pattern and return an answer that answers the prompt. This keeps on going until the user types in "Bye" in order to end the program.

3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?

This may be used in chatbot assistants that may be on movie sites. They would prompt the user what kinds of movies they are looking for. Due to the many different prompts and functions that can go together, there are many possibilities and uses of databases in order to return an answer that users would like. If I could improve it, I would attempt to recommend a few movies to gauge what kind of movies the user is interested in.