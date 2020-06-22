<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/docker.jpg">
</p>

Одоо байгаа upload хийгдсэн docker image үүдийг харахдаа эндээс орж харна.

Харин шинээр upload хийхдээ өөрийн image ийг tag хийх буюу domain хаягийг өөрчилж push хийнэ.

Жишээ нь : 
1.	Docker images  
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/1.jpg">
</p>
2.	Өөрт байгаа image үүдээс upload хийх image ийг сонгож tag хийх.
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/2.jpg">
</p>
Tag хийхэд тухайн image-ний аль tag ийг ямар болгох гэж байгааг оруулна.
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/3.jpg">
</p>

●	Docker.datanceter.gov.mn - Docker repository домайн хаяг
●	Darkhaa - Хэрэглэгчийн нэр, бүлэг
●	Busybox - Docker image нэр гэх мэтээр нэрлэвэл тохиромжтой.

3.	Tag хийсэний дараа push хийх боломжтой болох юм.
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/4.jpg">
</p>

4.	Шалгаж үзэхдээ docker.datacenter.gov.mn -ээс орж шалгах юм
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/5.jpg">
</p>
 
5. Татаж авах үедээ 
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/6.jpg">
</p>
``` 
docker pull docker.datacenter.gov.mn/darkhaa/busybox:latest	
```
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/7.jpg">
</p>
 

