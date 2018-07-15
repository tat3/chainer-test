# Chainer test

## 環境

* python 3.7.0

## 環境構築

```bash
pyenv install 3.7.0
pyenv local 3.7.0
brew install graphviz
pip install -r requirements.txt
```

もしzlibがないとか言われたら`xcode-select --install`

## Jupyter Notebookを起動

初めてmatplotlibでplotするときはひどく時間がかかる
次回以降は高速

### Jupyter Notebookの初期設定

~/.jupyter/custom/を作成し、custom.cssを追加
```bash
mkdir -p ~/.jupyter/custom/
```
```css
.CodeMirror pre, .output pre {
  font-family: Monaco;
  font-size: 10.5pt;
}
```

## 参考

https://qiita.com/mitmul/items/1e35fba085eb07a92560

