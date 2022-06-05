# Contactless Water Level Controller | Labview

Temassız su seviye kontrol cihazı,üzerinde bulunan sensörler sayesinde tankta depolanan suyun belli bir seviyeye geldikten sonra üreticiye uyarı vermesini sağlamak için tasarlanmıştır. Bu projede bir ultrasonik sensör, bir led, bir servo motor ve Ardunio Uno kullanılmıştır. Servo motora bağlanan ultasonik mesafe sensörü 6 farklı tank içersinde bulunan suyun seviye kontrolünü yapmamızı sağlıyor. Tank içinde bulunan suyun yükselmesi ile ultrosonik sensörümüz değeri okuyup, su tankının son 8 metrelik seviyesine ulaştıktan sonra uyarı alarmı veriyor. Servo motor manuel olarak kullanıcı tarafından istenilen tankın su seviye kontrolünü yapmak için kullanılıyor. Servo motorun manuel olarak kullanıcı tarafından labview üzerinden kontrol edebilmesinin en büyük avantajı,  istenilen sayıda su tankı kullanılmasını sağlamaktır.

![Controller](https://github.com/YavuzAktas/ContactlessWaterLevelControllerLabview/blob/master/images/image.png)

## Blok Diyagramı
Serial port ve servo motor pinini kullanıcı tarafında labview arayüzünden seçiliyor. Ultrosonik sensörün trig pini Ardunio üzerindeki 8 numaralı pine, echo pini 9 numaralı pine tanımlıdır. Uyarı için kullanılan led ise Ardunio üzerinde 7 numaralı pine tanımlıdır.  

![Block](https://github.com/YavuzAktas/ContactlessWaterLevelControllerLabview/blob/master/images/4.png)

## Çalışma Adımları
- 8 metreden az hesaplanan su doposu :

[Uygulama Arayuzu](https://github.com/YavuzAktas/ContactlessWaterLevelControllerLabview/blob/master/images/1.png), 
[Uygulama Resmi](https://github.com/YavuzAktas/ContactlessWaterLevelControllerLabview/blob/master/images/20220605_165643.jpg)

- 8 metreden az hesaplanan su deposu, servo motor hareket ettirme :

[Uygulama Arayuzu](https://github.com/YavuzAktas/ContactlessWaterLevelControllerLabview/blob/master/images/2.png), 
[Uygulama Resmi](https://github.com/YavuzAktas/ContactlessWaterLevelControllerLabview/blob/master/images/20220605_165707.jpg)

- 8 metreden fazla hesaplanan su deposu : 

[Uygulama Arayuzu](https://github.com/YavuzAktas/ContactlessWaterLevelControllerLabview/blob/master/images/3.png), 
[Uygulama Resmi](https://github.com/YavuzAktas/ContactlessWaterLevelControllerLabview/blob/master/images/20220605_165805.jpg)



