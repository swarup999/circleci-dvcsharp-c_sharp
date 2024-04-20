# API Usage

The *DVCSharp* application supports RESTful APIs to perform various operations such as:

* Register User
    * Start here to create a user in the application.
    * Change the membership type to Admin to create a Admin user
* Authentication and get access token
    * Use the info you created the account with to POST to the application in order to get a bearer token.
    * Set the Postman environment variable to be the bearer token.
    * Authenticate with the Admin account you created to get an Admin level token and then adding it to the Postman variable
* Get token info
* Update user
* Import user
* Delete user
* SSO authentication to get access token
* Password reset
* List products
* Create products
* Export products
* Generic import entities

[Download Postman Collection](DVCSharp-API.postman_collection.json)