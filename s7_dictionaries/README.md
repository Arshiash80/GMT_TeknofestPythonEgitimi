# Dictionaries (Sozlukler)
Sozlukler veya ingilizce ismiyle Dictionary'ler ayni gercek hayattaki sozlukler gibi davranan veri tipleridir.

Bu veri tipi simdiye kadar godrduklerimizden yapisi geregi farklidir. `dictionary`'nin icindeki her bir eleman index ile degil, `key`, `value` olarak tutulur. 

Gercek hayattaki sozluklere benzetmemdeki sebepte bu aslinda.


## __Sozluk olusturmak :__
```python
# Suslu parantez ve iki nokta ile {`key`: `value`} degerlerini yerlestirelim
sozluk = { "sifir": 0, "bir": 1, "iki": 2 }


# Bos bir sozluk olusturmak
sozluk1 = {}
# or
sozluk2 = dict()
```

## __Sozluk degerlerine erismek ve sozluge deger eklemek :__

```python
sozluk1 = { "bir": 1, "iki": 2, "uc": 3, "dort": 4 }

# Sozluk degerlerine erismek;

>>> sozluk1["bir"] 
1


>>> sozluk1["uc"] 
3


# Sozluge deger ekleme;
>>> sozluk1["bes"] = 5 
>>> sozluk1
{ 'bes': 5, 'iki': 2, 'bir': 1, 'uc': 3, 'dort': 4 }


>>> a = { "Bir": [1, 2, 3]. "iki": [[1 ,2], [3, 4], [5, 6]], "uc": 15 }

>>> a["iki"]
[[1 ,2], [3, 4], [5, 6]]

>>> a["iki"][1][1]
4

>>> a["uc"]
15
```

## __Temel sozluk metodlari :__

method | description | syntax
--- |  --- | ---
`.values()` | Sozlugun degerlerini (`value`'larini) bir liste olarak doner | `sozluk.values()`
`.keys()` | Sozlugub anahtarlarini (`key`'lerini) bir liste olarak doner. | `sozluk.keys()`
`.items()` | Sozlugun `value` ve `key`'lerini bir liste icinde demekt olarak doner | `sozluk.items()`


```python
>>> yeni_sozuluk = { "bir": 1, "iki": 2, "uc": 3 }

# .values()
>>> yeni_sozuluk.values()
dict_values([1, 2, 3])

# .keys()
>>> yeni_sozuluk.keys()
dict_keys(['bir', 'iki', 'uc'])

# .items()
>>> yeni_sozuluk.items()
dict_items([('bir', 1), ('iki', 2), ('uc', 3)])

```