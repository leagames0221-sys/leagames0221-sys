# tomohiro takada

AI 開発者。公式の仕様・法令・公的な基準を一次資料として読み、その要素を写してツールを作っています。各 repo の README と `docs/adr/` に、写し元と設計判断を残しています。

## 公開中のツール

| 領域 | repository | 内容 |
|---|---|---|
| 認証認可 / セキュリティ | [oidc-lens](https://github.com/leagames0221-sys/oidc-lens) | OIDC / OAuth の認可サーバ設定を、RFC 8414・RFC 9700・OIDC Discovery・FAPI 2.0 の条文を出典にして静的にレビュー |
| 経理 AP 自動化 | [invoice-lens](https://github.com/leagames0221-sys/invoice-lens) | 請求書 PDF から支払業務 (AP) の 11 工程を決定論で一気通貫 (抽出 / 仕訳 / 照合 / 承認 / 不正検知 / 電子保存)。ローカル・外部送信なし・合成データ |
| 労務 / AI ガバナンス | [stresscheck-sentinel](https://github.com/leagames0221-sys/stresscheck-sentinel) | 法定ストレスチェックの決定論的な採点コアと、その上の AI ガバナンス層 (境界ゲート・人間レビュー・評価) |

3 本とも MIT License、ランタイムはローカルで動きます。

## ご連絡

この repository の Issues からお願いいたします。
