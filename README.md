# codingbat
## Warmup-1
### sleep_in
> "weekday""vacation"というパラメータがあります。祝日か休日ならTrueを出力する。
```
def sleep_in(weekday, vacation):
  return(not weekday or vacation)
```

monkey_trouble
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
  
  ## sum_double
  > 2つの値があり、異なった値なら合計、同じ値なら合計の2倍の値を出力する。
  ```
  def sum_double(a, b):
  sum = a + b
  if a == b:
    sum = sum * 2
  return sum
  ```
