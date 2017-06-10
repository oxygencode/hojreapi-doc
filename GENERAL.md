#General Services

###Table List

1. Register New Customer [Go](https://google.com)




####Register New Customer

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

