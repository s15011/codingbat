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

  
