```python
phones=['XiaoMi','HuaWei','Apple']
print(phones[0].title())
```

****
Add at the rear end
```python
phones.insert(0,'OPPO')
print(phones[0].title())
```


****
Add at anyplace
```python
phones.insert(0,'OPPO')
print(phones[0].title())
```

****
Delete at anyplace
```python
del phones[0]
print(phones[0].title())
```
****

```python

Pop out & use it
first_got=phones.pop(0)
print(first_got.title())
```
****
```python
Remove （using when you only know what the element is without the imformation）
phones.remove('vivo')
print (phones)
```

****
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!


