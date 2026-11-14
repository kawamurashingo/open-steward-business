# Open Steward — Business Validation

> 既存のPerlシステムを安全に維持するための診断・保守サービスを、実際の顧客課題から育てる。

**企業・開発チーム向け:** [Perl / CPAN 保守リスク診断 — ホームページ](https://kawamurashingo.github.io/open-steward-business/)（試験価格55,000円・税込）  
**お問い合わせ:** [LinkedIn](https://www.linkedin.com/in/shingo-kawamura-20452443)（機密情報は最初の連絡に含めないでください）  

**Status:** 検証中 / 2026-11-15 時点の公開用初期計画  
**First milestone:** 2026-12-15までに「Perl / CPAN 保守リスク診断（55,000円・税込、試験価格）」を1件有償受注する。

## ホームページ（GitHub Pages）

企業向けの日本語ホームページはGitHub Pagesにデプロイされました。

- **[ホームページを開く](https://kawamurashingo.github.io/open-steward-business/)**
- [サイトソース（HTML）](docs/index.html)
- [公開設定・表示確認手順](SITE_SETUP.md)
- [GitHub Pagesの成功したデプロイ](https://github.com/kawamurashingo/open-steward-business/actions/runs/43654075009)

**公開状態:** GitHub Actionsのビルド・デプロイは2026-11-15（日本時間）に成功。外部ブラウザでのページ表示・モバイル表示の最終確認は未実施です。

## 方針

- OSS活動の実績は [CPAN Rescue](https://cpan-rescue.com/) と [JQ-Lite](https://kawamurashingo.github.io/JQ-Lite/) の公式ホームページで紹介する。重複する独立した「Open Steward」OSSプロジェクトは実績一覧から外し、OSS利用そのものを有料化しない。
- 販売対象は企業に提供する調査・診断・作業・支援。OSSに一般化できる修正は、適切な権利・守秘義務・ライセンスの範囲で還元を検討する。
- 最初の30日は大型受託よりも、**誰が・何に・なぜ支払うか**を検証する。
- 単価や月額保守は仮説。顧客の反応と工数で見直す。

## 現在のオファー

**Perl / CPAN 保守リスク診断** — 55,000円（税込・試験価格）  
対象: 小規模な1システム、または限定したモジュール群。  
納品: 依存関係一覧、保守・互換性リスク、テスト/CI改善案、優先度付き保守計画。  
**まずはこちら:** [企業向けホームページ](https://kawamurashingo.github.io/open-steward-business/) / [文章版サービス案内](SERVICE.md)  
詳細: [サービス仕様](docs/service-offer.md) / [レポートひな形](docs/sample-diagnostic-report.md) / [事前確認シート](docs/intake-checklist.md)

## KPI（初期30日）

| 指標 | 目標 | 実績（随時更新） |
| --- | ---: | ---: |
| 協業候補・紹介先の意見 | 3件以上 | 0 |
| YAPC等での課題ヒアリング | 5人 | 0 |
| 後日相談につながる相手 | 2人 | 0 |
| 具体的見積もり | 1〜3件 | 0 |
| 有償診断受注 | **1件** | **0件** |

## 実行ロードマップ

| 期限 | やること | 成功条件 | 状態 |
| --- | --- | --- | --- |
| 11/20 | 商品説明ページと診断範囲の確定 | 料金・納品物・除外事項を説明できる | **完了（11/15）** |
| 11/25 | 開発会社2社＋紹介先に連絡 | 意見3件以上を得る | 未着手 |
| 11/27–29 | YAPCで課題を聞く（開催・参加は要確認） | 5人と会話・2件の継続接点 | 未着手 |
| 12/07 | 小規模診断の提案 | 見積もり1〜3件 | 未着手 |
| 12/15 | 実験結果を見直す | 受注1件を目標に判断・改善 | 未着手 |

各タスクの詳細・チェックリストは [GitHub Issues](../../issues) に登録する。

## 管理の原則

1. **GitHub Issues:** 作業を1タスク1Issueで追跡。
2. **GitHub Projects（必要になったら）:** 状態は `Todo / Doing / Waiting / Done`、種別は `商品設計 / 接点づくり / ヒアリング / 提案 / 検証`。
3. **営業・接点管理:** [docs/lead-pipeline.md](docs/lead-pipeline.md)。公開できる仮説とテンプレートのみを記載する。実際のやり取りは非公開で管理する。
4. **週次レビュー:** [reviews/weekly-review.md](reviews/weekly-review.md) を週1回更新。
5. **公開範囲:** 本リポジトリはPublic運用。個人情報・契約書・非公開の提案/見積・商談メモ・APIキー・顧客ソースコードをコミットしない。実顧客データや連絡履歴は安全な非公開の場所で別管理する。

## 最初にやること

[サービス仕様](docs/service-offer.md)と[公開サービス説明ページ](SERVICE.md)は策定済み。次は11月25日までに協業候補からの意見収集に取り組む。[運用手順](PROJECT_SETUP.md)
