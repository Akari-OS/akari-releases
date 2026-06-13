# AKARI Releases

> AKARI 公式リリース配布リポ。**バイナリ配布専用**。ソースコードは別リポで開発しています。

## 最新版

最新リリース: **[Releases](https://github.com/Akari-OS/akari-releases/releases)** から該当バージョンの `.dmg` / `.exe` をダウンロード。

| プラットフォーム | 状態 |
|---|---|
| macOS (Apple Silicon、M1 / M2 / M3 / M4) | ✅ 配布開始 |
| macOS (Intel x86_64) | 🚧 近日対応 |
| Windows 10 / 11 | 🚧 準備中 |
| Linux | ⏸ 未定 |

> **最終確認**: 2026-06-13。上記 macOS Intel / Windows / Linux の状態は初期化時（2026-05-10）から変更なし。v0.1.0-beta.1 タグは Apple Silicon のみ対象。他プラットフォームの対応開始時にこの表を更新する。

## ダウンロード

現在 **招待制クローズドベータ**です。ベータ参加は [公式サイト](https://akari-oss.app) からウェイトリストに登録してください。招待後、個別の DL URL をメールでお送りします。

## ソースコード

- **[Akari-OS/shell](https://github.com/Akari-OS/shell)** — Tauri ホストアプリ (段階公開 private、Phase 1 完了後 public 化判定)
- **[Akari-OS/.github](https://github.com/Akari-OS/.github)** — 公開正典 (VISION / ROADMAP / CoC / SECURITY)
- **[Akari-OS/sdk](https://github.com/Akari-OS/sdk)** — App SDK (public, MIT)
- **[Akari-OS/m2c](https://github.com/Akari-OS/m2c)** — Media to Context Protocol (public, Apache 2.0)
- **[Akari-OS/amp](https://github.com/Akari-OS/amp)** — Agent Memory Protocol (public, Apache 2.0)
- **[Akari-OS/ace](https://github.com/Akari-OS/ace)** — Agent Context Engineering (public, Apache 2.0)

エコシステム全体: <https://github.com/Akari-OS>

> **命名の使い分け**: ローカルリポ接頭辞は `akari-`、GitHub org は `Akari-OS`（<https://github.com/Akari-OS>）、公式サイトドメインは `akari-oss.app`（oss suffix）。詳細は `docs/README.md` を参照。

## ライセンス

各リリースバイナリは **AKARI Beta End User License Agreement (EULA)** に従います。詳細は [LICENSE](./LICENSE) と各 Release notes を参照してください。

## サポート

- 公式サイト: <https://akari-oss.app>
- ベータ参加: <https://akari-oss.app/#waitlist>
- バグ報告 / フィードバック: 招待メールに記載の専用窓口

## 配布フロー (maintainer 向け)

リリース手順の詳細は [`Akari-OS/shell` の `docs/dev-howto/release-process.md`](https://github.com/Akari-OS/shell/blob/main/docs/dev-howto/release-process.md) を参照 (private リポ — org member のみアクセス可)。

手順要約（ローカル参照用）:
1. `akari-shell` でビルド・コード署名・公証を完了させる
2. GitHub Releases でタグを作成しバイナリを Assets に添付する
3. 本リポのタグを同じバージョン番号で打つ
4. 本 README のバージョン表記・プラットフォーム対応表を実態に合わせて更新する
