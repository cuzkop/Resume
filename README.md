# 業務経歴書
## 基本情報

| key            | value                                     |
|----------------|-------------------------------------------|
| 名前           | 高橋 一貴                                 |
| エンジニア歴   | 2018/4~                                       |
| GitHub         | [https://github.com/kazuki5555](https://github.com/kazuki5555)             |
| Qiita          | [https://qiita.com/kazuki5555](https://qiita.com/kazuki5555)              |
| Twitter        | @cuzkop                                |
| ポートフォリオ | [https://kazuki5555.github.io/Portfolio/#/](https://kazuki5555.github.io/Portfolio/) |

## 会社経歴

* 2018/4 株式会社セプテーニ・クロスゲート入社
* 2019/4 株式会社トライコーン常駐
* 2019/4 株式会社ミロゴス出向

## 概要

* 基本的にはバックエンドエンジニアとして活動しています。
* 弊社プロダクトのxmaxの改修、社内管理ツールの開発等を行なっています。
* 小規模組織のため、フロントエンドやインフラ周りを触ることも日常茶飯事です。
* ２０１９年4月以降は主にLINE Botの開発業務に従事しております。

## スキル
* 業務経歴のあるもののみ列挙します。

### 言語

PHP7.x | JavaScript | Go1.12

### FW

Laravel5.8 | Codeigniter | Slim | ZendFramework | Vue.js

### その他

MySQL | PostgreSQL | GCE | GCA | CloudFunctions | GCS | S3 | DynamoDB | Redis | BackLog | Git | GitLab | GitLabCI | Jenkins | Docker | nginx

## 得意なこと

* Laravelを使った開発
* 保守性、柔軟性の高い設計
* ビジネスサイドとの要件定義

## 業務経歴(新しいもの順)

### pay系アプリ×会計アプリのLINE Bot作成　２０１９/9~

#### <u> 概要 </u>

会計APPに計上されているpay系APPにおける支払いをLINE上で確認できるBotを作成中。
期間指定による売上情報や支払い情報などを会計APPのAPIを通して取得。データ構造が売上ごとで膨大な長さのJSONなため、
効率よくソートできるようにCarbon等を使用。

#### <u> 職務範囲 </u>

* 設計
* バックエンドの実装(PHP/Laravel)
* 手動テスト
* ユニットテスト

#### <u> 発揮した強み </u>

* 共通処理になる部分が多いのでカプセル化、継承をうまく使い可読性、可用性の高いソースを実現。
* 趣味の競技プログラミングにて慣れた効率的なソートを実装。
* 自由に開発できた分、Laravelの便利な機能を用いた省エネ開発を実現。

### 電機メーカー写真プリント受付Bot作成　２０１９/6~9

#### <u> 概要 </u>

某電機メーカーの写真プリント受付Botを作成。
ストーリーが長く、分岐が激しいアプリだった。
また、枚数によって金額が代わり写真受付もある分間２００リクエストのBot。

#### <u> 職務範囲 </u>

* 設計
* バックエンドの実装(PHP/Slim)
* 手動テスト
* LIFFの作成

#### <u> 発揮した強み </u>

* Redisをうまく活用し、誤タップ(ダブルタップ)等によるズレを確実に排除を実現。
* ストーリーが長い分再利用性の高くなるような設計。




### 社内管理ツールの開発 2018/6 ~ 2019/3
#### <u> 概要 </u>

弊社プロダクトのxmaxの提携、単価等の設定関連を管理するツールの開発に途中からアサインされる。未経験からエンジニアになり、2ヶ月の勉強期間の末PHP/Laravelを使用してバックエンド開発。最初はリファクタリングから入るが10月以降は開発業務に着手

#### <u> 職務範囲 </u>

* 要件定義
* 設計
* フロントエンドの実装(HTML5/CSS3/MaterializeCSS)
* バックエンドの実装(PHP/Laravel)
* 手動テスト

#### <u> 発揮した強み </u>

* 理解速度の速さを活かして、アサインされてからすぐにLaravelの書き方に慣れる
* 先輩が退職した際に落ちると思われていた開発速度を落とさず、穴を埋める。開発完了を1ヶ月早めることを実現。
* 好奇心の広さからフロント、バックエンド共に触ったり、積極的にLaravel,PHPの機能を使いDRYを意識したコード設計を行う


### 社内管理ツールのGCP移行 2018/11月
#### <u> 概要 </u>

上記管理ツールのインフラをオンプレからGCPに移行するというプロジェクトにおいて、インフラ未経験ながら手を上げて担当。上司と二人三脚で実行。基本的な設計は変わらずということは決まっていたので、載せ替える作業を担当し、インフラの楽しさに気付く。

#### <u> 職務範囲 </u>

* 現状の調査
* インストールリストの洗い出し
* 動くところまで移行作業

#### <u> 発揮した強み </u>

* 好奇心の強さを行動に生かして3件の移行を担当
* 初学であり、何度も失敗、エラーを出すが粘り強さを生かして完遂


### 社内管理ツール開発環境のDocker化 2019/1
#### <u> 概要 </u>

vagrantで立てられていた仮想マシンをDockerによるコンテナ化するPJ。これは上記のGCP移行の際にインフラに興味を持ったことによって自らPJ化し、上司と二人三脚で達成。

#### <u> 職務範囲 </u>

* Dockerfileの作成
* docker-compose.ymlの作成
* 新たな開発環境リリース

#### <u> 発揮した強み </u>

* 業務遂行意識の高さから、なるべく自分で調べて動くところまで完遂
* 好奇心の強さを生かしたこの行動により、環境構築における工数を大幅に削減

