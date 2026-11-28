# 配布方針

このリポジトリは ATMERA 描画 SDK の配布先です。開発・変更・ビルドは [RenderingWorkspace](https://github.com/FUREQ-DEVELOP/RenderingWorkspace) で行います。ここには `.sln`、Visual Studio プロジェクト、C++/C# 実装ソース、開発用テストや Studio のソースを置きません。

完成した SDK は GitHub Releases の資産として配布します。資産には利用者がリンクまたは実行するライブラリ、バックエンド DLL、必要な公開ヘッダー、利用手順、チェックサムを含められます。ヘッダーは SDK 利用のための成果物であり、このリポジトリの編集可能なソースツリーには配置しません。公開前に Workspace の Visual Studio ソリューションで Release ビルドとテストを通し、バージョン、対象アーキテクチャ、依存ランタイム、ライセンス、チェックサムを確認します。

モジュール配布では `module-<id>-v<major>.<minor>.<patch>` タグと `<id>-<version>-win-x64.dll` / 同名の `.sha256` 資産を使います。これらは Workspace の `Tools/SearchModules.ps1` と `Tools/DownloadModule.ps1` が参照する形式です。現時点でモジュールリリースはありません。
