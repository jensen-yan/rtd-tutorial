Template for the Read the Docs tutorial
=======================================

This GitHub template includes fictional Python library
with some basic Sphinx docs.

Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/


本地测试方法
```
pip install sphinx sphinx-rtd-theme

cd docs
make html

cd build/html
python -m http.server
```

