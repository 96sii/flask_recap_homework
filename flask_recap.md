# Flask Recap

This week we've built out the back end of an app and added data persistence in the form of PostgreSQL. This week we've been building the `M` in MVC.

![MVC](img/mvc.png)

Our next step will be to add Flask. Flask will provide us with the `V` and the `C`.

Let's review what Flask is and where it will fit in our applications.

Flask is a web framework for building web applications with Python. 

## Task

Your task is to review the Events App that we built last week. Ask yourself the following questions:

<!-- 1. What does the directory structure look like?  -->
Controllers | controller.py
Models | event_list.py event.py
Static | main.css
Templates | base.html index.html

<!-- 2. What are the different parts that make up the app? -->
Models, controller, view 


<!-- 3. What are controllers responsible for? -->
Controllers are responsible for binding the functionality of the models to the user's interaction with views.


<!-- 4. What are templates responsible for? -->
Templates are responsible for the content of the webpage shown to the user. They house the html which the customer sees and interacts with. 

<!-- 5. What is the static folder for? -->
To hold static files i.e. files that don't change and are the same regardless of which user is accessing it. css files are stored here as the webpage is styled the same for each user. 

<!-- 5. How do you think we will combine what we've done this week with Flask? -->
I think the next step would be to create an interactive webpage that can store data provided by a user in a web browser within a database so that the data persists even after the server has been rebooted. 

<!-- 6. How do you create a `route` in the controller? -->
By using the @app.route() method. For example, to creat a route called 'events' you would enter @app.route('/events'
)

<!-- 7. The `models/events.py` file acted as some dummy data for our app. This will no longer be necessary. Why is that the case? -->
Now that we can save data to a database we won't beed to create dummy data to make sure it's working correctly. We should hopefully be able to enter data on the front end that will persist. 


