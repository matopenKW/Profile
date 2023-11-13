# 業務経歴書

## 自己紹介
理工学部物理学系を卒業。新卒でITベンチャーに入社しSESとして業務アプリケーション開発を行う。 基本設計から保守工程まで一通りこなす。 自社の開発や研究等でとしてCMSでHPを作成する事も。  
現在はフリーランスエンジニアとして活動中（一人法人）。 勉強は比較的好きな方でバックエンドが主な業務です。 経験上フロントは多くないが読めます、書けます。但し、デザインは苦手です。（センスもなし）  
ものづくりも好きな方ですが手先は不器用。キャンプからスノボ、釣り、天体観測とアウトドアが大好きです！!
最近はGoよく触ってます。

## スキル
### 言語
+ Java
    + SpringBoot | SpringMVC | Struts2 | Seasar2 | Java Servlet
+ Go
    + gin | echo
+ Swift
+ javascript
    + jQuery | React(0.5年) | Nuxt.js(0.5年)
+ HTML
+ CSS

### DB
+ RDS
    + MySQL | Oracle | PostgreSQL
+ NoSQL
    + Cloud Firestore
+ Other
    + Cloud Spanner

### クラウド / インフラ
#### クラウドスキル
+ AWS
    + 基本的なAWSサービスは触れますが深くまではやってはいません。
    + よく触ったサービス
      + EC2 | S3 | ECS
+ GCP
    + コアなサービスを除いて割と何でもやりました。
+ herorku
    + 微経験ありです。
#### インフラスキル
+ terraform | terraform cloud
+ Datadog
    + Logs | Monitors | Metrics | Tracing | Dashboards

### CI/CDツール
+ GitHub Actions | CircleCI | CloudBuild | ArgoCD | Spinnacker

### その他技術
+ gRPC | microservice architecture

## 経歴
### toB向け仮想通貨販売サービス機能開発
企業向けに仮想通貨を販売しているサービスのバックエンド開発

#### 使用技術
Go言語。インフラはKubernetesで動いています。
副業としてスポット作業の担当としてJoinしたため、簡単なCRUDの処理　-> テストロジックを担当。

### toB向け仮想通貨販売サービス機能開発
企業向けに仮想通貨を販売しているサービスのバックエンド開発

#### 使用技術
Go言語。インフラはKubernetesで動いています。
副業としてスポット作業の担当としてJoinしたため、簡単なCRUDの処理　-> テストロジックを担当。

### BtoB,BtoC向けマッチングサービス
企業→企業、個人→企業でのマッチングサービス。新規開発プロジェクト

#### 使用技術
バックエンドはGo言語、フロントサイドはReactで開発。インフラはKubernetesで構築されており、APIはgRPCで連携。クライアントとはgrpc-gatewayを用いて通信を行う。

#### 主な業務内容
バックエンドエンジニアとして参画し、主にAPI開発者として従事。
Envoyを使用したサイドカーパターンで構築されていたりと新しく触るインフラの部分が多く、自学しながらキャッチアップした。
リリースも担当しKubernetesの基本的コマンド、構築方法、GitOpsの仕組みなどを習得した。

### 電子書籍データ連携API
デジタルコンテンツの配信プロジェクトで既存JavaシステムのGoへのマイグレーションを行った。

#### 使用技術
旧サービスはJava8で構築。新サービスはGo言語でフレームワークはechoを用いて実装。
インフラはAWSを使用。開発手法はアジャイルで設計はクリーンアーキテクチャで構築。

#### 主な業務内容
現行Javaで動いているバッチ処理をGoにマイグレーションをする部分の設計、実装、テストを担当。DBから取得したデータの加工、S3に連携、ログ解析、FTP通信、エラーログ送信等の処理を開発。

### 法人向け交通費管理アプリケーション
交通費を入力、保存、印刷するWebアプリケーションの作成。

#### 使用技術
Go言語でフレームワークはgin。DBは無料枠でとの事のため、Cloud Firestore（firebase）を使用。

#### 主な業務内容
設計から実装、テストまで行い、GAEへのデプロイを行う。知人からの作成依頼のため開発規模は小さいが要件定義から実装まで一通り行った。

### 保険営業業務Webアプリケーション
タブレット端末などを使用して保険営業、契約を行うWebアプリケーション開発。

#### 使用技術
バックエンドはJava8、フロントはReactを使用して作成。

#### 主な業務内容
バックエンドは保守作業、プロジェクト改善作業をメインに 行っておりテストツール等の導入を支援を行った。開発作業はReactがメインで初めてのJSフレームワークだったが自学しキャッチアップを行った。

### 大手ビルダー向けWebアプリケーション
工務店向けの契約→工期→会計までを行うWebアプリケーションの開発

#### 使用技術
バックエンドはJava6、フロントはjspで作成。DBはOracleを使用して行った。

#### 主な業務内容
長く従事したため、初めはテスト→開発といった作業から、お客様との要件定義→運用保守→提案までの業務まで任せて頂く事となった。
主に承認処理、ワークフローと言った機能の設計、構築。サーブレットベースの独自フレームワークのため独自で起こるエラーが多く、デバックスキルが大変上がった。新卒から長くプロジェクトに関わったため、技術者としての基本的な作業工程を覚えた。


