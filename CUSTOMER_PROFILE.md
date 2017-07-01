*Customer Web Services*

Table of contents
---
1. [Chat Logs](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#chat-logs) 

2. [Chat Messages](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#chat-messages) 

3. [Broadcasts](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#broadcasts) 

4. [Store Messages](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#store-messages) 

5. [Submit Store-Messages](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#submit-store-messages) 

6. [Bazzar User Comments](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#bazzar-user-comments) 

7. [Mall User Comments](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#mall-user-comments) 

8. [Store User Comments](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#store-user-comments) 

9. [Product User Comments](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#product-user-comments) 

10. [User User Comments](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#user-user-comments) 

11. [Add Comment](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#add-comment) 

12. [Add Notification](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#add-notification) 

13. [Read Offer](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#read-offer) 

14. [Bazzar User Notification](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#bazzar-user-notifcation) 

15. [Mall User Notification](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#mall-user-notifcation) 

16. [Store User Notification](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#store-user-notifcation) 

17. [Product User Notification](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#product-user-notifcation) 

18. [Bazzar User Like](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#bazzar-user-like) 

19. [Store User Like](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#store-user-like) 

20. [Mall User Like](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#mall-user-like) 

21. [Product User Like](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#product-user-like) 

22. [Bazzar User Dislike](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#bazzar-user-dislike) 

23. [Mall User Dislike](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#mall-user-dislike) 

24. [Store User Dislike](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#store-user-dislike) 

25. [Product User Dislike](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#product-user-dislike) 

26. [Bazzar User Favorite](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#bazzar-user-favorite) 

27. [Mall User Favorite](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#mall-user-favorite) 

28. [Store User Favorite](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#store-user-favorite) 

29. [Product User Favorite](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#product-user-favorite) 

30. [Bazzar User View](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#bazzar-user-view) 

30. [Mall User View](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#mall-user-view) 

31. [Store User View](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#store-user-view) 

32. [Product User View](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#product-user-view) 

33. [View Offers](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#view-offers) 

34. [Edit Profile](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#edit-profile) 

35. [Add Like](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#add-like) 

36. [Add Dislike](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#add-dislike) 

37. [Add Favorite](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#add-favorite) 

38. [Add View](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#add-view) 

39. [Delete Favorite](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#delete-favorite) 

40. [Delete Notification](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#delete-notifcation) 

41. [Delete Like](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#delete-like) 

42. [Delete Dislike](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#delete-dislike) 

43. [Change Password](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#change-password) 



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
perPage:10
page:2
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

**Chat Messages**
----

* **URL**

```  
    https://api.hojrenama.com/web/main-chats
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
id:7
perPage:10
page:2
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
               {
    "items": [
        {
            "id": 4,
            "sender": "Mostafa Azizi",
            "text": "test4",
            "sentDate": 1497088004,
            "status": "sent",
            "chat": 7,
            "senderId": 1,
            "senderAvatar": "defaults/avatars/4.png"
        },
        {
            "id": 3,
            "sender": "Jasem Eshghi",
            "text": "test3",
            "sentDate": 1497088003,
            "status": "sent",
            "chat": 7,
            "senderId": 4,
            "senderAvatar": "img/defaults/avatars/51.png"
        },
        {
            "id": 2,
            "sender": "Jasem Eshghi",
            "text": "test2",
            "sentDate": 1497088001,
            "status": "sent",
            "chat": 7,
            "senderId": 4,
            "senderAvatar": "img/defaults/avatars/51.png"
        },
        {
            "id": 1,
            "sender": "Mostafa Azizi",
            "text": "test",
            "sentDate": 1497088000,
            "status": "sent",
            "chat": 7,
            "senderId": 1,
            "senderAvatar": "defaults/avatars/4.png"
        }
    ],
    "_links": {
        "self": {
            "href": "http://localhost/hojreapi/web/main-chats?username=09121111111&token=x8FRh4z7_TG_WA3ZLWtuMIVtJAnQBnk9&id=7&page=1&per-page=300"
        }
    },
    "_meta": {
        "totalCount": 4,
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
        "message": "there is no chat for u",
        "data": ""
        }  
        
        OR 
        
        {
            "status": "error",
            "message": "not login",
            "data": ""
        }
    ```
 
* **Notes:**


---

