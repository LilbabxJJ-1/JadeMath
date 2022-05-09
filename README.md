[![PyPI version](https://badge.fury.io/py/JadeMath.svg)](https://badge.fury.io/py/JadeMath)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![Downloads](https://pepy.tech/badge/jadeGeometry)](https://pepy.tech/project/jadegeometry)
### Jade-Math
``pip install JadeMath``
####Used to make doing math while coding a lot easier
####Example:
```py
import JadeMath as JM

sa = JM.rect_prism(1, 5, 19)
print(f"The surface area of the rectangular prism is {sa}")

all = JM.add(sa, JM.rect_prism(4, 1, 29))
print(f"And added by my second prism will be will be {all}")

temp = JM.f_to_c(60)
print(f"The temperature is {temp} degrees celcius")
```