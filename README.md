# tomohiro takada

AI 開発者 / フルスタックエンジニア。 AI ツール・完成品を計 25 repo 公開しています。 すべて MIT license、 商用利用可。

> 「○○ AI ツールは作れますか?」 という商談ご質問は不要です。
> 完成品 + 数値証拠 + 設計判断履歴 + 自動 test 結果が、 GitHub 上でそのままご覧いただけます。

## 完成品ポートフォリオ

| 領域 | repository | 内容 |
|---|---|---|
| M&A 業務 AI | [mais-portfolio](https://github.com/leagames0221-sys/mais-portfolio) (5 tool hub) | ソーシング / DD / Day-1 / 100 日 PMI / 知識蓄積を 5 つの独立ツールで自動化 |
| SaaS データ分析 | [craftstack/data-analytics-demo](https://github.com/leagames0221-sys/craftstack/tree/main/packages/data-analytics-demo) | 解約予測 ROC-AUC 0.7448 + アップセル lift 2.81× + 経営層向け日本語 brief + dashboard 自動生成 |
| フルスタック SaaS | [craftstack](https://github.com/leagames0221-sys/craftstack) | リアルタイム協業 Kanban + 単一テナント RAG を 1 monorepo 同居 (Next.js 16 / Vercel) |
| AI 性能検証 | [longctx-bench-honest](https://github.com/leagames0221-sys/longctx-bench-honest) | 1M token 長文脈性能を 3 基準 (RULER + LongBench v2 + NIAH) で再現可能に数値比較 |
| AI 自動化 RPA | [browser-agent-demo](https://github.com/leagames0221-sys/browser-agent-demo) | 手元 Ollama 経由でブラウザ操作 AI、 外部 API 課金 ZERO |
| 認証認可 / セキュリティ | [oidc-lens](https://github.com/leagames0221-sys/oidc-lens) | OIDC / OAuth / FAPI 認可サーバ設定を条文出典つきで静的レビュー。ほか防御系 CLI を複数公開 |
| 経理 AP 自動化 | [invoice-lens](https://github.com/leagames0221-sys/invoice-lens) | 請求書 PDF から支払業務 11 工程を決定論で一気通貫 (抽出 / 仕訳 / 照合 / 承認 / 不正検知 / 電子保存) |

## 5 分で確認いただける品質指標

- **自動 test 全 PASS** — 各 repo Actions tab で常時緑判定
- **設計判断の完全履歴** — `docs/adr/` に Architecture Decision Record を連番保存
- **security 24h 自動監視 緑** — CodeQL / OpenSSF Scorecard / Dependabot
- **再現性** — clone + 5 コマンド以内で同じ結果
- **商用利用可** — 全 PUBLIC repo に MIT LICENSE 同梱

## 商談

御社の用件に近い完成品を 1 本ご指定いただければ、 派生工数と納期感をご提示いたします。

ご連絡は本 GitHub アカウントの Issues / Discussions 経由でお願いいたします。
