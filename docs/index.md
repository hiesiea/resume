# 職務経歴書

## 基本情報

|Key|Value|
|---|---|
|氏名|鎌田 均（Hitoshi KAMADA）|
|生年月日|1992年2月26日|
|居住地|千葉県|
|最終学歴|愛知工業大学 情報科学部 情報科学科 メディア情報専攻|

## スキルセット

### 職務要約

Kotlin, Java による Android ネイティブアプリ開発や、Flutter, Unity によるクロスプラットフォーム開発など、様々な技術やプロジェクトを経験してきました。

1 社目では住宅関連 Web3D/CAD システム開発の企業に入社し、toB 向けの Web システムの開発に従事しました。具体的には、Java によるフロントエンド、バックエンドの開発を担当しました。

2 社目では SES 企業に入社し、Java の経験を活かして主に Android のネイティブアプリ開発のプロジェクトに従事しました。

2 社目を退社後、フリーランスとして独立して主に Android のネイティブアプリ開発のプロジェクトに従事しました。直近のプロジェクトでは、これまでの経験や現場での実績を買われて Android アプリ開発におけるテックリードをさせていただいております。

### 自己PR

私の強みとしては、8 年以上にわたる Android ネイティブアプリ開発の経験があること、レガシーコードのリファクタリングおよびリプレイスを得意としていること、テックリードとして 5 名程のメンバーをリードした経験があることです。

「`N`予備校開発支援業務」では、テックリードとして自前で実装されていた通信処理を Retrofit に移行したり、RxJava 3 から Kotlin Flow に移行したりなどのリファクタリングに取り組みました。その際、他メンバーがすぐ着手できるよう実装方針をまとめたドキュメントを作成したり、必要最小限の単位でタスクを作成することでいずれも無事完遂させることができました。これらの取り組みにより、可読性の向上やコード量の削減に貢献しました。チームメンバーからもドキュメントがわかりやすいと評価していただきました。

将来的にはテックリードとしての経験をもっと積んでいき、技術にも携わりつつマネジメントもできる人材を目指したいです。

また、可能であれば日常会話程度以上の英語力を身に付けたり、技術書を出版したり、カンファレンスでの登壇を目指したいです。

### 主な技術スタック

|言語名|業務経験|フレームワーク・ライブラリ名|業務経験|
|---|---|---|---|
|Kotlin|5年半|Android Jetpack|4年半|
|Java|5年半|RxJava 3|3年|
|Dart|半年|Kotlin Coroutines|4年半|
|C#|1年半|Kotlin Flow|1年半|
|Swift|1年|OkHttp|5年半|
|JavaScript|2年半|Retrofit|4年半|
|||JUnit|5年|
|||Flutter|半年|

## 職務経歴詳細

### 2019年4月〜現在 フリーランス

#### 2021年3月〜現在 N予備校開発支援業務

|Key|Value|
|---|---|
|概要|ZEN Study（旧：`N`予備校）Android アプリの開発支援業務|
|担当工程|設計、コーディング、テスト、運用/保守|
|役割|当初はメンバーとして参画、2023 年よりテックリード|
|規模|7 名（マネージャー兼リーダー 1 名、テックリード 1 名、メンバー 5 名）|
|言語|Kotlin, Markdown|
|OS・DB|Android, Mac OS|
|ライブラリ・フレームワーク|Android Jetpack(Jetpack Compose, Navigation, Media3, DataStore), Glide, Coil, Sentry, Firebase(Analytics, Messaging, Crashlytics, Remote Config), OkHttp3, Retrofit2, JUnit, kotlin.test, Mockito, Timber, Kotlin Coroutines, Kotlin Flow, ExoPlayer, RxJava 3, Version Catalog, Composite Build|
|ツール|Android Studio, JIRA, Slack, Confluence, GitHub, Figma, avocado|

##### 業務内容・主な実績

- 機能追加、不具合改修
  - 接続先サーバの移行対応
  - Edge-to-edge の導入
