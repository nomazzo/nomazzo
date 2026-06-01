# 日本語バージョン

## モバイルアプリ開発 / 取引API・Bot / 市場データ基盤 / 機械学習

iOS / Android向けのモバイルアプリ開発を中心に、取引APIを使ったBot開発、市場データの収集・解析、LightGBMを用いた機械学習パイプライン構築にも取り組んできました。

モバイルアプリでの主な開発領域は、フォトエディター、カメラ、ユーティリティ系アプリなどです。
App Store / Google Play向けのアプリ開発、リリース、運用、広告・課金導線、ローカライズ、ASOまで含めた実務経験があります。

一方で、金融・暗号資産領域では、SAXO BANK、OANDA、Bybit、Binance、HyperliquidなどのAPIを用いたデータ取得、Bot開発、市場データレコーディング、AWS上での運用、LightGBMによる分析・戦略検証にも取り組んできました。

単なる「iOSアプリ開発者」ではなく、**モバイルアプリ開発を軸に、Pythonによる自動化、取引API連携、市場データ基盤、機械学習まで扱えるエンジニア**として、実装から運用までを意識した開発を行っています。

---

## 主なスキル

### Mobile App Development

* iOSアプリ開発

  * Swift
  * SwiftUI
  * UIKit
  * Objective-C
  * StoreKit / In-App Purchase
  * AdMob
  * App Store公開・運用
  * ローカライズ
  * ASO
* Androidアプリ開発

  * フォトエディター系アプリの開発・リリース経験
  * iOSアプリからの移行
  * Google Play公開・運用
* アプリ領域

  * フォトエディター
  * カメラアプリ
  * ユーティリティアプリ
  * 生産性・生活支援系アプリ

### Python / Automation / Bot Development

* Pythonによるデータ処理・自動化
* 取引API連携
* Bot開発
* WebSocket / REST API
* AWS上でのBot・データ収集処理の運用
* ログ設計、エラーハンドリング、リトライ処理
* Docker / CLIツール / バッチ処理

### Trading API / Market Data

* SAXO BANK APIを使用したFXグリッドトレーディングBot開発
* OANDA APIを用いたFXデータ取得
* Bybit / Binance APIの利用経験
* Binance Depthデータのレコーディング・解析
* Hyperliquid APIを用いたMM Bot開発
* MeteoraでのLP Bot開発
* 市場データの保存、前処理、特徴量生成、検証用データセット構築

### Machine Learning

* LightGBM
* 時系列データの特徴量生成
* 市場データ分析
* 学習・検証パイプライン構築
* バックテスト用データ整備
* 特徴量重要度の確認
* リークを避けた検証設計

---

## GitHubで公開予定の主なプロジェクト

### Mobile App

| Repository                  | Description                                   |
| --------------------------- | --------------------------------------------- |
| `ios-photo-editor-sample`   | Swift / SwiftUIによるフォトエディター系iOSアプリのポートフォリオサンプル |
| `mobile-app-production-kit` | AdMob、IAP、ローカライズ、レビュー導線など、アプリ公開・運用に必要な実装サンプル  |
| `mobile-app-portfolio`      | iOS / Androidアプリの開発・リリース実績をまとめたケーススタディ集       |
| `objc-swift-interop-sample` | Objective-C資産とSwiftの連携、既存iOSアプリ改修を想定したサンプル    |

### Trading / Market Data / ML

| Repository                     | Description                                    |
| ------------------------------ | ---------------------------------------------- |
| `market-data-recorder-aws`     | 取引所APIやWebSocketから市場データを継続取得し、AWS上で保存・監視するサンプル |
| `trading-bot-framework-sample` | 取引Botのアーキテクチャ、発注抽象化、リスク管理、mock実行環境を示すサンプル      |
| `lightgbm-market-ml-pipeline`  | 市場データを対象にしたLightGBMの特徴量生成・学習・検証パイプライン          |
| `defi-lp-bot-simulator`        | DeFiのLPポジション管理、リバランス、手数料、リスク評価を扱うシミュレーター       |
| `hyperliquid-mm-simulator`     | オーダーブック、在庫リスク、スプレッド管理を扱うマーケットメイクBotのシミュレーター    |

---

## 開発で重視していること

* 実運用を意識したシンプルな設計
* 読みやすく保守しやすいコード
* APIキーや秘密情報を含めない安全な構成
* READMEを読めば目的・使い方・設計意図がわかること
* テストしやすい責務分離
* エラー発生時に追跡しやすいログ設計
* 小さく動くものを作り、検証しながら改善する開発スタイル

---

## 対応しやすい案件領域

* iOSアプリの新規開発
* 既存iOSアプリの改修・保守
* Swift / SwiftUI / UIKitによる画面・機能実装
* Objective-C資産を含む既存アプリの改善
* App Store公開前後の実装支援
* AdMob / IAP / ローカライズ対応
* Androidアプリの改修・機能追加
* PythonによるAPI連携・自動化
* 取引APIを用いたデータ取得・Bot開発
* 市場データの収集・保存・分析基盤構築
* LightGBMを用いた分析・検証パイプライン構築

