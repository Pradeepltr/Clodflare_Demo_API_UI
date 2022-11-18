### **Worker for get product details from Worker KV Storage**
>>We get all product details that present in Worker KV with help of following **steps**

>>> **Step 1**
>>>>First we take list of product details not full details like product id ,product name etc it only provides numbers of data with key.

>>> **Step 2**
>>>>Second filter all keys from list and get all product details like product id ,product name, product price and image url (Image get Worker endpoint with product id) with the help of key that is product id.

### **Worker end point**
>> ***https://infoget.pk6361439.workers.dev***

>>>Method - GET
