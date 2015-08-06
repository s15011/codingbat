# codingbat
## Warmup-1
### sleep_in
> "weekday""vacation"というパラメータがあります。祝日か休日ならTrueを出力する。
```
def sleep_in(weekday, vacation):
  return(not weekday or vacation)
```

### monkey_trouble
> aと猿とbと言う猿がいます。一匹がsmileでもう一匹がnot smileならトラブルになる。
```
def monkey_trouble(a_smile, b_smile):
  if a_smile and b_smile:
    return True
  if not a_smile and not b_smile:
    return True
  if not a_smile and b_smile:
    return False
  else:
    return False
  ```
  
### sum_double
> 2つの値があり、異なった値なら合計、同じ値なら合計の2倍の値を出力する。
```
def sum_double(a, b):
sum = a + b
if a == b:
sum = sum * 2
return sum
```
  
## diff21
> 21 と n の絶対値を求める。n が 21 を越したら絶対値の2倍を出力する。
```
def diff21(n):
if n <= 21:
  return 21 - n
else:
  return(n - 21) * 2
```
  
### parrot_trouble
> おしゃべりオウムがいます。7時~20時の間にオウムが喋るとトラブルになる。
```
def parrot_trouble(talking, hour):
  return(talking  and (hour < 7 or hour > 20))
```
  
### makes10
> a と b の2つの整数のどちらかが 10 または2つを足して 10 なら True を出力する。
```
def makes10(a, b):
  return(a == 10 or b == 10 or a+b == 10)
```

### near_hundred
> 整数 n があります。100 または 200 と n の絶対値が10以内なら True を出力する。
```
def near_hundred(n):
  return((abs(100 - n) <=10) or (abs(200-n) <=10))
```

### pos_neg
> 両方が negative または not negative なら True を出力する。
```
def pos_neg(a, b, negative):
  if negative:
    return(a < 0 and b < 0)
  else:
    return((a > 0 and b < 0) or (a < 0 and b > 0))
```

### not_string
> 文字列の最初に not があったらそのまま出力、なかったら not を前に追加して出力する。
```def not_string(str):
  if len(str) >= 3 and str[:3] == "not":
    return str
  return "not " + str
```

### missing_char
> 文字が入ってる文字列と整数 n があります。 n 番目の文字を消して新しく文字を出力する。
```def missing_char(str, n):
  return str[:n] + str[1+n:]
```


  
