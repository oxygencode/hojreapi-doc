#General Services
----

***Table Of Content***
----

1. [Checking For Previous LIKE/DISLIKE/NOTIFICATION/COMMENT/VIEW On target Bazzar/Mall/Product/Store](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)


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
