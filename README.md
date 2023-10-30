Java Shopping
--------------

Java console application has the following sections:
---------------------------------------------------
    1. Login - Existing User and Admin
    2. Register - New User
    3. Home - User
        * View Categories 
            - View products based on category.
            - Add products to cart.
        * View Products 
            - Add products to cart.
        * View Cart 
            - Check out products from cart.
        * View Order 
        * Logout

-> Java for coding 
-> 'CSV' file for storing and retrieving data.

Files used for each sections:
-----------------------------
    1. "User credential" file for storing user data.
    2. Invoice for every order will be generated.

Application  contains:
----------------------

    1. Used MVC (Model, View, Controller) architecture for developing the console application.
    2. Added the required Models, Views and Controller along with Interface implementation to achieve abstraction.
    3. Added user-defined exceptions to catch and handle the exceptions.
    4. Used encapsulation to hide data and used getter and setter for getting and setting the data for the models.
    5. Used "ArrayList" to store and manipulate data according to the user preferrences.
    6. Used "CSV" Files for handling data.
    7. Stored the file path, Scanner class other sensitive information in a separate Utility folder.
    8. Used Singleton pattern to avoid creating objects.
    9. Used "Date" class for handling date for orders.
    10. Handled exceptions for invalid choices.
