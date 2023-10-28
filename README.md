# Rust Auth API

In this project I'm gonna develop an API in which anyone can register and login with their user. And they could also make a simple GET request for testing their authentication.

Down below you can see the requisits for the creation of you user, and the requisits for the login of your user.

**For this project I'll using**:

* Rust
* Redis
* Docker
* PostgreSQL
* JWT

# Entities

#### **For User Registration**:

* username: String
* user_email: String
* user_password: String

#### **For User Login**:

* user_email: String
* user_password: String

# List of possible requests

* POST -> /api/login
* POST -> /api/register
* GET -> /api/authtest
* DELETE -> /api/{username}
* PUT -> /api/{username}/changepassword 







