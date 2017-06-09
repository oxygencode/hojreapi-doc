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
    **Content:** `{ id : 12 }`
 
* **Error Response:**

  <_Most endpoints will have many ways they can fail. From unauthorized access, to wrongful parameters etc. All of those should be liste d here. It might seem repetitive, but it helps prevent assumptions from being made where they should be._>

  * **Code:** 401 UNAUTHORIZED <br />
    **Content:** `{ error : "Log in" }`

  OR

  * **Code:** 422 UNPROCESSABLE ENTRY <br />
    **Content:** `{ error : "Email Invalid" }`

* **Sample Call:**

  <_Just a sample call to your endpoint in a runnable format ($.ajax call or a curl request) - this makes life easier and more predictable._> 

* **Notes:**
@ => Cellphone
@password  => Min length 6 
@x => Longitude
@y => Latitude 

  <_This is where all uncertainties, commentary, discussion etc. can go. I recommend timestamping and identifying oneself when leaving comments here._> 