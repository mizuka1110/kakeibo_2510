## 概要
> ※ 本リポジトリは、Webアプリ開発学習開始から約2カ月時点で作成した試作アプリです。
> 設計・構成には改善余地がありますが、基礎理解を目的として実装しました。

Next.jsで作成した家計簿アプリのフロントエンド。
月別の収支管理と家計簿CRUD機能を実装。

## 主な機能
- 家計簿の一覧表示（年月別）
- 入金・出金・収支の自動集計
- 家計簿データの追加 / 編集 / 削除
- モーダルによる詳細表示・編集
- REST API（/records）との連携

## 技術スタック
### Frontend
- Next.js (pages router)
- React / TypeScript
- Tailwind CSS

### Backend
- Node.js / TypeScript
- REST API
- Prisma ORM
- Database（開発用）

## API
- GET /records
- POST /records
- PUT /records/:id
