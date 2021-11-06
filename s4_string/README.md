# [Strings (Karakter Dizileri)](https://www.w3schools.com/python/python_strings.asp)

Python'da bir veri tipi olan `string`'ler veya Turkce ismiyle Karakter Dizileri gercek hayatta kullandigimiz yazilardan bir farki yok.

## __String olusturma :__
Asagidakilerden hangisini kullanmak istediginiz tamamen size baglidir.
```python
# Tek tirnak ile ' '
'Merhaba Python!!'

# Cift tirnak ile " "
"Merhaba Python!!"

# 3 tirnak ile """ """
"""Merhaba Python"""
```

Burada dikkat etmemiz gerek nokta, eger bir `string`'i nasil olustuduysak oyle bitirmeliyiz.

__Ornegin :__
```python
    # Hatali kod ❌
    "Merhaba' 
```
```
    # output: SyntaxError: unterminated string literal
```

## __String indexleme ve parcalama:__
Stringler birer karakter dizileri olduklari icin her bir karakterin aslinda string icinde bir yeri var. ornegin `'ali'` stringinde `'a'`, `'l'` ve `'i'` karakterlerinin yerleri _`index`_ olarak adlandirilir.

Python'da ve bircok programlama dilinde index'lenme 0'dan baslar. Yani `'ali'` stringinin `0`'inci indexi `'a'` olur

__Ornek :__
```python
    a = "ali"

    # ornegin 0. index'e ulasmak icin `[]` operatorunu kullanarak a[0] ifadesini yazicaz.

    print(a[0])
    # output: 'a'

    print(a[1])
    # output: 'l'

    print(a[2])
    # output: 'i'


    # Sondan indexleme icin `-` kullanmaliyiz.

    print(a[-1])
    # output: 'i'

    print(a[-2])
    # output: 'l'

    print(a[-2])
    # output: 'a'
```

    NOTE: bir string'in icindeki karakterlerinin sayisinin uzunlugunu bulabilmek icin len() fonkisyonunu kullanabiliriz.

```python
    string = "ali"
    len(string)
    # output: 3
```

    NOTE: Python'da stringler ayni sayilarda oldugu gibi birbirleriyle toplanabilirler.

```python
    string1 = "Hello"
    string2 = "World"

    toplam = string1 + string2

    print(toplam)

    # output: "HelloWorld"
```


--- 
## Beraber cozelim;

```python
# Programın çıktısı ne olur ?
a = "Python"
a[1]
```