- リファクタリング
  - Java から Kotlin に移行
  - Deprecated な処理の置き換え
  - 画面遷移を Navigation に移行
  - Single アクティビティ に移行
  - Android View を Jetpack Compose に移行、UI テストの導入
  - マルチモジュールの導入
  - 自前で実装されていた通信処理を Retrofit に移行
  - JSON ライブラリについて、org.json と Gson がごちゃ混ぜになっていたので Moshi に一本化
  - Serializable なデータクラスを Parcelable に移行
  - RxJava 3 から Kotlin Flow に移行
  - buildSrc から Composite Build に移行
  - SharedPreferences から DataStore に移行
  - ExoPlayer から Media3 に移行
- テックリードとしてチームメンバーのマネジメント
  - 新技術導入に向けた調査、ドキュメント作成および共有
  - リファクタリングタスクの工数見積もり、計画作成、チームメンバーへの割り振り
  - Codelab にて学習コンテンツの選定
  - チーム内での取り組みを Qiita にて記事化し発信
  - コードレビュー、ペアプロ
  - GitHub のプルリクエストのテンプレート改善
  - インターン生の開発サポート
- DroidKaigi への参加

リーダーから与えられたタスクだけでなく、改善できそうな箇所（アーキテクチャに沿っていない、Deprecated な処理があるなど）に関して改善案を提案したり、リファクタリングを積極的に進めるようにしました。その結果、評価されてテックリードを任せてもらえるようになりました。

新技術導入に向けた調査、ドキュメント作成および共有をしていく中で、ただ調べた内容を共有するのではなく、実際に手を動かしてアプリの動作にも影響がないかどうかも検証したうえでより正確な情報を提供するようにしました。また、コード例も記載して他メンバーが実装をイメージできるようにすることで、チームメンバーからはわかりやすいとの評価を得られ、属人化を防ぐことができました。

ソースコードのバージョン管理として、GitHub を運用していましたが、プルリクエストを出す際に以下の課題がありました。

- 複数機能の修正を 1 つのプルリクエストにまとめてしまい、レビュアーの負担を増やしてしまっていた
- レビューに必要な情報（仕様書のリンク、確認可能な環境、ユーザー情報、確認手順、キャプチャなど）の記載忘れがあり、その確認のために余計なコミュニケーションが発生してしまっていた

そこで、以下の取り組みを行いました。

- 極力プルリクエストを分割する
- コミットの単位を細かくして、それぞれのコミットメッセージを詳細に書く
- 修正内容についてわかりにくそうな点があれば適宜コメントで補足するようにした
- プルリクエストのテンプレートに必要事項を記載するための欄を追加した

これにより、各メンバーがレビュアーの負担を減らすことを考慮したプルリクエストを作成する習慣が身につき、レビューにかかる時間が短縮されるようになりました。

#### 2020年6月〜2021年2月 屋外広告配信システム開発案件

|Key|Value|
|---|---|
|概要|Windows および Android 向けの屋外広告配信システム開発案件|
|担当工程|要件定義、設計、コーディング、テスト、運用/保守|
|役割|メンバー|
|規模|6 名（プロジェクトマネージャー1 名、プロジェクトリーダー1 名、メンバー4 名）|
|言語|Kotlin, C#|
|OS・DB|Android, Windows, Mac OS, SQLite|
|ライブラリ・フレームワーク|AAndroid Jetpack, OkHttp, Retrofit, JUnit, MockK, Timber, Kotlin Coroutines, WPF, UWP, Prism, RestSharp, EF Core、.NET Core, NLog, msix|
|ツール|Android Studio, Visual Studio, JIRA, GitLab, GitHub, Slack, zoom, VS Code, LucidChart, Postman, Mmock, Docker, Confluence|

##### 業務内容・主な実績

- Android アプリの機能追加、不具合改修、リリース作業
  - 異常報告機能の過剰報告の抑止対応
  - Web ページ表示機能の実装
  - 広告の分割表示機能の実装
  - 他社向けへの新規アプリ追加
