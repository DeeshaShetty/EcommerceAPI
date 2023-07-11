Ecommerce API Test This Java code performs API testing for an e-commerce application. It includes various API requests such as login, adding a product, creating an order, and deleting a product/order. The code uses the RestAssured library for making HTTP requests and handling responses. Prerequisites To run this code, you need to have the following dependencies set up: • RestAssured library • TestNG framework • Java SDK Getting Started To get started with this code, follow the instructions below:

Clone the repository or download the code files.
Open the code in your preferred Java development environment (e.g., Eclipse, IntelliJ).
Make sure you have the required dependencies mentioned above set up.
Update the code with appropriate values for the API endpoints, user credentials, and file paths as needed.
Compile and run the EcommerceAPITest class. Code Structure The code is structured as follows:
Importing necessary libraries and classes.
Setting up logging for request and response.
Performing the login request to obtain the authentication token and user ID.
Adding a product using the obtained token and user ID.
Creating an order with the added product.
Deleting the added product and order.
Asserting the response messages for successful deletion.
The code includes error handling and logging of request/response details. Logging The code logs the request and response details to a file named logging.txt. This can be useful for debugging and analysing the API interactions.
