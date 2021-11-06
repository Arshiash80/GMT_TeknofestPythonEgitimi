# Kullanicidan Girdi Alma - `input()` Fonksiyonu

Python'da kullanicidan girdi almamizi saglayan `input()` fonksiyonu bulunmakta.

## __Input fonksiyonunun kullanimi__

```python
input() # Calistirdigimiz zaman input fonksiyonu bizden bir girdi bekler
```
    >>> 25 
    '25'
---
```python
# Eger istersek fonskiyonun icinde deger gonderebiliriz
input("Lutfen bir deger giriniz: ")
```
    >>> Lutfen bir deger giriniz: 10
    '10'

---
```python
# Inputtan gelen degeri kullanabilmek icin bir degiskende saklamaliyiz.
x = input("Lutfen x'in degerini giriniz: ")
```
    >>> Lutfen x'in degerini giriniz: 5
    >>> x
    '5'
---



## __Alistirma :__
1. Aşağıdaki programın çıktısı nedir ?

    Note : a : 4 , b : 3, c : 2

        a = input("Birinci Sayı:")
        b = input("İkinci Sayı:")
        c = input("Üçüncü Sayı:")
        
        print("Toplamları:",a+b+c)