- 今後の機能追加のため、Android Jetpack を活用してのリプレイス対応
  - 公式ホームページのアプリアーキテクチャガイドをベースに MVVM アーキテクチャを採用
  - Room, Retrofit(OkHttp)を利用しての Repository クラスの実装
  - 非同期処理を Thread から Kotlin Coroutines に移行
  - ViewModel, LiveData, DataBinding による UI ロジックの実装
  - Hilt による DI の導入
  - JUnit, MockK によるテストコードの実装
  - 複雑化していたロジックのシンプル化
  - 映像切り替え時のパフォーマンスチューニングを実施
  - API 未実装の箇所の実装を先行して進められるよう、Postman, Mmock, Docker によるモックサーバの構築
  - ビルドバリアントの整理
- Windows アプリの新規開発にあたっての技術選定
  - WPF, UWP などの各種プラットフォームの概要調査
  - ビジネスサイドとの機能要件、非機能要件の認識合わせおよび整理
  - 各機能要件、非機能要件についてサンプルアプリを作成しながらの技術検証
- 開発に関する問題改善のための提案および実施
  - 各社ごとの機能要望の整理ができていなかったのを指摘および整理
  - アプリのパッケージ化の検討
  - 開発体制やビジネスサイドとの進め方について見直しの提案
- チームメンバーの技術教育
  - 新人向けに開発ルールなどのドキュメント作成
  - コードレビュー、設計レビュー

#### 2020年2月〜2020年5月 バイトルApp機能拡張開発

|Key|Value|
|---|---|
|概要|バイトルアプリ（Android・iOS）の追加開発・改修|
|担当工程|要件定義、設計、コーディング、テスト、運用/保守|
|役割|メンバー|
|規模|11〜50 名|
|言語|Java, Kotlin, Swift, Markdown|
|OS・DB|Android, iOS, Mac OS, SQLite, Realm|
|ライブラリ・フレームワーク|Retrofit, Swagger, Maps SDK for Android, Adobe Target|
|ツール|Android Studio, Xcode, Redmine, Backlog, GitHub, VS Code, PlantUML, Postman, Mmock, ngrok, Toggl, DocBase, Bitrise, VS App Center, Slack|

##### 業務内容・主な実績

- コードレビュー
- AB テスト取込
  - AB テストの結果を機能概要書、ソースコードに反映
  - 単体、結合試験書の作成および実施
- 地図検索機能の開発検討
  - API チームとの仕様確認および調整
  - Maps SDK for Android の調査および DocBase への情報共有
  - 機能概要書、プロトタイプ作成
  - 要求元チームとの要求仕様の確認および整理
- リリースに向けたブランチのマージ作業
- モックサーバの立て方について DocBase への情報共有
- 不具合解析、調査

#### 2019年7月〜2020年1月 モバイルアプリの追加開発・改修

|Key|Value|
|---|---|
|概要|格安 SIM を提供している会社様向けに、契約者のご利用状況などを確認できるスマホアプリの追加開発・改修|
|担当工程|要件定義、設計、コーディング、テスト|
|役割|開発メンバー|
|規模|6 名（プロダクトオーナー1 名、スクラムマスタ 1 名、開発メンバー4 名）|
|言語|Dart, Kotlin, Markdown, Swift, JavaScript|
|OS・DB|Android, iOS, Mac OS, SQLite|
|ライブラリ・フレームワーク|Flutter, Appium, Swagger, FCM, Mockito, Notification Hubs|
|ツール|Azure DevOps, Git, Backlog, Toggl, Mmock, Docker, Typora, ngrok, Xcode, zoom, VS Code, Slack, Android Studio|

##### 業務内容・主な実績

