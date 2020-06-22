<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/docker.jpg">
</p>

Одоо байгаа upload хийгдсэн docker image үүдийг харахдаа `https://docker.datacenter.gov.mn` орж харна.

Харин өөрийн image-г оруулахдаа `docker.datacenter.gov.mn/{image_name}:{tag}` загварын дагуу tag-ласны дараа push хийнэ.

# Жишээ зааврыг доор оруулав

## 1. Docker images  
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/1.jpg">
</p>

## 2. Өөрт байгаа image-үүдээс cloud repo рүү оруулах image-г сонгож tag-лах.
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

## 3. Tag-ласны дараа push хийх боломжтой болох юм.
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/4.jpg">
</p>

## 4. Шалгаж үзэхдээ docker.datacenter.gov.mn-с шалгана
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/5.jpg">
</p>
 
## 5. Татаж авах үедээ
<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/6.jpg">
</p>
 
`docker pull docker.datacenter.gov.mn/darkhaa/busybox:latest`	

<p align="center">
    <img src="https://fibo-resources.s3-ap-southeast-1.amazonaws.com/7.jpg">
</p>

# Анхаарах зүйлс

* Одоогийн байдлаар ямар уг docker repo нь ямар auth байхгүй public-аар тавьсан тул ариг гамтай 😃 хэрэглэхийг хүсье.
* Өөрт хамааралгүй image-ээ оролдох нь нэгнийхээ гэрт зөвшөөрөлгүй орж байгаатай ижилхэн шүү. Адилхан мэргэжилтэй хүмүүс нэгнийхээ зовлонг сайн ойлгох байхаа 😃
* Push хийсэн image нь мөн устгагдахгүй гэх баталгаа өгч чадахгүй тул Production-доо ашиглахгүй байхыг зөвлөж байна.
* Устгах ёсгүй чухал image байвал Issues дээр image-н нэр болон юунд ашиглаж байгааг тайлбарлаж бичвэл хадгалагдаж үлдэх магадлалтай 😃
