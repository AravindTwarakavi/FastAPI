Basic FastAPI Project

API (Application Programming Interface) for Web Applications
	It is like a waiter in a restaurant who takes the order and approaches the chef in the kitchen with the request. Then take the order from the kitchen as response and deliver it back to the customer.
APIs interact with data in 4 main methods
-	Create
-	Read
-	Update
-	Delete

1.	Create: Done using POST method. Telling the API that we need to do something new.
2.	Read: Done using GET method. Asking to show some piece of information.
3.	Update: Done using PUT or PATCH methods. Asking to update the existing value with a new value.
4.	Delete: Done using DELETE method. To delete some piece of information.

API is usually connected to a database. All the tasks that are to be executed can be stored in the database. But here we’re only going to develop for learning purposes we will use an in-memory database (which means all the data is lost when the system is off).
