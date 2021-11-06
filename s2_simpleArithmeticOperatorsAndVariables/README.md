# Python Sayilar

Bu bolumde artik Python'u ogrenmeye basliyoruz. Pythonda temeli saglam atmamiz icin oncelikle veri tiplerini ve veri yapilarini ogrenmeliyiz.

__OZAMAN SAYILARI OGRENEREK MARATONUMUZA BASLAYALIM ✌️✌️__

## Bu bolumde sunlari ogrenicegiz;

- Tamsayi (`integer`) ve Ondalikli sayi (`Float`) veri tipleri.
- Basit matematik islemleri.
- Degisken tanimlama.
- Yorum satirlari.

---

## __Tamsayilar (`Integer`) ;__ 

Matematikte gordugumuz tum sayilar aslinda Pythonda bir __veri tipidir__. tam sayilar ingilizcede __Integer__ olarak gecmektedir. 

```
Ornek: `-100`, `34`, `0`, `2`, ...
```

## __Ondalikli Sayilar (`Float`) ;__ 

Tamsayilar gibi ondalikli sayilarda bizim matematikte gordugumuz sayi cesitlerinden birtanesidir. Ondalikli sayilar ingilizcede __Float__ olarak gecmektedir.

```
Ornek: `3.14`, `2.0`, `-13.82`, `0.72`, ...
```

## __Basit Matematik Operatorleri ;__

```python
    # Toplama (Addition)
    3 + 4 # output: 7

    # Cikarma (Subtraction)
    10 - 9 # output: 1

    # Carpma (Multiplication)
    9 * 3 # output: 27

    # Bolme (Division)
    4 / 2 # output: 2.0
```

## __Degiskenler ve Degisken Tanimlama ;__

Degiskenler aslinda bir veri tipinden deger tutan birimlerdir.

```python
    # degisken_ismi = degisken_degeri

    pi_sayisi = 3.14

    x = 12

    i = -32

    arshia = 10
```

Simdi degiskenleri nasil olusturuldugunu gorduysek birakac ornek yapalim.

- Bir degisken olusturalim
- Degsikenin degerini ekranda basalim
- Bundan sonra degiskenimizi kullanarak basit matematik islemleri yapalim
- Degiskenimize baska bir deger atayalim.

__ONEMLI ❗️❗️❗️__

```
    1. Degisken isimleri bir sayi ile baslayamaz.

    2. Degisken ismi arasinda bosluk olamaz.

    3. Asla özel sembolleri kullanmayın (!, @, #, $, %, ., ;, vb.) sadece (_) sembolunu kullanabilirsiniz.

    4. Pythonda tanimli olan anahtar kelimeler degisken ismi olarak kullanilamaz (while, not, vb.)
```
Bunlari ezberlemeniz gerek yok. Zamanla buna alisicaksiniz. Zeten eger gecersiz bir degisken ismi kullanirsaniz Python size hata vericektir.

__Ornegin :__
```python
    #Yanlis gosterim ornekleri ❌

    1dolar = 9.69 
    # output: SyntaxError: invalid decimal literal

    pi sayisi = 3.14
  # output: SyntaxError: invalid syntax.
```

## __Yorum Satirlari ;__

Yorum satirlari Python tarafindan gorulmuyor ve calistirilmiyor. Yorum satirlarini kodu daha okunabilir hale getirmek icin kullanmaniz onemli.

__Ornegin :__
```python
    # tekli yorumu satiri ...

    """
        Coklu yorum satiri
        ...
        ..
        .
    """
```