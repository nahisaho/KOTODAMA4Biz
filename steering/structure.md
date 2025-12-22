# KOTODAMA4Biz プロジェクト構造

```
KOTODAMA4Biz/
├── README.md                 # プロジェクト説明
├── LICENSE                   # MITライセンス
├── AGENTS.md                 # エージェント設定（任意）
├── docs/
│   ├── iap-creation-manifest.md      # IAP作成マニフェスト
│   ├── interactive-agentic-prompt-guide.md  # 完全ガイド（任意）
│   └── customization-guide.md        # カスタマイズガイド（任意）
├── steering/                 # プロジェクト設定
│   ├── product.md            # プロダクト定義
│   ├── structure.md          # 構造定義（このファイル）
│   ├── tech.md               # 技術仕様
│   └── rules/
│       └── constitution.md   # プロジェクト憲章
└── templates/                # 43種類のIAPテンプレート
    ├── full/                 # フル版（約30,000文字）
    │   ├── strategy-consultant.md
    │   ├── business-development.md
    │   ├── m-and-a-advisor.md
    │   └── ... (43ファイル)
    └── compact/              # コンパクト版（8,000文字以内）
        ├── strategy-consultant.md
        ├── business-development.md
        ├── m-and-a-advisor.md
        └── ... (43ファイル)
```

## ファイル命名規則

### テンプレートファイル
- 形式: `{role-name}.md`
- 例: `strategy-consultant.md`, `cfo-advisor.md`
- 小文字、ハイフン区切り

### ドキュメント
- 形式: `{document-name}.md`
- 小文字、ハイフン区切り

## ディレクトリ説明

| ディレクトリ | 説明 |
|-------------|------|
| `docs/` | ドキュメント・ガイド |
| `steering/` | プロジェクト設定・ルール |
| `templates/full/` | フル版テンプレート |
| `templates/compact/` | コンパクト版テンプレート |
