# kafeterya-bot

ODTÜ'de bilgisayar başında pineklerken yemekhanede/kafeteryada nelerin olduğunu öğrenmek için yazdığım bir masaüstü bildirim botu servisi.

## Gereksinimler

+ Herhangi bir GNU/Linux dağıtımı (btw I use Arch)
+ `notify-send` 
+ `curl`
+ `cut`
+ `sed`

## Kullanım ve Test

Proje deposunu klonladıktan sonra:

+ Terminal üzerinden proje dizinine girip `chmod +x kafeterya` yazarak çalıştırılabilir duruma getirmeniz,
+ Herhangi bir dizinde çalışırken kafanız estiğinde bakabilmeniz için `kafeterya` programını `sudo cp kafeterya /usr/local/bin/` şeklinde belirtilen dizine kopyalamanız gerekiyor.
+ Eğer düzenli aralıklarla bildirim almak isterseniz cronjob atayabilirsiniz.

## Ekran Görüntüsü

 ![Ekran Görüntüsü](/ss.png)

## Lisans

Bu proje, *GNU GPLv3* ile Copyleft olarak bir özgür yazılım lisansı ile sunulmaktadır.
