# [@MadakaHeri](https://x.com/MadakaHeri)

[X](https://x.com/MadakaHeri)
| [YouTube](https://www.youtube.com/@madakaheri)
| [face（制作中）](https://face.onface.io/madakaheri)

> 私のコード確認には [DependaHub](https://github.com/dependahub) のプロジェクトをご覧ください。

#### コードの耐用年数に重きをおくWebエンジニア

- ２年目からリーダー（テックリード兼フルスタックエンジニア）をしてきました。リーダには負の遺産のリプレイス、事故で稼働停止したサービスの再リリースなど重い作業ばかり回ってきます…
- React、Nextなど無駄に複雑な構造のフレームワークは破壊変更が多いので嫌煙しています。
- 逆にLaravelは、推奨はしませんが全部入りのパッケージとしては優秀。
- TypeScriptもフレームワークに等しく変更があるため **JS(ESM)+JSDoc** での開発を好みます。（TSを辞めるOSSも出てきている現状）
- ルーティング程度の簡単なものは自作してパッケージ化します（事業をフレームワークに振り回されないため）
- インフラは今だにAWS一強という感じなのでAmplifyとSAMでの構築が多かったです。
- 業務外ではイラストレーターとしても活動しています。


## 📣 ごあいさつ

**10年動くコード** をスローガンにして開発しており、基本は サーバーレス と JavaScript（ESM） で作成し、バックエンドにフレームワークは使用しないことを理想にしています。
Laravel等フレームワークのメンテナンスサイクルが事業スピードに合わないと思っていたので、Nextなども極力使わずにサーバーレスに任せる設計を推奨しています。
TypeScript に関しても更新頻度の高いフレームワークと見なし、リスクを考慮して使用しない方針のため JavaScript(ESM) + JSDoc での開発を推奨しています。  
Go言語 は方針に合うので使っていきたいですが、想像以上に自力で組み上げないといけない所が難点。


## ❤️ オープンソース・プロジェクト

OSSをやるなら戦略性を持って資金集めしていかないと継続できないと判断し足並み整え中。

### [DependaHub](https://github.com/dependahub) - 2025年2月〜
「破壊変更しないこと」をポリシーにパッケージ開発をしています。

### [Laravel Expansions](https://github.com/laravel-expansions) - 2021年 〜 2022年（更新終了）
Laravelの便利な拡張やサーバーレス化ツールを公開しています。  
＊ 資金が集まらず、最新版に対応していませんので非推奨

### ⚙️ VSCode拡張

### [node test runner](https://marketplace.visualstudio.com/items?itemName=MadakaHeri.vsce-node-test-runner) - 2025年11月〜

こちらnodeの標準テストモジュールで作成されたテストファイルに、Runボタンを表示するVSCode拡張です！
開発スピードが爆上がりするので是非みなさんお試しください！

![vsce-node-test-runner](https://github.com/user-attachments/assets/fdcb48f7-0427-4457-8dcf-7533d01d14ef)


---

## 🧩 アーキテクチャ

AWSをメインに使い、10年これでやってきましたが最近やっと一般的になった印象です。  
キーワード的には SPA / REST API / BFF / マイクロサービス 辺りが該当するアーキテクチャで、BtoBのクローズドなWebアプリは大体この構成で制作できます！

<img width="1333" height="817" alt="スクリーンショット 2026-10-19 13 18 43" src="https://github.com/user-attachments/assets/39a91dbe-a89f-4544-9e90-1f7fd19b5c64" />

Cloudflareを使う場合は、性質上どうしてもこれの劣化縮小版になってしまいますが、SPAでも手軽にプリレンダリング可能なためSEOやSNS対策のヘッダを仕込めるメリットがあります。（あと安い）  
正直、Cloudflareはまだ未完成感があるので、個人プロジェクト以外での使用はものすごく簡素なものだけになります。

---

## 👀プロフィール

性別：男 / 出身：大阪府

大学卒業後、上京して音楽制作で舞台の劇伴制作をしていました。
ランサーズなど便利なサイトが無い時代なので怪しい掲示板でチャットしながら仕事をとっていましたが、活動の中でホームページ制作、動画制作などやっていくうちにWeb系への転向を視野に入れて勉強し始め、WordPress全盛の少し前あたりからフリーランスで仕事を取るようになりました。
途中でウェアラブルキーボード「MettsKey」の特許申請して開発していましたが中略。
リーマンショックでなかなか本格的にWeb職につけなかったですが、2017年からフリーランス時代にお世話になった企業（ホテル系分析システム）で開発リーダーを6年務め2024年秋に退社。  
2024年春にエンジニアからお誘いがあり、渋谷の会社（NGワードチェックシステム）でリーダーを務めていました。
2026年夏に退社し、やっと大阪に帰ってこれました！
流石にもう大阪で根を張って活動していく所存です。

## 💖 趣味

少しでも趣味が合えばと思い書いておきます。  
イラストと音源はYouTubeに上がっています。

- 🎨 イラスト
- 🎹 DTM
- 🛹 スケートボード
- 🕺 ダンス

基本的に業務後と休日はこのどれかで活動しています。
＊ スケボーとダンスはダイエット目的

## 🌱 スキル / SPEC

### 🧑🏻‍💻 使用マシン
- MacBook Pro
- iPad mini

### 🖥 WEB系
- HTML5 / CSS3
- SCSS（全体フレームワークとパーツスタイリング）
- JavaScript(ESM)
- PHP
- MySQL
- Laravel（API）
- Vue.js（フロント）
- AWS Amplify

### 🦄 AWS（主に使用したもの）
- SAM CLI / Amplify CLI
- EC2 / Lambda / StepFunctions
- Aurora / Dynamo DB / S3
- SQS / Kinesis
- SNS /  SES

### 🦄 Cloudflare
＊ 個人プロジェクトはCloudflareで組んでます。
＊ 認証は clerk を使用します。
- Worker
- D1 / R2

### 🎨 デザイン
＊ Adobe系は常駐するし謎フォルダ勝手に作るので捨てました。
- **[基本] [Affinity (Designer/Photo/Publisher)](https://affinity.serif.com)**
- **[設計] [Figma](https://www.figma.com)**
- **[3D CAD] [Fusion360](https://www.autodesk.co.jp/products/fusion-360)**
- **[色彩設計] カラーコーディネーター３級**
