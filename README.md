# Hello, World

Flask で作った簡単な Web アプリです。ブラウザで開くと、画面中央に **Hello, World** と表示されます。

## 必要なもの

- Python 3.11 以降

## 使い方

プロジェクトのルートで、次の手順を実行します。

### 1. 仮想環境を作る

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Windows の場合:

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 2. 依存関係を入れる

```bash
pip install -r requirements.txt
```

### 3. アプリを起動する

```bash
python app.py
```

起動に成功すると、ターミナルに次のような表示が出ます。

```text
Running on http://127.0.0.1:5000
```

### 4. ブラウザで確認する

[http://127.0.0.1:5000](http://127.0.0.1:5000) を開きます。  
「Hello, World」が表示されれば成功です。

### 5. 終了する

起動したターミナルで `Ctrl + C` を押します。

## ファイル構成

```text
.
├── app.py               # Flask アプリ本体
├── requirements.txt     # 依存パッケージ
├── templates/
│   └── index.html       # 表示するページ
└── README.md
```
