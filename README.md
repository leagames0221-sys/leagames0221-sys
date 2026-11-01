# tomohiro takada

業務の仕組みを、公開されている資料と無料の部品で作っています。どの repository も 1 台のノート PC で動きます。README には「既存の物との違い」と「確かめた結果」を書いています。

## ポートフォリオ

| repository | 何をするか | 確かめた結果 |
|---|---|---|
| [mfg-revision-diff](https://github.com/leagames0221-sys/mfg-revision-diff) | 工程表と部品表の 2 つの版を比べ、同じ・変更・追加・削除・移動に分けて、画面と Excel に出します (Java・B2MML) | 試験 101 本。架空のデータで、分け方の正しさを測っています |
| [close-matching-kit](https://github.com/leagames0221-sys/close-matching-kit) | 月末に銀行の明細と帳簿を突き合わせます。差を直す仕訳は作る人と承認する人を分け、残高が合ったかを 1 枚で見せます (Python・SQLite) | 正解付きの公開データで、自動で組んだ 5,564 組のうち 5,541 組が正しい組でした。試験 450 本 |
| [camera-cloud-core](https://github.com/leagames0221-sys/camera-cloud-core) | 監視カメラの映像を、会社ごとに分けて見せるクラウドの小型版です。他社のカメラは「見つかりません」と表示されます (Docker Compose・Keycloak・MediaMTX) | 単体試験 419 本、結合試験 52 + 42 + 11 本。コードを 19 か所わざと壊し、どれも試験が失敗することを確かめました |
| [devlake-agent-review-burden](https://github.com/leagames0221-sys/devlake-agent-review-burden) | Claude・Cursor・Copilot など AI ツール別に、PR のマージ数・最初のレビューまでの時間などを、無料の Apache DevLake と Grafana で比べます | 公開 repository 2 本の PR 297 本で、別の script で計算した値と 7,062 項目すべてが一致しました |

## それ以前に作った物

- [oidc-lens](https://github.com/leagames0221-sys/oidc-lens)：OIDC / OAuth 2.0 の認可サーバの公開設定を、RFC などの条文を出典にして点検します
- [invoice-lens](https://github.com/leagames0221-sys/invoice-lens)：請求書 PDF から、支払業務の工程 (抽出・照合・承認など) を通します
- [stresscheck-sentinel](https://github.com/leagames0221-sys/stresscheck-sentinel)：法定ストレスチェックの採点と、その上で AI に何を触らせないかの守り (人のレビューなど) です

## ご連絡

この repository の Issues からお願いいたします。
