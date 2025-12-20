# カナ：字創ノ界 (KANA: ZISOHKAI) ⚔️

<p align="center">
  <b>「漢字を創り、その力で戦う。」</b><br>
  Kanji Creation Action RPG
</p>

![Status](https://img.shields.io/badge/status-in%20development-orange)
![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-black)
![Engine](https://img.shields.io/badge/engine-Unity-black)

---

## 📖 概要 (Overview)

**カナ：字創ノ界 (KANA: ZISOHKAI)** は、漢字の「部品」を集めて「実在する漢字」を創造し、その漢字に変身して戦う **2Dアクションゲーム** です。

「漢字を勉強させる」のではなく、**「漢字を使って遊んでいたら、結果として理解していた」** という **Stealth Education (ステルス教育)** を目指しています。
意味や読みを強制的に表示せず、プレイヤーは「形」と「構造」を武器として扱うことで、直感的に漢字の本質を理解します。

### 🌏 世界観 (World)
この世界は **「字霊（じれい）」** によって成り立っている。
かつて完全な形を持っていた漢字たちは、ある事件をきっかけに崩壊し、部品だけの存在や、意味を失った文字が徘徊するようになった。
主人公 **Kana** は、唯一失われた漢字を再構築できる **「創字（そうじ）」** の力を持つ存在として、世界を取り戻す旅に出る。

---

## 🎮 ゲームループ (Core Loop)

1.  **探索・戦闘 (Explore):** 崩壊した世界を探索し、敵（崩れた文字）と戦う。
2.  **部品収集 (Collect):** 敵を倒したり宝箱から「偏（へん）」や「旁（つくり）」などの部品を入手。
3.  **創字 (Synthesize):** 手に入れた部品を正しい位置に配置し、実在する漢字を完成させる。
4.  **変身・攻略 (Transform):** 完成した漢字の力を宿して変身。新たな能力でステージを攻略する。

---

## ✨ 主要機能 (Key Features)

### 1. 🧩 漢字合成システム (Kanji Synthesis)
単なるクラフトではありません。「木」を左に、「公」を右に置けば「松」になる。
**実際の漢字構造** に基づいたパズル要素。正しい位置（偏・旁・冠・脚）に配置しなければ漢字は生まれません。
正解を暗記するのではなく、「構造」を直感的に理解するデザインです。

### 2. 🔥 変身システム (Transformation)
創り出した漢字に変身することで、その意味に応じた能力を発揮します。
*   **「火」**: 燃焼攻撃、氷を溶かす。
*   **「水」**: 激流攻撃、溶岩を冷やす。
*   **「林」**: 分身、足場生成。
*   **「山」**: 高い防御力、強固な壁。

### 3. 📜 熟語スキル (Idiom Skills)
単体では戦えない文字も、組み合わせることで強力な **「熟語（必殺技）」** となります。
二字熟語や四字熟語を完成させることで、一時的に強力な効果を発動できます。

### 4. 🧠 適応型ヒント (Adaptive Hints)
ユーザーの習熟度や年齢に応じてヒントレベルが自動調整されます。
*   **低年齢:** 視覚的なガイドを多めに表示。
*   **上級者:** 部品のみのストイックな表示。

---

## 🛠 技術スタック (Tech Stack)

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Engine** | **Unity (2D)** | Cross-platform game engine |
| **Language** | **C#** | Game logic scripting |
| **AI Support** | **Gemini / Antigravity** | Development assistance & data generation |
| **Data** | **ScriptableObject** | Kanji, Enemy, and Stage data management |
| **Assets** | **Nono Banana Pro** | Pixel art style integration |
| **Platform** | **iOS / Android** | Mobile first design |

---

## 📂 開発方針 (Development Policy)
*   **Data Driven:** 漢字、敵、ステージは全てデータとして管理し、拡張性を確保。
*   **No Forced Learning:** ポップアップや強制的な解説UIは排除。
*   **Small Start:** 小さく作り、AIを活用して高速にコンテンツを拡充する。

---

## 🚀 今後のロードマップ (Roadmap)
*   [ ] 合成UIのプロトタイプ作成
*   [ ] 最初のステージ（チュートリアル）の実装
*   [ ] 漢字データ基盤（ScriptableObject）の構築
*   [ ] 辞典UI ("Meaning" is hidden until opened) の実装

---

## 👨‍💻 開発者 (Developer)
**Enludus**
Contact: <https://enludus.vercel.app>

<p align="center"> 
    © 2025 Kana: ZISOHKAI Project. All rights reserved. 
</p>
