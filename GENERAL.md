# General Services

Table Of Content

---

1.[Checking For Previous LIKE/DISLIKE/NOTIFICATION/COMMENT/VIEW On target Bazzar/Mall/Product/Store](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

2.[Login](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

3.[Register](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

4.[Forget Password](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

5.[Home Page Images](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

6.[Popular Bazzars](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

7.[About Us](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

8.[Contact Us Data](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

9.[Send Support Message](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

10.[Main Search](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

11.[Get Countries](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

12.[Get States](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

13.[Get Cities](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

14.[Get Hoods](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

15.[Get One Bazzar](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

16.[Get One Mall](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

17.[Get One Store](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

18.[Get One Product](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

19.[Check Activation Code](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

20.[New Activation Code](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

21.[New Token](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

22.[Is Login](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

23.[Bazzar Categories](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

24.[Bazzar View](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

25.[Mall View](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

26.[Store View](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

27.[Product View](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

28.[Store Register](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#store-register)


---

**Login**
----

* **URL**

```  
        https://api.hojrenama.com/web/user/login

```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
@username => Cellphone
@password => Min length 6
@x => Longitude
@y => Latitude
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
                
                {
                "status": "error",
                "message": " Cellphone already registered but not activatad ",
                "data": -1
                }
                
                {
                "status": "error",
                "message": " User not found ",
                "data": ""
                }

    
    
    ```
 
* **Notes:**


---

---

**Store Register**
----

* **URL**

```  
        https://api.hojrenama.com/web/user/store-register

```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
username:09112325628
password:123456
x:51.408364
y:35.708647
email:masada2@asdasdas.com
state:1
city:19
hood:402
phone:33835516
name:Mosadhsd
family:Hasnaabaidi
certificate:img/defaults/product.png
title:MOSIOUS-SHOP
address:Tehran
category:1
bazzar:26
mall:20
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "User intial register is done",
            "id": 12 ,
            "username": 0912345555
        }
    ```

* **Error Response:**
    ```
            {
                "status": "error",
                "message": "store has error",
                "data": ""
            }
            {
                "status": "error",
                "message": "Username or Password cannot be blank.",
                "data": ""
            }
            {
                "status": "error",
                "message": "Cellphone is not validated",
                "data": ""
            }
            {
                "status": "error",
                "message": "Server Error",
                "data": ""
            }
            {
                "status": "error",
                "message": "Cant validate data",
                "data": ""
            }
            {
                "status": "error",
                "message": "Cellphone or Email already existed",
                "data": ""
            }
           
    
    
    ```
 
* **Notes:**


---



---

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
    type:like  ( like , dislike , view , comment , notification , favorite )
    target:bazzar ( bazzar , mall , product , store )
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
 
* **Notes:**

This function is used for checking that target ( bazzar / mall / store / product ) is (liked/disliked/viewed/commented/notifcaioned/favorited ) by current user or not .

---
