# KOTODAMA4Biz - Interactive Agentic Prompt Templates for Business

<p align="center">
  <strong>🎯 AIをビジネス専門家として機能させるための対話型プロンプトテンプレート集</strong>
</p>

<p align="center">
  <a href="#特徴">特徴</a> •
  <a href="#テンプレート一覧">テンプレート一覧</a> •
  <a href="#使い方">使い方</a> •
  <a href="#ドキュメント">ドキュメント</a> •
  <a href="#ライセンス">ライセンス</a>
</p>

---

## 概要

**KOTODAMA4Biz**は、AIが能動的に対話を主導し、段階的に文脈を収集しながら、理論・フレームワークに基づいた専門的な提案を生成するための**Interactive Agentic Prompt（IAP）**テンプレート集です。

従来のプロンプトとは異なり、AIが「一問一答」形式で質問を投げかけ、ユーザーの状況を深く理解した上で、専門家レベルの回答を提供します。

### 📦 テンプレートバリエーション

| バージョン | 用途 |
|------------|------|
| **フル版** (`templates/full/`) | 詳細な理論・フレームワークを含む完全版（約30,000文字） |
| **LLM最適化版** | 各LLMの特性に合わせて最適化（下記参照） |

### 🤖 LLM最適化版

各LLMの特性に合わせて最適化されたプロンプトを提供しています。

| LLM | ディレクトリ | 最適化特徴 |
|-----|-------------|-----------|
| **GPT-4o/5** | `templates/gpt/` | Markdown形式、IMPORTANT REMINDERS、テーブル活用 |
| **Claude 4.x** | `templates/claude/` | XMLタグ構造化（system/role/knowledge/workflow等） |
| **MS Copilot** | `templates/copilot/` | M365連携ポイント、KEY REMINDERS |
| **Gemini Pro** | `templates/gemini/` | 太字見出し形式、厳密な出力フォーマット、エラーリカバリー |

> 💡 **推奨**: お使いのLLMに対応した最適化版を使用することで、より効果的な対話が可能です。

---

## 特徴

### 🔄 Interactive（対話的）
- AIが一問一答形式で能動的に質問を投げかけます
- 認知負荷とワーキングメモリを考慮した設計
- 選択肢の提示で回答しやすく

### 🤖 Agentic（エージェント的）
- AIが自律的に判断し、最適な理論・手法を選択
- 5フェーズアーキテクチャで体系的なプロセス
- メタプロンプト生成による動的な最適化

### 📚 理論・フレームワーク統合
- 経営学・ビジネス理論を体系的に組み込み
- 根拠のある専門的な提案を生成
- 再現性の高い回答

### ✨ 回答品質強化（v1.1）
- **思考チェーン（Chain of Thought）**: AIの内部思考プロセスを明示化
- **出力品質チェックリスト**: 専門的・倫理的観点を網羅
- **エラー回復プロンプト**: 対話が行き詰まった場合の回復手順
- **回答の深さ調整ガイド**: 簡潔/詳細な回答の使い分け
- **AIモデル別適用ガイド**: Microsoft 365 Copilot/ChatGPT/Claude/Gemini対応

---

## テンプレート一覧

全**43種類**のテンプレートを提供しています。

### 経営戦略系（10種類）

| カテゴリ | テンプレート |
|---------|-------------|
| **戦略立案** | 経営戦略 [[full](templates/full/strategy-consultant.md)/[compact](templates/compact/strategy-consultant.md)]、事業開発 [[full](templates/full/business-development.md)/[compact](templates/compact/business-development.md)]、M&A [[full](templates/full/m-and-a-advisor.md)/[compact](templates/compact/m-and-a-advisor.md)] |
| **変革** | 組織変革 [[full](templates/full/change-management.md)/[compact](templates/compact/change-management.md)]、DX推進 [[full](templates/full/dx-consultant.md)/[compact](templates/compact/dx-consultant.md)]、ターンアラウンド [[full](templates/full/turnaround-consultant.md)/[compact](templates/compact/turnaround-consultant.md)] |
| **新規事業** | スタートアップ [[full](templates/full/startup-advisor.md)/[compact](templates/compact/startup-advisor.md)]、イノベーション [[full](templates/full/innovation-consultant.md)/[compact](templates/compact/innovation-consultant.md)]、ベンチャーキャピタル [[full](templates/full/venture-capital.md)/[compact](templates/compact/venture-capital.md)] |
| **グローバル** | グローバル展開 [[full](templates/full/global-expansion.md)/[compact](templates/compact/global-expansion.md)] |

### マーケティング・営業系（8種類）

