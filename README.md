<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/docker.jpg">
</p>

Одоо байгаа upload хийгдсэн docker image үүдийг харахдаа `https://docker.datacenter.gov.mn` орж харна.

Харин өөрийн image-г оруулахдаа `docker.datacenter.gov.mn/{image_name}:{tag}` tag-ласны дараа push хийнэ.

## Жишээ зааврыг доор оруулав

# 1. Docker images  
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/1.jpg">
</p>
# 2. Өөрт байгаа image-үүдээс cloud repo рүү оруулах image-г сонгож tag-лах.
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/2.jpg">
</p>
Tag хийхэд тухайн image-ний аль tag-г ямар болгох гэж байгааг оруулна.
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/3.jpg">
</p>

* docker.datanceter.gov.mn - Docker repository домайн хаяг
* darkhaa - Хэрэглэгчийн нэр/бүлэг
* busybox:latest - Docker image нэр болон tag

# 3. Tag-ласны дараа push хийх боломжтой болох юм.
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/4.jpg">
</p>

# 4. Шалгаж үзэхдээ docker.datacenter.gov.mn-с шалгана
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/5.jpg">
</p>
 
# 5. Татаж авах үедээ
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/6.jpg">
</p>
 
`docker pull docker.datacenter.gov.mn/darkhaa/busybox:latest`	

<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/7.jpg">
</p>
