# 職務経歴書

## 目指したいエンジニア像

- SREやバックエンドのスペシャリストとして会社の基盤やシステム全体を支えるエンジニア
- 身につけた知識をチームにフィードバックして、周囲と一緒に成長していくエンジニア

## 強み

### 自走力と継続力があります

- 主体的にテーマを持って技術習得を行っており、日々キャッチアップを欠かしません
- 会社の勤務制度を利用して、朝6時出社、15時退社し、その後を時間を日々自習時間に充てています
- 2019年の後半は約週4,5の頻度で勉強会に参加しておりました
  - コロナ禍でも、オンライン勉強会に参加し、仲の良い人たちで週1で9:00-17:00で勉強会をしています

### 利他意識が強めです

- 学んだ技術を積極的に周囲に共有することに積極的です
- 勉強会等の自由参加の場でも、疑問や質問をこちらから掘り出し積極的に知識共有します
- もともと教師を目指していたことをあるくらい、人に教えることが好きです
  - 例として、Vagrantという[環境構築のツールのハンズオン](https://github.com/sunakan/vagrant-tips)を開きました。効果として、参加者が各自必要な環境を自力でVagrantfileを作成し、構築できる知識習得に貢献

### インフラ〜バックエンド〜フロントエンド、且つ構築・運用・保守・改善の経験があります

- 1人での0->1のWebサービスの構築経験があります
- フルスタックの対応ができ、どのフェーズ、ポジションでアサインされても、全体を考慮して構築、設計を行うことができます

## こんなことやりたい・興味があります

|やりたい・興味があること|
|:---|
|ペアプロ・モブプロ・コードレビュー|
|DDDでのチーム開発|
|クリーンアーキテクチャを採用したチーム開発|
|AWSマルチアカウントの設計と運用|
|クラウドネイティブなCI/CD基盤の構築|
|k8sの導入・運用|
|バッチ基盤の作成|
|継続的な負荷テストと可視化|
|Rust/Golangによるバックエンド開発|
|Elmによるフロントエンド開発|

## 基本情報

Name: sunakan

|メインで利用しているアウトプットサービス||概要|
|:---|:---|
|[Lapras/sunakan](https://lapras.com/public/ZQTTQGP)|ざっくりとした自分のアウトプットのまとめリンク集として使っています|
|[Github/sunakan](https://github.com/sunakan)|簡単なものでもとりあえずコミットとして残しています|
|[Scrapbox/sunabako](https://scrapbox.io/sunabako/)|自分のメモ書きとして利用しています|

## スキル

※実務経験があるスキルを列挙しています

### 言語

- Ruby
- Bash
- Java
- JavaScript
- CoffeeScript
- Groovy
- C#
- 日本語
  - ネイティブ
- 英語
  - ドキュメントが読める程度

### フレームワークやライブラリ

|key|value|
|:---|:---|
|バックエンド|Ruby on Rails / Grails / Sinatra / Padrino|
|フロントエンド|jQuery / d3.js / Bootstrap|
|デスクトップアプリ|JavaFX|
|モバイルアプリ|Unity|

### その他

|key|value|
|:---|:---|
|全般|GitHub / Docker / Makefile / Redmine / Slack|
|RDB/NoSQL|MySQL / SQLServer / Redis|
|ミドルウェア系|Solr / Fluentd / Nginx|
|DevOps・監視系|Jenkins / Webistrano|
|クラウド|ECS / CloudFront / S3 / Terraform|


## 主な職務経歴

### 自社サイトへのチャネルを増やす

|項目|内容|
|:---|:---|
|期間|2020/11 - 2020/12|
|概要|他社さんのサイトに自社サイトのキャンペーンページへのリンクを貼ってもらい、購入があった分だけ報酬を払う。そのために特定の期間内にどれだけ購入があったかをトラッキングできるような仕組みを作り、メールで送付するまでのプロセスの自動化システムの作成|
|効果|自社サイトへの流入のチャネルを増やす。バックオフィスが報酬メールを定期的に送る手間をなくす。|
|特徴|短納期、toB案件、PO1人/開発者1人/ヘルプ1人/QA1人の4人チーム|
|担当業務|要件定義、詳細設計、開発、デプロイ|
|技術スタック|Grails/Groovy/Ruby/Ruby on Rails/Javascript/jQuery|
|詳細|ヒアリング開始前に、概要だけさくっと聞いていました。<br>その事前説明の概要から自分なりの図を作成し、それをベースに話を聞くことで、1回目のミーティングを濃く進めることができました。<br>システム側の認識とPO側の認識のズレを発見できたので、それを修正する案を出しました。<br>キックオフ前にwikiに書いて、開発者が困った時要件を確認しやすいようにしました。<br>QAを含めて事前に見積もりをし、2週間を1イテレーションとしてプロジェクトを回しました。<br>バーンダウンチャートを常にPOに共有しながら、スピード感を持って開発を進められました。|

|直面した課題|どのように解決したか|
|:---|:---|
|メインで触るRailsプロダクトに実装されているAPIクライアント系のほとんどが返ってきたJSONデータをそのまま使いまわしており、ものすごく追いにくい状況にありました。（ドキュメント等が無く、どういう形のjsonかがcallしないとわからないことに加えて、更にデータ構造が動的でした。）|状況を打破するべく、今回用意するAPIクライアントにはクライアント専用のエラーモデル、返ってきたjsonデータを専用のデータクラスに置きなおすような仕組みを導入しました。|
|関わるサブプロダクトの方はREADME等のドキュメントがない状況でした。|今回の経験を通して、初めて触る人がすぐに開発に着手できるよう、READMEを記述しました。|

### 他社ウェブサイトのリニューアル

|項目|内容|
|:---|:---|
|期間|2020/10 - 2020/12|
|概要|他社さんのウェブサイトの外注先とリプレイス元のインテグレーションとキャンペーサイト構築|
|特徴|開発に関わる人たちが複数社あり、アプリが載るAWSアカウントも自社含め計3社あり、ステークホルダーが多めのプロジェクト|
|担当業務|アーキテクチャ設計、AWSを使ったソリューションの調査・実践、開発環境構築|
|技術スタック|Docker/Lightsail/CloudFront/ALB/S3/Terraform|
|詳細|会社Aさんのウェブサイトのリニューアルを機会に、開発と運用を会社Bさんから会社Cさんへ移行する大きめなプロジェクトでした。<br>諸事情に絶対守りたい納期に間に合わないという判断があったため、スポットでアーキテクチャ周りの補助として参画しました。|

|直面した課題|解決した方法|
|:---|:---|
|納期的に間に合わないという判断のもと、別会社別AWSアカウントのフレームワークも異なるアプリを合体させて1つに見せる必要があり、その方法が課題でした|CloudFrontというCDNを使い、パスによって振り分けることにより低コストで実現できました。|
|レスポンスや技術に課題のある会社さんと一緒に開発しており、課題に対してのソリューションがAWS応用編になってしまい、実行に難がある状況が多発しました。|スクショを張り付けた丁寧な手順書を用意し、共有して解決しました。|
|AWSのサービス応用する機会が多い中、知見がある人が社内にほぼいない状況でした。|もともと興味があったことでしたので、プライベートで積極的にキャッチアップを行い、実務でコミットして解決を図りました。|

忙しいながらも、なかなかないであろう体験だったため、このプロジェクトを通して得られた知見、課題、ソリューションを社内ブログと雑談会にて共有しました。

### WordPressプロジェクトのアーキテクチャ設計

|項目|内容|
|:---|:---|
|期間|2020/9 - 2020/10|
|概要|WordPressを使ったプロダクトのアーキテクチャの検討と見積もり|
|特徴|toB案件、WordPressを使う、WordPressのDBとは別に行動履歴を保存するプロジェクト、プロジェクトの数自体をスケールすることを考える|
|担当業務|アーキテクチャ設計、見積もり|
|技術スタック|WordPress/Fluentd/Lightsail/S3/ALB/Route53/ECS/CloudFront/EC2/Kinesis DataFirehose/RDS/EFS|
|詳細|PHPのモジュールを開発して、それを売りに他社さんのメディア基盤を自社が運用するというビジネスモデルの核となるアーキテクチャ設計。どういうアーキテクチャなら、急激な流入に耐えられそうか、またランニングコストとしていくらかかりそうか、そのビジネスモデルの料金設定に関わる設計。|


|直面した課題|解決した方法|
|:---|:---|
|トラフィック予想などが全くない状況で、通信量に関わる部分においても見積もりが要求としてありました。|サンプルページのサイズを計測して1日の訪問数を仮置きして見積もりを行いました|

この経験を通して、従量課金なサービスでもある程度の仮説をもって見積もりすることができるようになりました。

また、見積もり自体に慣れてなかったのですが、今回の経験を通してAWSの見積もりへの抵抗が減りましたが、パブリッククラウドを使っていくにあたって、どうコストを最適化していくべきかということを考えられるようになりました。

この経験や成果物としてのアーキテクチャ図を社内ブログにて共有し、雑談会でも共有し、社内メンバ全員のAWS知識の向上に貢献しました。

### チームが持つ古いプロジェクトのDocker化

|項目|内容|
|:---|:---|
|期間|2020/9 - 2020/10|
|概要|チームが持つプロジェクトをDocker化|
|効果|新しい人が入ってきてもすぐに環境構築ができて、開発効率を向上させる|
|特徴|IaCメイン、開発者3人|
|担当業務|Dockerfileのチーム独自のルール提案、docker build～保存するまでのチーム独自のフローの提案、いくつかのプロジェクトをDocker化|
|技術スタック|Docker/Ruby/Ruby on Rails/Padrino/Sinatra/Grails/Groovy/Jenkins|
|詳細|レガシープロジェクトだと環境構築自体にハードルが高いことが多く、場合によってはライブラリがどこにもないという状況も有り得ました。それをDockerを使うことでライブラリを閉じ込めた環境自体をあらかじめ用意しておき、すぐに環境構築できることを目指しました。また、毎日ビルドすることでライブラリが消えたことに早期発見できるような仕組みづくりも並行して行いました。|

アピール

```
チーム目標を立てた時点では、「チームが持ってるプロジェクトをDocker化する」というだけで、どのようにするかは決まっていませんでした。
それを実際に実行するにあたって、チームで統一性を持たせるために決めるべき項目がたすうありました。
実際に組もうとしてみて、課題を洗い出し、共通化させた方が理解が速そうな部分を積極的に発言と提案をしました。
また、仮に共通化したい場合だとこういう風リポジトリ構成をするのはどうか、説明だけではイメージしにくいだろうと思った（ピンとこないだろうなと思った）ので、実際にRubyだけでもリポジトリを作って、大変さやメンテしていくイメージも共有しました。（https://github.com/sunakan/ruby-docker）
（チームで統一性を持たせたい理由：チームの中で個人個人が考えてそれぞれのベストプラクティスでやった場合、次の人が入ってきたとき困惑する。さらに1つ1つの説明にも困る。属人化の排除にもつながります）

例：
「Dockerfileは何をBaseImageにするのか。debianか、チームで作るオリジナルか」
「ruby 2.4等で共通化したいなら、別途専用リポジトリを作るべきであるし、そうでないなら、特定のリポジトリで作ったbaseimageを他で使いまわさない等（どこで作られたかどうかわからなくなるため）」
「Dockerfile.development等複数ファイルにするのか、マルチステージングビルドにするのか」
「ステージングビルドの時のそれぞれのステージ名」
「既存のDockerfileはどうするのか」
「Jenkinsでのスクリプトはmake build && make xxxxとかにするなど、タスク名の統一等」
```

### 自社サイトのバナー管理の仕組みの改修

|項目|内容|
|:---|:---|
|期間|2020/7 - 2020/9|
|概要|商品ページのバナーの管理方法の改修と、文言の出し入れロジックの改修|
|特徴|PO1人、開発者3人、デザイナ1人、QA1人|
|担当業務|文言自体の変更と出し入れロジックの変更、出し入れロジックをモデルから剥がす|
|技術スタック|Ruby/Ruby on Rails/Docker|
|詳細|内製CMSを運用しているのですが、作ったバナー自体を色々な商品ページへ使い回しがしやすいよう、専用の管理ページの作成。また、商品の種類によって、適切な文言が出るようにするなどの改修。|

### カテゴリ・ランキングページ改修

|項目|内容|
|:---|:---|
|期間|2020/3 - 2020/6|
|概要|カテゴリページとランキングページの統合とUIの変更|
|効果|お客さんがカテゴリページとランキングページを横断的に見やすいようにする。独自コンテンツを増やし、SEO効果向上|
|特徴|PO1人、開発者3人、デザイナ1人、QA1人|
|担当業務|改修担当箇所の要件定義、開発（取得する商品情報のモデルの改修、ビジネスロジックをモデルから剥がす）|
|技術スタック|Ruby/ActiveRecord/Docker/Bash(Makefile)/Jenkins|
|詳細|顧客体験向上のために、できるだけUIを統一。商品ページへの誘導を増やすために魅力的なViewへ改修。表示するコンテンツ量を増やしSEO効果向上にも貢献|

### 他社さんから入力のあるDBから自社DBへ整形して入れこむバッチ改修

|項目|内容|
|:---|:---|
|期間|2020/4 - 2020/7|
|概要|他社さんから入力のあるDBから自社DBへ整形して入れこむバッチ改修|
|特徴|バッチ処理|
|特徴|開発者2人|
|担当業務|フロー設計、詳細設計、CD基盤構築、通知プログラムモジュールの作成|
|技術スタック|Ruby/ActiveRecord/Docker/Bash(Makefile)/Jenkins|

### ログ収集基盤のリプレイス

|項目|内容|
|:---|:---|
|期間|2020/1 - 2020/2|
|概要|古いコンテンツ検索のシステムの冗長化やインデックスのフローの設計・開発|
|特徴|リプレイス案件|
|担当業務|アーキテクチャ設計、詳細設計、実装、デプロイフローの確立|
|技術スタック|Fluentd/ECS/S3/Athena/Terraform/Docker|
|詳細|ログ収集基盤を古いミドルウェアからクラウドネイティブな基盤へと変更。<br>また、あと後分析するための分析基盤をある程度構築。|

チームで初めてのパブリッククラウドの本格利用でしたので、普段のキャッチアップが活きたプロジェクトでした。

### コンテンツ検索システムのリプレイス（途中でプロジェクト終了）

|項目|内容|
|:---|:---|
|期間|2019/6 - 2020/1|
|概要|古いコンテンツ検索のシステムの冗長化やインデックスのフローの設計・開発|
|特徴|リプレイス案件|
|担当業務|アーキテクチャ設計、詳細設計、実装|
|技術スタック|Solr/Java/Docker/AWS SQS/digadag/Apache |
|詳細|既存の古い検索システムを新しいものに置き換え、定期的にindexするというバッチの仕組みの維新|

途中で予算が合わないと判断があったため、設計書等を残してプロジェクトが悔しくも途中で終了しました。

途中で終わってしまいましたが、得られた知見は自分にとって大きく、特にDockerのVolumeマウント周りの知見は社内でも知る人がいなかったので、積極的に共有しました。
