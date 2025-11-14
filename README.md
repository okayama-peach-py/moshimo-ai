# 🎭 もしもAI - Streamlit × LLM エンタメチャットアプリ

「もしも猫が話せたら？」「もしも織田信長が令和にいたら？」
そんな“妄想”をLLMで現実にする、キャラクター選択型の対話アプリです。

---

## 🚀 概要

このアプリは、OpenAI API と Streamlit を使って構築した
**対話型ジェネレーティブAIアプリ**です。
ユーザーはキャラクターを選び、自然な会話を楽しむことができます。

| 🐱 猫 | ⚔️ 織田信長 | 🚀 宇宙船AI |
|------|-----------|------------|
| ツンデレで知的な猫が皮肉を交えて回答 | 戦国時代の思考で現代を語る信長 | 論理的な宇宙船AIが冷静に応答 |

---

## 🧰 使用技術

- 🧠 **LLM API**: OpenAI GPT-4 / GPT-4o-mini
- 💻 **フレームワーク**: [Streamlit](https://streamlit.io/)
- 📁 **構成管理**: Git + GitHub
- ⚙️ **その他ライブラリ**: `python-dotenv`, `PyYAML`

---

## 🗂️ プロジェクト構成
```
moshimo-ai/
├─ app.py                # メインアプリ本体
├─ characters.yaml      # キャラクター設定（人格プロンプト）
├─ requirements.txt     # 依存パッケージ
├─ .env.example         # 環境変数テンプレート
└─ assets/              # 各キャラクターのアイコン画像
   ├─ cat.png
   ├─ oda.png
   └─ spaceship.png
```

---

## 📄 ライセンス

このプロジェクトは [MIT License](https://opensource.org/licenses/MIT) の下で公開されています。

### 使用条件
- ✅ 商用・非商用問わず自由に使用可能
- ✅ 改変・再配布可能
- ⚠️ OpenAI APIの使用には別途[OpenAI利用規約](https://openai.com/policies/terms-of-use)が適用されます
- ⚠️ 画像素材（assets/）は各自で用意するか、ライセンスを確認の上ご使用ください

```
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
