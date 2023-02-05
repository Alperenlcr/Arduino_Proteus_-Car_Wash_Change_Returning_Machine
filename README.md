# Arduino_Proteus_-Car_Wash_Change_Returning_Machine


##  👇 Project explained in detail
[Project Explanation](Dokumanlar/Report.pdf)


## How To Run
1. (Önce Proteus devresini içeren dosyayı demo proteusunla açmayı dene. Açılmazsa eğer demo proteus’u sil ve bu adımı uygula, açılırsa uygulama)Proteus.exe programını, https://docs.google.com/uc?export=download&id=15VhXODqKgDTvycWFW1XAY3kJWGDZ7wgr adresinden indir. İndikten sonra çalıştır ve nereye kurmak istediğin gibi bilgileri seçtikten sonra yükleme bitecek.
2. (Okuma ve yazma yaptığımız .txt dosyasını el ile açmana gerek yoksa bu programı indirmesen de olur)Winimage programını,https://www.winimage.com/download/wima64100.exe adresinden indir. İndikten sonra çalıştır ve nereye kurmak istediğin gibi bilgileri seçtikten sonra yükleme bitecek.
3. Proteusda arduino simule edebilmek için gereken dosyalar,’ Proteus_Arduino_Library’ klasörünün içinde.Proteusu kurduğun klasöre git. ‘DATA’ klasörünü aç. ’ Proteus_Arduino_Library’ klasöründeki .LIB uzantılı dosyayı ‘DATA’ klasörünün içindeki ‘LIBRARY’ klasörüne kopyala. .IDX uzantılı dosyayı ‘DATA’ klasörünün içindeki ‘Library Indexing’ klasörüne kopyala.
4. Arduino yazılımını, https://www.arduino.cc/en/software adresinden yükle.
5. ‘ParaUstu.ino’ dosyasını aç.
6. https://youtu.be/SCJfYbeJ4b8?t=104 bu videonun seçili saniyesinden sonraki işlemleri gerçekleştir. (.hex uzantılı dosyayı videoda olduğu gibi başka bir klasöre taşımak zorunda değilsin.Olduğu adreste de kullanabilirsin aynı şekilde.)
7. Sd kardın okuma yazma yapacağı dosyayı seçmek için, proteusta sd kart okuma modülünün üzerine sağ tık yap. Sonra ‘Edit properties’e tıkla, ordan adres seçme kutucuğuna bas. Sana attığımız ‘sandisk_MMC_128M.image’ dosyasının adresini çıkan pencereden bul, adresini bulduğunda dediğimiz dosyanın ismini görmezsen eğer, penceredeki dosya adı bölümüne ‘*’ yazıp enterla, aradığımız dosya şimdi çıkmış olmalı. Onu seç.Ve aç a bas.
8. Simulasyon çalışmaya hazır.
9. Eğer simulasyonu başlattığında pencere açılmazsa, simulasyon çalışırken yukarıdaki debug butonuna bas, sonra en altta virtual terminal’e bas şimdi açılmış olmalı.


## Collaborations
Collaborated with [Omer Bahadir Gokmen](https://github.com/Omer-sync)