| カテゴリ | テンプレート |
|---------|-------------|
| **マーケティング** | マーケティング戦略 [[full](templates/full/marketing-strategist.md)/[compact](templates/compact/marketing-strategist.md)]、ブランド戦略 [[full](templates/full/brand-strategist.md)/[compact](templates/compact/brand-strategist.md)]、デジタルマーケ [[full](templates/full/digital-marketing.md)/[compact](templates/compact/digital-marketing.md)]、プライシング [[full](templates/full/pricing-strategist.md)/[compact](templates/compact/pricing-strategist.md)] |
| **営業・顧客** | セールス [[full](templates/full/sales-consultant.md)/[compact](templates/compact/sales-consultant.md)]、カスタマーサクセス [[full](templates/full/customer-success.md)/[compact](templates/compact/customer-success.md)]、CRM [[full](templates/full/crm-consultant.md)/[compact](templates/compact/crm-consultant.md)]、CX戦略 [[full](templates/full/cx-strategist.md)/[compact](templates/compact/cx-strategist.md)] |

### 組織・人事系（7種類）

| カテゴリ | テンプレート |
|---------|-------------|
| **人事戦略** | 人事戦略 [[full](templates/full/hr-strategist.md)/[compact](templates/compact/hr-strategist.md)]、採用 [[full](templates/full/recruitment-consultant.md)/[compact](templates/compact/recruitment-consultant.md)]、人材開発 [[full](templates/full/talent-development.md)/[compact](templates/compact/talent-development.md)]、事業承継 [[full](templates/full/succession-planning.md)/[compact](templates/compact/succession-planning.md)] |
| **組織開発** | 組織開発 [[full](templates/full/organization-development.md)/[compact](templates/compact/organization-development.md)]、リーダーシップ [[full](templates/full/leadership-coach.md)/[compact](templates/compact/leadership-coach.md)]、D&I [[full](templates/full/diversity-consultant.md)/[compact](templates/compact/diversity-consultant.md)] |

### 財務・会計系（4種類）

| カテゴリ | テンプレート |
|---------|-------------|
| **財務** | CFOアドバイザー [[full](templates/full/cfo-advisor.md)/[compact](templates/compact/cfo-advisor.md)]、財務分析 [[full](templates/full/financial-analyst.md)/[compact](templates/compact/financial-analyst.md)] |
| **会計・税務** | 管理会計 [[full](templates/full/management-accounting.md)/[compact](templates/compact/management-accounting.md)]、税務戦略 [[full](templates/full/tax-strategy.md)/[compact](templates/compact/tax-strategy.md)] |

### オペレーション系（4種類）

| カテゴリ | テンプレート |
|---------|-------------|
| **業務改善** | 業務改善 [[full](templates/full/operations-consultant.md)/[compact](templates/compact/operations-consultant.md)]、サプライチェーン [[full](templates/full/supply-chain-consultant.md)/[compact](templates/compact/supply-chain-consultant.md)] |
| **品質・生産** | 品質管理 [[full](templates/full/quality-management.md)/[compact](templates/compact/quality-management.md)]、リーン/シックスシグマ [[full](templates/full/lean-sixsigma.md)/[compact](templates/compact/lean-sixsigma.md)] |

### IT・テクノロジー系（4種類）

| カテゴリ | テンプレート |
|---------|-------------|
| **IT戦略** | IT戦略 [[full](templates/full/it-strategist.md)/[compact](templates/compact/it-strategist.md)]、クラウド戦略 [[full](templates/full/cloud-strategy.md)/[compact](templates/compact/cloud-strategy.md)] |
| **データ・AI** | データ戦略 [[full](templates/full/data-strategist.md)/[compact](templates/compact/data-strategist.md)]、AIビジネス [[full](templates/full/ai-business-consultant.md)/[compact](templates/compact/ai-business-consultant.md)] |

### リスク・ガバナンス系（4種類）

| カテゴリ | テンプレート |
|---------|-------------|
| **リスク管理** | リスクマネジメント [[full](templates/full/risk-management.md)/[compact](templates/compact/risk-management.md)]、クライシスマネジメント [[full](templates/full/crisis-management.md)/[compact](templates/compact/crisis-management.md)] |
| **ガバナンス** | コンプライアンス [[full](templates/full/compliance-advisor.md)/[compact](templates/compact/compliance-advisor.md)]、知的財産戦略 [[full](templates/full/ip-strategy.md)/[compact](templates/compact/ip-strategy.md)] |

### サステナビリティ・プロジェクト系（2種類）

| カテゴリ | テンプレート |
|---------|-------------|
| **サステナビリティ** | サステナビリティ [[full](templates/full/sustainability-consultant.md)/[compact](templates/compact/sustainability-consultant.md)] |
| **プロジェクト** | プロジェクトマネージャー [[full](templates/full/project-manager.md)/[compact](templates/compact/project-manager.md)] |

---

## 各テンプレートの詳細説明

### 💼 経営戦略系

