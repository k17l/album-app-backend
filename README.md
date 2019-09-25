#Back-end Developer Coding Challenge

## Demo of the application can be seen in the below URL

### https://album-app-backend.herokuapp.com/users(UnAuthenticated) - GET Request

### https://album-app-backend.herokuapp.com/authenticate - POST Request

- [ ] Sample Authentication Request:

Header : 
	"Content-Type" - application/json

Body : 
	{
	 	"username":"Kamren",
	  	"password":"mavennet"
	}

- [ ] Sample Authentication Response:

{
"token": "eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJLYW1yZW4iLCJpYXQiOjE1Njk0MjQ4NDksImV4cCI6MTU3MDAyOTY0OX0.2bt3axeKQ8S-he3cZe2Rivzepimh91alO4QCZAvCYdnAShFlY8Bj5PUHl69KkgVVhWPLVRLXh1JV8fcUgONUIw"
}


### https://album-app-backend.herokuapp.com/albums(Authenticated) - GET Request
### https://album-app-backend.herokuapp.com/photos(Authenticated) - GET Request
### https://album-app-backend.herokuapp.com/albums/1(Authenticated) - GET Request
### https://album-app-backend.herokuapp.com/photos/1(Authenticated) - GET Request


- [ ] Sample Header:

Header:
	"Content-Type" -  application/json
  "Authorization" -  Bearer eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJLYW1yZW4iLCJpYXQiOjE1Njk0MjQ4NDksImV4cCI6MTU3MDAyOTY0OX0.2bt3axeKQ8S-he3cZe2Rivzepimh91alO4QCZAvCYdnAShFlY8Bj5PUHl69KkgVVhWPLVRLXh1JV8fcUgONUIw








## Goal:

#### Develop a Back-end app that allows a user to see their albums and its' associated photographs

- [ ] Fork this repo. Keep it public until we have been able to review it.
- [ ] Web : Node.js/Java/C#/Go/any language you're comfortable with
- [ ] User/Albums/Photos structure similar to https://jsonplaceholder.typicode.com/
- [ ] App should restrict some routes and not others

### Evaluation:
- [ ] App operates as asked
- [ ] No crashes or bugs
- [ ] Follow Clean Code and SOLID principles
- [ ] Code is understandable and maintainable

Suggestion: 
- JWT, Cookies, etc for Authentication
- /users to fetch all users (unauthenticated)
- /albums to fetch all albums associated with the user (authenticated)
- /photos to fetch all photos associated with the user (authenticated)
- /albums/:id to return a specific album (authenticated)
- /photos/:id to return a specific photo (authenticated)
- Feel free to use frameworks
