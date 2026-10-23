# 🧸 Toy Lyric Video Maker (おもちゃ風リリックビデオメーカー)

> **スマホ／PCのブラウザ完結で、子供からお年寄りまでおもちゃ感覚でリリックモーションビデオ（MV）を作成・保存できるWebアプリ**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-ff5e7e?style=for-the-badge&logo=github)](https://takosuke0215-ship-it.github.io/toy-lyric/)

---

## 🌟 特徴・機能

- 🎵 **音声＆歌詞の魔法の自動同期**:
  - MP3 / WAV ファイルのアップロード対応
  - Web Audio APIによるリアルタイム波形・ビート解析
  - ワンタップで即座に遊べる内蔵デモ音源（ポップシンセビート）
  - 再生時間（duration）に応じた歌詞の自動タイミングマッピング
- 📱 **画面アスペクト比切替**:
  - 縦型（9:16 - TikTok / Instagram Reels / YouTube Shorts用、720×1280）
  - 横型（16:9 - YouTube通常 / 横画面用、1280×720）
- 🖼️ **背景画像スライドショー**:
  - 最大15枚までの写真・イラストをアップロード可能
  - ビートや小節に合わせたクロスフェード＆Ken Burnsアニメーション
  - 画像がない場合はジャンル別動的グラデーション背景を自動描画
- 📐 **文字レイアウト（4種）＆ サイズ（3種）**:
  - レイアウト: ↔️ 横書き / ↕️ 縦書き / ↗️ 斜め書き / 🌀 ミックス
  - サイズ: 💥 ド派手（超特大・強いビート振動） / 🔤 大きめ / 📝 普通
- 🎨 **スタイルジャンル（全7種）**:
  - シンプル / ポップ / ロック / アイドル / 文学的 / エモい / レトロ8bit
- ✨ **背景図形エフェクト（全8種）**:
  - 🚫 なし / 🔷 幾何学フロー / 🌀 ネオンリング / 🫧 ポップバブル / ⚡ スピードライン / 📐 ポリゴングリッド / ⭐ スターシャワー / 🎪 ミックス
- 🎰 **【最重要】おまかせガチャボタン**:
  - 特大ガチャボタンで、ファンファーレ・画面シェイク・紙吹雪演出とともに全パラメーターを一発ランダム抽選！
- 🌸 **リズム遊び・タップ演出**:
  - キャンバスタップや「はな」「ピカッ」「ハート」「はなび」ボタンで弾けるパーティクル演出
- 🎬 **完全クライアントサイド動画保存 (MP4 / WebM)**:
  - サーバー維持費0円・個人情報安心のブラウザ完結エクスポート
  - `canvas.captureStream()` + Web Audio API + `MediaRecorder` による高画質録画

---

## 🚀 GitHub Pages 公開手順

1. 本リポジトリの **Settings** > **Pages** に移動します。
2. **Build and deployment** の **Source** で `Deploy from a branch` を選択します。
3. **Branch** で `main`（または `master`）の `/ (root)` を選択し、**Save** をクリックします。
4. 数十秒〜数分で `https://<ユーザー名>.github.io/<リポジトリ名>/` にてWebアプリが公開されます！

---

## 🛠️ 技術スタック

- HTML5 / CSS3 (CSS Variables, Flexbox, Grid, 3D Button Shadows)
- JavaScript (Vanilla ES6+)
- Web Audio API (AudioContext, AnalyserNode, AudioBufferSourceNode, MediaStreamDestination)
- HTML5 Canvas 2D API (60FPS レンダリングエンジン)
- MediaRecorder API (ブラウザ内動画・音声エンコード)
- [canvas-confetti](https://github.com/catdad/canvas-confetti)
- Google Fonts (M PLUS Rounded 1c, Dela Gothic One, Shippori Mincho, DotGothic16, Outfit)
