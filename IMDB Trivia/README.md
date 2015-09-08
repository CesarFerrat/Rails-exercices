Movie Trivia Game!
Let's create a movie quiz Web app!!

Use Sinatra to create the Web application. So far, you only know about that one, hehe.
Use the IMDB gem to get the movie information.
Use RSpec to test your classes.
Go step by step. Don't get ahead of yourself! Move forward only when you finish the previous step!

Make a search and show 9 movie posters!

Create a page that will ask for a search term in an input field.
When the user submits the form, it should make a POST request to another page that searches IMDB with that search term.
Narrow down the search results to the first 9 movies.
Show the posters of those 9 results.
Make sure that there are always 9 posters

Trivia game about the movies!

Now choose a question to ask the user about one those 9 movies. For example, you could ask "Which movie was released in 1999?"

Choose one question that you will always ask.
Show the question on the page where you show the 9 posters.
Get the answer for each the 9 movies and store them for another request.
Create a button for each movie to select it as the answer. You could place the button each poster, for example.
The button should do a new request that would check whether or not that movie is the answer.
Redirect to a page that tells you whether you were right or not.
Make sure there is only one correct answer

Classes and methods

If you had any, remove all the logic inside the GET and POST requests. You should only be instantiating a class and calling a method on each of them. Or a few methods maximum.

Create the classes and methods that you need. Separate different behaviour in different classes. Don't put every method in one huge class. One class should be responsible for handling all the search results and returning only the results we want.

Test those classes

Create the specs to test that the classes and methods work properly. Create a file for each class. Require it where you want to use it. There should be a spec file that requires the files with the classes and checks them.

Recommendation: Use stubs if there is a dependency on IMDB gem because every query you make can last forever

Make images clickable

Can you think of a way to be able to choose your answer by selecting the image instead of the button? Try it out!

More questions

Create more questions to ask about the movies. Choose one answer randomly and choose the answer for that one. Show that question on the page.

Make sure there is only one correct answer

No search query

Show 9 random movies that you can search with a random word for example. Do not expect the user to ask you for a word.

The whole Quiz!

After answering a question you get the answer. Store if that was correct or not. Ask the user if he/she wants another question and show it to him/her. When he decides to stop anwering. Show him the total score!