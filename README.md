# Login

_italics_
***bold***


Users Sign Up

Path: POST '/users/signup'
Params:
email: a string
password: a string
user name: a string
full name: a string
Response:
Status Code: 201 if successful, 422 if unsuccessful
Example success:
  { "user":{
    "id":5,
    "username":"whitney_hoggs",
    "full_name":"Whitney Hoggs",
    "email":"whitney1@gmail.com",
    "access_token":"03c0b80efbe2b23a2c0764599ad60015"}
  }
Example Failure: {"errors":["Email has already been taken"]}
