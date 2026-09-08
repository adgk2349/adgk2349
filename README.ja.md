# イ・スンミン (Seung Min Lee)

[English](README.md) · [한국어](README.ko.md) · [日本語](README.ja.md)

**iOS & Full-Cycle Developer**  
課題を素早く構造化し、プロダクト化までつなげる開発者です。

[Email](mailto:adgk2349b@gmail.com) | [GitHub](https://github.com/adgk2349) | [Portfolio](https://adgk2349.github.io)

---

## Professional Summary

- 企画、開発、デプロイまでを一人で回し、実用的なツールを継続的に作っています。
- Swift/SwiftUI を中心としたアプリ開発と、Python ベースの自動化ツール開発を並行しています。
- On-device AI、ローカル実行環境、文字コード/互換性の問題解決に強みがあります。
- Linux + Docker + Nginx を用いた個人サービス運用環境を構築・管理してきました。

---

## Tech Stack

| Category | Skills |
| --- | --- |
| Mobile | Swift, SwiftUI, UIKit, Combine |
| AI & Data | Python, PyTorch, Whisper (Local/API), Prompt Engineering |
| Backend & Infra | Django, Docker, Nginx, Linux (Ubuntu) |
| Collaboration | Git, GitHub Actions, Figma, Slack |

---

## Featured Public Repositories

### 1) PLOS: データと実行環境を自ら管理する個人AIワークスペース
- Repo: [PLOS-for-Mac](https://github.com/adgk2349/PLOS-for-Mac)
- 外部AIサービスのデータ処理に対する不安をきっかけに、GPTやClaudeを使う中で観察した挙動をもとに、ローカル推論・出力処理・会話メモリの構造を自ら設計しました。
- モデルの性能が向上するたびにガードレール(sanitizer)の介入度合いを見直し、ユーザー情報を個別の事実単位で保存するか文脈ごと保持するかを検討してメモリ構造を設計しました。

### 2) FlowMap: AIコーディング中のコード構造と変更影響を確認するツール
- Repo: [FlowMap-AI_Code_Hallucination_Guard_for_Swift](https://github.com/adgk2349/FlowMap-AI_Code_Hallucination_Guard_for_Swift)
- AIコーディングで会話が長くなると、モデルが変数名を混同したり、以前実装した機能を見落とす問題を経験し、コード構造と関係をグラフで直接確認できるツールとして開発しました。
- 高速な解析のためコアエンジンをRustで実装し、VS Code拡張の配布版でのみ発生した右クリック不具合や、ノードの重なりによる可読性の問題を後のアップデートで改善しました。

### 3) Biblity: 毎日気軽に出会う聖書の一節
- 既存の聖書アプリは情報量が多く画面が複雑に感じたため、ランダムな一節や通知で一つの節に集中できるiOSアプリを作りました。
- 初期はWebから節を取得する方式でしたが、データ整形の手間、連続リクエスト時の欠落、インターネット必須という制約から、アプリ内のローカルDBに切り替えました。

### 4) KDecoder for Mac
- Repo: [KDecoder_for_Mac](https://github.com/adgk2349/KDecoder_for_Mac)
- macOS で発生する韓国語ファイル名文字化け (NFD/NFC) をドラッグ&ドロップで修正するユーティリティです。
- 正規化ロジックを実装し、実運用でのファイル互換性を改善しました。

### 5) SPSS Converter
- Repo: [SPSS_Converter](https://github.com/adgk2349/SPSS_Converter)
- macOS向けのドラッグ&ドロップ型 SPSS(.sav) → CSV 変換ツールです。
- 複数ファイル変換の反復作業時間を削減することに注力しました。

### 6) ArDrone Controller for iPad
- Repo: [ArDrone_Controller_for_iPad](https://github.com/adgk2349/ArDrone_Controller_for_iPad)
- SwiftUI + BLE ベースの iPad ドローンコントローラープロジェクトです。
- UI/状態制御フローとハードウェア連携の両方を扱っています。

### 7) YouTube Looper (Safari Extension)
- Repo: [Youtube_Looper](https://github.com/adgk2349/Youtube_Looper)
- macOS Safari で YouTube の無限ループ再生を提供する軽量拡張です。

---

## Education

- ハンシン大学 コンピュータ工学部 (編入) | 2023.03 - 2027.02 (卒業予定)
- スンチョン国立大学 マルチメディア工学部 | 2021.03 - 2022.12

---

## Languages

- Korean: Native
- Japanese: Advanced (JLPT N1)
- English: Intermediate (technical documentation and practical communication)
