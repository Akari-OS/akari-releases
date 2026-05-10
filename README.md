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

## ライセンス

各リリースバイナリは **AKARI Beta End User License Agreement (EULA)** に従います。詳細は [LICENSE](./LICENSE) と各 Release notes を参照してください。

## サポート

- 公式サイト: <https://akari-oss.app>
- ベータ参加: <https://akari-oss.app/#waitlist>
- バグ報告 / フィードバック: 招待メールに記載の専用窓口

## 配布フロー (maintainer 向け)

リリース手順は [`Akari-OS/shell` の `docs/dev-howto/release-process.md`](https://github.com/Akari-OS/shell/blob/main/docs/dev-howto/release-process.md) を参照 (private)。
