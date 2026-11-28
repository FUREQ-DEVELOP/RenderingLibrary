# RenderingLibrary

ATMERA の完成した描画 SDK と配布物を公開するリポジトリです。変更可能な実装ソースと Visual Studio 開発環境は [RenderingWorkspace](https://github.com/FUREQ-DEVELOP/RenderingWorkspace) に置きます。

## 開発目標

- DirectX 11 / DirectX 12対応
- C++20による実装
- 描画バックエンドの抽象化
- 描画機能の独立モジュール化
- 静的ライブラリおよび動的プラグインへの対応
- 他のゲームエンジンやアプリケーションへの組み込み

## 責務

描画処理、GPUリソース、シェーダー、描画パイプラインおよび描画機能を提供します。

ゲーム固有のロジックやエディター機能は対象外です。

## 開発環境

Windows / Visual Studio 2022 / C++20

## 統合開発環境

[RenderingWorkspace](https://github.com/FUREQ-DEVELOP/RenderingWorkspace)

## 管理担当

Rendering-Team

## 開発状況

SDK の配布準備中です。現時点でリリース資産はありません。ビルド可能な実装ソースはこのリポジトリに置きません。配布形式と公開条件は [配布方針](DISTRIBUTION.md) を参照してください。

## ライセンス

未決定。

## 利用方法

- 作業は `main` からブランチを作成し、Pull Requestで提案してください。
- タスクはGitHub Issues / Projectsで管理します。
- 変更の責務: RenderingLibrary。担当Team: `Rendering-Team`。
- 依存関係や開発状況は [DevelopmentDocs](https://github.com/FUREQ-DEVELOP/DevelopmentDocs) を参照してください。