---

## Notes

公開リポジトリには、商用アプリ本体のソースコード、本番Bundle ID、AdMob本番ID、IAP設定、APIキー、秘密鍵、取引Botの本番戦略、非公開データは含めません。
ポートフォリオ用に再構成したサンプル、mock実装、シミュレーター、ケーススタディを中心に公開しています。

---

# English

## Mobile App / Trading API Bot / Market Data / Machine Learning Engineer

I am a software developer focused on mobile app development, with additional experience in trading API integration, bot development, market data engineering, and machine learning pipelines using LightGBM.

My primary background is iOS and Android app development, especially photo editor apps, camera apps, and utility apps.
I have experience not only in app implementation, but also in App Store / Google Play release, monetization, localization, ASO, and production-oriented app operations.

In addition to mobile app development, I have worked on financial and crypto-related systems using APIs such as SAXO BANK, OANDA, Bybit, Binance, Hyperliquid, and Meteora.
This includes trading bot development, FX and crypto market data collection, Binance depth data recording, AWS-based bot operation, and LightGBM-based research pipelines.

Rather than being only an iOS developer, I aim to position myself as an engineer who can combine **mobile app development, Python automation, trading API integration, market data infrastructure, and machine learning**.

---

## Core Skills

### Mobile App Development

* iOS development

  * Swift
  * SwiftUI
  * UIKit
  * Objective-C
  * StoreKit / In-App Purchase
  * AdMob
  * App Store release and operation
  * Localization
  * ASO
* Android development

  * Photo editor app development and release experience
  * Google Play release and operation
* App categories

  * Photo editor apps
  * Camera apps
  * Utility apps
  * Productivity and lifestyle apps

### Python / Automation / Bot Development

* Python scripting and automation
* Trading API integration
* Bot development
* WebSocket / REST API
* AWS-based bot and data recording operation
* Logging, error handling, and retry design
* Docker / CLI tools / batch processing

### Trading API / Market Data

* FX grid trading bot development using SAXO BANK API
* FX data collection using OANDA API
* Bybit and Binance API experience
* Binance depth data recording and analysis
* Market-making bot development using Hyperliquid API
* LP bot development on Meteora
* Market data storage, preprocessing, feature engineering, and research dataset creation

### Machine Learning

* LightGBM
* Time-series feature engineering
* Market data analysis
* Training and validation pipeline design
* Backtesting dataset preparation
* Feature importance analysis
* Leakage-aware validation design

---

## Planned Portfolio Repositories

### Mobile App

| Repository                  | Description                                                                                         |
| --------------------------- | --------------------------------------------------------------------------------------------------- |
| `ios-photo-editor-sample`   | A Swift / SwiftUI portfolio sample for photo editor-style iOS app development                       |
| `mobile-app-production-kit` | Production-oriented mobile app components such as AdMob, IAP, localization, and review prompt flows |
| `mobile-app-portfolio`      | Case studies of iOS / Android app development and release experience                                |
| `objc-swift-interop-sample` | A sample project for Objective-C and Swift interoperability in existing iOS apps                    |

### Trading / Market Data / ML

| Repository                     | Description                                                                                     |
| ------------------------------ | ----------------------------------------------------------------------------------------------- |
| `market-data-recorder-aws`     | A sample architecture for recording market data from exchange APIs and WebSocket streams on AWS |
| `trading-bot-framework-sample` | A trading bot architecture sample with order abstraction, risk control, and mock execution      |
| `lightgbm-market-ml-pipeline`  | A reproducible LightGBM pipeline for market data feature engineering, training, and validation  |
| `defi-lp-bot-simulator`        | A simulator for DeFi LP position management, rebalancing, fee estimation, and risk analysis     |
| `hyperliquid-mm-simulator`     | A market-making simulator focused on order book handling, inventory risk, and spread management |

---

## Development Principles

* Simple architecture designed for real-world operation
* Readable and maintainable code
* Secure repository structure without API keys or secrets
* README-first documentation
* Testable separation of responsibilities
* Logs and error handling designed for troubleshooting
* Build small, verify early, and improve iteratively

---

## Areas I Can Support

* New iOS app development
* Existing iOS app maintenance and feature development
* Swift / SwiftUI / UIKit implementation
* Objective-C to Swift migration or interoperability
* App Store release support
* AdMob / IAP / localization implementation
* Android app maintenance and feature development
* Python automation and API integration
* Trading API data collection and bot development
* Market data recording and analysis infrastructure
* LightGBM-based research and validation pipelines

---

## Notes

Public repositories do not include commercial app source code, production Bundle IDs, production AdMob IDs, IAP settings, API keys, private keys, live trading strategies, or private datasets.
The repositories are designed as portfolio samples, mock implementations, simulators, and case studies.
