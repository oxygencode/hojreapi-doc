*Seller Profile Web Services*

Table of contents
---
1. [Chat Logs](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#chat-logs) 

2. [Chat Messages](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#chat-messages) 

3. [Send Offer](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#send-offer) 

4. [Add Product](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#add-product) 

5. [Edit Product](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#edit-product) 

6. [Delete Product](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#delete-product) 

7. [View Physical Customers](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#view-physical-customers) 

8. [View Virtual Customers](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#view-virtual-customers) 

9. [Statistics](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#statistics) 

10. [Unique Broadcast](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#unique-broadcast) 

11. [List All Broadcats](https://github.com/mosi1994/hojreapi-doc/blob/master/SELLER_PROFILE.md#list-all-broadcats)


**List All Broadcats**
----

* **URL**

```  
        https://api.hojrenama.com/web//broadcasts
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
