将普通话转换为方言

安装：
```
pip install -U happytrans
```

使用:
```python
import happytrans.translate_model as ht
model = ht.Model()
sentence = '没有事的，不要发神经，我是个杀手，我没有感情，杀了你我就去睡觉了。'
print(model.convert(sentence))
#么得事哩，不要神戳戳，我是个杀手，我么得感情，杀老你我豆克睡告告哒。
```
备注:

python setup.py sdist upload