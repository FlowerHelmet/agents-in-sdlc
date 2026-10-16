---
title: "実践的な開発"
slug: ja-jp/real-world-development
authors:
  - geektrainer
lastUpdated: 2026-09-16
---

現実的なシナリオ、完成したアプリケーション、共有バックログを使って、ソフトウェア開発ライフサイクル全体で GitHub Copilot を活用します。変更の計画、コードの作成、動作のテスト、プルリクエストの確認、エージェントを使った作業管理を繰り返しながら進めます。

## シナリオ

あなたは、開発者をテーマにしたボードゲームのクラウドファンディングを提供する架空の会社、Tailspin Toys の新しい開発者です。チームのバックログは GitHub イシューとして登録されており、すぐに取り組めます。そこにはフィルタリングやページネーションなどの機能開発と、アクセシビリティやコーディング標準などの品質改善が含まれています。

## 作業環境を選ぶ

GitHub Copilot は、どこで作業していても利用できます。自分の開発スタイルに合った環境を選びましょう。各ワークショップは個別のセットアップから始まり、共通の Tailspin Toys シナリオを使用します。

### [GitHub Copilot CLI][cli]

ターミナルでエージェント型アシスタントを使います。Plan モードと Autopilot モード、指示、スキル、カスタムエージェント、Playwright MCP、Agent Merge、実用的なスラッシュコマンドを扱います。

### [GitHub Copilot アプリ][app]

エージェントセッションを並行して実行し、セッションモードを切り替え、Canvas で共同作業を行い、デスクトップアプリから GitHub イシューやプルリクエストを管理します。

### [GitHub Copilot クラウドエージェント][cloud]

GitHub イシューを非同期エージェントに割り当て、作業を案内し、進捗を監視して、エージェントが作成するプルリクエストを確認します。

### [Visual Studio Code][vscode]

Visual Studio Code と GitHub Codespaces で GitHub Copilot を使います。エディターを離れずに、Copilot Chat のエージェントモード、MCP サーバー、カスタムエージェントを活用します。

[cli]: cli/
[app]: app/
[cloud]: cloud/
[vscode]: vscode/
