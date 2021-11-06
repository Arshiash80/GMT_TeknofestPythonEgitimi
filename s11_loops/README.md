# Python Loops (Donguler)

Python has two primitive loop commands:

1. `while` loops
2. `for` loops


## __The while Loop :__

`while` döngüsü ile bir koşul doğru olduğu sürece bir dizi ifadeyi çalıştırabiliriz.

    Print i as long as i is less than 6:
```python
i = 1
while i < 6:
  print(i)
  i += 1
```

### The `break` Statement
`break` ile `while` koşulu doğru olsa bile döngüyü durdurabiliriz:

    Exit the loop when i is 3:
```python
i = 1
while i < 6:
  print(i)
  if i == 3:
    break
  i += 1 
```

### The `continue` Statement
`continue` ile mevcut donguyu durdurabilir ve bir sonraki ile devam edebiliriz:

    Continue to the next iteration if i is 3:
``` python
i = 0
while i < 6:
  i += 1
  if i == 3:
    continue
  print(i)
```


### The `else` Statement
`else` ifadesi, koşul artık doğru olmadığında calistirilicak kod blogunu belirler,

    Print a message once the condition is false:
```python
i = 1
while i < 6:
  print(i)
  i += 1
else:
  print("i is no longer less than 6")
```

### Sonsuz dongu (infinite loop)
`while` dongusunun kosulu dogru oldugu surece calisiyorsa 

`while True:` ifadesi bizi sonsuz donguye sokucaktir

``` python
    i = 0
    while True:
        # Bu kod blogu "sonsuza kadar" calisicak.
        prtin(i) 
        i += 1
```