- スクラム開発、1 週間スプリントによるイテレーション
- フロントエンドの要件定義、設計、実装、テスト
  - 設計に関しては、Markdown によるドキュメント作成および、元々 Excel で記載されていた設計書を Markdown 形式への移行作業
  - UI に関してはマテリアルデザインをベースに設計
  - アーキテクチャは BLoC パターンを採用
  - プッシュ通知（Notification Hubs）の改修
  - テストに関しては、ロジック部分を Mockito でユニットテストを実装
  - API 未実装の箇所の実装を先行して進められるよう、Mmock と Docker によるモックサーバの構築および、YAML でのモックデータ作成
  - Android 10 に関する調査およびリリース対応
  - 64bit 対応に関する調査およびリリース対応
  - Azure Pipelines による CI 環境の構築。ビルドおよびテスト実行結果を Slack へ通知する仕組みを実現
  - UI テストの自動化のための Appium の調査、Appium Desktop に接続するまでの環境構築、JavaScript によるテストコードのプロトタイプ作成
- iOS 版の開発にあたり、差分で開発する必要がある箇所について洗い出し、および iOS 版でどのように実現するかの調査および実装
  - プッシュ通知、データ暗号化、ユーザ認証の実現方法の調査および開発環境準備、データ暗号化の実装、ユーザ認証のプロトタイプ作成

#### 2019年4月〜2019年10月 Android TV お手続き資料請求アプリおよび、請求確認アプリの新規開発

|Key|Value|
|---|---|
|概要|Android TV 搭載の STB 向けに、テレビプランや各種サービスへのお手続き資料請求アプリと、加入中のプランなどの料金詳細が確認できる請求確認アプリの新規開発（いずれもプリインアプリ）|
|担当工程|要件定義、設計、コーディング、テスト|
|役割|開発メンバー|
|規模|7 名（プロダクトオーナー1 名、スクラムマスタ 1 名、開発メンバー5 名）|
|言語|Kotlin, Markdown, shell script, YAML|
|OS・DB|Android TV, Mac OS, SQLite|
|ライブラリ・フレームワーク|Kotlin Coroutines, Swagger, Timber, Leanback, Data Binding, Glide|
|ツール|Android Studio, Azure DevOps, Backlog, Git, Toggl, zoom, miro, Docker, Slack, VS Code, Mmock|

##### 業務内容・主な実績

- スクラム開発、1 週間スプリントによるイテレーション
- フロントエンドの要件定義、設計、実装、テスト
  - 設計に関しては、Markdown によるドキュメント作成
  - UI に関してはマテリアルデザインをベースに設計
  - アーキテクチャは MVVM パターンを採用
  - テストに関しては、ロジック部分についてユニットテストを実装
  - API 未実装の箇所の実装を先行して進められるよう、Mmock と Docker によるモックサーバの構築および、YAML でのモック作成
- お手続き資料請求アプリ、請求確認アプリそれぞれの共通処理を Git submodule で別リポジトリとして分割

### 2015年10月〜2019年3月 株式会社ASCOM

#### 2018年8月〜2019年1月 IPTV の Android FW 標準化検討

|Key|Value|
|---|---|
|概要|MMT(MPEG Media Transport) を Android 上で実現するための検討および調査|
|担当工程|要件定義|
|役割|メンバー|
|規模|6〜10 名|
|言語|Java|
|OS・DB|Android TV, Ubuntu, Windows|
|ライブラリ・フレームワーク|Android SDK, ExoPlayer|
|ツール|Android Studio, GitHub, Backlog, Redmine, Wireshark, tcpreplay|

##### 業務内容・主な実績

- MediaCas、MediaDescrambler、MediaCodec クラスに関するドキュメント調査、シーケンス図の作成
- マルチキャスト構成の調査と、配信ツールの比較選定、資料作成
- MMT(MPEG Media Transport)や、コーデックに関する調査
- コードレビュー、メンバーが作成した資料のレビュー

#### 2017年12月〜2018年3月 ペット心電図アプリ開発

|Key|Value|
|---|---|
|概要|ペット用の心電図アプリの開発|
|担当工程|コーディング、テスト|
|役割|メンバー|
|規模|1〜5 名|
|言語|C#, JavaScript, HTML|
|OS・DB|Windows|
|ライブラリ・フレームワーク|i18next, Windows Form|
|ツール|Redmine, Git, Visual Studio 2017|

##### 業務内容・主な実績

