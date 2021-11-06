# [Python Arithmetic Operators](https://www.geeksforgeeks.org/python-arithmetic-operators/)

Pythonda ve diger programlama dillerinde matematik operatorleri cok onemlidir. Bu bolumde onceki bolumde ogrendigimiz temel matematik operatorlerinin uzerine katarak diger matematik operatorlerini gormus olucaz.


Operator | Description | Syntax 
--- | --- | --- 
`+` | __Addition__ (Toplama) | `x + y` 
`–` | __Subtraction__ (Cikarma) | `x – y` 
`*` | __Multiplication__ (Carpma) | `x * y` 
`/` | __Division - float__ (Bolme) | `x / y` 
`//` | __Division - floor__ (Tam sayi bolmesi) | `x // y` 
`%` | __Modulus__ (kalani bulma) | `x % y` 
`**` | __Power__ (Us bulma) | `x ** y` 


## __Operatorleri beraber kullanalim :__

Python'daki islem sirasi matematiktekiyle birebir aynidir.

1. Parantez ici her zaman once yapilir.
2. Carpma ve Bolme her zaman Toplama ve Cikarmadan once yapilir.
3. Islemler soldan saga dogru yapilir.

__Ornek :__
```python
    8 + 4 * 3 / 2 - 18
    # output: -4.0

    # Ayni sonucu veren baska bir gosterim;
    # 8 + ((4 * 3) / 2) - 18
    # output: -4.0
```

---

Aşağıdaki işlemin ciktisi nedir ?
```python
    val1 = 10
    val2 = 2
    val3 = 3

    result = ((val1 ** val2) // val3) / 3

    print(result)
```