**LOGIN**
----

* **URL**

```  
    (https://api.hojrenama.com/web/user/login)
```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

1. **Required:**
```

@username=[String]
@password=[String]

```
2.   **Optional:**
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
        "message": "Login Success",
        "data": {
            "id": 7617,
            "username": "09123566777",
            "token": "6DaLwhDEyDA2jMYm4LyQ5mlZxhktWhu3"
        }
    }
    ```

* **Error Response:**
    ```
     {
         "status": "error",
         "message": "Username or Password is incorrect",
         "data": ""
       }
       
       OR
       
        {
           "status": "error",
           "message": "Cellphone already registered but not activatad",
           "data": -1
         }
         
         OR
         
         {
             "status": "error",
             "message": "User not found",
             "data": ""
           }
         
    ```
 
* **Notes:**

Username field is Cellphone
@password  => Min length 6 
@x => Longitude
@y => Latitude 

  <_This is where all uncertainties, commentary, discussion etc. can go. I recommend timestamping and identifying oneself when leaving comments here._> 