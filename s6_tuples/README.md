# Demetler (Tuple'lar)

Tuple'lar Listelere oldukca benzerler. Ancak, en onemli farklari `tuple`'in degistirilemez olmasidir. Bu sayede programimizda degistirilmesini istemedigimiz degerleri `tuple` icinde depolayabiliriz.

## __Tuple Olusturma :__
```python
# tuple elemanlari '()' parantezinin icine alinarak olusuturulabilir
demet = (1, 2, 3, 4, 5, 6)
```

## __Tuple Methodlari :__

Tuple'larin sadece 2 methodu bulunuyor.
cunku biz Tuple'larin uzerin herhangibir degistirme islemi yapamiyoruz.


### `demet.index(x)`
        Eger x'degeri demet'in icinde varsa bize index numarasini vericek. yoksa hata vericek.

### `demet.count(x)`
        x'degerinin demet'in icinde kac defa gectigini bize soyler


---
## __Alistirma:__

Programın çıktısı nedir ?

    >> demet = ("Elma","Armut","Muz")
    >> demet[0] = "Kiraz"
    >> demet