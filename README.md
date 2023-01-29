# EN AZ SAYIDA BANKNOT PARA ÜSTÜ VERME


## ÖZET
Bu proje ile bir otomatik araç yıkama makinesinin minimum sayıda para üstü vererek çalışması amaçlanmıştır. Kullanıcı butonlar aracılığı ile para girişi yapabilecek, isterse para girşini resetleyebilecek ve onaylayabilecektir. Para girişinden sonra hizmet seçecek isterse seçilen hizmetleri resetleyebilecektir.
Hizmet sonunda para sıkısma durumu olur ise uyarı alacak, yeterli sayıda paraüstü olmaz ise uyarı alacak, varsa en az sayıda banknot ile para üstü iade edilecektir. 

## GİRİŞ
Tinkercad internet sitesi üzerinden ardunio kart simüle edilmiştir. Kodlama ve çalıştırma işlemleri de aynı site üzerinden eş zamanlı sağlanmıştır. Butonların üstüne etiketler ile görevleri/numaraları belirtilmiş, butonların karsılıkları ve islem kontrolü seri monitör üzerinden takip edilmiştir. 
  

## YÖNTEM

Sanal ardunio kartın setup kısmına butonlar ve ledler tanımlanmıstır.   hizmetID-hizmetAD-kalanHizmet-fiyat-malzemeAdet bilgileri için struct yapı kullanılmıstır ve hizmet bilgileri tutulmustur. Kasa bilgileri ve banknot bilgileri için struct yapı kullanısmıstır. Loop içerisinde buton sayımı yapılmıs ve if else if kontrolü ile onayla – reset butonlarına basılması halinde buton sayacları ve onaylanan – resetlenen islem tamamlanmıstır. Durum degiskeni ile durumlar – para alımı, hizmet secimi – kontrol ve takip edilmistir.