- 不具合修正
- エンドユーザ様との合同デバッグ
- i18next による多言語化対応

#### 2017年11月〜2019年3月 Android TV 衛星放送プレイヤーの追加開発・改修

|Key|Value|
|---|---|
|概要|Android TV 搭載の STB 専用の、IPTV アプリの衛星放送プレイヤー部分の追加開発・改修|
|担当工程|設計、コーディング、テスト、運用/保守|
|役割|メンバー|
|規模|5 名（プロジェクトマネージャー1 名、プロジェクトリーダー1 名、メンバー3 名）|
|言語|Java|
|OS・DB|Android TV, Windows|
|ライブラリ・フレームワーク|Android SDK, OkHttp、Volley, ExoPlayer|
|ツール|Android Studio, Subversion, Redmine, Wireshark|

##### 業務内容・主な実績

- ザッピング機能の詳細設計、実装、結合試験、総合試験、リリース作業の実施
- 不具合解析のため、Wireshark によるパケット解析の実施。API との疎通確認や、ルータとの IGMP パケットの疎通確認などを実施
- Volley から別の通信ライブラリへの置き換えのため、通信ライブラリの比較選定および、実際に置き換えての動作検証
- Android Oreo へのアップデート対応

#### 2017年11月〜2018年5月 スマートスピーカー検討

|Key|Value|
|---|---|
|概要|スマートスピーカーと STB の連携方法に関する調査・検討|
|担当工程|要件定義|
|役割|メンバー|
|規模|1〜5 名|
|言語|JavaScript, HTML, CSS|
|OS・DB|Windows, SQLite|
|ライブラリ・フレームワーク|Node.js, JQuery, Bootstrap|
|ツール|ngrok, Redmine, Dialogflow, Alexa Skills Kit, IFTTT, Git, Actions on Google, Node-RED|

##### 業務内容・主な実績

- スマートスピーカー(Google Home、Amazon Echo)に関する調査および資料作成
- STB 連携に関する調査検討および納品用の調査報告書の作成
- 客先での打ち合わせ、デモ実施

#### 2017年10月〜2017年11月 社内新人研修

|Key|Value|
|---|---|
|概要|新入社員向けのプログラミング研修|
|役割|講師|
|規模|11〜20 名|
|言語|Java, C#|
|OS・DB|Windows, Mac|
|ツール|GitHub|

##### 業務内容・主な実績

- 2 か月間、1 日 8 時間のスケジュールおよびカリキュラムの作成
- 設計およびコードレビュー
- 新人へのマネジメントおよび進捗管理

#### 2017年4月〜2017年9月 Android 搭載 の IoT デバイスの新規開発

|Key|Value|
|---|---|
|概要|Android 搭載の非接触センサー付 IoT デバイスの新規開発|
|担当工程|設計、コーディング、テスト|
|役割|メンバー|
|規模|31 名（プロジェクトマネージャー1 名、プロジェクトリーダー5 名、開発メンバー15 名、テスター10 名）|
|言語|Java, shell script|
|OS・DB|Android, Windows, Ubuntu, SQLite|
|ライブラリ・フレームワーク|Andorid SDK, Javadoc|
|ツール|Android Studio, JIRA, Redmine, Gerrit, Repo, Git, Mattermost|

##### 業務内容・主な実績

- スマホアプリ側に提供する I/F 仕様書作成（Javadoc）
- Service コンポーネントを利用した IoT デバイス側の実装、結合試験書の作成および実施

#### 2016年10月〜2017年3月 Android 搭載のコミュニケーションロボットの新規開発

|Key|Value|
|---|---|
|概要|Android 搭載の音声認識、顔認識によるコミュニケーションロボットの新規開発|
|担当工程|要件定義、設計、コーディング、テスト|
|役割|メンバー|
|規模|12 名（マネージャー1 名、デザイナー1 名、メンバー10 名）|
|言語|Java|
|OS・DB|Android, Windows|
|ライブラリ・フレームワーク|Android SDK, Data Binding, JUnit, AssertJ|
|ツール|Android Studio, JIRA, GitHub, Checkstyle, FindBugs, astah, Coverity, Jenkins|

