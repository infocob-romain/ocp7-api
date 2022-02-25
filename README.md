[![Codacy Badge](https://app.codacy.com/project/badge/Grade/1faf2041e6124da599eb1889426c9902)](https://www.codacy.com/gh/thaydan/ocp7/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=thaydan/ocp7&amp;utm_campaign=Badge_Grade)

# ocp7

BileMo is a BTB smartphone provider, when you have a client account with us, you can access the list of smartphones we offer through our API. You also have the possibility to manage your customers directly from our API. 
Here is how to use it.

## Read the API documentation
To know all about the request entries, the parameters and make tests, go to the documentation by accessing : /api/doc

## Get a JWT authentication token
Send a GET or POST request with json content to /api/login_check

Example :
{
    "username":"your_login",
    "password":"your_password"
}

This will return your token.

## Add your token in your requests
[explain]

## Make a request
Exemple :

