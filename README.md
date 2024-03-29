# ProductCatalogMicroservice
 Manages Product listngs, details, Categorization
 Uses My SQL
 Follows MVC Architecture

 # Package Structure:

1. *models*: Contains classes that represent the data model of the application.
2. *controllers*: Contains classes that handle incoming requests and interact with the service layer.
3. *services*: Contains classes that implement the business logic of the application.
4. *repositories*: Contains classes that interact with the database.

# Flow Explanation:
1. *Controllers*: 
   - Handle incoming requests from the client.
   - Communicate with the service layer to retrieve data or perform actions.
   - Send responses back to the client.
2. *Services*:
   - Implement the business logic of the application.
   - Perform operations like fetching product details, browsing products by category, and searching for products.
   - Interact with repositories to retrieve or modify data.
3. *Repositories*:
   - Interact with the database to perform CRUD (Create, Read, Update, Delete) operations.
   - Responsible for querying and updating data in the database.


