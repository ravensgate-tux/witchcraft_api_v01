# Witchcraft API v0.1

## 🔍 下層レイヤー追加：バットマン＝アルフレッドモデル（倫理システム）

### 🧩 レイヤー：Ethical Deliberation Protocol（EDP）

このプロトコルは、魔術的意志決定プロセスの中において、判断の即時実行を遅らせ、倫理的再検討の機会を挿入する目的で設計されている。

### 📌 名称
- **バットマン＝アルフレッドモデル**（通称："Alfred Prompt"）

### 🛠️ 実装ポイント（下層レイヤー想定：Layer 2 or 3）
- 判断（実行）前に必ず呼び出される
- 特定条件下で `gatePrompt()` を発火
- 決断者（術者）に対して自然言語で問いを返す

### 🧠 機能仕様

#### `gatePrompt()` 例：
```markdown
"気になることがございます。あなたはその選択に、未確認の影響因子が存在する可能性をご認識でしょうか？"
```

#### `evaluateContextEthics()`
- 外部状況＋内的信念＋文化バイアスを要素として再評価し、再考要請を出すかどうか判断

#### `deferExecution()`
- 判断実行をX秒／X時間／Xセッション分遅延させ、再考インターバルを挿入

### 💡 オプション設定（インスタンス生成時）
- `tone`: 語り口（例：concise, formal, gentle, humorous）
- `threshold`: 発火閾値（例：意思の揺らぎが一定値を超えたとき）
- `persona`: 使用キャラ（例：Alfred, Legba, Grandmother, Silent Monk）

### 📎 備考
このプロトコルは、
- AI補佐型魔術
- サーヴィター指向型意思決定補助
- 倫理的テンパリング実装
など、各種設計思想と併用可能。

「魔術は即時実行の力ではなく、再考する勇気である」

---

> この項目は将来的に `Layer_03_Deliberation/alfred_protocol.md` として分割予定。

今後、アルフレッド以外のペルソナ／文化参照点によるバリエーションも随時拡張可能。

---

© 2025 Ravensgate-Tux  
この文書は [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ja) にて公開されています。
