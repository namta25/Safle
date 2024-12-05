# Safle

## About the App
  I have built a NodeJS application that simulates a basic 'task manager'. It has 2 basic API's:  
  
    1.GET /tasks - Fetches and returns all tasks stored in the database (mongodB) as a JSON array.  
    2.POST /tasks - Accepts a task name in the request body, validates it, creates a new task in the database, and returns the created task as a JSON response.

## Lets get the app to run locally! here's how: 
**PREREQUISITES**

  Make sure you have docker desktop intalled on your laptop or visit -> https://www.docker.com/products/docker-desktop/  

Now run the following commands to initalise your local environment to get the app running for you.
```
   git clone https://github.com/namta25/safle-api.git
```
```
   cd safle-api
```
```
   docker-compose build
```
```
   docker-compose up -d
```
on your browser now open -> http://localhost:3000

There you have it, the task manager on your laptop! :smile: :rocket: :tada:
