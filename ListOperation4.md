dimentions.py
****
```python
dimentions=(200,50)
print (dimentions[0])
print (dimentions[1])
#这里有一个小问题，我想加一个含有中文的备注就会报错SyntaxError: Non-ASCII character 'xxxxxx' in file xxx
```


****
 ```python
 #当然了，元组最初定义的时候 也是可以改的
 dimensions=(200,50)
print("Original dimentions:")
for dimension in dimensions:
    print (dimension)

dimensions=(400,100)
print ("\nModifyed dimentions")
for dimension in dimensions:
    print (dimension)
#我们首先定义了一个元组，并将其存储的尺寸打印了出来（见❶）；接下来，将一个新元组存储到变量dimensions 中（见❷）；然后，打印新的尺寸（见❸）。这次，Python 不会报告任何错误，因为给元组变量赋值是合法的：

```