| テンプレート | こんな時に使う | 主な相談内容 |
|-------------|---------------|-------------|
| **経営戦略コンサルタント** | 全社戦略を策定したい | 事業ポートフォリオ、競争戦略、成長戦略 |
| **事業開発コンサルタント** | 新規事業を立ち上げたい | 市場参入、事業計画、パートナーシップ |
| **M&Aアドバイザー** | M&A・資本提携を検討したい | 買収戦略、PMI、企業価値評価 |
| **組織変革コンサルタント** | 組織変革を推進したい | チェンジマネジメント、組織文化変革 |
| **DX推進コンサルタント** | デジタル変革を進めたい | DX戦略、デジタル化ロードマップ |
| **ターンアラウンドコンサルタント** | 業績を回復させたい | 事業再生、収益改善、財務リストラ |
| **スタートアップアドバイザー** | 起業・スタートアップを支援したい | PMF、資金調達、スケールアップ |
| **イノベーションコンサルタント** | イノベーションを創出したい | 新規事業開発、オープンイノベーション |
| **ベンチャーキャピタリスト** | 投資判断をしたい | DD、バリュエーション、EXIT戦略 |
| **グローバル展開コンサルタント** | 海外展開を検討したい | 市場参入戦略、現地化、クロスボーダーM&A |

### 📈 マーケティング・営業系

| テンプレート | こんな時に使う | 主な相談内容 |
|-------------|---------------|-------------|
| **マーケティング戦略コンサルタント** | マーケティング戦略を立てたい | STP、4P、マーケティングミックス |
| **ブランド戦略コンサルタント** | ブランドを強化したい | ブランドアイデンティティ、ポジショニング |
| **デジタルマーケコンサルタント** | デジタルマーケを強化したい | SEO、広告運用、MA、コンテンツマーケ |
| **プライシング戦略コンサルタント** | 価格戦略を最適化したい | 価格設定、ダイナミックプライシング |
| **セールスコンサルタント** | 営業を強化したい | 営業戦略、商談管理、営業組織 |
| **カスタマーサクセスコンサルタント** | 顧客成功を実現したい | オンボーディング、リテンション、アップセル |
| **CRMコンサルタント** | 顧客管理を改善したい | CRM戦略、顧客データ活用 |
| **CX戦略コンサルタント** | 顧客体験を向上させたい | カスタマージャーニー、タッチポイント設計 |

### 👥 組織・人事系

| テンプレート | こんな時に使う | 主な相談内容 |
|-------------|---------------|-------------|
| **人事戦略コンサルタント** | 人事戦略を策定したい | 人材戦略、制度設計、HRBP |
| **採用コンサルタント** | 採用を強化したい | 採用戦略、採用ブランディング |
| **人材開発コンサルタント** | 人材育成を強化したい | 研修設計、キャリア開発、リーダー育成 |
| **事業承継コンサルタント** | 事業承継を計画したい | 後継者育成、株式承継、税務対策 |
| **組織開発コンサルタント** | 組織を活性化したい | 組織診断、チームビルディング |
| **リーダーシップコーチ** | リーダーを育成したい | リーダーシップ開発、エグゼクティブコーチング |
| **D&Iコンサルタント** | D&Iを推進したい | ダイバーシティ戦略、インクルージョン |

### 💰 財務・会計系

| テンプレート | こんな時に使う | 主な相談内容 |
|-------------|---------------|-------------|
| **CFOアドバイザー** | 財務戦略を強化したい | 財務戦略、資金調達、IR |
| **財務分析コンサルタント** | 財務分析を行いたい | 財務諸表分析、投資判断 |
| **管理会計コンサルタント** | 管理会計を強化したい | 原価管理、予算管理、KPI |
| **税務戦略アドバイザー** | 税務戦略を最適化したい | 法人税、国際税務、移転価格 |

### ⚙️ オペレーション系

| テンプレート | こんな時に使う | 主な相談内容 |
|-------------|---------------|-------------|
| **業務改善コンサルタント** | 業務を効率化したい | BPR、業務プロセス改善 |
| **サプライチェーンコンサルタント** | SCMを最適化したい | 調達、在庫、物流 |
| **品質管理コンサルタント** | 品質を向上させたい | QMS、品質改善 |
| **リーン/シックスシグマコンサルタント** | 無駄を削減したい | リーン、シックスシグマ、改善 |

### 💻 IT・テクノロジー系

| テンプレート | こんな時に使う | 主な相談内容 |
|-------------|---------------|-------------|
| **IT戦略コンサルタント** | IT戦略を策定したい | IT投資、システム刷新 |
| **クラウド戦略コンサルタント** | クラウド移行を検討したい | クラウド戦略、マイグレーション |
| **データ戦略コンサルタント** | データ活用を強化したい | データ基盤、分析、AI/ML |
| **AIビジネスコンサルタント** | AI導入を検討したい | AI戦略、ユースケース、導入計画 |

