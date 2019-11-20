# sprinoauth2


->OAuth 2 is an authorization framework 

# DESCRIPTION

When user wants to login with with authotized access
  -> frist he request for login page 
  -> then when login page is delivered
  -> then user enter user details in login page
  -> then user request for login with user details and authorize access
  -> then it is checked that user is valid or not
  -> if user is valid then it redirect to the application
  -> then after authentication user requests to the application with valid user and authorized access
  -> then application send a request for access token to authorized server
  -> authorized server return an access token to the application
  -> then application can use that token for accessing data ( application request for getting data)
  -> then in resource server it is checked that token is valid or not
  -> if token is valid then data is returned to the application

# Pictorial representation is given in the below given video link

image->https://www.youtube.com/watch?v=L1PDqJkedZ0

description->https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2
