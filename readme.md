# python template

## 依存関係
- pyenv

## 初期化
```
pyenv install 3.12
pyenv local 3.12
python -m venv .venv
source .venv/bin/activate
```

## ライブラリのインストール
```
pip install -r requirements.txt
```

## テスト
```
python -m pytest test
```