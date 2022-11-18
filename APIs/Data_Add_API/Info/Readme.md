### **Worker for Add product details in Worker KV storage**
We store product details like product id , product name , product price , product image url in Worker KV.

>>>First we store product image in R2 bucket and after that store R2 bucket worker image url with all product details in Worker KV.

>>>KV Method for Add data - env.namespace.put(key,value)

### **Worker endpoint**
>> ***https://info.pk6361439.workers.dev***

>>>Method - POST

 **Input Format**

>>>>
    {
    "ProductId":"123",
    "ProductName":"MacbookAir",
    "ProductPrice":"Rs 80000"
    }

>>If product details successfully Add in KV  it will return 1 as response and If it not happend return 0 as response.

##If you want to know about how worker create how it is bind with KV and R2 visit below link
>>For Worker and KV - *https://github.com/Pradeepltr/CloudFlare_Worker_urlShortner*

>>For R2            - *https://github.com/Pradeepltr/Cloudflare_R2_Storage_operation* 
