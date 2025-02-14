# タスク管理アプリケーション

## 概要
tRPCを活用したシンプルなタスク管理アプリケーションです。

## 機能

- タスク管理機能

  - タスクの作成、編集、削除機能
  - タスクの完了状態の切り替え

- バリデーション機能

  - 入力値の検証
  - 型安全性の確保

## 技術スタック

- 🚀 Next.js
- 🚀 TypeScript
- 🚀 tRPC
- 🚀 Vercel

- 📦 Mantine
- 📦 Tailwind CSS
- 📦 Prisma
- 📦 Biome

- 🛠️ ESLint
- 🛠️ Docker Compose
- 🛠️ Zod

## システム要件

- Node.js 20.0.0以上
- Docker 24.0.0以上
- npm 8.0.0以上または yarn 1.22.0以上

## プロジェクト構成

```
.
├── app/ # App Router
│   ├── api/
│   │   └── trpc/ # tRPCエンドポイント
│   └── busyness/
├── constants/ # 定数
├── features/ # 機能
│   ├── busyness/ # 非表示用
│   └── tasks/ # タスク管理
├── prisma/ # データベース関連
└── utils/ # ユーティリティ
```

## 主要なコンポーネント

- `TaskManager`：タスク管理の中核となるコンポーネント
