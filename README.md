# 暗号資産損益計算システム

## 概要

暗号資産取引の損益を計算するための Web アプリケーション。
標準フォーマットの CSV ファイルから取引データを取り込み、FIFO 方式で損益を計算します。

## 機能

- 標準フォーマット CSV ファイルからの取引データインポート
- FIFO 方式による損益計算
- 基本的なレポート出力

## 技術スタック

- Backend: Python (FastAPI)
- Database: PostgreSQL
- Frontend: HTML + JavaScript + Bootstrap
- Infrastructure: Docker

## 開発環境のセットアップ

開発環境のセットアップ手順は[documents/setup.md](documents/setup.md)を参照してください。

## プロジェクト構造

```
crypto-calculator/
├── backend/          # バックエンドアプリケーション
├── documents/        # ドキュメント
├── docker/          # Docker関連ファイル
└── README.md
```

## ライセンス

MIT License