##### 業務内容・主な実績

- アジャイル開発、2 週間スプリントによるイテレーション
- フロントエンドの要件定義、設計、実装、テスト
- 音声認識率の低下の問題が発生したため、場所を変えての環境音の収集、および動作時の認識率といった、原因の調査に必要なデータの収集

#### 2016年5月〜2016年8月 大手物流企業向け宅配管理システム開発

|Key|Value|
|---|---|
|概要|大手物流企業向けの宅配管理を行うための Andorid アプリの開発|
|担当工程|設計、コーディング|
|役割|メンバー|
|規模|11〜50 名|
|言語|Java|
|OS・DB|Android, Windows, SQLite|
|ライブラリ・フレームワーク|Android SDK|
|ツール|Eclipse, Redmine, JIRA, CAT, TortoiseSVN|

##### 業務内容・主な実績

- ソースコードの解析および詳細設計書の修正といったリバースエンジニアリング対応
- 他機能との連携処理の設計〜実装、設計案の検討および、エンドユーザへの提案
- 新規参入者への引き継ぎ作業

#### 2016年4月〜2016年5月 社外研修

|Key|Value|
|---|---|
|概要|若者正社員チャレンジ事業で受け入れたインターン生向けのプログラミング講習（Android アプリ開発）の実施|
|役割|講師|
|規模|6〜10 名|
|言語|Java, Markdown|
|OS・DB|Android, Mac OS|
|ライブラリ・フレームワーク|Android SDK|
|ツール|Android Studio, GitHub, Qiita|

##### 業務内容・主な実績

- 15 日間、1 日 8 時間のスケジュールおよびカリキュラムの作成
- Qiita での教材作成
- 当日のメイン講師

#### 2015年10月〜2016年3月 iOS・Android 向け観光支援スマホゲームアプリの新規開発

|Key|Value|
|---|---|
|概要|iOS、Android 向けの地方観光支援のためのスマホゲームアプリの新規開発|
|担当工程|コーディング、テスト|
|役割|メンバー|
|規模|6〜10 名|
|言語|C#, JavaScript|
|OS・DB|Android, iOS, Windows, Mac OS|
|ライブラリ・フレームワーク|d3.js, Cardboard SDK, Joker Script|
|ツール|Unity, Backlog, TortoiseSVN, Xcode|

##### 業務内容・主な実績

- ライブラリやフレームワーク等の選定
- アプリの UI、画面遷移など全ての実装
- Google Play および App Store へのリリース作業

### 2014年4月〜2015年8月 株式会社ケイ・アイ・テック

#### 2015年4月〜2015年8月 収納家具見積 Web システムの新規開発

|Key|Value|
|---|---|
|概要|収納家具のレイアウトを作図し、作図内容をもとに見積もり金額を算出するための Web システム|
|担当工程|コーディング、テスト|
|役割|メンバー|
|規模|6〜10 名|
|言語|Java|
|OS・DB|Windows|
|ライブラリ・フレームワーク|Jakarta Tomcat, Swing|
|ツール|Eclipse, GitHub, Redmine, SQL Server, Sourcetree|

##### 業務内容・主な実績

- Swing を用いた全体的な 画面 UI 、画面遷移の実装
- XML 形式でのデータ保存機能の実装

#### 2014年7月〜2015年3月 プレゼンボード作成 Web システムの新規開発

|Key|Value|
|---|---|
|概要|プレゼンボードやチラシを作成するための Web システム|
|担当工程|コーディング、テスト|
|役割|メンバー|
|規模|6〜10 名|
|言語|Java, HTML, JavaScript|
|OS・DB|Windows, MySQL|
|ライブラリ・フレームワーク|PDFLib, Apache Tomcat, SAStruts, Seasar2, Swing|
|ツール|Eclipse, GitLab, Redmine, MySQL Workbench|

##### 業務内容・主な実績

