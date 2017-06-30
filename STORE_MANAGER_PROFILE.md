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

15. [Add Store Gallery](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#edit-product)

16. [Delete Store Gallery](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#delete-store-gallery)

17. [Physical Customers](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#physical-customers)

18. [Virtual Customers](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#virtual-customers)

19. [List All Chats](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#list-all-chats)

20. [List Chat Messages](https://github.com/mosi1994/hojreapi-doc/blob/master/STORE_MANAGER_PROFILE.md#list-chat-messages)



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

