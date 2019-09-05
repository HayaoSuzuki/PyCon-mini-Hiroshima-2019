# PyCon-mini-Hiroshima-2019

## 環境構築

```console
$ python -m venv venv
$ venv\Script\activate.bat
$ (venv) pip install -r requirements.txt
```

## スライドの作成

```console
$ jupyter nbconvert 20191012slide.ipynb --to slides --reveal-prefix https://cdnjs.cloudflare.com/ajax/libs/reveal.js/3.3.0
```
