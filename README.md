安装：

pip install -U happytrans


使用:
```
import happytrans.translate_model as ht
model = ht.Model()
sentence = '我没有感情'
print(model.convert(sentence))
```
备注:

python setup.py sdist upload