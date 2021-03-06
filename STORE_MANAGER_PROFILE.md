*Store Manager Web Services*

Table of contents
---
1. [Edit Store Information](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#edit-store-information) 

2. [Add New Seller](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#add-new-seller) 

3. [List All My Sellers](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#list-all-my-sellers)

4. [Delete My Seller](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#delete-my-seller)

5. [Active Seller](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#active-seller)

6. [Edit Seller](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#edit-seller)

7. [Statistics](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#statistics)

8. [List All Store Messages](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#list-all-store-messages)

9. [Answer Store Message](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#answer-store-message)

10. [List All Offers](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#list-all-offers)

11. [List All Products](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#list-all-products)

12. [Add New Product](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#add-new-product)

13. [Delete Product](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#delete-product)

14. [Edit Product](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#edit-product)

15. [Add Store Gallery](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#add-store-gallery)

16. [Delete Store Gallery](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#delete-store-gallery)

17. [Physical Customers](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#physical-customers)

18. [Virtual Customers](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#virtual-customers)

19. [List All Chats](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#list-all-chats)

20. [List Chat Messages](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#list-chat-messages)

21. [List All Broadcats](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#list-all-broadcats)

22. [Unique Broadcast](https://github.com/mosi1994/hojreapi-doc/blob/master/CUSTOMER_PROFILE.md#unique-broadcast) 

23. [Unique Store Message](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#unique-store-message) 

24. [Unique Product](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#unique-product) 

25. [List Store Gallery](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#list-store-gallery) 

**Add Store Gallery**
----

* **URL**

```  
        https://api.hojrenama.com/web/store-manager/add-store-gallery
```  
    
* **Method:**
 ```  
        POST
 ```
*  **URL Params**

```
username:09121714981
token:DcW0AM5OseZiPYJ8680w3w4XV7wpnh1W
x:35.235564
y:45.234523
source:img/filename.jpg
type:image
order:1

```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
```
          
         {
            "status": "success",
            "message": "done",
            "data": ""
         }
```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---

**Delete Store Gallery**
----

* **URL**

```  
        https://api.hojrenama.com/web/store-manager/delete-store-gallery
```  
    
* **Method:**
 ```  
        POST
 ```
*  **URL Params**

```
username:09121714981
token:DcW0AM5OseZiPYJ8680w3w4XV7wpnh1W
x:35.235564
y:45.234523
id:24
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
```  
         {
            "status": "success",
            "message": "done",
            "data": ""
         }
            
```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---


**List Store Gallery**
----

* **URL**

```  
        https://api.hojrenama.com/web/store-manager/list-gallery
```  
    
* **Method:**
 ```  
        POST
 ```
*  **URL Params**

```
username:09121714981
token:DcW0AM5OseZiPYJ8680w3w4XV7wpnh1W
x:35.235564
y:45.234523
perPage:300
page:1
id:24
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
```
            
```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---

**Unique Product**
----

* **URL**

```  
        https://api.hojrenama.com/web/store-manager/unique-product

```  
    
* **Method:**
 ```  
        POST
 ```
*  **URL Params**

```
username:09121714981
token:DcW0AM5OseZiPYJ8680w3w4XV7wpnh1W
x:35.235564
y:45.234523
id:24
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
```
           {
    "status": "success",
    "message": "media result",
    "totalCount": "4",
    "totalPages": 1,
    "page": 1,
    "perPage": 300,
    "data": [
        {
            "id": 53,
            "title": "موبایل اوتفیترز ایران",
            "type": "",
            "store": 413,
            "source": "defaults/media.png",
            "order": null
        },
        {
            "id": 8,
            "title": "3",
            "type": "image",
            "store": 413,
            "source": "img/store/a523bf9fe5f990d65ab9fb24e3ee8b7d.jpg",
            "order": 3
        },
        {
            "id": 7,
            "title": "2",
            "type": "image",
            "store": 413,
            "source": "img/store/d280f3d53521a42b3ddf4ec533495857.jpg",
            "order": 2
        },
        {
            "id": 6,
            "title": "1",
            "type": "image",
            "store": 413,
            "source": "img/store/84f5bcb41b09a23c9dbdf677cabc1e55.jpg",
            "order": 1
        }
    ]
}
```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---


**Unique Store Message**
----

* **URL**

```  
        https://api.hojrenama.com/web/store-manager/unique-store-message

```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
username:09121714981
token:DcW0AM5OseZiPYJ8680w3w4XV7wpnh1W
x:35.235564
y:45.234523
id:24
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
```
              {
    "status": "success",
    "message": "store messages result",
    "totalCount": "1",
    "totalPages": 1,
    "page": 1,
    "perPage": 300,
    "data": [
        {
            "id": 24,
            "user": 1,
            "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. ",
            "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
            "attachment": null,
            "sendDate": 1500808133,
            "read": 0,
            "store": 413,
            "answer": "گیرد.",
            "answerDate": 1500808133,
            "answerAttachment": null,
            "status": "active",
            "senderName": "Mostafa Azizi"
        }
    ]
 }
```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---




**Unique Broadcast**
----

* **URL**

```  
        https://api.hojrenama.com/web/broadcasts/<<ID>>
```  
    
* **Method:**
 ```  
GET
 ```
*  **URL Params**

```
username:09121111111
token:abdcdefghijklmno
x:51.23123
y:31.1231
id:41
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
                {
                    "id": 41,
                    "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت",
                    "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.  \r\n\r\nلورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان",
                    "user": null,
                    "role": 8,
                    "date": "2017-06-01",
                    "show": "yes"
                }

    ```

* **Error Response:**
    ```
    
    
    ```
 
* **Notes:**


---


**List All Broadcats**
----

* **URL**

```  
        https://api.hojrenama.com/web/broadcasts
```  
    
* **Method:**
 ```  
GET
 ```
*  **URL Params**

```
@username
@token
@x
@y
@perPage
@page
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
        "items": [
        {
        "id": 1,
        "title": "Test",
        "text": "Test",
        "user": 7617,
        "role": null,
        "date": 1494757007,
        "show": "yes"
        }
        ],
        "_links": {
        "self": {
        "href": "http://localhost/hojreapi/web/broadcasts?
        username=09123566777&token=2k8JIZwjUYpCizwcpq3__GVrD_o3cpwZ&page=1&per-
        page=300"
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
                "message": "not login",
                "data": ""
                }
    
    ```
 
* **Notes:**


---
**Edit Store Information**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-store
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
Store[title]:تست
Store[country]:102
Store[state]:1
Store[hood]:274
Store[phone]:02133835561
Store[address]:لورم ایپسوم یا طرح‌نما (به انگلیسی: Lorem ipsum) به متنی آزمایشی
Store[about]:لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.
Store[email]:mhpro2008@gmail.com
Store[telegram]:@test
Store[instagram]:@test
Store[facebook]:@test
Store[twitter]:@test
Store[googleplus]:@test
Store[website]:@test
Store[logo]:defaults/storeLogo.png
Store[storeFrontImage]:defaults/storeLogo.png
Store[certificateImage]:defaults/storeLogo.png
Store[locationImage]:defaults/storeLogo.png
Store[mainImage]:defaults/storeLogo.png
Store[city]:19
Store[linkedin]:@linkedin
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
       {
          "status": "success",
          "message": "updated successfully",
          "data": ""
       }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---

**Add New Seller**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/addseller
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
Seller[name]:Mostafa
Seller[family]:Hasanabadi
Seller[cellPhone]:09336658833
Seller[avatar]:defaults/avatar.png
Seller[password]:123456
Seller[email]:jkashdasd@asdas.com
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "Seller Created",
            "data": ""
        }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---


**List All My Sellers**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/mysellers
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

```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
    
            {
            "status": "success",
            "message": "sellers",
            "data": [
                {
                    "id": 1,
                    "name": "محمد",
                    "fmaily": "تستتسی س",
                    "avatar": "img/defaults/avatars/51.png",
                    "onlineStatus": "online"
                },
                {
                    "id": 2,
                    "name": "محمد",
                    "fmaily": "تستتسی س",
                    "avatar": "img/defaults/avatars/51.png",
                    "onlineStatus": "online"
                },
                {
                    "id": 3,
                    "name": "محمد",
                    "fmaily": "تستتسی س",
                    "avatar": "img/defaults/avatars/51.png",
                    "onlineStatus": "online"
                },
                {
                    "id": 4,
                    "name": "محمد",
                    "fmaily": "تستتسی س",
                    "avatar": "img/defaults/avatars/51.png",
                    "onlineStatus": "online"
                },
                {
                    "id": 9,
                    "name": "Mostafa",
                    "fmaily": "Hasanabadi",
                    "avatar": "img/defaults/avatars/51.png",
                    "onlineStatus": "online"
                },
                {
                    "id": 10,
                    "name": "Mostafa",
                    "fmaily": "Hasanabadi",
                    "avatar": "defaults/avatar.png",
                    "onlineStatus": "offline"
                }
            ]
        }

    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Delete My Seller**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/deleteseller
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
seller:24
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "Seller Successfully Deactived",
            "data": ""
        }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Active Seller**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/active-seller
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
seller:24
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "Seller Successfully activated",
            "data": ""
        }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Edit Seller**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-seller
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
Seller[name]:Mostafa
Seller[family]:Hasanabadi
Seller[cellPhone]:09336658833
Seller[avatar]:defaults/avatar.png
Seller[password]:123456
Seller[email]:jkashdasd@asdas.com
seller:24
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "Seller Edited",
            "data": ""
        }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Statistics**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/statistics
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
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "success",
            "data": {
                "views": 23,
                "likes": 21,
                "dislikes": 20,
                "favorites": 21,
                "notifications": 22,
                "comments": 28
            }
        }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**List All Store Messages**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/store-messages
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
pageSize : 300
page: 1

```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
```
              {
    "status": "success",
    "message": "store messages result",
    "totalCount": "9",
    "totalPages": 1,
    "page": 1,
    "perPage": 300,
    "data": [
        {
            "id": 24,
            "user": 1,
            "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. ",
            "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
            "attachment": null,
            "sendDate": 1500808133,
            "read": 0,
            "store": 413,
            "answer": "گیرد.",
            "answerDate": 1500808133,
            "answerAttachment": null,
            "status": "active",
            "senderName": "Mostafa Azizi"
        },
        {
            "id": 25,
            "user": 1,
            "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. ",
            "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
            "attachment": null,
            "sendDate": 1500808133,
            "read": 0,
            "store": 413,
            "answer": "گیرد.",
            "answerDate": 1500808133,
            "answerAttachment": null,
            "status": "active",
            "senderName": "Mostafa Azizi"
        },
        {
            "id": 26,
            "user": 31,
            "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. ",
            "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
            "attachment": null,
            "sendDate": 1500808133,
            "read": 0,
            "store": 413,
            "answer": "گیرد.",
            "answerDate": 1500808133,
            "answerAttachment": null,
            "status": "active",
            "senderName": "فرشاد نظری"
        },
        {
            "id": 27,
            "user": 32,
            "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. ",
            "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
            "attachment": null,
            "sendDate": 1500808133,
            "read": 0,
            "store": 413,
            "answer": "گیرد.",
            "answerDate": 1500808133,
            "answerAttachment": null,
            "status": "active",
            "senderName": "بشیر نظری"
        },
        {
            "id": 28,
            "user": 33,
            "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. ",
            "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
            "attachment": null,
            "sendDate": 1500808133,
            "read": 0,
            "store": 413,
            "answer": "گیرد.",
            "answerDate": 1500808133,
            "answerAttachment": null,
            "status": "active",
            "senderName": "حمید تکاپویی"
        },
        {
            "id": 29,
            "user": 34,
            "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. ",
            "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
            "attachment": null,
            "sendDate": 1500808133,
            "read": 0,
            "store": 413,
            "answer": "گیرد.",
            "answerDate": 1500808133,
            "answerAttachment": null,
            "status": "active",
            "senderName": "سجاد بیگدلو"
        },
        {
            "id": 30,
            "user": 35,
            "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. ",
            "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
            "attachment": null,
            "sendDate": 1500808133,
            "read": 0,
            "store": 413,
            "answer": "گیرد.",
            "answerDate": 1500808133,
            "answerAttachment": null,
            "status": "active",
            "senderName": "مجید توکلی"
        },
        {
            "id": 31,
            "user": 36,
            "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. ",
            "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
            "attachment": null,
            "sendDate": 1500808133,
            "read": 0,
            "store": 413,
            "answer": "گیرد.",
            "answerDate": 1500808133,
            "answerAttachment": null,
            "status": "active",
            "senderName": "مهدی مشهدی"
        },
        {
            "id": 32,
            "user": 37,
            "title": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. ",
            "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
            "attachment": null,
            "sendDate": 1500808133,
            "read": 0,
            "store": 413,
            "answer": "گیرد.",
            "answerDate": 1500808133,
            "answerAttachment": null,
            "status": "active",
            "senderName": "مهدی کرمانی"
        }
    ]
}
```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Answer Store Message**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/answer-store-message
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
message:23
answer:Test
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
            {
                "status": "success",
                "message": "message replied",
                "data": ""
            }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**List All Offers**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/offers
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
page:2
perPage:10
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
            {
                "status": "success",
                "message": "offers result",
                "totalCount": "21",
                "totalPages": 3,
                "page": 2,
                "perPage": 10,
                "data": [
                    {
                        "id": 104,
                        "user": 12,
                        "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                        "sentDate": 1497099238,
                        "read": 0,
                        "store": 1,
                        "targetName": "محمد تستتسی س"
                    },
                    {
                        "id": 114,
                        "user": 13,
                        "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                        "sentDate": 1497099238,
                        "read": 0,
                        "store": 1,
                        "targetName": "محمد تستتسی س"
                    },
                    {
                        "id": 124,
                        "user": 14,
                        "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                        "sentDate": 1497099238,
                        "read": 0,
                        "store": 1,
                        "targetName": "محمد تستتسی س"
                    },
                    {
                        "id": 134,
                        "user": 15,
                        "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                        "sentDate": 1497099238,
                        "read": 0,
                        "store": 1,
                        "targetName": "محمد تستتسی س"
                    },
                    {
                        "id": 144,
                        "user": 16,
                        "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                        "sentDate": 1497099238,
                        "read": 0,
                        "store": 1,
                        "targetName": "محمد تستتسی س"
                    },
                    {
                        "id": 154,
                        "user": 17,
                        "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                        "sentDate": 1497099238,
                        "read": 0,
                        "store": 1,
                        "targetName": "محمد تستتسی س"
                    },
                    {
                        "id": 164,
                        "user": 18,
                        "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                        "sentDate": 1497099238,
                        "read": 0,
                        "store": 1,
                        "targetName": "محمد تستتسی س"
                    },
                    {
                        "id": 174,
                        "user": 19,
                        "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                        "sentDate": 1497099238,
                        "read": 0,
                        "store": 1,
                        "targetName": "محمد تستتسی س"
                    },
                    {
                        "id": 184,
                        "user": 20,
                        "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                        "sentDate": 1497099238,
                        "read": 0,
                        "store": 1,
                        "targetName": "محمد تستتسی س"
                    },
                    {
                        "id": 194,
                        "user": 21,
                        "text": "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                        "sentDate": 1497099238,
                        "read": 0,
                        "store": 1,
                        "targetName": "محمد تستتسی س"
                    }
                ]
            }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**List All Products**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/products
```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
username:09121714981
token:DcW0AM5OseZiPYJ8680w3w4XV7wpnh1W
x:35.235564
y:45.234523
perPage:300
page:1
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "List of products",
            "data": [
                {
                    "id": 1,
                    "title": "Creative SBS A520 Desktop Speaker",
                    "mainImage": "img/defaults/product.png",
                    "category": 94,
                    "store": 1,
                    "description": "اسپیکر «SBS-A520» محصولی حرفه\u200cای از شرکت «کریتیو» است که از کیفیت ساخت بسیار بالایی بهره می\u200cبرد. این اسپیکر از طریق جک 3.5میلی\u200cمتری به رایانه متصل می\u200cشود و وظیفه\u200cی پخش صدا با کیفیت بالا را برعهده می\u200cگیرد. این محصول قدرتمند شرکت کریتیو از یک ساب\u200cووفر قدرتمند به اضافه\u200cی 5 اسپیکر تشکیل شده است. قدرت صدای تولیدی یکی از فاکتورهای بسیار مهم در انتخاب تجهیزات صوتی از قبیل اسپیکرهاست. اسپیکر SBS-A520 از حداکثر توان خروجی 5 وات برای هرکدام از اسپیکرها و 12 وات برای ساب\u200cووفر بهره می\u200cبرد که جمع تمامی\u200c این\u200cها با هم برابر 37 وات خواهد بود. یک ریموت کنترل با سیم در جعبه SBS-A520 مشاهده می\u200cشود که می\u200cتوان آن را روی میزکار خود قرار داد و به\u200cراحتی به کنترل صدای موسیقی درحال\u200cپخش پرداخت. صدای تولیدی این اسپیکر بسیار قدرتمند است و می\u200cتوان روی آن به\u200cعنوان محصولی حرفه\u200cای حساب باز کرد. اسپیکر SBS-A520 محصولی کاربردی برای کاربرانی خواهد بود که قصد دارند برای گوش\u200cکردن به موسیقی یا مشاهده\u200cی فیلم\u200cهای سینمایی با صدایی واقعی، اسپیکری با کیفیت بالا تهیه کنند.",
                    "status": "active",
                    "createDate": 1495371673,
                    "updateDate": 1497847759,
                    "price": 100000,
                    "top": "no",
                    "viewed": 22,
                    "liked": 21,
                    "disliked": 21,
                    "favoriteCount": 21,
                    "commentsCount": 33,
                    "notificationCount": 21,
                    "slug": "product-44"
                },
                {
                    "id": 2,
                    "title": "TP-LINK TD-W8151N 150Mbps Wireless N ADSL2 Plus Modem Router",
                    "mainImage": "img/defaults/product.png",
                    "category": 94,
                    "store": 1,
                    "description": "شرکت «تی پی-لینک» یکی از تولیدکنندگان قدرتمند تجهیزات شبکه است که می\u200cتوان آن را در گروه سه شرکت بزرگ این حوزه قرار داد. به تازگی شرکت تی پی-لینک محصولی را با نام «TD-W8151N» روانه\u200cی بازار کرده است که درواقع یک مودم روتر ADSL است. این محصول از یک آنتن قدرتمند برای به اشتراک\u200cگذاری اینترنت و شبکه بهره می\u200cبرد. قدرت گیرندگی آنتن این مودم 5 دسی\u200cبل است که برای یک مودم روتر ADSL مقدار مناسبی محسوب می\u200cشود. همچنین فرکانس پشتیبانی 2.4 گیگاهرتزی در این مودم باعث می\u200cشود که بتوانید محدوده\u200cی وسیعی را تحت پوشش شبکه بی\u200cسیم قرار دهید. آنتن مودم روتر TD-W8151N از نوع ثابت است و نمی\u200cتوان آن را جدا کرد. در قسمت پشتی این محصول یک درگاه LAN به چشم می\u200cخورد که از آن برای اتصال به شبکه و اینترنت از طریق کابل RJ-45 می\u200cتوان بهره برد. در کنار درگاه\u200c RJ-45، یک کلید برای راه\u200cاندازی مجدد مودم و یک کلید WPS برای اتصال سریع و ایمن به چشم می\u200cخورد. در قسمت جلویی این محصول نشان\u200cگرهای LED به چشم می\u200cخورند که می\u200cتوانند اطلاعات بسیار خوبی از وضعیت کارکرد مودم و شبکه به کاربر ارائه کنند. این مودم انرژی خود را از یک آداپتور برق که در جعبه محصول قرار دارد تامین می\u200cکند. مودم روتر بی\u200cسیم تی پی-لینک، سری+ADSL2 ، مدل TD-W8151N ، طراحی بسیار دوست\u200cداشتنی دارد که تنها تفاوت بین این محصول با نمونه هم نامش عدم وجود کلید خاموش یا روشن کردن WIFI به همراه تغییراتی در نوع طراحی در این محصول بوده است.",
                    "status": "active",
                    "createDate": 1495371672,
                    "updateDate": 1497847759,
                    "price": 100000,
                    "top": "no",
                    "viewed": 0,
                    "liked": 0,
                    "disliked": 0,
                    "favoriteCount": 0,
                    "commentsCount": 0,
                    "notificationCount": 0,
                    "slug": "product-43"
                },
                {
                    "id": 241,
                    "title": "کالای شماره یک",
                    "mainImage": "img/defaults/product.png",
                    "category": 5,
                    "store": 1,
                    "description": "لورم ایپسوم یا طرح\u200cنما (به انگلیسی: Lorem ipsum) به متنی آزمایشی و بی\u200cمعنی در صنعت چاپ، صفحه\u200cآرایی و طراحی گرافیک گفته می\u200cشود. طراح گرافیک از این متن به عنوان عنصری از ترکیب بندی برای پر کردن صفحه و ارایه اولیه شکل ظاهری و کلی طرح سفارش گرفته شده استفاده می نماید، تا از نظر گرافیکی نشانگر چگونگی نوع و اندازه فونت و ظاهر متن باشد. معمولا طراحان گرافیک برای صفحه\u200cآرایی، نخست از متن\u200cهای آزمایشی و بی\u200cمعنی استفاده می\u200cکنند تا صرفا به مشتری یا صاحب کار خود نشان دهند که صفحه طراحی یا صفحه بندی شده بعد از اینکه متن در آن قرار گیرد چگونه به نظر می\u200cرسد و قلم\u200cها و اندازه\u200cبندی\u200cها چگونه در نظر گرفته شده\u200cاست. از آنجایی که طراحان عموما نویسنده متن نیستند و وظیفه رعایت حق تکثیر متون را ندارند و در همان حال کار آنها به نوعی وابسته به متن می\u200cباشد آنها با استفاده از محتویات ساختگی، صفحه گرافیکی خود را صفحه\u200cآرایی می\u200cکنند تا مرحله طراحی و صفحه\u200cبندی را به پایان برند.",
                    "status": null,
                    "createDate": 1497705877,
                    "updateDate": 1497849866,
                    "price": 100000,
                    "top": "no",
                    "viewed": null,
                    "liked": null,
                    "disliked": null,
                    "favoriteCount": null,
                    "commentsCount": null,
                    "notificationCount": null,
                    "slug": "product-241"
                },
                {
                    "id": 242,
                    "title": "کالای شماره یک",
                    "mainImage": "img/defaults/product.png",
                    "category": 5,
                    "store": 1,
                    "description": "لورم ایپسوم یا طرح\u200cنما (به انگلیسی: Lorem ipsum) به متنی آزمایشی و بی\u200cمعنی در صنعت چاپ، صفحه\u200cآرایی و طراحی گرافیک گفته می\u200cشود. طراح گرافیک از این متن به عنوان عنصری از ترکیب بندی برای پر کردن صفحه و ارایه اولیه شکل ظاهری و کلی طرح سفارش گرفته شده استفاده می نماید، تا از نظر گرافیکی نشانگر چگونگی نوع و اندازه فونت و ظاهر متن باشد. معمولا طراحان گرافیک برای صفحه\u200cآرایی، نخست از متن\u200cهای آزمایشی و بی\u200cمعنی استفاده می\u200cکنند تا صرفا به مشتری یا صاحب کار خود نشان دهند که صفحه طراحی یا صفحه بندی شده بعد از اینکه متن در آن قرار گیرد چگونه به نظر می\u200cرسد و قلم\u200cها و اندازه\u200cبندی\u200cها چگونه در نظر گرفته شده\u200cاست. از آنجایی که طراحان عموما نویسنده متن نیستند و وظیفه رعایت حق تکثیر متون را ندارند و در همان حال کار آنها به نوعی وابسته به متن می\u200cباشد آنها با استفاده از محتویات ساختگی، صفحه گرافیکی خود را صفحه\u200cآرایی می\u200cکنند تا مرحله طراحی و صفحه\u200cبندی را به پایان برند.",
                    "status": "active",
                    "createDate": 1497705936,
                    "updateDate": 1497849869,
                    "price": 100000,
                    "top": "no",
                    "viewed": null,
                    "liked": null,
                    "disliked": null,
                    "favoriteCount": null,
                    "commentsCount": null,
                    "notificationCount": null,
                    "slug": "product-242"
                }
            ]
        }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Add New Product**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/add-product
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
Product[title]:کالای شماره یک
Product[mainImage]:defaults/product.png
Product[category]:5
Product[description]:لورم ایپسوم یا طرح‌نما (به انگلیسی: Lorem ipsum) به متنی آزمایشی و بی‌معنی در صنعت چاپ، صفحه‌آرایی و طراحی گرافیک گفته می‌شود. طراح گرافیک از این متن به عنوان عنصری از ترکیب بندی برای پر کردن صفحه و ارایه اولیه شکل ظاهری و کلی طرح سفارش گرفته شده استفاده می نماید، تا از نظر گرافیکی نشانگر چگونگی نوع و اندازه فونت و ظاهر متن باشد. معمولا طراحان گرافیک برای صفحه‌آرایی، نخست از متن‌های آزمایشی و بی‌معنی استفاده می‌کنند تا صرفا به مشتری یا صاحب کار خود نشان دهند که صفحه طراحی یا صفحه بندی شده بعد از اینکه متن در آن قرار گیرد چگونه به نظر می‌رسد و قلم‌ها و اندازه‌بندی‌ها چگونه در نظر گرفته شده‌است. از آنجایی که طراحان عموما نویسنده متن نیستند و وظیفه رعایت حق تکثیر متون را ندارند و در همان حال کار آنها به نوعی وابسته به متن می‌باشد آنها با استفاده از محتویات ساختگی، صفحه گرافیکی خود را صفحه‌آرایی می‌کنند تا مرحله طراحی و صفحه‌بندی را به پایان برند.
Product[price]:100000
Product[top]:no
Gallery[1]:img/defaults/product.png
Gallery[2]:img/defaults/product.png
Gallery[3]:img/defaults/product.png
video:img/defaults/product.png
```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "product created successfully",
            "data": ""
        }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Delete Product**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/delete-product
```  
    
* **Method:**
 ```  
POST
 ```
*  **URL Params**

```
    username:09121122777
    token:abdcdefghijklmno
    product:2

```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```
        {
            "status": "success",
            "message": "Product Deleted",
            "data": ""
        }
    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Edit Product**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-product
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
Product[title]:کالای شماره یک
Product[mainImage]:img/defaults/product.png
Product[category]:5
Product[description]:لورم ایپسوم یا طرح‌نما (به انگلیسی: Lorem ipsum) به متنی آزمایشی و بی‌معنی در صنعت چاپ، صفحه‌آرایی و طراحی گرافیک گفته می‌شود. طراح گرافیک از این متن به عنوان عنصری از ترکیب بندی برای پر کردن صفحه و ارایه اولیه شکل ظاهری و کلی طرح سفارش گرفته شده استفاده می نماید، تا از نظر گرافیکی نشانگر چگونگی نوع و اندازه فونت و ظاهر متن باشد. معمولا طراحان گرافیک برای صفحه‌آرایی، نخست از متن‌های آزمایشی و بی‌معنی استفاده می‌کنند تا صرفا به مشتری یا صاحب کار خود نشان دهند که صفحه طراحی یا صفحه بندی شده بعد از اینکه متن در آن قرار گیرد چگونه به نظر می‌رسد و قلم‌ها و اندازه‌بندی‌ها چگونه در نظر گرفته شده‌است. از آنجایی که طراحان عموما نویسنده متن نیستند و وظیفه رعایت حق تکثیر متون را ندارند و در همان حال کار آنها به نوعی وابسته به متن می‌باشد آنها با استفاده از محتویات ساختگی، صفحه گرافیکی خود را صفحه‌آرایی می‌کنند تا مرحله طراحی و صفحه‌بندی را به پایان برند.
Product[price]:100000
Product[top]:no
product:2
Gallery[1]:img/defaults/product.png
Gallery[2]:img/defaults/product.png
Gallery[3]:img/defaults/product.png
video:img/defaults/product.png

```

* **Success Response:**
  

  * **Code:** 200 <br />
    **Content:** 
    ```

    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Edit Store Information**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-store
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

    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Edit Store Information**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-store
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

    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Edit Store Information**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-store
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

    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---




**Edit Store Information**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-store
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

    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---




**Edit Store Information**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-store
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

    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---



**Edit Store Information**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-store
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

    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---





**Edit Store Information**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-store
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

    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---




**Edit Store Information**
----

* **URL**

```  
    https://api.hojrenama.com/web/store-manager/edit-store
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

    ```

* **Error Response:**
    ```
         
    ```
 
* **Notes:**


---
