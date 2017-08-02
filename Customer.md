# Customer Web Services

Table Of Content

---

1.[Get user information](https://github.com/mosi1994/hojreapi-doc/blob/master/Customer.md#get-user-information)

2.[Edit user information](https://github.com/mosi1994/hojreapi-doc/blob/master/Customer.md#edit-user-information)

3.[Forget Password](https://github.com/mosi1994/hojreapi-doc/blob/master/Customer.md#forget-password)


----

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
username:09335556196
```

* **Success Response:**
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
    "message": "Some Error Message In Your Language",
    "data": ""
}
```
 
* **Notes:**


---


**Get User Information**
----

* **URL**

```  
https://api.hojrenama.com/web/users
```  
    
* **Method:**
```  
GET
```
*  **URL Params**

```

token:nM-mZws3oL2WpSKuY10gpTccVMhhvm8a
username:09335556196
x:31.1213213
y:51.2131455

```

* **Success Response:**
```

{
    "items": [
        {
            "id": 1,
            "cellPhone": "09335556196",
            "email": "info@hojrenama.com",
            "name": "Mostafa",
            "family": "Azizi",
            "phone": "02133778865",
            "address": null,
            "city": null,
            "state": null,
            "role": 8,
            "country": 102,
            "hood": null,
            "instagram": null,
            "telegramChannell": null,
            "telegram": null,
            "linkedin": null,
            "facebook": null,
            "twitter": null,
            "googleplus": null,
            "website": null,
            "avatar": "img/defaults/avatars/51.png",
            "gender": "male"
        }
    ],
    "_links": {
        "self": {
            "href": "http://localhost/hojreapi/web/users?token=nM-mZws3oL2WpSKuY10gpTccVMhhvm8a&username=09335556196&x=&y=&page=1&per-page=300"
        }
    },
    "_meta": {
        "totalCount": 1,
        "pageCount": 1,
        "currentPage": 1,
        "perPage": 300
    }
}
               
```

* **Error Response:**
```

{
    "status": "error",
    "message": "Some Error Message In Your Language",
    "data": ""
}

```
 
* **Notes:**


---




**Edit User Information**
----

* **URL**

```  
https://api.hojrenama.com/web/user/edit
```  
    
* **Method:**
```  
POST
```
*  **URL Params**

```

username:09121111111
token:Jd6RQb0oW2XzmpUOmoWK5PdE96q6sqXL
x:31.123123
y:51.123123
User[name]:mostafa
User[family]:hasanabadi
User[phone]:02133835516
User[email]:mhiusadh@asada.com
User[state]:1
User[city]:19
User[hood]:402
User[address]:sadias daksghasjudw
User[age]:53
User[gender]:male
User[telegram]:
User[twitter]:
User[linkedin]:
User[facebook]:
User[instagram]:
User[googleplus]:
User[website]:
User[avatar]:

```

* **Success Response:**
```

{
    "status": "success",
    "message": "updated successfully",
    "data": ""
}
               
```

* **Error Response:**
```

{
    "status": "error",
    "message": "Some Error Message In Your Language",
    "data": ""
}

```
 
* **Notes:**


---

