# devops_project
This project consists of an app that uses Python and Django to utilize a todo list to complete tasks. This app uses the CRUD methology. 

The app uses POST requests to add titles of tasks to the DB. Python for loops through the DB and lists the items on the index page. 
To delete completed tasks, the app sets a variable to the ID of the posted requests and python uses a delete method to submit a delete request and redirect to the index page.