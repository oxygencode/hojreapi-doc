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
