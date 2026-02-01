---
agent: agent
description: 新しいプログラミング課題を作成する
argument-hint: 課題の詳細を指定
---

# 新しいプログラミング課題の作成

目的は、Mergington High School の学生向けに新しい宿題課題を作成することです。

## ステップ 1: 課題情報の収集

ユーザーからまだ提供されていない場合は、課題のテーマを確認してください。

## ステップ 2: 課題構成の作成

1. 課題のテーマに基づくユニークな名前で、`assignments` フォルダに新しいディレクトリを作成する
1. [assignment-template.md](../../templates/assignment-template.md) の構成に従って、ディレクトリ内に `README.md` を作成する
1. README に課題の詳細を記入する
1. （任意）課題に必要なスターターコードや添付資料があれば、同じ課題フォルダに追加する

## ステップ 3: Web サイト設定の更新

Web サイト設定ファイルの [config.json](../../config.json) にある assignments リストに新しい課題を追加してください。dueDate は、指定がない場合は「現在日 + 7 日」を使用します。