# C++'dan C Programlama Diline Geçiş

C++ programlama dili, C programlama dilinden geliştirilmiştir.
C++ C'dilinin bütün mirasını almıştır.
Yani; artısı ve eksisi ile olduğu gibi aktarılmıştır.
C++ dili içerisinde tamamen C dilini barındırdığından, C++'da yazacağınız
C kodları, C++'da çalıştırılır. C'nin kütüphanelerini destekler.
Ancak C dili içerisinde C++ komutları çalışmayacaktır.
	
C ile C++ Programlama Dili Arasındaki Farklar
C programlama dili donanımla konuşan bir dil olduğundan işletim sistemi
yazmak için geliştirilmiş bir dildir. Gelişen teknolojinin karşısında
C dili yetersiz ve karmaşık bir hal almaya başlamıştır. Bu sebeple
C++ dili geliştirilmiştir. 
C++ dili C'den farklı olarak Nesneye Dayalı Programlama Tekniklerini
bünyesinde barındırır.
<h2> C ile C++ Temel Komutları</h2>

|   	| C Dİli   | C++ Dili  | 
| -------- | ------------- | -------- |
|Ekran Çıktısı|printf(" ");|cout << " ";|
|Klavye Girişi|scanf(“tip_karakteri”,degisken_adi);|cin >> ; " ";|
|String Veri Tipi|C dilinde string veri tipi yoktur char isim[10]; yada char *isim; olarak kullanılırlar.|string isim;|
-----

| Tip Karakteri  | İşlevi  |  Tipi |
| -------- | ------------- | -------- |
| %c | tek bir karakter | char |
| %d veya %i | işaretli ondalık tamsayı | int, short |
| %ld | uzun işaretli ondalık tamsayı | long |
| %u | işaretsiz ondalık tamsayı | unsigned int, unsigned short |
| %f | Gerçel sayı | float, double |
| %s | karakter dizisi (string) | char |
| %lu | işaretsiz uzun tamsayı | unsigned long |
| %x | Hexa decimal sayılar |  |
| %o | Octal sayılar |  |

NOT: Yukarıda yer alan bütün Karakter Tip’lerini bilmenize gerek yoktur. %d, %c, %f ve %s en çok kullanılanlardır.
