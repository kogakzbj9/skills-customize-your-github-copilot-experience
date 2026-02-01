# 📘 Assignment: FastAPI REST APIs

## 🎯 Objective

FastAPI を使って REST API を設計・実装し、基本的な CRUD 操作とバリデーションを行えるようになる。

## 📝 Tasks

### 🛠️	シンプルなタスク管理 API を作成

#### Description
タスクを作成・取得・更新・削除できる API を作成し、ルーティングとデータモデルを整理する。

#### Requirements
Completed program should:

- POST /tasks でタスクを作成できる
- GET /tasks と GET /tasks/{id} でタスクを取得できる
- PUT /tasks/{id} と DELETE /tasks/{id} で更新・削除できる


### 🛠️	入力検証とエラーハンドリング

#### Description
Pydantic モデルで入力を検証し、異常系のレスポンスを適切に返す。

#### Requirements
Completed program should:

- 必須項目の欠落を 422 で返せる
- 存在しない ID へのアクセスに 404 を返せる
- レスポンスボディにエラーメッセージを含められる
