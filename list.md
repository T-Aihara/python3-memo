List
==========================
リスト内包表記
--------------------------
平方数の配列を普通に作ろうと思うとこんな感じ。
```python
numbers = []
for i in range(0, 10):
    numbers.append(i＊i)
```

でもリスト内包表記を使えば一行ですむぞ。
```python
numbers = [i*i for i in range(0, 10)]
```