- Swing を用いての図形や画像などのオブジェクトの描画、回転、縮小機能の実装
- PDFLib を用いた PDF 出力機能の実装
- MySQL を用いた DB チューニング、テスト用データの作成
- SAStruts, Seasar2 による API の実装

#### 2014年5月〜2014年6月 ウッドデッキ見積 Web システムの不具合改修

|Key|Value|
|---|---|
|概要|ウッドデッキを作図し、作図内容をもとに見積もり金額を算出するための Web システム|
|担当工程|コーディング、テスト、運用/保守|
|役割|メンバー|
|規模|1〜5 名|
|言語|Java|
|OS・DB|Windows|
|ライブラリ・フレームワーク|Jakarta Tomcat, Swing|
|ツール|Eclipse, Subversion|

##### 業務内容・主な実績

- 不具合調査および修正

## 業務外活動

- ワールドビジネスサテライト 2015 年 1 月 22 日出演
  - TimeTicket というサービスにて、プログラミング関連の相談に乗っていました
  - <https://blog.timeticket.jp/post/108879706835/%E3%83%86%E3%83%AC%E3%83%93%E6%9D%B1%E4%BA%AC%E3%83%AF%E3%83%BC%E3%83%AB%E3%83%89%E3%83%93%E3%82%B8%E3%83%8D%E3%82%B9%E3%82%B5%E3%83%86%E3%83%A9%E3%82%A4%E3%83%88%E3%81%A7%E7%B4%B9%E4%BB%8B%E3%81%95%E3%82%8C%E3%81%BE%E3%81%97%E3%81%9F>
- 株式会社 NOWALL 主催 スパルタキャンプ Java/Android 編 講師（2015 年 10 月、2016 年 3 月）
  - 3〜4 日間かけて Android アプリの開発を学べるプログラミング教室で講師を務めました
- 妖怪笑い袋（スマートスピーカーアプリ）の開発およびリリース
  - 全てのキーワードに対して、ランダムに笑い声を返すだけのスキルです
  - リリース初月で利用者数 100 人突破
    - Google アシスタント版 **※公開停止**
      - 動画 : <https://www.youtube.com/watch?v=N-AQ-Q36Ts0>
    - Alexa 版 **※公開停止**
      - 動画 : <https://www.youtube.com/watch?v=2d-1DX_Zojc>
- かんたん食事管理（iOS アプリ）の開発およびリリース **※公開停止**
  - ソースコード : <https://github.com/hiesiea/SimpleMealManager>
  - その日に食べた食事の画像とテキスト情報を入力して一覧表示してくれるアプリです
- PHP 勉強会の共同主催
  - バックエンドエンジニアの友人との共同主催で、教材作成、受講生の課題管理、新規コンテンツの検討を担当しました
- 技術発信
  - 主に Qiita で実務等で得られた技術的知見を発信しています
    - <https://qiita.com/hiesiea>
- OSS 活動
  - DroidKaigi 2021〜2024 official app コントリビューター

## 学会発表

- 鎌田均、丸橋駿平、澤野弘明： “指差し動作を利用したカーナビのための助手席ユーザの経路指示方法の一調査”, 電子情報通信学会総合大会 ISS 特別企画「学生ポスターセッション」, ISS-SP-317, 1 page (2013-3)

## 免許・資格

|年月|免許・資格|
|---|---|
|2009年11月|基本情報技術者試験|
|2010年2月|日商簿記2級|
|2010年3月|全商検定5冠（電卓、ワープロ、プログラミング、ビジネス情報、簿記）|
|2011年9月|普通自動車第一種運転免許|

## 希望条件

- 2024 年 5 月生まれの子供がいるため、家庭との両立がしやすい労働環境を希望します
- 言われたとおりにただ作るのではなく、機能要件に対しても一緒に考えたり、提案しやすい環境を希望します
- 役職関係なく、フラットにコミュニケーションを取り合える環境を希望します
- 新しい挑戦（新技術の導入など）や、技術的負債の解消に積極的に取り組める環境を希望します
- 技術発信や勉強会、カンファレンスへの参加に対して会社として支援いただける環境を希望します