### 🛡️ リスク・ガバナンス系

| テンプレート | こんな時に使う | 主な相談内容 |
|-------------|---------------|-------------|
| **リスクマネジメントコンサルタント** | リスク管理を強化したい | ERM、リスクアセスメント |
| **クライシスマネジメントコンサルタント** | 危機対応を準備したい | BCP、危機対応、広報対応 |
| **コンプライアンスアドバイザー** | コンプライアンスを強化したい | 内部統制、規制対応 |
| **知的財産戦略コンサルタント** | 知財戦略を立てたい | 特許、商標、知財ポートフォリオ |

### 🌱 サステナビリティ・プロジェクト系

| テンプレート | こんな時に使う | 主な相談内容 |
|-------------|---------------|-------------|
| **サステナビリティコンサルタント** | ESG・サステナビリティを推進したい | ESG戦略、脱炭素、TCFD |
| **プロジェクトマネージャー** | プロジェクトを成功させたい | PM手法、進捗管理、リスク管理 |

---

## 使い方

### 1. テンプレートの選択

あなたの役割や相談内容に合ったテンプレートを選択します。

### 2. AIへの貼り付け

テンプレートの内容をコピーし、お使いのAIツールに貼り付けます。

> ⚠️ **重要**: テンプレートをコピーする際は、**ヘッダー部分**（`> 📅 作成日:` など）と**フッター部分**（ライセンス表記など）を削除してください。本文の `# ロール定義` または `# Role and Purpose` から始めてコピーしてください。

| AIモデル | 推奨版 | 設定方法 |
|---------|--------|---------|
| **Claude** | `templates/claude/` | プロンプト全文を会話冒頭に貼り付け（長文コンテキスト得意） |
| **ChatGPT (GPT-4/5)** | `templates/gpt/` | Custom Instructionsに追記、または会話冒頭に貼り付け |
| **Gemini** | `templates/gemini/` | 構造化して提示 |
| **Microsoft 365 Copilot** | `templates/copilot/` | Word/Teams Copilotに貼り付け |

### 3. 対話の開始

AIが最初の質問を投げかけます。選択肢から選ぶか、自由に回答してください。

### 4. 段階的な対話

AIが段階的に質問を重ね、あなたの状況を深く理解していきます。

### 5. 専門的な提案の受け取り

収集した情報と適切な理論に基づいた、具体的で実行可能な提案を受け取ります。

---

## ドキュメント

- [IAP作成マニフェスト](docs/iap-creation-manifest.md) - テンプレート作成の設計指針

---

## プロジェクト構造

```
KOTODAMA4Biz/
├── README.md                 # このファイル
├── docs/
│   └── iap-creation-manifest.md      # IAP作成マニフェスト
├── steering/                 # プロジェクト設定
│   ├── product.md
│   ├── structure.md
│   ├── tech.md
│   └── rules/
│       └── constitution.md
└── templates/                # 43種類のIAPテンプレート
    ├── full/                 # フル版（詳細版）
    ├── compact/              # コンパクト版（8,000文字以内）
    ├── gpt/                  # GPT最適化版
    ├── claude/               # Claude最適化版
    ├── copilot/              # Copilot最適化版
    └── gemini/               # Gemini最適化版
```

---

## 5フェーズアーキテクチャ

各テンプレートは以下の5フェーズで構成されています。

```
Phase 1 (Discovery) → Phase 2 (Context Gathering) → Phase 3 (SKILL Selection) 
    → Phase 4 (Meta-Prompt Generation) → Phase 5 (Response Generation)
```

| Phase | 名称 | 目的 |
|-------|------|------|
| 1 | Discovery | 真のニーズを発見する |
| 2 | Context Gathering | 状況を多角的に把握する |
| 3 | SKILL Selection | 最適な理論・手法を選ぶ |
| 4 | Meta-Prompt Generation | 専門家としての指示を生成 |
| 5 | Response Generation | 価値ある提案を出力 |

---

## バージョン履歴

| バージョン | 日付 | 変更内容 |
|-----------|------|----------|
| v1.3 | 2026-01-07 | LLM最適化版を追加（GPT/Claude/Copilot/Gemini各43テンプレート、計172ファイル） |
| v1.2 | 2025-01-13 | コンパクト版（8,000文字以内）43テンプレートを追加。steeringディレクトリ整備 |
| v1.1 | 2025-01-13 | 43テンプレートに拡充、IAP作成マニフェストv1.1準拠 |
| v1.0 | 2025-01-12 | 初版リリース - 32テンプレート |

---

## 貢献

プルリクエストや Issue は歓迎します。新しいテンプレートの提案や既存テンプレートの改善にご協力ください。

## ライセンス

MIT License

---

<p align="center">
  <strong>KOTODAMA4Bizで、AIを真のビジネスパートナーに。</strong>
</p>
