# General Services

Table Of Content

---

1.[Checking For Previous LIKE/DISLIKE/NOTIFICATION/COMMENT/VIEW On target Bazzar/Mall/Product/Store](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-true)

2.[Login](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#login)

3.[Register](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#register)

4.[Forget Password](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#forget-password)

5.[Home Page Images](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#home-page-image)

6.[Popular Bazzars](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#popular-bazzars)

7.[About Us](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#about-us)

8.[Contact Us Data](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#contact-us)

9.[Send Support Message](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#send-support-message)

10.[Main Search](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#main-search)

11.[Get Countries](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#get-countries)

12.[Get States](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#get-states)

13.[Get Cities](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#get-cities)

14.[Get Hoods](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#get-hoods)

15.[Get One Bazzar](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#get-one-bazzar)

16.[Get One Mall](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#get-one-mall)

17.[Get One Store](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#get-one-store)

18.[Get One Product](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#get-one-product)

19.[Check Activation Code](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#check-activation-code)

20.[New Activation Code](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#new-activation-code)

21.[New Token](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#new-token)

22.[Is Login](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#is-login)

23.[Bazzar Categories](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#bazzar-categories)

24.[Bazzar View](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#bazzar-view)

25.[Mall View](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#mall-view)

26.[Store View](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#store-view)

27.[Product View](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#product-view)

28.[Store Register](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#store-register)

29.[Store Manager and Seller Login](https://github.com/mosi1994/hojreapi-doc/blob/master/GENERAL.md#store-login)



**Send Support Message**
----

* **URL**

```  
        https://api.hojrenama.com/web/static/send-contact-message
```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
name:Mostafa
email:maksdgas@asdasd.com
text:texst
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "Your Message Has been Sent",
            "data": ""
        }

    ```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---

**Contact Us Data**
----

* **URL**

```  
        https://api.hojrenama.com/web/static/contact
```  
    
* **Method:**
 ```  
GET
 ```
*  **URL Params**

```

```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
                {
                    "status": "success",
                    "message": "Contact Us Text",
                    "data": {
                        "text": "This is Contact US Text",
                        "phone": "021-22334455",
                        "email": "info@hojrenama.com",
                        "website": "https://hojrenama.com",
                        "company": "hojrenama",
                        "longitude": "51.2324",
                        "latitude": "31.12213"
                    }
                }

    ```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---



**About Us**
----

* **URL**

```  
        https://api.hojrenama.com/web/static/about
```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```

```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
                {
                    "status": "success",
                    "message": "About Us Text",
                    "data": {
                        "text": "This is About Text"
                    }
                }

    ```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---



**Home Page Image**
----

* **URL**

```  
        https://api.hojrenama.com/web/static/slider
```  
    
* **Method:**
 ```  
GET
 ```
*  **URL Params**

```

```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
                {
                    "status": "success",
                    "message": "Slider Images",
                    "data": {
                        "1": "img/slider1.jpg",
                        "2": "img/slider1.jpg",
                        "3": "img/slider1.jpg"
                    }
                }

    ```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---

**Popular Bazzars**
----

* **URL**

```  
        https://api.hojrenama.com/web/bazzar-categories
```  
    
* **Method:**
 ```  
GET
 ```
*  **URL Params**

```

```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
                {
                    "items": [
                        {
                            "id": 5,
                            "title": "Building Materials",
                            "image": "img/material.jpg"
                        },
                        {
                            "id": 6,
                            "title": "Car Tools",
                            "image": "img/car.jpg"
                        },
                        {
                            "id": 8,
                            "title": "Clothes and Fashion",
                            "image": "img/fashio.jpg"
                        },
                        {
                            "id": 1,
                            "title": "Digital",
                            "image": "img/digital.jpg"
                        },
                        {
                            "id": 4,
                            "title": "Furniture",
                            "image": "img/mobleman.jpg"
                        },
                        {
                            "id": 2,
                            "title": "Plants",
                            "image": "img/plants.jpg"
                        },
                        {
                            "id": 3,
                            "title": "Sports Cars",
                            "image": "img/sportscar.jpg"
                        },
                        {
                            "id": 7,
                            "title": "Vehicles",
                            "image": "img/car.jpg"
                        }
                    ],
                    "_links": {
                        "self": {
                            "href": "http://localhost/hojreapi/web/bazzar-categories?page=1&per-page=300"
                        }
                    },
                    "_meta": {
                        "totalCount": 8,
                        "pageCount": 1,
                        "currentPage": 1,
                        "perPage": 300
                    }
                }

    ```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---

**Check Activation Code**
----

* **URL**

```  
        https://api.hojrenama.com/web/user/checkactivationcode
```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
@username => Cellphone
@code => integer [10000 - 99999]
@x => Longitude
@y => Latitude
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
        "status": "success",
        "message": "User is Activated",
        "data": ""
        }

    ```

* **Error Response:**
    ```
    {
        "status": "error",
        "message": "Incorrect Code",
        "data": ""
        }
           
   
    ```
 
* **Notes:**


---


**New Activation Code**
----

* **URL**

```  
        https://api.hojrenama.com/web/user/newactivationcode
```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
@username => Cellphone
@x => Longitude
@y => Latitude

```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
        "status": "success",
        "message": "New Activation Code Generated",
        "data": ""
        }

    ```

* **Error Response:**
    ```
            {
        "status": "error",
        "message": "User is Activated",
        "data": ""
        }
        {
        "status": "error",
        "message": "User is not registered",
        "data": ""
        }
    
    ```
 
* **Notes:**


---

**New Token**
----

* **URL**

```  
        https://api.hojrenama.com/web/user/newtoken
```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
@username => Cellphone
@token => Access Token
@x => Longitude
@y => Latitude
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
        "status": "success",
        "message": "Token Updated",
        "data": {
        "id": 7617,
        "username": "09123566777",
        "token": "eJ-m_XcEeRPOz5ruWGkmfPbX2gAGMwoP"
        }
        }

    ```

* **Error Response:**
    ```
        {
        "status": "error",
        "message": "Token is not valid",
        "data": ""
        }
    
    ```
 
* **Notes:**


---

**Is Login**
----

* **URL**

```  
        https://api.hojrenama.com/web/user/islogin
```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
@username => Cellphone
@token => Access Token
@x => Longitude
@y => Latitude
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
        "status": "success",
        "message": "Token is true",
        "data": ""
        }

    ```

* **Error Response:**
    ```
        {
        "status": "error",
        "message": "Token is not valid",
        "data": ""
        }
    
    ```
 
* **Notes:**


---



**Forget Password**
----

* **URL**

```  
        https://api.hojrenama.com/web/user/forget
```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
@username => CellPhone
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```

        {
        "status": "success",
        "message": "New Password generated and sent ",
        "data": ""
        }
    ```

* **Error Response:**
    ```
            {
        "status": "error",
        "message": "User Not Found",
        "data": ""
        }
    
    ```
 
* **Notes:**


---

---

**Register**
----

* **URL**

```  
        https://api.hojrenama.com/web/user/register

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
        "message": "User intial register is done",
        "id": 7617,
        "username": "09123566777"
        }
    ```

* **Error Response:**
    ```
              {
                "status": "error",
                "message": "Cellphone already registered but not activatad",
                "data": -1
                }
                {
                "status": "error",
                "message": "Cellphone already existed",
                "data": ""
                }
                {
                "status": "error",
                "message": "Cellphone is not validated",
                "data": ""
                }
                {
                "status": "error",
                "message": "Username or Password cannot be blank.",
                "data": ""
                }
                {
                "status": "error",
                "message": “Cant Validate Data",
                "data": ""
                }
                {
                "status": "error",
                "message": "Server Error",
                "data": ""
                }

    
    
    ```
 
* **Notes:**


---

---

**Store Login**
----

* **URL**

```  
        https://api.hojrenama.com/web/user/store-login

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
                    "message": "You are not seller or store manager",
                    "data": ""
                }
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
