# vscode setup

## layout

* ```python/```
  * ```setup.py```
  * ```mylibs/```
    * ```__init__.py```
    * ```mymods.py```
  * ```tests/```
    * ```__init__.py```
    * ```test_mylibs.py```

## resolve

* ```setup.py```
  * https://docs.python.org/ja/3/distutils/setupscript.html
  * vscode-pythonが認識するルートパス
  * autocomplete, lint, ...etc
  * vscodeの再起動がいるかも
  * __pycache__の消去がいるかも
* ```__init__.py```
  * ディレクトリをパッケージとして扱うためのファイル
  * https://docs.python.org/ja/3/tutorial/modules.html
* ```.vscode/settings.json```
  * pytestのルートを```python/```に設定
  * http://doc.pytest.org/en/latest/goodpractices.html
  * jupyterのルートを```python/```に設定