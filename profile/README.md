<p align="center">
  <img src="https://raw.githubusercontent.com/yamisskey-dev/yamisskey-assets/main/yami.ski/yami-logo-192x192.png" width="120" alt="yamisskey">
</p>

<h1 align="center">yamisskey-dev</h1>

<p align="center">
  <strong>Privacy-first. Mental-first. For the Fediverse.</strong>
</p>

<p align="center">
  <a href="https://yami.ski"><img alt="Misskey" src="https://img.shields.io/badge/Misskey-yami.ski-A374FF?style=for-the-badge&labelColor=130E26&logo=misskey&logoColor=A374FF"></a>
  <a href="https://dao.yami.ski"><img alt="YAMI DAO" src="https://img.shields.io/badge/DAO-Optimism-D655D6?style=for-the-badge&labelColor=130E26&logo=ethereum&logoColor=D655D6"></a>
  <a href="https://chat.yami.ski"><img alt="Matrix" src="https://img.shields.io/badge/Matrix-chat.yami.ski-8B5CF6?style=for-the-badge&labelColor=130E26&logo=matrix&logoColor=8B5CF6"></a>
  <a href="https://hub.yami.ski"><img alt="Docs" src="https://img.shields.io/badge/Docs-hub.yami.ski-6BCB77?style=for-the-badge&labelColor=130E26&logo=astro&logoColor=6BCB77"></a>
</p>

---

「病み」や「闇」を言葉にできるSNS [やみすきー](https://hub.yami.ski/guides/about/) と、その周りに広がる [YAMI エコシステム](https://hub.yami.ski/guides/ecosystem/)を作っている開発者コミュニティ

## 参加

Issue と Pull Request はどのリポジトリでも歓迎します。

エコシステムの方向性そのものに関わりたい場合、[やみすきー](https://yami.ski) アカウントを取ったうえで [YAMI DAO](https://snapshot.org/#/s:yamidao.eth) の提案と投票に参加してください


## エコシステム

エコシステム全体のドキュメントは **[hub.yami.ski](https://hub.yami.ski)** にまとまっています。主なリポジトリ：

### SNS 本体・フォーク

| リポジトリ | 説明 |
|---|---|
| [yamisskey](https://github.com/yamisskey-dev/yamisskey) | Misskey フォーク本体。メンタルが弱い人向けにハードニング |
| [media-proxy-rs](https://github.com/yamisskey-dev/media-proxy-rs) | Rust 製メディアプロキシ |
| [summaly-docker](https://github.com/yamisskey-dev/summaly-docker) | URL プレビュー用 summary proxy |
| [neo-quesdon](https://github.com/yamisskey-dev/neo-quesdon) | プライバシー強化版 Neo-Quesdon（匿名質問） |
| [yui](https://github.com/yamisskey-dev/yui) | 公式 bot「唯」 |

### インフラ・運用（IaC）

| リポジトリ | 説明 |
|---|---|
| [yamisskey-host](https://github.com/yamisskey-dev/yamisskey-host) | 全サービスの構成図（Mermaid） |
| [yamisskey-ansible](https://github.com/yamisskey-dev/yamisskey-ansible) | Ansible + SOPS によるプロビジョニング |
| [yamisskey-terraform](https://github.com/yamisskey-dev/yamisskey-terraform) | Proxmox VE の Terraform 構成 |
| [yamisskey-backup](https://github.com/yamisskey-dev/yamisskey-backup) | Misskey DB の R2/B2 二重バックアップ |
| [yamisskey-doctor](https://github.com/yamisskey-dev/yamisskey-doctor) | バックアップの復元・検証・修復 |

### 周辺ツール

| リポジトリ | 説明 |
|---|---|
| [yamisskey-admin-notify-webhook-for-discord](https://github.com/yamisskey-dev/yamisskey-admin-notify-webhook-for-discord) | Misskey → Discord 通知（管理者向け） |
| [yamisskey-github-notifier-next](https://github.com/yamisskey-dev/yamisskey-github-notifier-next) | GitHub Webhook → Misskey/Discord 転送 |
| [yamioti](https://github.com/yamisskey-dev/yamioti) / [yamisskey-down](https://github.com/yamisskey-dev/yamisskey-down) | 障害時のメンテナンスページ切替と表示 |
| [yamisskey-anonote](https://github.com/yamisskey-dev/yamisskey-anonote) | 匿名投稿ツール |
| [yamii](https://github.com/yamisskey-dev/yamii) / [yamix](https://github.com/yamisskey-dev/yamix) | メンタルヘルス相談 API / プラットフォーム |
| [release-manager-actions](https://github.com/yamisskey-dev/release-manager-actions) | リリース自動化 Actions |

### ガバナンス・ブランド

| リポジトリ | 説明 |
|---|---|
| [yamidao](https://github.com/yamisskey-dev/yamidao) | YAMI DAO（[GOVERNANCE](https://github.com/yamisskey-dev/yamidao/blob/main/GOVERNANCE.md) / [ROADMAP](https://github.com/yamisskey-dev/yamidao/blob/main/ROADMAP.md)） |
| [yamisskey-hub-starlight](https://github.com/yamisskey-dev/yamisskey-hub-starlight) | hub.yami.ski のソース |
| [yamiuchi](https://github.com/yamisskey-dev/yamiuchi) | CTF チーム writeup（[team.yami.ski](https://team.yami.ski)） |
| [yamisskey-assets](https://github.com/yamisskey-dev/yamisskey-assets) / [yamisskey-theme](https://github.com/yamisskey-dev/yamisskey-theme) | ブランド資産・配色テーマ |

## 文献

- [hub.yami.ski](https://hub.yami.ski)：YAMI エコシステムの利用者向けドキュメント（理念・規約・使い方）
- [HackMD](https://hackmd.io/@yamisskey-dev)：サーバー管理者や開発メンバーによるドキュメント
- [team.yami.ski](https://team.yami.ski)：有志メンバーによるCTFチームyamiuchiのWriteUp
