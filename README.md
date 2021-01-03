# API Documentation
# Link =>```https://auth-backend-api.herokuapp.com/api```

## ```/users```

# POST ```/login```
 ``` returns user token```
 ``` { 
 "email": "example@gmail.com", 
 "password": "enter password"
 ```
# POST ```/register```
 ``` returns registered user (Object)```
 ``` { 
  "username": "enter username", 
  "email": "enter email",
  "password": "enter password",
  "password2": "confirm password" 
  ```

# POST ```/current```
 ``` returns current logged in user (Object)```
```{
"token": "Bearer + token"
```
