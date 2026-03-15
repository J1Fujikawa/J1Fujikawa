![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white)

# 職務経歴書

2026年3月15日現在 
氏名：藤川 隼一

## ■ 職務要約
エンジニア歴約8年の経験を持ち、現在は受託開発企業の開発チームリーダーを務めております。
私の最大の強みは、**「顧客との対話による要件定義」から「クラウドネイティブなインフラ設計」「高並行・AI連携を含むアプリケーション実装」までを一気通貫で完遂できる点**にあります。

情報処理安全確保支援士としての堅牢な設計をベースに、AWSを用いた複雑なネットワーク構築や、Python/Laravelによる高度なバックエンド開発を得意としています。リーダーとして、生産性を最大化する仕組み作りと、技術・ビジネスの両面から事業成長を牽引することを信条としています。

## ■ 技術スキル

* **インフラ:**
  * ALB/EC2/ECS(Fargate)/S3/RDS/ElastiCacheを用いたシステム設計
  * Site-to-Site VPN/VPCピアリング/AWS PrivateLinkを用いたネットワーク設計・構築
  * CloudWatchを使用した監視基盤構築
* **バックエンド:**
  * PHP (Laravel) : 8年
  * Python (FastAPI) : 3年
* **フロントエンド:**
  * JavaScript(Vue.js/Alpine.js) : 3年
  * Kotlin(Android) : 3年
* **ツール:**
  * インフラ: Docker(Docker-Compose), CloudWatch
  * バージョン管理: Git, Backlog, Github
  * テスト: PHPUnit, pytest

## ■ 職務経歴
### [現職：会社名]（2018年8月 〜 現在）
**事業内容：** 受託システム開発 
**ポジション：** 開発チームリーダー(2022年12月~)

#### 【主なプロジェクト実績】
**1. 自然言語解析とベクトル検索を用いた検索サジェスト基盤の構築**
* **役割:** 要件定義・システムアーキテクチャ設計・バックエンド実装
* **技術:** Python (FastAPI), OpenSearch, Nginx, Docker, AWS (ECS, OpenSearch), 自然言語モデル
* **概要:** 医療データという正確性重視の検索システムにおいて、ユーザの曖昧な入力にも対応できるようにしたいという要望を受け、言語モデルを使用したベクトル検索を解決策として提案・構築。
* **成果:** 多数の言語モデルでの実装を比較・検討することにより、レイテンシ・サジェスト精度ともに顧客から「文句なし」の評価を頂戴した

**2. 多数の外部拠点とのネットワーク統合**
* **役割:** 顧客交渉・インフラ設計・ネットワーク構築
* **技術:** AWS (ALB, EC2, RDS, ElastiCache, VPN, PrivateLink)
* **概要:** ネットワーク接続を前提としたシステムで、多数の外部拠点(IP重複あり)と接続したいという顧客課題に対し、Site to Site VPN + 外部拠点ごとのVPC構築 + AWS PrivateLinkにという、IP重複制約を無視できる構成を提案・構築。
* **成果:** IP重複のある外部拠点を接続した後も安定稼働中

**3. 月間ユーザ〇〇万人のコンシューマ向けシステムのインフラ移行**

## ■ 自己PR
### 1. セキュアで運用性の高いインフラ・アプリケーションを一気通貫で設計できる対応力
単なる機能実装に留まらず、顧客の要求を「セキュリティ」「スケーラビリティ（AWSネイティブ設計）」「運用保守性（CloudWatch等による監視）」の3軸で捉え、リリース後の安定稼働までを責任を持って設計・構築することを得意としています。
VPNやPrivateLinkを用いた複雑なインフラ要件にも対応可能で、特に2026年現在のAI導入に伴う機密情報保護や、安定した通信経路の確保において高い専門性を発揮します。

### 2. 自動テスト導入による「負債を負わない」開発文化の醸成
自動テストが存在しなかった環境において、テスト駆動の文化を一から構築し、チーム全体の生産性と心理的安全性を劇的に向上させました。
* **ボトムアップでの文化構築:** 自ら自動テスト（PHPUnit/Pytest等）の有用性を学習・検証し、メンバーへの勉強会やペアプログラミングを通じて導入を推進。既存コードへのテスト拡充により、デプロイに対する心理的障壁を解消しました。
* **テスト品質へのこだわり:** 単にカバレッジを追うだけでなく、**「実行速度の最適化（CI/CDの高速化）」「内部構造の変化に強いリファクタリング耐性」**を重視したテスト設計を徹底。長期的にメンテナンス可能なテストコードの指針を策定しました。

### 3. 「仕組み」と「心理的安全」を両立するマネジメント
開発リーダーとして、単なるコードの指摘に留まらない、チーム全体の品質底上げに注力しています。
* **建設的なレビュープロセスの導入:** 「なぜこの実装が必要か」という背景や意図を丁寧に言語化し、メンバーが自律的に判断できるようなレビューを実践。心理的安全性を担保することで、ミスを恐れず技術的挑戦ができる環境を構築しています。

## ■ 保有資格
* **情報処理安全確保支援士** 
* **応用情報技術者**
* **基本情報技術者**
* **AWSソリューションアーキテクト** 

## ■ 希望条件
* **希望年収:** 600万円以上
* **希望勤務形態:** 勤務形態への拘りは強くありませんが、 **月残業10時間以内** を希望します
