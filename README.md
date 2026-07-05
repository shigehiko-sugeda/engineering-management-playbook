# Engineering Management Playbook

## 目的

このリポジトリは、組み込みソフトウェア開発の管理職が、Engineering Management / VPoE / 技術部長 / CP 的役割を学び、実務に転用するための個人用プレイブックです。単なる読書メモではなく、将来「技術に強い組織変革リーダー」になるための学習・実践・内省の基盤として使います。

## 想定読者

- 組み込みソフトウェア開発の管理職、リーダー、CP、技術部長候補
- 車載ソフトウェア、SDV / CASE / 知能化、組み込み C++ に関わる人
- VPoE、Engineering Management、技術戦略、開発組織設計、若手育成、経営視点を体系化したい人

## 使い方

1. [概要](docs/00_overview.md) で全体像をつかむ。
2. 週に 1〜2 章を読み、各章の「管理職としての問い」に自分の言葉で回答する。
3. [templates](templates/) のテンプレートを使い、実務に近いメモやレビュー資料に変換する。
4. [exercises](exercises/) の演習で、読んだ内容を自組織に持ち込む前の仮説に落とす。
5. 月に 1 回、学びを [executive_summary](templates/executive_summary.md) 形式で整理する。

## 学習ロードマップ

- **Phase 1: 役割理解** — VPoE、CP、EM、部長の違いを理解する。  
  対象: [01_vpoe_role](docs/01_vpoe_role.md), [11_cp_vs_vpoe](docs/11_cp_vs_vpoe.md)
- **Phase 2: 組織と戦略** — 技術戦略、組織設計、Team Topologies を学ぶ。  
  対象: [02_engineering_strategy](docs/02_engineering_strategy.md), [03_organization_design](docs/03_organization_design.md), [04_team_topologies](docs/04_team_topologies.md)
- **Phase 3: 開発プロセス** — DevOps、DORA、品質、技術的負債、AI 活用を実務視点で整理する。  
  対象: [05_development_process](docs/05_development_process.md), [06_ai_development_platform](docs/06_ai_development_platform.md), [08_metrics_and_dora](docs/08_metrics_and_dora.md), [09_quality_and_technical_debt](docs/09_quality_and_technical_debt.md)
- **Phase 4: 人と経営** — 若手育成、財務、投資対効果、経営層への説明を学ぶ。  
  対象: [07_engineer_growth](docs/07_engineer_growth.md), [10_business_and_finance](docs/10_business_and_finance.md)
- **Phase 5: 文脈化** — 組み込み・車載・SDV の制約を踏まえ、4 年ロードマップを作る。  
  対象: [12_embedded_software_context](docs/12_embedded_software_context.md), [13_four_year_roadmap](docs/13_four_year_roadmap.md)

## 週次レビュー方法

- 今週読んだ章と、実務に使えそうな論点を 3 つ書く。
- 自組織に当てはめる場合の前提・制約・リスクを分ける。
- 「来週 30 分で試せる行動」を 1 つだけ決める。
- AI に要約、反対意見、経営層向け説明への変換を依頼し、表現を磨く。

## 成果物の増やし方

- 新しい学びは `docs/` に章として追加する。
- 実務で使える型は `templates/` に追加する。
- 自分に問いを立てる内容は `exercises/` に追加する。
- 書籍、論文、キーワードは `references/` に追記する。
- 追加時は、社外秘情報や会社固有情報を含めず、抽象化した学習資産として残す。

## 注意

社外秘情報、会社固有情報、未公開のプロジェクト情報、実在企業の内部事情として断定できない情報は入れないでください。実務メモを作る場合も、固有名詞・数値・組織名は匿名化または一般化してください。

## 次の学習ステップ

まず [01_vpoe_role](docs/01_vpoe_role.md) を読み、[organization_diagnosis](templates/organization_diagnosis.md) を使って自組織の課題を仮説レベルで整理してください。次に [05_executive_proposal](exercises/05_executive_proposal.md) で本部長向け 1 枚サマリーに変換します。
