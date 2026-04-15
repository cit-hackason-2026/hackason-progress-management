# 授業内ハッカソン 進捗管理リポジトリ

PMBOKの10の知識エリアに沿って、ハッカソンプロジェクトの進捗を管理します。

## ディレクトリ構成

| # | ディレクトリ | 知識エリア | 主な成果物 |
|---|---|---|---|
| 01 | [01-integration](./01-integration) | 統合マネジメント | プロジェクト憲章、統合計画、**SEMP** |
| 02 | [02-scope](./02-scope) | スコープ | スコープ記述書、WBS、**FBS**、**PBS**、要件定義 |
| 03 | [03-schedule](./03-schedule) | スケジュール | スケジュール、マイルストーン |
| 04 | [04-cost](./04-cost) | コスト | 予算計画・実績 |
| 05 | [05-quality](./05-quality) | 品質 | 品質計画、レビュー基準、**MOE/MOP/V&V/TRL/TPM** |
| 06 | [06-resources](./06-resources) | 資源・資材 | チーム編成、使用ツール |
| 07 | [07-communications](./07-communications) | コミュニケーション | 連絡ルール、議事録 |
| 08 | [08-risk](./08-risk) | リスク | リスク登録簿 |
| 09 | [09-procurement](./09-procurement) | 調達 | 調達計画、外部サービス一覧 |
| 10 | [10-stakeholders](./10-stakeholders) | ステークホルダー | ステークホルダー登録簿 |

## システムズエンジニアリング関連文書の対応
| 文書/指標 | 作成フェーズ | 配置場所 |
|-----------|-------------|---------|
| SEMP（SEマネジメント計画） | プロジェクト計画 | [01-integration/semp.md](./01-integration/semp.md) |
| FBS（機能分解） | 要件定義 | [02-scope/fbs.md](./02-scope/fbs.md) |
| PBS（製品分解） | 基本設計 | [02-scope/pbs.md](./02-scope/pbs.md) |
| WBS（作業分解） | PM作成 | [02-scope/wbs.md](./02-scope/wbs.md) |
| MOE（効果指標） | 要件定義→受入 | [05-quality/moe.md](./05-quality/moe.md) |
| MOP（性能指標） | 設計→各テスト | [05-quality/mop.md](./05-quality/mop.md) |
| V&V（検証・妥当性確認） | 検証フェーズ全般 | [05-quality/vandv.md](./05-quality/vandv.md) |
| TRL（技術成熟度） | 全期間 | [05-quality/trl.md](./05-quality/trl.md) |
| TPM（技術性能監視） | 開発中継続 | [05-quality/tpm.md](./05-quality/tpm.md) |

評価指標は `MOE → MOP → V&V → TPM` の4ステップで連携する。

## 運用ルール

- 変更は各ディレクトリ配下の Markdown を直接更新してコミットする
- 議事録は `07-communications/meeting-notes/YYYY-MM-DD.md` の形式で追加する
- 重要な意思決定は `01-integration/decision-log.md` に記録する
