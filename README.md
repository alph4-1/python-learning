# Python Development Project

## プロジェクト概要
このプロジェクトはPython開発環境のテンプレートです。

## 開発環境
- Python 3.12
- 仮想環境: `.venv`

## 開発ツール
- Ruff: コードフォーマッターとリンター
- Black: コードフォーマッター
- MyPy: 静的型チェッカー

## セットアップ方法
1. 仮想環境の作成と有効化:
```bash
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
# または
.venv\Scripts\activate  # Windows
```

2. 依存関係のインストール:
```bash
pip install -r requirements.txt
```

## 開発ガイドライン
- コードはBlackとRuffの設定に従ってフォーマットしてください
- 型アノテーションを使用し、MyPyのチェックに合格するようにしてください
- 行の長さは88文字を超えないようにしてください

## ライセンス
MIT License
