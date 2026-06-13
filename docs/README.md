# akari-releases Documentation

> **このリポの立ち位置**: バイナリ配布専用リポ。AKARI デスクトップアプリの公式リリース成果物（`.dmg` / `.exe` 等）を管理する。
> **扱う範囲**: リリース成果物の配布・EULA・バージョン管理
> **扱わない範囲**: ソースコード実装（→ `Akari-OS/shell` private）、アーキテクチャ設計（→ `akari-os/docs/`）
>
> - 🌐 正典: [Akari-OS/.github](https://github.com/Akari-OS/.github)
> - 🏛 Hub（非公開）: `akari-os` — 横断研究・戦略・Master Index
> - 🗺 全リポマップ: `akari-os/MAP.md`
> - 📋 Hub ドキュメント索引: `akari-os/docs/INDEX.md`

---

## このリポのドキュメント

| ファイル | 内容 |
|---|---|
| `../README.md` | ダウンロード案内・プラットフォーム対応表・サポートリンク |
| `../LICENSE` | All Rights Reserved + EULA 参照 + コンポーネント別ライセンス一覧 |

## ライセンス

本リポは **Layer 1 (proprietary)**。All Rights Reserved + AKARI Beta EULA。
ポリシー詳細: `akari-os/docs/governance/license-policy.md`

## 命名の使い分けについて

| 表記 | 用途 |
|---|---|
| `akari-os` | ローカルリポ接頭辞・エコシステム全体の総称 |
| `Akari-OS` | GitHub org 名（<https://github.com/Akari-OS>） |
| `akari-oss.app` | 公式サイトドメイン（oss suffix は org とは別物） |

## maintainer 向けリリース手順

詳細手順は `Akari-OS/shell`（private）の `docs/dev-howto/release-process.md` を参照。
本リポでの作業は基本的に「タグを打つ → GitHub Releases でバイナリを Assets に添付 → README を更新する」の 3 ステップ。

大まかな流れ:

1. `akari-shell` でビルド・コード署名・公証を完了させる
2. GitHub Releases でタグ（例: `v0.2.0`）を作成しバイナリを Assets に添付する
3. 本リポのタグを同じバージョン番号で打つ
4. `README.md` のバージョン表記・プラットフォーム対応表を実態に合わせて更新する
