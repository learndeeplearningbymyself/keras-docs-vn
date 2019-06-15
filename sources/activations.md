### Cách sử dụng hàm kích hoạt

Hàm kích hoạt là tầng `Activation`, hoặc là có thể sử dụng bằng tham số `activation` ở tất cả các tầng forward.

```python
from keras.layers.core import Activation, Dense

model.add(Dense(64))
model.add(Activation('tanh'))
```