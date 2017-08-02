# Customer Web Services

Table Of Content

---

1.[Get user information](https://github.com/mosi1994/hojreapi-doc/blob/master/Customer.md#get-user-information)



----



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
    "message": "Not Login",
    "data": ""
}

```
 
* **Notes:**


---
