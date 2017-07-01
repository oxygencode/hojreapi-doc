*Customer Web Services*

Table of contents
---
1. [Chat Logs](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#chat-logs) 

2. [Chat Messages](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#chat-messages) 



**Chat Logs**
----

* **URL**

```  
    https://api.hojrenama.com/web/chats
```  
    
* **Method:**
 ```  
GET
 ```
*  **URL Params**

```
username:09121122777
token:abdcdefghijklmno
x:35.235564
y:45.234523
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
               {
            "items": [
                {
                    "id": 1,
                    "user": 1,
                    "seller": "محمد تستتسی س",
                    "startDate": 1497088000,
                    "status": "pending",
                    "store": "تست",
                    "storeId": 1,
                    "sellerAvatar": "img/defaults/avatars/51.png"
                },
                {
                    "id": 2,
                    "user": 1,
                    "seller": "محمد تستتسی س",
                    "startDate": 1497088000,
                    "status": "pending",
                    "store": "تست",
                    "storeId": 1,
                    "sellerAvatar": "img/defaults/avatars/51.png"
                },
                {
                    "id": 3,
                    "user": 1,
                    "seller": "محمد تستتسی س",
                    "startDate": 1497088000,
                    "status": "pending",
                    "store": "تست",
                    "storeId": 1,
                    "sellerAvatar": "img/defaults/avatars/51.png"
                },
                {
                    "id": 4,
                    "user": 1,
                    "seller": "محمد تستتسی س",
                    "startDate": 1497088000,
                    "status": "finished",
                    "store": "تست",
                    "storeId": 1,
                    "sellerAvatar": "img/defaults/avatars/51.png"
                },
                {
                    "id": 5,
                    "user": 1,
                    "seller": "محمد تستتسی س",
                    "startDate": 1497088000,
                    "status": "chatting",
                    "store": "تست",
                    "storeId": 1,
                    "sellerAvatar": "img/defaults/avatars/51.png"
                },
                {
                    "id": 6,
                    "user": 1,
                    "seller": "محمد تستتسی س",
                    "startDate": 1497088000,
                    "status": "chatting",
                    "store": "تست",
                    "storeId": 1,
                    "sellerAvatar": "img/defaults/avatars/51.png"
                },
                {
                    "id": 7,
                    "user": 1,
                    "seller": "محمد تستتسی س",
                    "startDate": 1497088000,
                    "status": "finished",
                    "store": "تست",
                    "storeId": 1,
                    "sellerAvatar": "img/defaults/avatars/51.png"
                }
            ],
            "_links": {
                "self": {
                    "href": "http://localhost/hojreapi/web/chats?username=09121111111&token=x8FRh4z7_TG_WA3ZLWtuMIVtJAnQBnk9&page=1&per-page=300"
                }
            },
            "_meta": {
                "totalCount": 7,
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
