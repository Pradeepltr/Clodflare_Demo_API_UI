### **Worker(API) for Delete data**
This worker used for delete product data from Worker KV and also delete product image from R2 Storage.

>>#### **Flow**
>>> **Step 1**
>>>>First delete product details from Worker KV Store with the help of product id . 

>>> **Step 2**
>>>>Also delete product image from R2 Storage with the help of same product id that we used in step 1. 

### **Worker endpoint**
>> ***deleteapi.pk6361439.workers.dev?key=product_id***

>>>If product details successfully deleted from both storage KV and R2 it will return 1 as response and If it not happend return 0 as response.
