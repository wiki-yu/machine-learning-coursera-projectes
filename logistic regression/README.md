# Notes

* df.isin()
```
positive = data[data['Admitted'].isin([1])]

>>> df = pd.DataFrame({'A': [1, 2, 3], 'B': ['a', 'b', 'f']})   
>>> df.isin([1, 3, 12, 'a'])   
       A     B   
0   True   True   
1  False  False   
2   True  False   
```

