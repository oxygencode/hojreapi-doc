General Services
----

Table List
----

1. Register New Customer : [Go](https://google.com)

2. Activate New Customer : [Go](https://google.com)

3. User Login  : [Go](https://google.com)

4. Check User is Login : [Go](https://google.com)

5. Forget Password : [Go](https://google.com)

6. Generate and Send New Activation Code : [Go](https://google.com)

7. Update Token : [Go](https://google.com)

8. [Checking For Previous LIKE/DISLIKE/NOTIFICATION/COMMENT/VIEW On target Bazzar/Mall/Product/Store](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)


Register New Customer
----

* **URL**
    ```
    web/user/register
    ```

* **Method:**
  
  ```
  GET
  ```
*  **URL Params**

   **Required:**
    ```
    @username=[String]
    @password=[String]
    ```
   **Optional:**
   ```
   @x=[String]
   @y=[String]
    ```
   
 
* **Success Response:**
  
  * **Code:** 200 <br />
    **Content:** 
    ```
    {
                  "status": "success",
                  "message": "User intial register is done",
                  "id": 7617,
                  "username": "09123566777"
    }
    ```
 
* **Error Response:**

**Content:**
```
{
"status": "error",
"message": "Username or Password cannot be blank.",
"data": ""
}
```

OR

```
{
"status": "error",
"message": "Cellphone is not validated",
"data": ""
}
```

OR

```
{
"status": "error",
"message": "Cellphone already existed",
"data": ""
}
```

OR 

```
{
"status": "error",
"message": "Cellphone already registered but not activatad",
"data": -1
}
```

OR 

```
{
"status": "error",
"message": “Cant Validate Data",
"data": ""
}
```

OR 

```
{
"status": "error",
"message": "Server Error",
"data": ""
}
```


* **Sample Call:**

  <_Just a sample call to your endpoint in a runnable format ($.ajax call or a curl request) - this makes life easier and more predictable._> 

* **Notes:**

Activate New Customer
----

User Login
----

Check User is Login
----

Forget Password
----

Generate and Send New Activation Code
----

Update Token
----

----

**Is True**

----

* **URL**
    ```
    https://api.hojrenama.com/web/user/is-true

```

* **Method:**
  
  ```
  POST
  ```
*  **URL Params**

   ```
    username:09121122777
    token:abdcdefghijklmno
    x:35.235564
    y:45.234523
    type:like
    target:bazzar
    id:13

   ```
   
 
* **Success Response:**
  
  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "Liked",
            "data": ""
        }
    ```
 
* **Error Response:**

**Content:**
```
{
    "status": "error",
    "message": "Not Liked",
    "data": ""
}
```

OR

```
{
    "status": "error",
    "message": "Invalid Target",
    "data": ""
}
```

OR

```
{
    "status": "error",
    "message": "Not favorite",
    "data": ""
}
```

OR 

```
{
    "status": "error",
    "message": "Not dislike",
    "data": ""
}
```

OR 

```
{
    "status": "error",
    "message": "Not notifcation",
    "data": ""
}
```

OR 

```
{
    "status": "error",
    "message": "Not view",
    "data": ""
}
```
OR

```
{
    "status": "error",
    "message": "Invalid Type",
    "data": ""
}
```
OR

```
{
    "status": "error",
    "message": "Not Login",
    "data": ""
}
```

* **Sample Call:**

  <_Just a sample call to your endpoint in a runnable format ($.ajax call or a curl request) - this makes life easier and more predictable._> 

* **Notes:**
This function is used for checking that target ( bazzar / mall / store / product ) is (liked/disliked/viewed/commented/notifcaioned/favorited ) by current user or not .
---
