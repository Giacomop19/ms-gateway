# Express Gateway

Creating a gateway use of for 2 or more microservices:
  - to do list
  - user

Struct : 

            CLIENT 
              |
        API GATEWAY :8080
              |
        --------------
        |            |
    TO-DO LIST      USER
      :8081         :8081
    



# Express.js API example

The `api` uri preceed **all** API endpoints and the following endpoints are currently available

* GET `/api/tasks` - get all the tasks
* POST `/api/tasks` - insert a brand new task
* GET `/api/tasks/:id` - get a specific task
* PUT `/api/tasks/:id` - update a specific task
* DELETE `/api/tasks/:id` - delete a specific task
