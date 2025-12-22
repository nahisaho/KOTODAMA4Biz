# KOTODAMA4Biz 技術仕様

## テンプレート仕様

### フル版
- **文字数**: 約25,000〜32,000文字
- **用途**: 長文コンテキスト対応AI（Claude、GPT-4等）
- **特徴**: 詳細な理論・フレームワーク、複数の使用例

### コンパクト版
- **文字数**: 8,000文字以内（厳守）
- **用途**: トークン制限のあるAI、ChatGPT無料版等
- **特徴**: 必須要素を維持しつつ圧縮

## 5フェーズアーキテクチャ

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

## IAP作成マニフェスト v1.1 準拠要件

### 必須セクション
1. System Prompt
2. Phase 1-5
3. 対話フロー制御（状態遷移、1問1答の原則、例外処理）
4. 使用例（最低1つ）

### コンパクト版追加要件
- 8,000文字以内
- 必須セクション維持
- フレームワークテーブル圧縮

## 対応AIモデル

| AIモデル | 推奨版 | 設定方法 |
|---------|--------|---------|
| Claude | フル版 | プロンプト全文を貼り付け |
| GPT-4 | フル版 | Custom Instructionsまたは会話冒頭 |
| ChatGPT無料版 | コンパクト版 | 会話冒頭に貼り付け |
| Gemini | コンパクト版 | 構造化して提示 |
| Microsoft 365 Copilot | コンパクト版 | Word/Teams Copilotに貼り付け |

## Markdown形式

- 見出し: `#`, `##`, `###`
- テーブル: Markdown標準形式
- コードブロック: `` ``` `` で囲む
- リスト: `-` または `1.`
