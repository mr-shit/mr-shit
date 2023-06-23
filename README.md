```python
l = 8
s = f'km;im;hm;gm;gm;gikm;{"g;"*l}f;e;c;b;bm;bm;cm;egik'
[print("".join(["x" if chr(i+97) in l or chr(121-i) in l else " " for i in range(25)])) for l in s.split(';')]
```
