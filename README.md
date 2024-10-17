# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


## Checks for Understanding

1. Define CRUD.
 > Create, read, update, delete
2. Define MVC.
 > Model - store data in a specific way, view - view the data in a specific way, control - manipulate the data
3. What two files would you need to create/modify for a Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.
 > route to tell the reciever how to handle the request, controller to present the data
4. What are params? Where do they come from?
 > params - parameters, user supplied but can be set as hard params to protect data from being inputed or manipulated incorrectly 
5. What is the purpose of a serializer?
 > serializer is used to strip the view of undesired attributes of your table
