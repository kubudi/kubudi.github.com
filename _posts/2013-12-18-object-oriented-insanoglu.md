---
layout: post
title: "Object Oriented Insanoglu"
description: ""
category: kisisel
tags: []
---
{% include JB/setup %}

Yillar once bir arkadasa cpp anlatmaya calisirken soyle bir ornek vermistim:
>  *Insani bir class olarak dusun. Bazi public bilgileri var. Adi, yasi, cinsiyeti..*   
>>     
>  *Ayni zamanda bazi private bilgileri de var. Fikirleri, anilari veya paylasmak istemedigi diger bilgileri.*
>>  
>  *Bu insan da alt classlardan olusur. Kol, Bacak, Kafa.. *
>  *Alt classlar da kendi bilgilerine sahip vesair...*
>>
>  *Ayrica bu classin tum ozelliklerini barindiran, usune baska ozellikler ekleyen classlar da var:*
>  *Kadin, erkek, cocuk..*
>>
>  *Ve bu classlarin da instancelari var:*
>  *Ali, Ayse, Husamettin..*   

Boyle uzayip gidiyor. Kime anlattigimi hatirlamiyorum ama cok ise yaramadigi zihnimde.   
 
Asil konuya gelirsek, gecenlerde farkettim ki, anlamadan da olsa cok yerinde bir tespit yapmis olabilirim. 
OOP gercekten insanlara cok benziyor.   

Yakin zamanda fonksiyonel programlamayla hasir nesir olma firsati yakaladim. 
Dolayisiyla bir kac temel felsefenin insan karakteri ile olan catismasi haylice gozume batmaya basladi:   


###Imutability:

Fonksiyonel programlamanin temellerinden olan bu kavram soyle tanimlaniyor: 
> *"Yaradilisindan sonra durumu, hali degistirilemeyen varliklar duragan(immutable) varliklardir."*

Ilk alintidan ne demeye calistigim bir nebze anlasilmistir sanirim.    

Kavrami arastirirken ilginc bir de tanima rastladim:
> *"Tanri'nin sifatlari, iradesi ve vaatleri duragandir."*

Insanoglu tartismasiz mutable bir varliktir. Degisir, baskalasir, tutarsizdir, kararsizdir. Onceki bir durumunu bilmeniz size 
su anki haliyle ilgili hic bir teminat vermez.

Ve ilginctir ki su an, tam bu yaziyi yazarken, sirf denemek icin actigim bir grubun calan sarkisinin sozleri su sekildedir:

> *3 sey, yakalasaniz iyi edersiniz. Annem derdi ki, insanlar atesin yanisini izlemeye bayilirlar.*  
> *Hayat hakkinda bildigm tek bir seyden eminim. **Degisim kacinilmazdir.** *  
> *Inanin bana, her ne kadar konfor bolgenizde kalmak isteseniz de, ne kadar stabil kalmak isteseniz de, ne kadar etrafinizi kontrol etmek isteseniz de, gercek*  
> *sudur ki: "her sey degisir".*
 
Guzel bir tesaduf oldu.


###Side Effect:
 
> *Eger bir islev(function) veya ifade(expression), geriye deger dondurmenin yanisira, baska bir varligin durumunu degistiriyorsa,*
> *veya harici bir fonksiyonla gozlemlenebilir bir iletisimi varsa side effect(yan etki) sahibidir denir.*   

Hayatinizin bir doneminde siz de benim gibi olmasi gerekenin aksine sebep sonuca iliskisi tasimayan, akla gelmeyecek bin turlu farkli degisken, 
varlik ve iliskilere dayanan insan davranislarina tanik olduysaniz, insan davranislarinin yuksek miktarda side effect tasidigi 
konusunda bana yuzde yuz katilacaginiza inaniyorum.

Ve "cikar iliskisi" denen kavram var oldugu surece hic bir insan davranisi *pure* olmayacaktir, olamaz.

####Type Safety:   

Evet, pes etmediniz, yilmadiniz, bu yaziyi buraya kadar okudunuz. Iste odulunuz, bir kissa:
> *Nasrettin Hoca, suya gönderdiği çocuğun eline testiyi vermiş ve;*   
>>
> *“–Testiyi kırmadan getir.” diyerek bir de tokat patlatmış.*   
>>
> *Yanındakiler hocaya söylenmişler:*
>> 
> *“–Hocam, çocukcağız testiyi kırmadı ki, tokat atıyorsun! Bu yaptığın doğru bir iş değil!” Hoca istifini bozmadan cevap vermiş:*
>>
> *“–Doğru söylüyorsunuz; ancak testiyi kırdıktan sonra tokat atmanın ne faydası olur?”*   
   

Type safety denen tanim soyle aciklaniyor:
> Type safety, type hatalarinin olusmamasi icin caydirici onlemler alinmasi veya engellenmesidir.
>> 
> Type hataasi ise iki farkli tipteki(type) varligin birbirinden ayirt edilmesinde yasanan, arzu edilmeyen karisikliktir.    

Zorlamaya gerek yok; sogana portakal gibi davranip suyunu sikmak type hatasidir. 

Anlasilacagi gibi, type safe sistemler bu hatalari minimize etmek uzerine tasarlanir. Bunun da en kolay yolu testi kirilmadan
onlem almaktir. Eger sikilacak seyin portakal olup olmadigini sorgularsan, sogan suyu icmek zorunda kalmazsin.   

Peki insanoglu neden type safe degildir? Dusunsenize, biz ki her insana, her varliga olmasi gerektigi gibi davranan, 
taa bastan itibaren neyle ugrastigini bilen, her turlu iletisimde icin en ideal, en uygun tutuma sahip varliklar olarak
hangi mekanizma bizden daha type safe ki?
   
   
Sonuc? Tipki insanliga olan inancim gibi, Object oriented programlamaya olan inancimi da kaybetmis bulunuyorum.
Sanirim hayati daha fonksiyonel bir bakis acisi ile yasamak, en ideal davranis olacaktir.   


Sevgiler.
