### **Worker for store image in R2**
We store product image in R2 bucket with product id as a image key.

>>R2 Method for store object (Image)- env.bucket_name(variable_name).put(key,request.body)

### **Worker endpoint**
>> ***image.pk6361439.workers.dev?key=product_id***

>> **Input**
>>>binary data (image)

>If product image successfully Add in R2  it will return 1 as response and If it not happend return 0 as response.
