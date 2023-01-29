# EN AZ SAYIDA BANKNOT PARA ÜSTÜ VERME


## ÖZET
Bu proje ile bir otomatik araç yıkama makinesinin minimum sayıda para üstü vererek çalışması amaçlanmıştır. Kullanıcı butonlar aracılığı ile para girişi yapabilecek, isterse para girşini resetleyebilecek ve onaylayabilecektir. Para girişinden sonra hizmet seçecek isterse seçilen hizmetleri resetleyebilecektir.
Hizmet sonunda para sıkısma durumu olur ise uyarı alacak, yeterli sayıda paraüstü olmaz ise uyarı alacak, varsa en az sayıda banknot ile para üstü iade edilecektir. 

## GİRİŞ
Tinkercad internet sitesi üzerinden ardunio kart simüle edilmiştir. Kodlama ve çalıştırma işlemleri de aynı site üzerinden eş zamanlı sağlanmıştır. Butonların üstüne etiketler ile görevleri/numaraları belirtilmiş, butonların karsılıkları ve islem kontrolü seri monitör üzerinden takip edilmiştir. 
  

## YÖNTEM

Sanal ardunio kartın setup kısmına butonlar ve ledler tanımlanmıstır.   hizmetID-hizmetAD-kalanHizmet-fiyat-malzemeAdet bilgileri için struct yapı kullanılmıstır ve hizmet bilgileri tutulmustur. Kasa bilgileri ve banknot bilgileri için struct yapı kullanısmıstır. Loop içerisinde buton sayımı yapılmıs ve if else if kontrolü ile onayla – reset butonlarına basılması halinde buton sayacları ve onaylanan – resetlenen islem tamamlanmıstır. Durum degiskeni ile durumlar – para alımı, hizmet secimi – kontrol ve takip edilmistir.

Para Ekranı: 
![image](https://user-images.githubusercontent.com/121980906/215309089-f2d17e78-ecc9-4230-bde2-660bc01686f7.png)

Hizmet seçimi ekranı
![image](https://user-images.githubusercontent.com/121980906/215309136-ff540a2c-547a-4d24-8e66-7967de24d94b.png)

“Buton 5” ile para iade islemi cıktısı
![image](https://user-images.githubusercontent.com/121980906/215309148-e6d9cf18-dc9d-4882-b9ca-acf1a5a16894.png)

Basarılı gerçeklesmis hizmet sonucu para üstü verilmesi ve kasa durumu
![image](https://user-images.githubusercontent.com/121980906/215309155-2dbc782a-0e4e-4bda-9cf0-7fa4a3534312.png)

Para sıkısma durumu ve kırmızı led yanması, para iade islemi
![image](https://user-images.githubusercontent.com/121980906/215309159-ae76df47-0065-4d32-b542-fb77a6e81484.png)



Akış Şeması


![image](https://user-images.githubusercontent.com/121980906/215309162-6e2a40f2-58bd-4b68-b5d3-40d903f152be.png)




