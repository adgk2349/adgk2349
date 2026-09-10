# スンミン・リー

[English](README.en.md) · [한국어](README.md) · [日本語](README.ja.md)

**iOS開発者 | 企画からリリース・運用まで**  
課題を素早く構造化し、プロダクト化までつなげる開発者です。

[Email](mailto:adgk2349b@gmail.com) | [GitHub](https://github.com/adgk2349) | [Blog](https://adgk2349.github.io)

---

## プロフィール

- 企画、開発、デプロイまでを一人で回し、実用的なツールを継続的に作っています。
- Swift/SwiftUI を中心としたアプリ開発と、Python ベースの自動化ツール開発を並行しています。
- On-device AI、ローカル実行環境、文字コード/互換性の問題解決に強みがあります。
- Linux + Docker + Nginx を用いた個人サービス運用環境を構築・管理してきました。

---

## 技術スタック

| カテゴリ | スキル |
| --- | --- |
| モバイル | Swift, SwiftUI, UIKit, Combine |
| AI・データ | Python, PyTorch, Whisper (Local/API), Prompt Engineering |
| バックエンド・インフラ | Django, Docker, Nginx, Linux (Ubuntu) |
| コラボレーション・ツール | Git, GitHub Actions, Figma, Slack |

---

## 主な公開プロジェクト

### 1) PLOS: データと実行環境を自ら管理する個人AIワークスペース
- リポジトリ: [PLOS-for-Mac](https://github.com/adgk2349/PLOS-for-Mac)
- 外部AIサービスのデータ処理に対する不安をきっかけに、GPTやClaudeを使う中で観察した挙動をもとに、ローカル推論・出力処理・会話メモリの構造を自ら設計しました。
- モデルの性能が向上するたびにガードレール(sanitizer)の介入度合いを見直し、ユーザー情報を個別の事実単位で保存するか文脈ごと保持するかを検討してメモリ構造を設計しました。

### 2) FlowMap: AIコーディング中のコード構造と変更影響を確認するツール
- リポジトリ: [FlowMap-AI_Code_Hallucination_Guard_for_Swift](https://github.com/adgk2349/FlowMap-AI_Code_Hallucination_Guard_for_Swift)
- AIコーディングで会話が長くなると、モデルが変数名を混同したり、以前実装した機能を見落とす問題を経験し、コード構造と関係をグラフで直接確認できるツールとして開発しました。
- 高速な解析のためコアエンジンをRustで実装し、VS Code拡張の配布版でのみ発生した右クリック不具合や、ノードの重なりによる可読性の問題を後のアップデートで改善しました。

### 3) Biblity: 毎日気軽に出会う聖書の一節
- リポジトリ: [Biblity](https://github.com/adgk2349/Biblity)
- App Store: [Biblity: 毎日の聖書のことば](https://apps.apple.com/kr/app/biblity-%EB%8D%B0%EC%9D%BC%EB%A6%AC-%EC%84%B1%EA%B2%BD-%EA%B5%AC%EC%A0%88/id6805680473)
- 既存の聖書アプリは情報量が多く画面が複雑に感じたため、ランダムな一節や通知で一つの節に集中できるiOSアプリを作りました。
- 初期はWebから節を取得する方式でしたが、データ整形の手間、連続リクエスト時の欠落、インターネット必須という制約から、アプリ内のローカルDBに切り替えました。

### 4) KDecoder for Mac
- リポジトリ: [KDecoder_for_Mac](https://github.com/adgk2349/KDecoder_for_Mac)
- App Store: [KDecoder](https://apps.apple.com/kr/app/kdecoder-%EA%B9%A8%EC%A7%84-%ED%95%9C%EA%B8%80-%ED%8C%8C%EC%9D%BC%EB%AA%85-%EB%B3%B5%EC%9B%90/id6806795869?mt=12)
- macOS で発生する韓国語ファイル名文字化け (NFD/NFC) をドラッグ&ドロップで修正するユーティリティです。
- 正規化ロジックを実装し、実運用でのファイル互換性を改善しました。

### 5) SPSS Converter
- リポジトリ: [SPSS_Converter](https://github.com/adgk2349/SPSS_Converter)
- macOS向けのドラッグ&ドロップ型 SPSS(.sav) → CSV 変換ツールです。
- 複数ファイル変換の反復作業時間を削減することに注力しました。

### 6) ArDrone Controller for iPad
- リポジトリ: [ArDrone_Controller_for_iPad](https://github.com/adgk2349/ArDrone_Controller_for_iPad)
- SwiftUI + BLE ベースの iPad ドローンコントローラープロジェクトです。
- UI/状態制御フローとハードウェア連携の両方を扱っています。

### 7) YouTube Looper (Safari Extension)
- リポジトリ: [Youtube_Looper](https://github.com/adgk2349/Youtube_Looper)
- App Store: [Looper for Youtube](https://apps.apple.com/kr/app/looper-for-youtube/id6805764066?mt=12)
- macOS Safari で YouTube の無限ループ再生を提供する軽量拡張です。

---

## 学歴

- ハンシン大学 コンピュータ工学部 (編入) | 2023.03 - 2027.02 (卒業予定)
- スンチョン国立大学 マルチメディア工学部 | 2021.03 - 2022.12

---

## 言語

- Korean: Native
- Japanese: Advanced (JLPT N1 取得準備中)
- English: Intermediate (technical documentation and practical communication)
