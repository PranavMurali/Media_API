# Social Media Backend API
### A social media backend API, using Golang and a MongoDB backend. 

## Features:

### POST /users
Create a user object using name, email and password fields.
Password field is hashed and sent to mongo backend.
![alt](../main/readme/POST_users.png)

### GET /users/{id}
Get any user object using the user's ID
![alt](../main/readme/GET_user.png)

### POST /posts
Create a post object using caption, image URL and userID.
A server side timestamp is generated for the post.
![alt](../main/readme/POST_post.png)

### GET /posts/{id}
Get any post object using post ID.
![alt](../main/readme/GET_post.png)

### GET /posts/users/{id}
Get all of any user's posts using the user's ID.
![alt](../main/readme/GET_userposts.png)
