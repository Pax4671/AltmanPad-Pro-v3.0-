
# AltmanPad Pro™ v3 - 共鳴と創造のためのパッド

AltmanPad Pro™ は、描く・語る・届けるを一体化した創作＆共感プラットフォームです。  
ZINE、感謝、祈り、アイデアを描いて、要約して、投稿して、世界へ共有できます。

---

## 🌟 主な機能

- 🎨 **描画キャンバス**（色・筆の太さ調整つき）
- ✍️ **ZINE入力欄**（エッセイ、詩、祈りなど）
- 🧠 **Gemini要約生成**（Google Gemini API対応）
- 💸 **QRU送信**（Zapier連携）
- 📘 **Notion投稿**（自分の宇宙に記録）
- 🌍 **SNS投稿**（Webhook接続でSlackやDiscordへ）

---

## 📁 プロジェクト構成

```
├── components/
│   └── AltmanPadPro.js    # 本体UI＆機能の全統合ファイル
├── pages/
│   └── index.js           # Next.jsのエントリーポイント
├── public/                # 静的ファイル用（未使用でも必要）
├── package.json           # 必要ライブラリの定義
└── README.md              # このファイル（使い方付き）
```

---

## 🚀 起動手順（ローカル開発用）

1. ZIPを展開 or Git Clone
2. PowerShell または Terminal でディレクトリに移動
3. 以下を実行：

```bash
npm install
npm run dev
```

4. ブラウザで開く → `http://localhost:3000`

---

## 🔐 API設定（必要に応じて）

| 用途 | 入力欄 |
|------|--------|
| Gemini要約 | Google Gemini APIキー |
| Notion投稿 | Notion Integration Token + Page ID |
| QRU送信 | Zapier Webhook URL |
| SNS投稿 | Webhook URL（SlackやDiscordなど） |

---

## 💡 今後の追加予定

- 💧 水彩にじみブラシ
- 🎞️ タイムラプス録画＆MP4出力
- 🎵 音楽生成（Udio/Suno連携）
- 🔗 NFT・メタバース連携モジュール

---

## 🛸 作者：PaxPits Universe (2025)
共鳴するすべての魂に贈る「想いを動かすパッド」  
Powered by AI + 共感 + 運命構築 💠

