# data
 task report day 5
 Building a Basic REST API with Flask:
Topics:
● REST API design principles
● Flask route methods (GET, POST, PUT, DELETE)
● Handling JSON data and request parameters
● Writing basic CRUD endpoints (Create, Read, Update, Delete)

 Step 1:  REST API (Representational State Transfer API) is a type of application programming interface (API) that helps web service applications communicate with each other. design principles for REST APIs: Statelessness:- Each REST message contains all the information necessary to understand it. Uniform interface:- All client types should have a standard way to interact with a server. This simplifies the system's architecture. Layered system:- The API should be designed as a layered system, with each layer providing a specific set of functionalities. This allows for flexibility because layers can be added, removed, or modified without affecting the rest of the system.
 Client-server:- The user interface is separated from the data storage tasks, making it more portable. All components use a single uniform interface, simplifying how the applications interact with the API. Code on demand:-  Servers can temporarily extend or customize client functionality by transferring software programming code to the client. Cacheability:-  Responses from the server can be marked POSTas cacheable or non-cacheable. Caching enhances performance and reduces the need for repeated requests to the server. Versioning:- Versioning allows you to improve the representation for the resources of your API and alter behaviour between different clients.

 Step 2:  Get:- The Get method is commonly used to retrieve data from a server. Post:- POST method is commonly  used to submit data to server, Put:- The PUT method is commonly used to update an existing  resource on the server. Delete:-THE DELETE method is commonly used to request the  server to delete a resource. 

Step 3:  Handling JSON (JavaScript Object Notation) is the process of working with a data format that is used to store and transmit data: Request parameters, also known as query parameters or URL parameters, are key-value pairs that are appended to the URL when making an HTTP request. Parameters are used to pass and add additional information to a request.  can use parameters as part of the URL or in the headers.

Step 4:  Create: Adding new data or objects to the application. Read: Retrieving or fetching data from the application. Update: Modifying existing data within the application. Delete: Removing data from the application.

Activities:
1. Create a Flask API with endpoints for a simple data model (e.g.,a "Books" API with title, author, year fields).
2. Implement CRUD operations to interact with the data model.
3. Test API endpoints using a tool like Postman or Curl.
4. Recommended resources: Postman documentation, REST API tutorials with Flask.

Step 1:  Create a Flask API with endpoints for a simple data model: create a basic Flask application with a "Books" data model.  

Step 2:  Implement CRUD operations to interact with the data model: Add the endpoints for Create, Read, Update, and Delete operations. 1. Create a Book (POST request),2. Read all Books (GET request), 3. Read a specific Book by ID (GET request),4. Update a Book by ID (PUT request),5. Delete a Book by ID (DELETE request),

Step 3:  Test API endpoints using a tool like Postman or Curl: Testing with Curl To test the API, For example: Create a book:, Get all books:, Update a book:,Testing with Postman.

Step 4:  Postman Documentation,




