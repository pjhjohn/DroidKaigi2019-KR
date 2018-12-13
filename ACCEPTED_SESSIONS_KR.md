# 채택된 세션 목록 (88개 세션)

### ゼロから実装する縦書きTextViewとその周辺技術

`50분` `일본어` `기타`

**발표자** `六々 (@496_)`

View + InputConnection + Editable + Bitmapを使って縦書きのTextViewを実装した話をします。
TextVIewやStringを使わなくても文字入力ができるViewを作ることが可能です。

iOS / UWP / Windows / macOS / Ubuntuなどの他プラットフォームでの縦書きTextViewの実装経験も交えて、Androidでの縦書きTextView実装の概要と注意点について話します。
また周辺技術としてUnicodeの話、OpenTypeの仕様を中心としたフォントの話もあります。

**内容**

- TextViewとは何者か
  - 文字列入力系としての側面
  - フォント描画系としての側面
- IMEとは何か
  - 文字入力の仕組み
  - IMEとアプリの関係性
  - InputConnectionの罠
- StringとEditableについて
  - StringとAndroid Studioの関係 (閑話)
- UnicodeとフォントからBitmapが作られるまで
  - テキストレンダリングエンジン実装の概要
  - フォントの役割とOpenTypeの仕様
  - OpenTypeや文字列描画系から見たUnicode Emoji事情 (閑話)
- 昨今のAndroid内のフォント事情
  - Variable Fontの登場
- 縦書きTextView実装で気をつけるべきこと

**발표대상**

文字についてUnicode / IME / フォントと言われて何となくイメージが浮かぶ方を対象にしています。

特に: TextViewの独自実装に興味のある方 / 文字入力システムに興味のある方 / 文字描画システムに興味のある方 / 縦書きに興味のある方 に聞いてもらえると嬉しいです。

---

### Android Thingsでプロダクト開発

`30분` `일본어` `안드로이드 플랫폼`

**발표자** `Takuya Kubota`

Android ThingsのSoMを利用したプロダクト開発の実際について発表します。

Android ThingsのSoMをメインコントローラーとして採用したプロダクトを2019年にローンチします。プロダクト開発を通して得たThingsのPros / Consやノウハウを可能な限り共有します。

**발표대상**

Android Thingsを利用してプロトタイプから量産製品を開発しようと考えている方
Android Thingsが実用的なのか疑問に感じている方

---

### DialogFlowによる自然言語処理(NLP)を用いたボイスコマンド音声認識の精度向上

`30분` `일본어` `기타`

**발표자** `KAKKA`

近年、自然言語処理を用いた音声アシスタントやチャットBOTサービスが普及してきている。AndroidにおけるSpeechRecognizerも非常に認識精度が高い。
しかしこのような対話をベースとしたサービスは利用環境が制限される。例えば劣悪な環境雑音下での音声アシスタントとの会話や、文字自由に入力できないときのチャットBOTサービスはかなり使いづらい。対話が複数回必要になると更に難易度が増す。AndroidにおけるSpeechRecognizerが優秀であっても途中でユーザーがドロップする確率が高くなってしまう。

ユーザーにとって究極にフレンドリーなサービスは、何も言うことなく、何も文字を打つことなく正確に命令をすることであるが、現状では非常に実現難易度が高い。
よって今回は、ユーザーの仕事をなるべく減らし、かつ正確に命令をできる状態を目指す。

本セッションでは、最初にDialogFlowやAndroidのSpeechRecognizerの基本を極めて簡単に説明する。次にユーザーが特定の環境で、なるべくユーザーの仕事を減らしながら特定の目的を果たすために、AndroidのSpeechRecognizerとDialogFlowを組み合わせて用いることでボイスコマンド音声認識の精度向上を試みる。そしてその具体的な手法及び結果を示す。

**발표대상**

DialogFlowによる自然言語処理に興味がある
DialogFlowを使ってみたいけどいまいち実用化できるケースが思い浮かばない
Androidで音声アシスタントのようなものを作ってみたい

---

### Android Studio設定見直してみませんか？

`30분` `일본어` `개발툴 & 생산성`

**발표자** `shiraji`

2014年末からAndroid Studio v1.0.0が出てから、ほとんどの方がAndroid Studioを使ってAndroidアプリの開発をしていると思います。
IntellijをベースにしたAndroid Studioでは非常に多くの機能が存在しています。しかしあまりにも多いため、埋もれてしまっている便利な機能があるのではないのでしょうか？
このセッションでは、Android Studioの隠れた便利な機能を紹介して、Android Studioを使った開発をより快適に出来るようにお手伝いしたいと思います。

以下の知識がある方を想定しています。
* Android StudioでAndroidアプリの開発をしたことがある
* Android Studioの設定をあまり変えたことがない
* 複数人での開発を主にしている
* セッション中にすごいと思ったら「おー！」って言ってくれる

このセッションでは以下の設定の話をする想定です。独断と偏見で大半の方が触らないであろうと思った設定を中心に説明します。
* 自分専用のアクションリストを作ってみる
* !=をカッコ良く
* 通知周り
* File Color
* Kotlinのファイルフォーマット忘れ防止
* 急に別の言語書きたくなった時のストレス発散方法
* JSON書きやすくする
* Run Configurationや.ideaの共有
* Layout Editor
* Pluginのインストールの強制

발표대상**

少なくとも「Android StudioでAndroidアプリの開発をしたことがある」は満たして下さい。

---

### Fast Prototypes with Flutter + Kotlin/Native

`30분` `영어` `크로스플랫폼 개발`

**발표자** `JB Lorenzo`

working with Flutter and kotlin/native for cross platform development (done on a conference app). see article

https://tech.olx.com/fast-prototypes-with-flutter-kotlin-native-d7ce5cfeb5f1

**발표대상**

Developers

---

### Dexs, R8 & 3.2

`30분` `영어` `안드로이드 프레임워크 & JetPack`

**발표자** `Iñaki Villar`

In this talk we are going to see the internals of the new Dexing Compiler D8, introduced in AS 3.0 as experimental, D8 will give us faster and smaller outputs of dex files. We will understand better how is the Dex Processing in Oreo/P from the ART perspective, and how is affected in the new bundle apps.

Additionally, we will see more about R8 a replacement for Proguard used in AS 3.2

**발표대상**

Android Developers with basic knowledge of the build process.

---

### Deep dive into MotionLayout

`50분` `영어` `UI & Design`

**발표자** `thagikura` `John Hoford` `Nicolas Roard`

MotionLayout is a new ViewGroup focusing on animation, which is provided with the ConstraintLayout 2.0 library.
We provided this ViewGroup to allow developers to create complex animations in a declarative way, which existing Android animation framework, such as Layout Transition using TransitionManager, CoordinatorLayout or ObjectAnimator, didn't cover. 
In this talk we will going to cover the topics from the getting started and how MotionLayout differs from the existing animations framework to the deep dive into how the MotionLayout works.

Following topics are going to be included:
- Getting started
  - What is MotionLayout
  - Highlights of the key usages
  - What is the difference with the ways of animation Android framework provides
  - Integration with the layout editor
- Where to use MotionLayout
  - Real app examples
  - Replacing existing animations in a declarative way
  - Integration with other key Jetpack components
- How MotionLayout works internally
  - Math behind the scenes
- Future plans

**발표대상**

Difficulty level : Beginner - Intermediate
Target audience: Developers interested in animations or MotionLayout.
Prerequisite about MotionLayout isn't required, but we are also going to cover the topics beyond the getting started level.

---

### Best practice for text on Android and its internals.

`50분` `일본어` `안드로이드 플랫폼`

**발표자** `Seigo Nonaka`

私達Android Textチームは昨年のGoogle I/Oで"Best practices for text on Android"というタイトルで発表を行いました。
Droid Kaigi 2019では、この発表のフォローアップ、およびもう一歩踏み込んだ内容を話したいと思います。

トピックは以下の内容を検討しています。
・TextViewのパフォーマンス特性
・PrecomputedText(Compat)の使い方とその原理
・その他Google I/Oでは語られなかった雑多な変更等について

We did a session in Google I/O 2018 about the best practices for text on Android.
I'm going to follow up the Google I/O talk and give a talk of more internal details.

I will talk about

- The performance tuning of TextView
- How to use PrecomputedText(Compat) and its internal details.
- Minor changes not featured in Google I/O 2017

"Best practices for text on Android" in Google I/O 2018
  https://events.google.com/io/schedule/?section=may-9&sid=532cc42d-df69-4ded-9766-2987ea46d2d7

**발표대상**

AndroidのTextViewを使ったことがある方
Androidが文字を表示する仕組みに興味がある方

People who has an experience of using TextView on Android.
People who are interested in how the Android renders the text on the screen.

---

### Trash Talk

`50분` `영어` `안드로이드 플랫폼`

**발표자** `Romain Guy` `Chet Haase`

With improvements in the ART runtime, developers should feel better about favoring good development patterns over memory-optimized-but-ugly-and-fragile techniques. But all of this is based on assumptions about the improvements of ART over Dalvik — what are the details?

This talk will examine some of the specific improvements that ART has made, over Dalvik and over time, and will demonstrate what these improvements mean for raw performance of garbage allocation and collection work.

**발표대상**

Any Android developer wanting to better understand the behavior of the Garbage Collector to improve performance. No prerequisite knowledge is required.

---

### マルチモジュールプロジェクトでのDagger2を用いたDependency Injection

`30분` `일본어` `앱 아키텍처 디자인`

**발표자** `kgmyshin`

Dagger2とはJava用のDependency Injectorです。
そして、Dagger-AndroidとはそのDagger2をAndroid用に拡張したライブラリです。
昨今、Dependency InjectionはAndroidアプリ開発に欠かせない技術となっております。
そして様々なDI用のライブラリがある中で、Dagger2はその中で代表格であるといっても過言ではありません。

そのような状況の中、一方で、Androidアプリを開発する際にマルチモジュールなプロジェクトで開発する現場が増えてきました。
このマルチモジュールなプロジェクトを実践する中で、どのようにDependency Injectionを実現するか。
実はこれがマルチモジュールプロジェクトで開発する際の、大きなハマりどころの一つだったりします。
本セッションでは、この大きなハマりどころをDagger2を使ってどのように解決するかを説明します。

アジェンダとしては仮ですが下記を予定しています。

1. Dagger2再入門
2. Dagger-Androd再入門
3. シングルモジュールプロジェクトでのDI
4. マルチモジュールプロジェクトでのDIの辛さ
5. Dagger2を使ってマルチモジュールプロジェクトでDIを実現する

**발표대상**

- マルチモジュールプロジェクトでのDIにお困りの方
- マルチモジュールプロジェクトでのDIについて興味がある方
- Dagger2の使い方を知りたい方
- Dagger-Androidの使い方を知りたい方
- Dagger2, Dagger-Androidの内部実装を知りたい方

---

### 실천 Lottie

`30분` `일본어` `개발 프로세스`

**발표자** `kumanomi`

제가 담당하는 프로덕트에서 Lottie를 사용해 개발하였습니다.
그 결과 Android / iOS에서 부드럽게 풍부한 애니메이션을 사용하여 구현할 수 있었습니다.

- Lottie 도입으로 얻을 수 있었던 장점
- 단점
- 디자이너와 주고 받다가 생긴 일
- 도입사례
- 도입결과

위 항목으로 이야기 할 수 있으면 좋겠습니다.

**발표대상**

아직 Lottie를 사용해보지 못한 분
엔지니어의 힘을 빌리지 않고 풍부한 애니메이션을 도입하고 싶은 분

---

### PWAでここまで出来る

`30분` `일본어` `크로스플랫폼 개발`

**발표자** `SAMUKEI`

PWAはJava/Kotlinなどのネイティブアプリと対立するわけではなく、Webアプリの開発者をモバイル開発の土壌に上げるものとして非常に有用な仕組みであり、次世代のモバイルアプリケーションとしての答えの一つだと考えています。
PWAを知らない方に対しての簡単な説明をし、PWAの肝となるService Workerを実際に活用した"クライアントだけで動く"動画編集の体験を実現するための方法をご紹介します。

**발표대상**

- クロスプラットフォームに興味のある方
- PWAの技術に興味がある方
- PWAを知らない方
- Webの知識がある程度あるとより楽しめると思います！

---

### Optimize Builds with Android Plugin for Gradle 3.3.0+

`30분` `영어` `개발툴 & 생산성`

**발표자** `Adarsh Fernando` `Izabela Orlowska`

Builds can always be faster and more efficient. Whether you are a lone developer or a large team, a 10% build speed improvement adds up over the course of a project. And your time is important.

If you're an Android Developer using Android Studio, you are already familiar with the Gradle build system and the Android plugin. In this talk, a member for the Android Studio team discusses tips, tricks, and strategies you can use to improve build speeds using Android Gradle plugin 3.3.0+.

- Improve build speeds when supporting Android App Bundles
- Incremental compilation while using annotation processors
- Faster configuration with Lazy task configuration
- Utilizing single-variant project sync
- Understand classpath dependency synchronization
- Variant-aware dependency management
- Compilation avoidance via new dependency configurations
- Sneak peek into future improvements of the plugin

**발표대상**

Intermediate developers on moderately-sized teams that want to  improve build speeds.

---

### Grid systems and Android

`30분` `영어` `UI & Design`

**발표자** `soham`

A grid system is at core of any standard, objective design and yet most android applications (and mobile applications in general) fail to pick up on this. In this talk, I will talk about the grid system and why its so important for design in general and on android in particular.

Talk structure
- What is the grid?
- Why is it so important for design?
- Evolution of the grid
- Grid in print design, on the web and elsewhere
- The typographic grid
- Grid on mobile and android
- Material design guidelines
- Material design keylines, metrics, typographic grid
- Examples: With and without the grid
- Key takeaways for android/mobile designers, best practice on android
- Some tools to help with your design: keyline pushing, designer tools

**발표대상**

Intended audience
- mobile designers: grid guidelines for android and the best practices/tools that can be employed
- mobile developers: background on what the grid is and why its important? how to match designs given by the design team to the given design specifications
- startups and businesses: what is the grid in design and why every app/platform should be designed with the grid in mind

No specific prerequisite knowledge required.

---

### SpekでUnitTestを書こう

`30분` `일본어` `유지보수 & 테스팅`

**발표자** `morimoto ayako`

SpekはJetBrain社が開発しているUnit Testが書けるテストフレームワークです。RSpecというRubyのテストツールに記法が似ています。
JUnitに慣れているとはじめは特殊に感じるかもしれませんが、慣れると「このテストは何を確認したいのか？」がとてもわかりやすいのでおすすめです。
本セッションではまずSpekの利用方法をお話します。
後半は実例を交えながら、どのようなテストを書けばよいのか、ということや、開発の主流になってきているLiveDataやRoomを利用したクラスのUnit Testを作成する際にはまったポイントについてお伝えできればと思います。

- Spekの紹介と利用方法
   - Spekとは
   - given / on / it
   - Mockitoと組み合わせたテスト例
- Room導入時のUnit Testの書き方 / はまったところ
   - Roomはコンテキストを利用しなければならないが、Unit Testを行うには？
- LiveData導入時のViewModel Unit Testの書き方 / はまったところ
   - LiveDataのライフサイクルとテスト

**발표대상**

- Unit Testを今年こそ書くぞと思っている方
- もっと簡単にテスト書いてみたい方
- Spekを知らないけど、今後利用してみたい方

---

### 中規模以上のアプリ開発におけるCIレシピとリリースフロー戦略

`30분` `일본어` `유지보수 & 테스팅`

**발표자** `KazaKago`

BitriseやCircleCI, TravisCIなどに代表されるCIツール（継続的インテグレーション）の導入方法を解説した記事は多くありますが、実際に運用フローに組み込むところまで言及されていることは少ないと思います。
複数人のエンジニアが絡む中規模以上の開発においては、開発フローに一定のルールを設け、ブランチ運用とCIをうまく連携させて自動化しヒューマンエラーを減らすことが大事です。

3〜5人での開発体制の中規模アプリを2週に1度のペースでリリースを年単位で続けた自身の経験を元に、実運用に耐えうるブランチ運用とCIレシピから事故の少ないリリースフローまでをGitFlowとBitriseをベースに解説します。
また、Google Play Developer Publishing APIを活用して安定的なリリースを行うための手法や各プロダクトに合わせたカスタマイズ方法についても、実際の業務での運用を元に解説する予定です。

目次（予定）
1. 開発体制のルール化とマイルストーンの設定
2. GitFlowを用いたアプリ開発フロー
3. CIツールとブランチ運用の連携による作業自動化
4. Google Play Developer APIを活用した安定的なリリース手法

**발표대상**

- 複数人開発で開発フローに悩んでいる方
- 最近開発メンバーが増えてリリース運用の属人化脱却を考えている方
- 今のデプロイやリリースの作業が全て手動でなんとかしたい方
- CIを動かしただけで満足してしまって効果的に活用できてないと感じているそこのあなた！

---

### ああ、素晴らしきTDD ~アプリとエンジニアの心に安寧を~

`30분` `일본어` `유지보수 & 테스팅`

**발표자** `Saiki Iijima`

**概要**

近年、Androidアプリはどんどん複雑化していますが、それと裏腹に、よりスピード感を持った開発が求められています。
しかし、そのような状況でもエンジニアとしてアプリの品質を落とすわけにはいきません。
本発表では、発表者が業務で行なっているTDDの知見を基に、テストとはなにか、そしてアプリの品質を高めより早くリリースするために如何に重要であるかを再確認し、また、エンジニアにとってどれだけメリットがあるかを熱く語ります。
そして実際のAndroid開発(MVVM)において効果的なテストを書くために何を考え、どのような意識をもつべきか、espressoを使ったUIテストとJUnitを使ったunitテストを例に話していきます。
本発表を聴き終わった後、きっと誰もがテストを書きたくなることでしょう。

**発表のゴール**

* テストを書きたくなる
* どうすればテストを書けるかわかる
* 良いテストを書ける気がしてくる

**予定している内容**

テストとは？

* テストの四つの価値
* テスト makes happy

TDDとは？

* 開発の流れ
* メリット・デメリット

テストの種類と特徴

* unitテストーJUnit
* UIテストーespresso
* 中間のテストーRobolectric

テストの書き方

* 基本知識
* unitテストーJUnit
* UIテストーespresso
* Tips：AssertJ
* 粒度と数

テストのためのAndroidコード設計

* ロジックとUIの分離（MVVMを例に）
* 依存の注入とmockの活用
* Tips：LiveDataのテスト
* Tips：Daggar2が使えない時は

まとめ

**발표대상**

- Android開発初心者〜中級者
- テストに興味があるがいまいち良くわからない方
- テスト駆動したいと思っている方
- テストなど書かない方

---

### Journey of APK from compilation to launch

`50분` `영어` `안드로이드 플랫폼`

**발표자** `Amanjeet Singh` `Romi Chandra`

In this talk we will cover journey of APK when we hit run button of Android studio till the point when Launcher Activity onCreate method is called. Following is the outline of the talk:
1. Compilation of APK: Basic components of APK, how the APK zip archive is formed, compiling java to class file format and how this is changed to DEX,  JVM vs DVM, zipping to APK format
2. Decoding runtime of Android: Comparing ART and Dalvik, different steps involved till installation of android app, how the modern AAB, split APK works during runtime and optimizes. Importance of optimizing bytecode.
3. Multidex: The point where app meets multidex, what happens under the hood during multidex and best practice to avoid common errors of multidex.
4. Starting of Android App and best practice to have minimum app start time: How the app starts from forking a zygote to the onCreate callback and how the start time can be badly affected if not taken care of. Best practice to have minimum start time of apps.

**발표대상**

Intermediate/Advance

---

### 今日から始める依存性の注入

`30분` `일본어` `앱 아키텍처 디자인`

**발표자** `kobakei`

アプリケーションが巨大になってくると、コンポーネント同士が密結合したり依存関係が複雑になりがちです。こうしたアプリケーションではテストが書きにくくなったり、特定のビルドだけ依存先のコンポーネントをカスタマイズするといったことが難しくなります。こうした問題を解決する設計パターンとして、依存性の注入（Dependency Injection: DI）というものがあります。依存性の注入とは、コンポーネントの依存関係をソースコードから排除し、外部に追い出してしまうソフトウェアパターンです。

本セッションでは、皆様が普段開発されているAndroidアプリにおいて、依存性の注入がどのように適用できるか、どういったメリットをもたらすかを解説します。また、現時点で最も利用されているDIコンテナであるDaggerと最近注目されつつあるKoinを比較しつつ、それぞれのDIコンテナでの実装についても紹介します。

アジェンダ（予定）

- 依存性の注入（DI）とは？
- Androidアプリ開発におけるDI
- 主なDIコンテナの紹介
  - Dagger / Google製の最もポピュラーなDIコンテナ
  - Koin / 今注目のKotlinで実装されたDIコンテナ
- DI導入後のテストの書き方
  - 単体テスト
  - UIテスト

**발표대상**

以下のような課題を感じているAndroid初級者が対象です

- クラス間の複雑な依存関係や密結合に悩んでいる人
- 依存性の注入という単語は知っているがイマイチ理解しきれていない人
- 雰囲気でDaggerを使っている人

---

### ぼくのかんがえた最強のUsecaseの作り方~あるいはビジネスロジックとはなにかという1つの回答~

`30분` `일본어` `앱 아키텍처 디자인`

**발표자** `Keisuke Kiuchi@fei_kome`

ビジネスロジック、Domain層、UseCase。これらはMVVMやMVP、CleanArcitectureなど、3-Layeredアーキテクチャーではよく聞く単語だ。

しかし、いざ設計しようとすると
「つまり、ビジネスロジック/Domain/UseCaseって何？」
「レポジトリから取得したデータをそのまま渡すだけになるんだけど、これでいいの？」

などなど、首をひねりながら設計する人は多いのではないだろうか。かくいう私もその一人だった。

今回の発表では、CleanArchitectureにフォーカスし、「ビジネスロジック/Domain/UseCase is 何」という疑問を紐解いていこうと思う。
具体的には個人で開発しているアプリの「らくでん」の実装を元に、

- ビジネスロジックってどういうものを指すのか
- Domain層(UseCase)をどのように設計していくか
- 何をDomain層に入れるか/入れないか

を話していく予定だ。

**발표대상**

- CleanArchitectureに興味がある人
- CleanArchitectureを導入しようと考えている人 
- CleanArchitectureを使ってるけどUseCaseの設計が迷ってる/よく分からない人
- ビジネスロジック、Domain層、Usecaseって単語は聞くけどつまり何？という疑問がある人

---

### マテリアルデザインの起源とベースとなる哲学

`50분` `일본어` `UI & Design`

**발표자** `ken`

**概要**
マテリアルデザインの根底にある哲学とそこに至る背景を整理考察した内容を発表します。

「デザイン哲学=そのデザインを作成した人の哲学」という視点から、マテリアルデザインの本質を紐解いていきます。

**背景**
マテリアルデザインが2014に発表されてから、多くの開発者やデザイナーはGoogleが提供するマテリアルデザインガイドラインを参照して開発を行ってきました。

マテリアルデザインガイドラインにはルールの記載はあるが、ルールにいたった理由や背景が記載されていません。
理由や背景がないために、企画・開発・デザイン間でガイドラインにどこまで従うべきかの判断が難しい状況が度々起こるかと思います。
そもそも作った人はどういった意図でこのガイドラインに落として行ったのかを考察することで、議論の有効な論点の一助となればと思います。

**발표대상**

マテリアルデザインに興味がある方であればどなたでも

---

### ちゃんとつくる Google Assistant アプリ

`30분` `일본어` `안드로이드 플랫폼`

**발표자** `sesta`

Google Assistant や Amazon Alexa といった音声アシスタントシステムが登場し、様々な場面で日常に入り込んで来ています。
しかし、音声をベースとしたサービスやプロダクトはまだまだ試行錯誤の段階であり、
Webやネイティブアプリ以上にプロトタイプの作成や改善の繰り返しが重要です。

本セッションではそのような開発の流れに耐えうる Google Assistant アプリをちゃんと作成できるように、
リリース前にユーザーにテストをしてもらう方法や、開発環境と本番環境の切り分け、
CLIベースでのテストが行える構成について実際の運用での知見を交えて紹介します。

**발표대상**

- Google Assistant アプリを開発・運用していきたい方
- スマートスピーカー関係の案件が降ってきそうで慌てている方

---

### Android Vitals徹底活用

`30분` `일본어` `유지보수 & 테스팅`

**발표자** `kr9ly（からくり）`

快適なAndroidアプリをユーザーに提供しようと思うと、避けて通れないのが

- クラッシュフリー
- ANRフリー
- 高い描画パフォーマンス
- 短い起動速度

等の非機能要件です。現在のGoogle Play Consoleでは、Android Vitalsというこれらの各種パフォーマンス指標をウォッチし、改善の役に立てることができる情報を見ることができる機能が提供されています。

本発表ではAndroid Vitalsを知らない方、知っているが何となく触れずに来た方、見ているが実際にどう活用するべきかわからない方などに向けて、Android Vitalsをどう見るか、どう活用していくかという話をします。起動速度や描画速度の改善を目的とした際に、Android Studioのパフォーマンスプロファイリングの機能を活用する方法、あるいはGoogle Play Consoleの自動テストを活用して致命的なクラッシュ問題を避ける方法など、Android Vitalsに限らずAndroidアプリのパフォーマンス改善に役立つ方法についても実践内容を交えてお話ししますので、そちらに興味がある方にもおすすめです。

**발표대상**

- Android Vitalsを知らない方
- Android Vitalsを知っているが何となく触れずに来た方
- Android Vitalsを見ているが実際にどう活用するべきかわからない方
- Android Studioのパフォーマンスプロファイリング機能を有効に活用する方法を知りたい方  前提知識  Androidアプリ開発についての基本的な知識

---

### Guide to app architectureを踏まえた既存アプリの設計改良

`30분` `일본어` `앱 아키텍처 디자인`

**발표자** `nakamuuu`

Androidに限らずアプリケーションの開発において、設計・アーキテクチャの課題は常々付きまとうものです。
MVP / MVVM / MVI / Clean Architectureなど、今回のDroidKaigiにおいても多くの登壇者が設計に関する知見を共有してくださることと思います。
しかし、Androidの初学者、あるいは既にレガシーなコードを抱える開発者にとって、モダンな設計というのはどうにも取っつきにくい領域です。
公式のドキュメントであるAndroid Developersには「Guide to app architecture」というページがあります。
このページでは、Architecture Componentsを用いたテスタビリティと構成の変更（Activity / Fragmentの再生成）への強さを兼ね備えた設計について細やかな解説がされています。
https://developer.android.com/jetpack/docs/guide
本セッションでは実際に「Guide to app architecture」を参考にして既存アプリの改良を進めた経験を基に、以下のようなお話をさせていただく予定です。

- 「Guide to app architecture」で解説されている設計の概要と要点
- 既存アプリの設計改良において留意したポイント
- 既存アプリの特徴、開発体制に合わせた設計のアレンジ
- 実際に既存アプリに取り入れた設計とその効果

**발표대상**

- 既存アプリの設計改良についてどこから着手していいか悩んでいる方
- プロダクトの成熟フェーズへの変化の中で既存アプリの設計改良を検討している方
- MVP / MVVMなどのレイヤー化された設計に興味を持ちつつも取っ掛かりが掴めない方

---

### What does "adb lolcat" do? A deep dive into adb

`30분` `영어` `개발툴 & 생산성`

**발표자** `32bitdesi`

If you've been an Android developer for any length of time, sooner or later you will have encountered adb -- the Android Debug Bridge. Part of the Android SDK, it is most commonly used to view the logs continuously being emitted within a device (via adb lolcat) or to run commands directly on device via a shell. But it is, as its name suggests and as you might already know, also a bridge to a variety of other functionality and information.
Have you ever wondered how adb does its magic? Or what _actually_ happens when you type in `adb shell`? In this session, we'll dive right into the deep end and take a peek under the hood to understand how every Android developer's favorite tool works.

**발표대상**

Intermediate Android developers would derive the most from this. Audience should have a working knowledge of the Android SDK tools, and have ideally viewed device logs indirectly or via the adb tool itself. Anyone curious about adb's functionality and/or puzzled by some of the tool's behavior will find this session useful.

---

### 実践 WorkManager

`30분` `일본어` `안드로이드 프레임워크 & JetPack`

**발표자** `_atsushisakai`

私が現在開発をしているAndroidアプリ「家族アルバム みてね」では、画像を高速に閲覧するための工夫を随所に入れています。WorkManagerを使ったバックグラウンドでの画像の事前キャッシュ機能もそのひとつです。

このセッションでは、画像の事前キャッシュ機能を開発するに至った経緯を共有したうえで、WorkManagerの実践的な利用方法や実装・テスト手法や実装上の苦労した点などを知っていただければと思います。

**予定しているアジェンダ**

画像表示速度に関する課題について
「みてね」のAndroidアプリでは、特に海外ユーザーに対してより快適にアルバムを閲覧してもらうために画像の表示を高速化しなくてはいけない課題を抱えていました。セッションではより詳細に課題のポイントを説明します。

WorkManagerの利用に到るまでの経緯
課題を解決するために、最終的にAndroidアプリ側でバックグラウンドで画像を事前にキャッシュする手法を選択し、その実装のためにAndroid Jetpackに含まれるWorkManagerを利用することにしました。

WorkManagerによる機能実装について
WorkManagerは「ネットワークなどの端末リソースの状態を検知する」「定期実行する」「ユニークなジョブ実行を保証する」などバックグラウンドで処理を実行する際に気をつけたいことがAPI自体にすでに備わっているため、それらの複雑な条件はAPIに任せて実装したい処理に自体に集中することができます。
ここでは、Workerを実装する際に重要な以下の点についてを話したいと思います。

- 冪等性を担保した処理の実装
- テストの書き方について
- タイムアウトなどWorkManager自体の制約について
- その他

機能を実装した結果得られた効果とさらなる課題
WorkManagerによって効率的に画像を事前キャッシュすることで得られたユーザー体験の向上をデモンストレーションによって体験していただければと考えています。また、残されている課題についてもご紹介できればと思います。

**발표대상**

- Androidアプリで画像表示速度についての課題を抱えている方
- WorkManagerを用いた実際の課題解決のサンプルを知りたい方
- Androidアプリのバックグラウンド処理実装に興味のある方

---

### Chromebookで始めるラップトップ向けAndroidアプリ

`30분` `일본어` `기타`

**발표자** `Hosshan`

ChromeOSでは、Androidのアプリを動かすことができ、beta版ではありますが、LinuxをChromebook上で起動することができるため、Android Studioを使用した開発から実機での確認までが端末上で完結する開発環境となります。
そんな今後Androidの開発環境として魅力的なChromebookでのAndroid開発環境の構築と、キーボードや画面サイズ変更などが頻繁にあるラップトップAndroidアプリ開発における注意するポイントなどを発表したいと思います。

**발표대상**

ChromeOSに興味がある人、ラップトップ向け、キーボードありなどのタブレットなど、スマホとは違う環境向けのAndroidアプリ開発に興味のある人

---

### Navigation Architecture Component によるアプリ内遷移の管理

`30분` `일본어` `앱 아키텍처 디자인`

**발표자** `Yuta Takahashi`

Navigation Architecture Component は, AndroidアプリにおけるActivity および Fragment 間の遷移をより簡単に実装するために開発されました. これまで, Fragment間の遷移はFragmentTransactionを用いて実装したり, Deep Link も独自に実装することが主流でした. Navigation Architecture Component は, アプリ内における遷移を包括的に管理するために開発され, 同時に先述の問題を解決しています.

このセッションでは, 実際にプロダクションで Navigation Architecture Component を利用してリリースした経験を元に, 以下の内容について発表する予定です.

- Navigation Architecture Component の基本的な考え方と使い方
    - Navigation は何を解決するのか
    - 基本的な使い方 (Fragment同士の遷移, ActivityをまたぐFragment間遷移, Shared Element, etc.)
    - Deep Link の実装方法
    - コードから読み取れるNavigationライブラリの思想から考えるアンチパターン
- Navigation Editor の使い方と, そもそも使うべきかの話
    - Navigation Editor の概要
    - Navigation Editor はいつ使うのか / 使ったほうがいいのか
- SafeArgs によるActivity/Fragment間のデータ受け渡し
    - SafeArgs の概要と使い方
    - サポートされているデータ型と使い方
    - 独自クラスの受け渡し方法などのTips
- 実際にプロダクトで用いた経験に基づく個人的ベストプラクティス
    - AAC(Android Architecture Components) と併用したときに困ったこととその解決策など
    - Navigation Graph をどう分けるか

**발표대상**

Navigation Architecture Component を使ったことがない方 / 使い始めたい方
複雑になってしまった Activity / Fragment の遷移やDeepLinkをよりシンプルに記述・管理したい方

---

### WiFi Direct + VpnServiceでSIM無しAndroidをWeb世界に社会復帰させる話

`50분` `일본어` `기타`

**발표자** `soranakk`

**前提1**
AndroidにはWiFi DirectというAndroid端末同士でP2P通信ができる機能があります。
これを使うとAndroid端末間でByteStreamを使ってbyteデータをやり取りすることができます。

**前提2**
AndroidにはVpnServiceというサービスクラスがあります。
これはAndroidでVPNを繋ぐときに利用するサービスでVPNソフトを作りたいときなどに利用します。
このサービスにはAndroid端末で外部通信に流れるPacketデータが全て流れてきます。

さて、これらの前提を元に、ここにSIMが刺さっていないAndroid端末が一台あります。
さらにSIMの刺さったAndroid端末がもう一台あります。
もうわかりますね？
さあ、SIMの刺さっていないAndroid端末からHTTP通信を成功させてください。

- え？なんでWiFi Direct + VpnServiceなの？普通にテザリングでよくない？
- VpnServiceに流れてくるbyteデータは生のIP Packet
- HTTP通信はTCP通信というプロコトルの上で成り立っている
- TCP通信って？UDP通信ってのもあるの？
- Packetの構成
- TCP通信の仕組み
- AndroidでSocket通信する
- Socket通信で流れてくるbyteデータは生Packetではない
- 足りないデータは作るしかない
- いろいろ頑張ったら〜、できた！

このセッションでは通信の低レイヤーの話が出てきますが、それを理解してもらうことが目的ではないです。
このセッションを聞いて「Androidではこういうことも出来るのか」という可能性を感じてもらえると嬉しいです。

**발표대상**

マニアックな話が大好きな人
Androidの可能性に興味のある人
KotlinでSocket通信を実装する話に興味のある人

---

### Unit test for ViewModel and LiveData

`30분` `일본어` `유지보수 & 테스팅`

**발표자** `hkusu`

Android Architecture Components の ViewModel を利用した MVVM アーキテクチャを採用する場合、ロジックは必然的に ViewModel に集まり ViewModel のサイズは膨らみがちです。

このセッションではテストしやすいよう ViewModel をどう設計するか、どうテストするかについて説明させていただきます。

（テストフレームワークは Spek を予定していますが、セッション近辺の状況しだいで変更する可能性があります。）

**발표대상**

- Android Architecture Components に興味がある方
- これからテストを書いていきたいというテスト初学者

---

### Lifecycle, LiveData, ViewModels - The inner wiring

`30분` `영어` `안드로이드 프레임워크 & JetPack`

**발표자** `Florina Muntenescu`

Android Architecture Components is a set of libraries for designing great apps. It contains APIs for implementing concepts like Lifecycle and ViewModel.
Whilst these APIs are great, they do come with some questions:

- How do Lifecycle, LiveData and ViewModels work under the hood? How and where should each of them be used?
- What is the difference between a ViewModel from Architecture Components and the one from the MVVM pattern?
- Lifecycle components exist for Activities, Fragments and Application. Why don’t we have the same for Views?
- Can we have ViewModels for Views also?
- Is LiveData a replacement for RxJava? Can they live side by side?
- How does LiveData work with DataBinding?
- How should view state be handled and what goes into a Bundle versus a ViewModel?

To answer all of these questions and more we’ll do a deep dive in the internals of Lifecycle, LiveData and ViewModels.

**발표대상**

No other knowledge needed

---

### From Monolithic to Modularized codebase with Dagger

`50분` `일본어` `앱 아키텍처 디자인`

**발표자** `tsuyoyo`

このトークでは
- “monolithic”（= appのモジュールに大量なコードが入っている)
- dagger2で依存管理を行なっている
  という特徴を持つアプリから、1機能を別moduleに切り出す (実際に切り出した) お話をします。

instant appの登場 (2016 Google I/O) などでアプリのmodule分割（modularization）の重要性は以前から薄っすらと広まっていたものの、dynamic feature module (dynamic delivery) の登場によりその重要性は決定的となりました。

アーキテクチャについての議論が盛んだった昨年の流れに則り、DIライブラリを使って依存関係をきちんと管理しているプロジェクトも多くあるかと思いますが、いざそんなプロジェクトでmodularizeを行おうとすると一筋縄では上手くいきません。

このトークではメジャーなDIライブラリの1つであるdagger2を使った設計パターンで、よくあるケース(*1) を例に取ります。このパターンでappから1機能をmoduleとして切り出した際、大きく3つの困難 (*2) がありました。monolithicな状態からスタートして、どのようなstepでmodule切り出しを進めていくのが良いか、どのような困難に当たるのか、どういうアプローチで解決すれば良いのか、順々に紹介していきます。

これから同じ事をやっていこうとしている方達への前準備にもなれば良いなと思ってますし、さらにこのセッションを通してDagger (DIライブラリ) へのさらなる理解を手助けすることができれば最高です。

本トークは、参加頂く皆さんに「問題」と「アプローチ」の両方をきちんと理解して持って帰ってもらいたいと思っていますので、課題設定に15分ほど時間を使って進めていく予定です。本トークで取り上げる実例（課題）が一体どういうアプリなのか？何のためにdagger2を使っているのか？moduleとして切り出すものは何を実現する機能で、どういう実装をしていたのか？それらを踏まえた上で話を進めますので「Dependency Injectionとは何か？」「dynamic deliveryとは何か？」をそれぞれ薄く知っているくらいの前提知識で楽しんでいただけるようにしていきます。

(*1) 
App全体で共有したいデータやクラスを “AppComponent“ で管理し、各機能の依存はそのcomponentの “SubComponent” として管理するパターン。AppComponentに @Singleton スコープを与え、いくつかの @provider メソッドに @Singleton スコープを与えることで シングルトンで管理しているデータなどが存在している。

(*2) 
これらの話を深掘りしていく予定です
[1st step (appの外に新たなmoduleを作ろう)]
- どうやってmoduleをsetupすればよいか (AndroidManifest, build.gradle)
  [2nd step (buildを通そう)]
- buildが通らない理由
- moduleを作ったことによる依存グラフの変化を改修する
  [3rd step (Dagger2の依存グラフを再度チェックしよう)]
- 各moduleの中のdependency graphとインスタンスの生存期間をreviewする
- 切り出したmoduleを精査してclassへ internal 修飾子をつけていくことで、将来的に都合の悪い依存が生まれないようにしてしまおう

**발표대상**

- appを複数moduleに分割することを考えている方

- Dagger2を使ったアプリでmodularizationすることを考えている方
- dynamic feature deliveryの準備をそろそろ始めようと思っている方
- Dagger2をより理解して使えるようになりたい方 (普段Dagger2を “なんとなく” 使っている人)

---

### Spek2+MockK+JaCoCoでイケてるUnit Test環境を手に入れろ！

`30분` `일본어` `유지보수 & 테스팅`

**발표자** `Subroh Nishikori`

Android開発の現場にKotlinが急速に普及しつつある昨今、ユニットテストの領域にも様々なKotlin製ライブラリが登場しています。代表的なモノとして、RSpecライクなDSLでテストケースの記述が可能な「Spek2」、Kotlinの言語仕様に沿った自由度の高いモックライブラリ「MockK」などが挙げられます。

これらのライブラリは、これまでデファクトであったJava製ライブラリと異なり、Kotlinの言語仕様をフルに活かせる設計で作られており、導入することでKotlinを使ったAndroid開発の生産性を大きく向上させることができます。

しかし、「これらKotlin製テストライブラリを複合してAndroidのユニットテストに導入した事例」はあまり表に出ておらず、発表者である私自身も導入に多大な苦労を強いられました。

このセッションでは、発表者が業務でSpek2、MockK、JaCoCoを導入した経験を元に、各ライブラリの概要および簡単な利用方法、導入時にハマったポイント等の知見を共有します。最終的に、聴講者がSpek2、MockKの基本的な利用方法を知り、Kotlinフレンドリーなユニットテスト環境をライブラリの導入までできるようになることをセッションのゴールとします。

時間に余裕があれば、JaCoCoを使ったカバレッジ算出の手順も解説し、カバレッジレポートの出力まで含めたテスト環境の構築を一通りできるような発表とします。

**アジェンダ**

- Kotlin製テストライブラリの紹介
- ライブラリの基本的な利用方法
  - Spek2
  - MockK
- 導入
  - ハマりポイントの紹介(Gradleの記述、JUnit4との共存等)
- カバレッジレポートの出力 ※時間に余裕があれば
  - JaCoCoの導入
  - マルチモジュールでのカバレッジ算出 by JaCoCo

**발표대상**

- Kotlin製アプリにイマドキのユニットテストを導入したい方
- テストの生産性を上げたい方
- Java製テストライブラリに不満を持っている方

---

### All About Test of Flutter

`50분` `일본어` `크로스플랫폼 개발`

**발표자** `kikuchy`

Google i/O 2018でもFlutterブースが開設される、メルカリさんの技術カンファレンスの公式アプリでも使用されるなど、Androidエンジニアからも注目度の高いFlutter。
業務でも使用される例もちらほらと聞こえるようになり、普及してきた様子が伺えます。

しかし、テストは書かれているでしょうか？
また、Flutterアプリケーションに対するテストの知見は一般化されているでしょうか？

本セッションでは、Flutter記述言語であるDartの基本的なテストの記述方法から、
応用的なアサーション方法、Flutter特有のモジュールのテスト方法まで、幅広く解説します。

本セッションの内容だけで自動テストを書き始められるようになっていただくのが目標です。

以下、アジェンダです（予定）。

1. Flutterで使用できるテスト環境
2. テストのテンプレート
3. 基本のアサーション expect
4. matcherを使って複雑な条件を組み立てる
5. よく使う便利なライブラリとイディオム
6. 「テストできない！」がなくなる設計のアドバイス

**발표대상**

- Flutterアプリケーション開発をしたことがある方
- Flutterアプリケーションのテストを書きたい方

---

### アプリをさらに成長させるための技術戦略（振り返りとこれから）

`50분` `일본어` `개발 프로세스`

**발표자** `shaunkawano`

アプリ開発に携わるエンジニアは、多かれ少なかれ担当アプリの成長のために仕事をしています。エンジニアリングやその他の方法をもちいてアプリを成長させたり、その成長をより加速させることは、アプリ開発を担当するエンジニアの大切な仕事です。
本セッションのゴールは、受講対象者の方が、アプリを成長させるためにエンジニアができることを一つでも学ぶことができ、それをDroidKaigiが終わってから実務で真似しようと思えることです。
本セッションでは、「アプリの成長」の定義を下記2つとしています：
1. エンジニア目線でアプリケーションをスケールさせる、またはスケール可能な状態にすること
2. より多くのユーザーにアプリを利用してもらうこと
  ４−５人以上で開発するような大きいアプリケーション、かつ歴史が長く数年前からのコードも共存するようなアプリのメンテナンスにおいて、開発者の人数が増えた場合でも開発スピードを落とさず、さらにより多くのユーザーにアプリを利用してもらうための機能追加が容易にできるような内部構造にしておくことは、アプリを成長させるためにはもはや必要不可欠であるといえます。
  本セッション内では、アプリを成長させるために業務の中で行ったAndroid技術の選定やAndroidチーム内での取り組み（ペアプロ・モブプロ・お集まり会・もくもく木曜日）を含め、クオーターや半期目線で立てた技術戦略（テスタブル化・テストカバレッジ・Kotlin化率）について紹介し、どのようにアプリの成長や、開発スピードの向上につながったか（またはつながらなかったか）を成功事例・失敗事例を踏まえて振り返ります。振り返ったのち、今までやってきたことを踏まえ、今後アプリをさらに成長させるためにこれから行いたいことについても紹介します。

**발표대상**

- 「アプリをさらに成長させたい」と考えている方
- ある程度の規模、かつ歴史の長いようなアプリをこれからもっと良くしていきたい方
- チームビルディングやチーム開発について興味のある方
- 技術戦略について考えている方、興味のある方

---

### Not Just Rotation: Configuration Changes on Android

`30분` `영어` `안드로이드 플랫폼`

**발표자** `Nicole Borrelli`

"Screen rotation!" Rotate the screen and the Activity is recreated. It's a big reason to use ViewModels, but orientation changes aren't the only type of configuration change that happen on Android. And even when a configuration change happens, Android doesn’t need to destroy and recreate the Activity. In this talk we'll discuss the different types of configuration changes, what they mean, and why they happen. After the talk, you'll have a better understanding of the various types of configuration changes on Android and be able to make an informed choice for when—and when not—to handle them in your app.

**발표대상**

The talk is aimed for beginner to intermediate Android developers. Having a basic understanding of the Activity lifecycle is helpful. The goal is to help developers approach the challenges that really start to come up when porting apps to Android on Chrome, but the material is useful even just for phones.

---

### The good and bad of modern app architecture

`30분` `영어` `앱 아키텍처 디자인`

**발표자** `Johannes`

Building an app from scratch that is supposed to be maintained and extended for years to come and needs to replace an active application with millions of downloads in Japan alone is no easy task.
Still, that’s what we tried when completely rewriting the UNIQLO Android app this year.
This talk will go over our requirements and design choices, the things we think we did right and we think we did wrong.

Topics covered:

- There is no silver bullet.
- Clean architecture
- Architecture components
- RxJava 
- DI with Dagger 2
- Behavior driven testing
- Effective testing
- Clean vs velocity

**발표대상**

Developers and software architects interested in a discussion about architecture and best practices.

---

### 詳解定期購入

`50분` `일본어` `안드로이드 프레임워크 & JetPack`

**발표자** `Ryo Yamazaki`

アプリ内課金には、一回きりの購入と定期購入の2種類があります。ユーザーにとって普段見慣れたUIでワンタップで簡単に決済できるのは魅力的です。
アプリ内課金では公式のライブラリが提供されており、非常に簡単に導入することができます。以前はIn-app Billing Version 3 APIというライブラリを使う必要がありました。現在はよりシンプルなGoogle Play Billing Libraryがリリースされています。このライブラリには、使いやすいAPIが用意されており、AIDLを直接触らず、冗長な共通処理も書かなくて済みます。ライブラリ以外にも、Google Play ストアアプリやGoogle Play Consoleも継続的に機能やデザインが改善され、ますますアプリ内課金を導入しやすい状況になっていると言えます。

本セッションでは、定期購入をアプリに導入した経験をもとに実装方法や運用方法について説明します。まず、定期購入を導入した経緯や、どのような効果が得られたかについて紹介します。次に、Google Play Billing Libraryの各メソッドの使い方を、内部実装や実際の挙動を踏まえて詳細に説明します。そして、アプリに組み込む際の導線設計や具体的な実装方法を説明します。ここでは、ライブラリを使いやすくするためにRxJavaと組み合わせる方法についても解説します。最後に、課金時の動作確認の方法や、課金動向を分析する各種ダッシュボードの使い方など運用時に欠かせない事項も紹介します。
なお、このセッションでは定期購入の話を中心とし、一回きり購入にはあまり触れません。

定期購入は、運用して初めて分かることが多々あります。決済タイミングや無料試用期間、支払い猶予期間など、ドキュメントの説明と実際の動作をつきあわせることで更に理解が進みます。アプリ内課金はユーザーにとって非常にセンシティブで、販売者の利益にも直結する重要なシステムですので、定期購入対応で得られた知見、実装前に知りたかったノウハウを詳しく紹介できればと思います。

**발표대상**

- 定期購入について関心のある方
- 今既に定期購入を使われている方
- Play Billing Libraryの仕様や内部実装について知りたい方
- アプリ内課金で何ができるのか知りたい方

---

### Chrome + WebAuthn で実現できるパスワードレスなユーザー認証体験と開発者の課題

`30분` `일본어` `보안`

**발표자** `ritou`

最近、「FIDO 2.0」「Web Authentication(WebAuthn) API」「生体認証」といったキーワードを目にする機会が増え、いわゆる「パスワードレスなユーザー認証」がすぐそこまで来ています。
フィッシング攻撃、漏洩からの〜パスワードリスト攻撃、最大文字数や統一されない使用可能文字など、パスワード認証に関わる苦々しい記憶からついに抜け出すことができると注目されています。

Android と FIDO のこれまでの経緯としては、2017年12月に次のような発表がありました。

- FIDO UAF 1.1技術仕様を実装した初のFIDO(R) Certified（認定）製品が利用可能になった
- Android 8.0以降のデバイスへのFIDO認証導入が容易になった
  キャリアのアカウント設定で生体認証が利用できたり、生体認証に対応したアプリを用いてインターネットバンキングアプリにログインできる事例も出てきました。

また、Androidアプリに関わる開発者にとって生体認証に関わる機能自体は新しいものではないでしょう。

- 2015年 : Android 6.0 Marshmallow : FingerPrintManager
- 2018年6月 : Android P(Android 9 Pie) : BiometricPrompt 
  このように生体認証を取り巻く環境は確実に変化しているものの、
  まだまだ「アプリやサービスに生体認証 "のみ" でログイン」よりも「画面ロック解除」の用途としてのイメージが強いように感じます。

今回のセッションで扱う "WebAuthn" はWebアプリから生体認証やセキュリティキーを用いた認証を可能にする仕組みです。
Chrome の新しいバージョン(70)では "WebAutnn" で Android の指紋認証、 Mac の Touch ID をサポートしているため、Chrome + WebAutnn を組み合わせることでWebサービスに Android の指紋認証を用いてログインできるようになります。
パスワードレスなユーザー認証の普及の障壁だったWebサービスへの生体認証への導入が今後普及することにより、モバイルアプリにおける生体認証にも影響を与え、業界全体で安心安全なユーザー認証をできる世界に向かっていけると考えられます。

本セッションではその準備として、以下の内容を予定しています。

- WebAutnn 概要
- Chrome + WebAuthn でできること
- Webサービス開発者は何をする必要があるか
- 新規サービスで導入する際の注意点、パスワード認証からの移行方法など

**발표대상**

概要、できることはみんなに聞いてもらいたいところですが、

- 新しい技術に興味がある開発者
- 生体認証に興味はあるけど実装難しそうで手を出せない開発者 : "誤解" をときましょう
- モバイル/Web問わず、登録や認証を担当したことがある開発者 : パスワード認証との"違い"、パスワード認証からの移行方法を理解しましょう
- モバイル/Web問わず、登録や認証をこれから担当する開発者 : 新規サービスでパスワードレスな認証方式を導入する際のポイントを理解しましょう

と言った皆さんに楽しんでいただけると考えています。

---

### 外部デバイスと密に連携するAndroidアプリに最適なアーキテクチャとは？

`30분` `일본어` `앱 아키텍처 디자인`

**발표자** `tomoya0x00` `Yuri Hondo`

ユーザーが画面操作しなくても頻繁に外部からのイベントで画面遷移が発生するアプリ、
あなたならどのようなアーキテクチャを採用しますか？

弊社ではタクシー配車サービスを提供しています。
そのため、タクシーメーターと連携するアプリを開発し、各タクシーに設置しています。

このアプリは画面操作はもちろんタクシーメーターの操作、またプッシュ通知をトリガーに画面遷移する必要があります。

このように外部デバイスと密に連携し、様々なイベントを処理するアプリに最適なアーキテクチャとは何なのでしょうか。

アーキテクチャはそのアプリごとに最適なものが異なる、と考えています。
少々特殊な事例ですが、我々の試行錯誤の結果、またどのように改善を進めていこうと考えているか、をお話しできればと思います。

キーワード

- MVVM
- Redux
- Flux
- StateMachine
- multi module

발표대상**

- アーキテクチャの採用理由や事例を聞きたい
- デバイスと連携するアプリに興味がある

---

### Android アプリ開発における、デザイナーとエンジニアのワークフロー

`30분` `일본어` `UI & Design`

**발표자** `taquo`

ユーザー体験が高いAndroid アプリを開発する上で、デザイナーとエンジニアの効率的なワークフローは重要です。

特に Material Design を利用したアプリ開発の場合、Material Component を利用すれば、ある程度エンジニアだけでも見栄えするアプリが開発できてしまうので、どこまでをデザイナーが行い、どこからエンジニアが実装を行うのかという、デザイナーとエンジニアの作業の流れ(ワークフロー)が曖昧になってしまうという課題があります。

こういった課題を解決する上で、Google ではエンジニアとデザイナーが協業しやすいよう、Material Design を中心として、Gallery, Material Theme Plugin, Resizer, Google Fonts 等様々なツールを提供する事で、より良いアプリ開発のワークフローを提案しています。

本セッションでは、エンジニアとデザイナーが Material Design のアプリを作る上でどのようなワークフローでアプリをデザイン・開発していくかのが良いかを、Material Theming, Gallery などを利用したワークフローを通じて説明します。

**발표대상**

- デザイナーと協業しているエンジニアの方
- エンジニアと協業しているデザイナーの方
- Material Design をこれから使いたいと思っている方
- 既存のアプリに Material Componentを組み込みたいと思っている方

---

### クロスプラットフォーム開発3種の神器 React Native / TypeScript / GraphQL

`50분` `일본어` `크로스플랫폼 개발`

**발표자** `takuji31` `Ryo Kitamura`

はてなではこれまで、Webサービスと連携するスマートフォンアプリをいくつも開発・メンテナンスしてきました。このようなアプリは、サービスをグロースさせるために、Webアプリと歩調を合わせて開発していく必要があります。Android / iOSの二つのプラットフォームで展開するアプリを改善していくのは途方もないことです。

継続的にアプリを改善していくために、私たちは新たにReact Nativeの採用を決めました。開発言語には当然ながらTypeScriptを選び、また新規にGraphQL APIも開発しています。

React Nativeはただクロスプラットフォームのコードを書けるだけではなく、ReactというWeb業界で進化を遂げてきたライブラリの、先進的なパラダイムを利用できるところにも大きなメリットがあります。また型による恩恵を受けるためにTypeScriptを利用しています。

長い期間スマートフォンアプリを開発していると、REST likeなAPIが徐々に腐敗していくことにも課題感を感じていました。これを解決するためにGraphQLを採用することにしました。アプリを改善する過程で表示要素の増減がある場合でも、GraphQLであれば小さな変更で対応でき、メンテナンス性も維持できます。

React Native + TypeScript + GraphQLのシナジーは、アプリの開発に大きな変化をもたらしました。Apolloライブラリを利用することで、ReactからGraphQLを効果的に利用でき、またGraphQLのクエリからTypeScriptの型を生成することもできます。これらの効果によって、クライアントサイドで必要な情報をクエリに記述していちどに取得し、型で保護されたまま一気にUIへと流し込むことができました。

いいことづくめのようですが、苦労した部分もあります。パラダイムがすっかり変わってしまったため、設計もいちから考え直す必要に迫られました。またネイティブコードとReact Nativeのハイブリッドで開発するために、コードの棲み分けや連携に気を遣う必要がありました。さらにReactで高いパフォーマンスを発揮させるために必要だったこともあります。

ReactNative及びGraphQLの台頭によって、今、我々スマートフォンアプリエンジニアの開発が大きく変わろうとしているのかもしれません。本セッションでは、React Native + TypeScript + GraphQLを実際に既存のアプリに取り入れたことで知り得たアプリケーション構成方法について、皆さんにノウハウを共有したいと思います。

**발표대상**

- React Nativeを使ってAndroid/iOSアプリを素早く開発したい人
- React Nativeのプロダクション導入を検討している人
- GraphQLの導入に興味がある人

---

### マルチモジュールなプロジェクトでテストはどう変わる？

`30분` `일본어` `유지보수 & 테스팅`

**발표자** `Nozomi Takuma`

Android開発にモジュール化の波が来ています。モジュール化は我々の開発を変えていきますが、それにあわせてテストで気をつけなければいけないことは何でしょうか。本セッションではテストに焦点をあてて、マルチモジュールなプロジェクトにおけるテストとテストに関わるタスクがどう変わるのか？をお話したいと思います。
アジェンダは下記を予定しています。

- マルチモジュールプロジェクトでのテスト方針
- モジュール内のテスト
- モジュールをまたいだテスト
- テストメトリクスの集計

**발표대상**

- マルチモジュールなプロジェクトでテストがどうしたらよいか気になっている人
- マルチモジュールなプロジェクトでテストのメトリクスをとりたい人

---

### 巨大なアプリの開発を支えるフラグ管理術

`30분` `일본어` `개발 프로세스`

**발표자** `munetoshi`

LINEのクライアントチームでは、巨大なコードベースに対して沢山のエンジニアが同時に複数の機能を開発しています。
それら開発中の機能はリリースバージョンが一つ一つ異なっており、かつ、ある機能が別の機能に依存しているということも頻繁に起こっています。
そのような環境の中で、リリーススケジュールを管理したり、同時に横断的なリファクタリングを行うことは困難です。

この問題を解決するために、私達はフィーチャーブランチを使う代わりに、多くの場合次のような戦略をとっています。
まず、機能はたとえ開発中であっても、開発のメインブランチに入れてしまいます。
次に、その完成していない機能がリリースビルドに含まれないよう、フラグを使ってガードします。
このフラグは、プロパティファイルに記述しておくことで、BuildConfig クラスの boolean フィールドとして生成されます。

このフラグを使った機能の管理を行うことで、フィーチャーブランチによる管理と比べて、以下のような利点があります。

- 開発そのものとリリーススケジュールを分離できる
- リリース前に問題が発覚したときに、安全に機能を無効化できる
- 横断的なリファクタリングやライブラリAPIの更新を行っても、大きなコンフリクトが発生しにくい
- デバッグのためだけの機能の管理が楽になる
- 開発中の機能を他の開発者に見せることができる
- 企画者やデザイナーにデモを見せる際の機能切り替えが楽になる

このセッションでは、フラグの実装の詳細とその利点、さらに実装中に起きた問題とその対処法についてお話します。

**발표대상**

チームで開発を行っている方
git-flow で起きるコンフリクトに頭を悩ませている方
リリース予定より早くフィーチャーブランチをマージしてしまい、泣く泣くリバートをしたことある方
リリースブランチで機能に問題が見つかって、リバートしたかったけれど他のコミットのせいでうまく行かず、大変な思いをしたことがある方

---

### Code Review as a Collaborative Journey

`30분` `영어` `개발 프로세스`

**발표자** `hydrakecat` `punchdrunker`

Code review is not just an inspection but rather a journey of the reviewer and the reviewee working together to reach the goal - delivering a good product.

In this talk, we plan to speak about how a reviewer can make a collaborative code review, especially on Android app development. Android app development requires the reviewer to take into account various considerations; while there are some useful tips for the reviewer to find out potential bugs or improvements in the code.

First, we define what a good code review is and explain the typical steps of a good code review. We think a typical process of a good code review is as follows:

1. Understand the goal and the background of the change
2. Run the app and verify the behaviour
3. Read the code and the layout XML carefully
4. Add any comments you come up with in your mind
5. Take back and think if there might be a better way
6. Have a conversation with the reviewee

Then we will dive into each step and show some key tips for the review of Android development with an example from our real experience. For example, we believe running the app on a device is crucial to the review of the Android app code, so we will give an example and explain why it is important.

Instead of talking about important yet too general things around code review, such as wordings of the comments, whether or not pointing out a format, etc., we are rather focusing on the entire process and Android-specific topics.

**발표대상**

- A developer who wants to improve the quality of the code through code review
- Senior software engineers responsible for mentoring junior software engineers
- Those who are interested in how to make a collaborative code review

---

### Troubleshooting your designer's, and vector graphics

`30분` `영어` `UI & Design`

**발표자** `Mitchell Tilbrook`

Have you ever had you're a designer give you SVGs that just don't render correctly? UI performance decrease since moving to vector icons from PNG? There are lots of things that can cause lower performance when drawing android vector drawables. The cause of all of them is a lack of communication. Designers know how to create beautiful and marvelous icons. What they might not know how Android works with vectors, limitation of the format and performance characteristics.

In this talk, we will look at some of the common mistakes both developers and designer make when moving to vector drawables. How you can retroactively correct common problems when converting an SVG to vector XML, and how you can effectively communicate with your designer to reduce bouncing back and forth

**발표대상**

Some experience with using Vector drawables

---

### Gradle BOM importでライブラリバージョン管理

`30분` `일본어` `개발툴 & 생산성`

**발표자** `Kohei Yamamoto`

GradleはJavaやC++, Pythonなどいつくかの言語で使われているビルドシステムです。
Androidのビルドシステムとしても採用されており、プロジェクトの設定からアプリのビルド、ライブラリ・依存関係の管理、プラグインによる拡張など、Androidアプリ開発に便利な機能が揃っています。

Gradle5.0からBOM importのサポートが予定されており、Preview版としてGradle4.6から使用可能になりました。
BOMファイルには関連した複数のライブラリのバージョンをまとめて定義することができ、BOMファイルを参照することでプロジェクト内で各ライブラリのバージョンを個別に設定しなくてよくなります。
Androidアプリ開発ではあまり馴染みのないBOMについての説明と、マルチモジュールプロジェクトでの導入、他プロジェクト・チームに導入する際の展望についての話になります。

大規模なプロジェクトではいくつものライブラリを使うことになりますが、全ライブラリのバージョン情報をBOMファイルに定義することで、BOMファイルの更新のみで複数モジュール、プロジェクトのライブラリをまとめて更新することができます。

また関連ライブラリのバージョンをまとめて定義することで、誤ったバージョン指定によるライブラリ間のバージョン差異によるビルドエラーを防ぐことができます。
BOMファイル自体もバージョニング可能なため、BOMファイル内に定義しているライブラリ群のいずれかで新しいバージョンがリリースされたときは、BOMファイルを更新しBOMファイルを参照している他のモジュール・プロジェクト内でBOMファイルのバージョンを更新する、という流れになります。
BOMファイルを活用することで、複数のプロジェクトで最新のライブラリバージョンを使いやすくなるのではと考えています。

**アジェンダ**

- Graldeでのライブラリ管理についておさらい
- BOMファイルの起源と書き方
- １つのBOMファイルに書くライブラリ群の分け方
- 複数BOMファイルを参照する際に気をつける点
- 複数プロジェクト、チームにまたがったBOMファイル運用

**발표대상**

- いくつものライブラリの管理で疲労している方
- 常に新しいライブラリで開発をすすめていきたい方
- 複数案件のライブラリ管理をまとめてスッキリさせたい方

---

### BLEアプリ設計パターン

`30분` `일본어` `하드웨어`

**발표자** `8yabusa`

**概要**

弊社ではスマートロックを作っていて、スマートロックとの通信はBLEで行なっています。本セッションではスマートロックのアプリを作った経験を元に、BLEを使用したアプリの設計、ハマりどころについて話します。

**このセッション得られるもの**

- BLEアプリ開発のハマりどころ
- 通信先が複数あるアプリ設計の参考

**発表内容(予定)**

- BLEについての簡単な説明
- AndroidのBLEのAPIをそのまま触るのは辛いので、RxAndroidBLEの導入をおすすめ
- BLE通信設計のパターン
  - どのようにService, Characteristicを配分するか
  - MTU(1パケットに詰められるデータ量)を超えるデータを転送するときに起きる問題と対処法
- BLE通信デバイスとWebサーバーの両方にデータがあり、それらをアプリが中継する場合のアプリ設計パターン
  - どうモデリングするか
  - モデルの取得先がデバイスとサーバー両方にあるけど、Repositoryはどう作る？
  - デバイスとサーバーの情報をアプリでいかに同期するか

**발표대상**

- BLEもしくはIoTに興味がある人、ハマりたくない人
- BLEを使用するアプリの設計に興味がある人

---

### カスタムブラウザの作り方 ー 実例から学ぶ Chrome と Firefox のカスタムビルド開発 ー

`50분` `일본어` `기타`

**발표자** `dynamis`

デスクトップもモバイルも最大のシェアを持つ業界標準 Web ブラウザは Chrome ですが、Android であっても通常の Chrome ブラウザでは要件を満たせないケースは意外と多くあります。

そもそも Chrome を始めとした Google 謹製アプリが提供されない AOSP 端末の開発、非標準的な UI/UX 端末開発時に専用のブラウザが必要とされる場合、セキュリティ問題などのために標準ブラウザを採用できないケース、マルチプラットフォーム対応に Web を利用したいがブラウザの制約によってやりたいことが出来ない場合、などなど ...

Mozilla が世界中のキャリアやメーカーに向けてカスタマイズした Firefox の提供をしている取り組み、独自のブラウザを必要とする国内企業へのカスタム Chromium ブラウザ提供、Web 標準 API だけでは実現できない場合にカスタムブラウザを作って実現するアプリ開発、さまざまな目的と実装のカスタムブラウザ案件を見てきた経験から、ドキュメント通りのブラウザのビルドだけではないカスタムブラウザ開発をご紹介します。

具体的な発表内容は時間・要望あるいはカスタムブラウザ採用企業の意向によって調整しますが、Chromium/Firefox をベースにカスタムブラウザ開発を行った案件から学んだ知見やノウハウ、ブラウザベンダーが標準で提供しているブラウザカスタマイズのための仕組み、WebView ベースでブラウザアプリ開発を行う際に役立つフレームワークの紹介などを行う予定です。

Firefox 1.0 日本語リリース担当から始まり Mozilla Japan (現 WebDINO Japan) にて国内での Firefox OS 端末展開や世界中の Firefox カスタマイズ事例を見てきて、現在 CTO として Web とブラウザの領域拡大に取り組む立場ならではの視点でお話しします。

**발표대상**

ブラウザ・ウェブ・オープンソースなどが好きな方。

オープンソースという言葉とトレンドを生んだ Netscape のソースコード公開から 20 年、一度自分でカスタムブラウザを開発してみたかった人、ブラウザをビルドしてみたが何故か標準ブラウザと機能やパフォーマンスの違いがあり困った人、カスタムブラウザではどんなことが出来るのか興味のある方、自社の製品開発でカスタムブラウザを必要として困っている人、Web エンジニアだが Web プラットフォームの限界から抜け出す仕事がしたい人、などおのお越しをお待ちしております。

勿論、現ブラウザベンダーのエンジニアもウェルカム！

---

### FridaによるAndroidアプリの動的解析とフッキングの基礎

`30분` `일본어` `보안`

**발표자** `Ken Kitahara`

Fridaは主にモバイルアプリケーションをデバッグするための開発者向けツールであり、アプリケーションに実装されている関数呼び出しを追跡やフッキング（メモリ上で関数などの処理を改ざんする手法を指します）による関数の改ざんを可能とします。近年はモバイルアプリケーションに限らず、情報セキュリティ技術者の間では様々なソフトウェアをリバースエンジニアリングする目的で活用されています。サイバーセキュリティの観点では、悪意のあるソフトウェアの動的解析のような防御視点の使い方だけでなく、フッキングによりゲームのチート行為のような攻撃者視点の用途で使われてしまうことがあります。
本講演では、サイバー攻撃の技術を専門とする情報セキュリティ技術者として、Fridaを用いたアプリケーションの解析手法や、フッキングによりアプリケーションを改ざんする手法を初心者向けに解説することで、アプリケーション開発者のセキュリティ対策に貢献することを目標とします。講演ではFridaというツールやフッキングという手法の解説に加えて、Fridaを用いたフッキングによる簡単なアプリケーションの改ざん手法の実演を交えることで、聴講者の理解を深められるように努めます。

**발표대상**

情報セキュリティ技術に興味がある人

---

### EspressoのテストをAndroidの最新トレンドに対応させよう

`50분` `일본어` `유지보수 & 테스팅`

**발표자** `外山純生 (sumio_tym)`

Androidを取り巻く状況はこの2年間で大きく変化しています。例えば次のような変化がありました。

- Android関連パッケージのAndroidX (Jetpack)への再編
- 記述言語のKotlinへのシフト
- Android Architecture Components(AAC)の浸透

このめまぐるしい変化にEspressoのテストコードも対応していかなければなりません。
本セッションでは、最新トレンドに対応したEspressoのテストが書けるようになることを目標に、次のトピックを紹介します。

- EspressoをAndroidX対応にする
- EspressoをKotlin対応にする
- Espresso Test Recorderを使ってKotlinで記録する
- 変更に強くするためにKotlinでPage Objectデザインパターンを適用する
- AACを採用したアプリに対するEspressoテストの注意点

また、2018年後半に公開が予定されているProject Nitrogen導入に伴う変化についても(具体的な公開時期や発表時間の制約によりますが)可能であれば紹介したいと考えています。
本セッションの内容を学んで、UIテストコードもAndroidの最新潮流に乗り遅れないようにしましょう！

**발표대상**

- EspressoのテストをKotlinで書きたいと考えている方
- 既存のEspressoテストを最新トレンドに移行したいと考えている方
- AACを採用したAndroidアプリのUIテストをEspressoで書きたいと考えている方

※ Espresso初心者の方も付いていけるように配慮しますが、時間の制約から、詳しいAPIの説明などは割愛すると思います。

---

### R8、Proguard徹底比較

`30분` `일본어` `개발툴 & 생산성`

**발표자** `Sato Shun`

R8はJavaコードを最適化されたdexコードに変換するためのシュリンカーです。Proguardを置き換える目的で作成されました。R8ではコンパイルタイムの軽減、dexコードのさらなる最適化を目指しています。
dexコードのさらなる最適化とは具体的にどのようなものでしょうか？
本セッションでは、R8でどのような最適化が行われているかをバイトコードレベルから説明します。また、Kotlinに関する最適化など、R8の特徴について説明し、Proguardと比べどこが進化したのかを紹介します。
具体的に以下のことを学ぶことが出来ます。

- R8の内部実装
- R8とProguardの違い
- R8ではどのような最適化が行われているか？

**발표대상**

- dexファイルの最適化に興味ある人
- R8でどのような最適化が行われているかを理解したい人

---

### Deep Dive to fido.fido2 Packages

`50분` `영어` `보안`

**발표자** `ken5scal`

**English Description (Japanese below)**

We are exhausted with passwords. Users are exhausted with passwords because of too many web-services. Operators are exhausted with passwords because of defense against password-related attacks like Phishing. We, as developers, are also exhausted because of poor UX in passwords.

In last DroidKaigi, I have presented “AuthN and AuthZ with Android”(認証と認可と君と) for the purpose of introducing FIDO UAF 1.1, the password-less authentication framework. Since the presentation, a lot of innovation has been made. For example, major browsers adopted, implemented, and released WebAuthN which will play important role in FIDO 2.0, which will be the new version of UAF 1.1. 

Android hasn’t been left behind by the advancement in Authentication. In March 2018, FIDO2.0 package was released in Android API, and that is exactly what I am going to talk about. At the end of this session, the audience will understand what `com.google.android.gms.fido.fido2*` will do, how to use it with `BiometricPromptAPI`, and how it is related to WebAuthN.

**Outline**

1. Reviewing FIDO UAF 1.1
2. Safetynet Attestation vs Key Attestation
3. com.google.android.gms.fido.fido2
4. fido2 with BiometricPrompt
5. fido2 with WebAuthN

**日本語Description**

去年のDroidKaigi2018「認証と認可と君と」ではそういった苦労から我々を開放するパスワードレス認証「FIDO UAF 1.1」とAndroid上での実装方法についてお話しました。それから早1年、次バージョンにあたるFIDO 2.0の一翼を担うWebAuthNが主ブラウザに実装され、更にChromeの最新Ver70ではAndroidの指紋認証との連携ができるようになりました。勿論、Android自体にも大きな動きがあり、2018年にはAndroidのAPIに新しくFIDO2.0用パッケージが登場しました。本セッションでは、com.google.android.gms.fido.fido2* についてBiometricPromptAPIなどのAndroid内のFIDO2関連のAPIと絡めつつ、実装方法をお話します。

**Outline**

1. Reviewing FIDO UAF 1.1
2. Safetynet Attestation vs Key Attestation
3. com.google.android.gms.fido.fido2
4. fido2 with BiometricPrompt
5. fido2 with WebAuthN

**발표대상**

- anyone interested in Authentication
- anyone interested in FIDO
- whoever wants to understand difference between FIDO in Android and WebAuthN

---

### Redux for Android

`50분` `일본어` `앱 아키텍처 디자인`

**발표자** `yuyakaido`

**概要**
クライアントアプリの要件は年々高度化・複雑化してきており、それに伴ってクライアントアプリが扱わなければいけない状態もどんどん増えていきます。扱う状態が増えていくにつれてバグや開発コストが増加することが多く、クライアントアプリにおける状態管理は重要なウェイトを占める題材です。

状態管理にまつわる問題をスマートに解決するための手段として、WebフロントエンドではReduxが採用されることが増えており、同じフロントエンドとしてReduxから得られるメリットの多くはAndroidにも当てはまります。本セッションでは、Androidにおける状態管理の難しさを具体例を交えて紹介し、それを解決する手段の1つとしてのReduxをコードレベルで解説します。

**目次**

- Androidにおける状態管理の難しさ
 - ライフサイクルとの付き合い方
 - 画面を跨いだ情報のリアルタイム同期
 - 複数のデータソースを扱う必要性
- Reduxの概要
 - Reduxが登場した背景
 - Reduxが解決する課題・解決しない課題
 - Action/Reducer/Storeの概要
- Reduxの実装
 - Action/Reducer/Storeの実装
 - Middlewareの実装
 - RxJavaの活用
- Reduxのテスト
- Android Architecture Componentsとの関係性
- 他のアーキテクチャ（MVP/MVVM/Layered Architecture）との関係性

**발표대상**

- アプリの状態管理に苦労している方

- 画面を跨いだ情報同期に苦労している方
- Reduxのメリット・デメリットや実装方法を知りたい方
- 他のアーキテクチャとの比較結果を知りたい方

---

### Understanding Kotlin Coroutines: コルーチンで進化するアプリケーション開発

`50분` `일본어` `앱 아키텍처 디자인`

**발표자** `mhidaka`

Kotlin Coroutinesは非同期処理をシンプルに記述できるKotlinの言語機能です。実験的な機能としてこれまでも提供されてきましたがKotlin 1.3で正式にリリース予定です。

Androidの誕生から10年たちアプリの利用シーンが増えた結果、アプリ開発の複雑さも増してきています。開発者はアプリの性質に合わせてMVVMをはじめとしたアーキテクチャとArchitecture Components（AAC）など複雑性を解消するライブラリを組み合わせ、実装上の課題を解決してきました。

本セッションでは新登場のCoroutinesを既存のアプリケーションへ適用する方法と導入するメリットを中心に解説します。

Coroutinesの本質を理解することはアーキテクチャをよりシンプルに保ちます。そして言語機能の追加がアプリ開発現場に与える影響を考察していきます。

設計・開発の効率化といえば、これまで多くの場合、ライブラリの導入がメインでした。しかしアプリの複雑性が増加するにつれて多数のライブラリを導入しつづけることは開発者に多くの知識を要求し、イニシャルコストの増加に繋がります。言語そのものの力を理解することでコストを下げ、より素早い開発を実現できます。

本セッションはアプリ開発で実践できるよう、なじみのあるアーキテクチャを通じてCoroutinesを学んでいきます。
聞き終わったときには、AACなどモダンなライブラリのなかで効率的な非同期処理に対応する方法を習得できます。

セッションの構成（変更する可能性があります）

- はじめに：Coroutines登場の背景
- 現代のアプリケーション開発の課題
- 期待されるCoroutinesの役割
- アプリケーションへの適用
- MVVMアーキテクチャで実践するCoroutines
- Coroutinesの便利な使い方
- 他アーキテクチャにおける利用指標
- まとめ：AndroidアプリにおけるCoroutinesの役割

**발표대상**

手を動かして実践してひとへのヒントとなります

- Coroutinesを使いたいと感じているひと
- よりモダンで効率的なAndroidアプリ開発に興味があるひと
- 新しいパラダイムをいち早く知りたいひと
- アプリ開発が複雑だと感じるひと
- アプリ開発経験を前提としてあったほうが楽しめます

---

### UIテスト(Espresso)の高速化をさらにすすめる

`30분` `일본어` `유지보수 & 테스팅`

**발표자** `tarappo`

しかし、UIテストで避けては通れない課題として実行時間が長くなるという問題があります。

なにも対策を行わなければ、UIテストの実行時間は右肩上がりになってしまいます。
UIテストの実行時間を短くするにはどうしたらいいのでしょうか。

本セッションでは、UIテストを高速化するためにどのようなことをやると良いのかについて紹介していきます。

主に紹介することは以下のようにいろいろな方面からの話を予定しています。
・テストコードでおこなうべきtips
・テストを実行する環境に対するtips
・効果的なワークフローにするためのtips

そして、なにもおこなっていないときと上記のようなことをしたときの実行時間を比べ、どの程度効果があるかもふくめ紹介します。
これによりUIテストをより効果的に利用できるようになればと思います。

**발표대상**

- UIテストをさらに広く利用したい方
- UIテストの実行時間で悩んでいる方
- UIテストについてより知りたい方

---

### Android Enterpriseで実現できる端末管理の世界

`30분` `일본어` `안드로이드 플랫폼`

**발표자** `Daisuke`

Android端末管理の高度化・標準化を実現するために企業でのAndroid端末の利用をサポートするためのプログラム「Android Enterprise」

Android Enterpriseでは管理者がGoogle Playを管理し、承認したアプリのみを配信する事が可能となります。

会社から支給するデバイス向けに、利用デバイスを企業の監視下において管理できる「DeviceOwner」と端末内のデータを個人領域と仕事領域に分け、仕事領域のみ企業の監視下で管理できるBYOD向けの「ProfileOwner」等があり、端末のセキュリティをより強固にする事が可能です。

このセッションではAndroid Enterpriseについての詳細や機能を、デモを交えて紹介し、端末管理の仕組みにおける今後の方向性などのお話ができればと思います。

- 使い慣れたこれまでの機能と企業向けに設計された管理機能を組み合わせた「管理されたGoogle Play」
- 会社所有端末の管理
   - Device Ownerで完全な端末の管理を行う
   - Device OwnerとProfileOwnerの併用で多様なニーズに応えた端末の管理を行うCOMPモード
   - Device Adminはレガシー機能
- 従業員が所有している端末の管理
   - 仕事領域を作成し、ProfileOwnerで仕事用プロファイルを適用
- 会社所有の端末を専用端末として管理
- デバイスプロビジョニング方式
  - QR code device provisioning
  - NFC device provisioning
  - DPC identifier install
  - Google Accounts Method
  - Zero-Touch Enrollment
- ここまで出来る！DevicePolicyManagerで制御可能な機能について
- 端末管理の今後
  - Device Admin Deprecation

**발표대상**

- 端末管理機能（DevicePolicyManager）に興味があり、活用したい方
- ニッチな機能に興味がある方
- MDM導入を検討されている方

---

### 2019年の技術であのARアプリを再現する

`30분` `일본어` `xR`

**발표자** `KENICHI TAKAHASHI`

ARCore, Sceneform, Firebase等, 2019年の技術を駆使してスマートフォン黎明期のARアプリであるセカイカメラを再現したらどのような構成になるのか試してみました（発表者は当時の開発メンバーの1人）。その過程を通じてScneformを使ってJavaで実装する方法、Cloud AnchorsとFirebaseを組み合わせてAR空間を共有するための実装をする方法等、AndroidでのARアプリの開発方法についてお話したいと思います。

**발표대상**

Androidアプリを開発したことがあり、ARCoreを使ったARアプリ開発に興味を持っている方

---

### From TensorFlow to ML Kit: power your Android application with machine learning

`30분` `영어` `기타`

**발표자** `Qian`

As a mobile app developer, you probably have noticed Google's active efforts on bringing their machine learning expertise to mobile development. From TensorFlow's earliest mobile app demo to TensorFlow Lite and Android Neural Networks API, we are witnessing how latest research (e.g. MobileNet) drastically reduced machine learning model size and CPU / memory consumption on mobile devices. This year, with the beta release of ML Kit, we now have another powerful toolbox to leverage machine learning in the mobile application development.

This talk features a side project Magritte, an educational application that helps people learn foreign languages. It's sort of like Duolingo but with eyes, the application recognizes daily objects using custom machine learning models embedded on device and speaks the vocabulary out loud with the chosen language. By presenting the Magritte app, the talk will reveal how the models for TensorFlow mobile were initially trained and optimized, how the performance was improved with TensorFlow Lite and MobileNet models, and eventually the migration to ML Kit.

**발표대상**

Android developers who are interested in getting to know how to leverage machine learning power in their applications by running the inference with model on-device.

---

### UI profiling in examples. Where is my bottleneck?

`50분` `영어` `유지보수 & 테스팅`

**발표자** `Artur Badretdinov`

You developed a feature, tested it yourself - everything works well. You send it to the internal testing, your managers... And they say it is slow!

We ran into the exact same situation and dug into the tools that may be used to make your Android app work on 60 frames per second.

This presentation is intended for the people who haven't dived into the UI performance yet. You will see some examples of easy and fast ways to check if your app works well and if it is not, how to find the potential problem.

In the presentation, I will tell you about:

How android renders views and why does it matter to you (DisplayLists, Choreographer, VSync, Render Thread - things that will be covered)
How to understand that you have a problem (GPU profiling, SysTrace)
How to get metrics about the current rendering speed (fps) of your app ( dumpsys gfxinfo, Systrace, HierarchyViewer)
Some of our mistakes we made, how we found them and how we fixed them (overlaying Controllers (analog of Fragments), incorrect usage of RecyclerView with NestedScrollView
How to easily find GPU overdraw and fix it (using GPU overdraw in dev settings and export view layers in HierarchyViewer or Scalpel to show you the ways to improve)
How to be sure that the problem doesn’t regress (Android Vitals,  dumpsys gfxinfo)

**발표대상**

People who have only a basic knowledge about UI profiling or doesn't have it at all. Developers who ran into the low-fps app problem who does not know how to start and what to measure.

---

### つらいと評判のAndroid BLEを頑張って使い続けた話

`30분` `일본어` `하드웨어`

**발표자** `Kenta Harada`

**概要**
IoTデバイスとスマホとの接続方式として採用されることが多いBluetooth Low Energy(BLE)。
Android 4.3(kitkat)でBLEのサポートが開始されて早くも5年が経過しました。
iOSのBLEに比べて何かと辛いところが多いAndroid BLEですが、BLEを使ったアプリやサービスは順調に増えており、今後もいろいろなIoTサービスの中で活用されていくことが予想されます。

この発表ではAndroidのBLEアプリ開発で遭遇するはまりどころ、解析方法、つながりやすくするために
試してみたいことなどを紹介したいと思います。

**対象者**

- BLEを使ったAndroidアプリを開発中またはこれから開発したみたい方。
- BLEを使ったIoTハードウェアのFWを開発している方でAndroid側の実装に興味がある方。

**話す内容**

- AndroidのBLEはどうして繋がりにくいのか？
- つながらないときの解析方法
- つながらないときに試してみたいこと
- おすすめBLEライブラリ紹介

**발표대상**

- BLEを使ったアプリの開発しているかた、興味がある方
- BLEを使ったIoTハードウェアのFWを開発している方でAndroid側の実装に興味がある方

---

### Androidにおけるパフォーマンスチューニング実践

`50분` `일본어` `안드로이드 프레임워크 & JetPack`

**발표자** `neonankiti`

Androidアプリを開発していると、以下のような経験をしたことはないでしょうか？
「アプリの動作重くない？速くしてほしいんだよね。」
「データ消費量やばくない？減らしてほしんだよね。」
「アプリの消費電力多すぎない？減らしてくれない？」

Google Play Storeに公開しているアプリであれば、ユーザーレビューでアプリパフォーマンスの指摘を受けることもあると思います。
私が開発しているヘルスケアのプラットフォームアプリは上記の問題が発生していました。

もちろん、パフォーマンスを改善するための方法論に関しては、Android公式ドキュメントやAndroid Perfomance Patternという公式動画でも丁寧に説明されています。

しかし、紹介されているツールの使い方が難しかったり、定量的かつ継続的な改善のノウハウには言及していません。
実践的なパフォーマンス改善に関しての日本語ブログは少なく、日本語ネイティブのAndroid Developerにとってラーニングコストも高い状況です。

更に、パフォーマンス悪化の原因は、複合的であり、何から始めればよいのかわからないことも多々あります。

今回のセッションでは、複合的な原因を分解し、アプリパフォーマンスの定量化と改善のための実践的な方法論を紹介します。
ついつい起こしがちなアンチパターンに関しても具体例を交えて説明していきます。
このセッションでは、小難しい話はなしにして、初心者でも実際にアプリに適用できる状態を目指します。

1. アプリパフォーマンスへの考え方
  - アプリマルチスレッドの全体像(thread, handler, looper, service)

2. アプリのパフォーマンス測定の基礎(CPU, Memory, Network)
  - ツールを使いこなす(Android Profiler, Command Line Tool)

3. 定量化と継続的改善のための実装と数値の追跡方法
  - データ通信量
 - ANR対応
 - 消費電力

具体的内容
1. Androidアプリケーションにおける、パフォーマンスに影響を与える要素について全体像を話します。
2. アプリのパフォーマンス測定のために必要なツールの紹介と使い方について説明します。
3. パフォーマンス改善のための具体的な項目について考え、踏みやすいアンチパターンの実装例とベストプラクティスについて説明します。また、アドホックな定点観測ではなく、継続的に観測していく方法に関しても言及します。

**발표대상**

- アプリパフォーマンスを向上させたいが何から始めればよいのかわからない人
- アプリパフォーマンスでの継続的な結果測定と改善方法が知りたい人
- パフォーマンスを悪化させるアンチパターンに関して具体的実装が知りたい人

---

### build.gradle.ktsに移行しよう

`30분` `일본어` `개발툴 & 생산성`

**발표자** `tnj`

build.gradleのカスタマイズ、あまり補完が効かなかったり、エラー箇所が分かりづらかったりして、毎回苦労されていませんか？それ、Kotlinで解決しましょう。

2016年5月の発表から開発が続けられてきたKotlin Gradle DSLが、Gradle 5.0において1.0のリリースを迎えてプロダクションレディになりました。このセッションでは実際のAndroidアプリのbuild.gradleをKotlin化する手順を通じて、Kotlin移行するべきなのか、どの位手間が掛かるのか、移行するメリットは、といったトピックについてお話しします。

- Kotlin Gradle DSLの位置づけ
- Kotlin化で嬉しいこと
- 既存プロジェクトを移行してみる
- よくある問題と対策

**발표대상**

普段build.gradleに手を焼いている方、Gradleプラグインを書いている方

---

### LiveData と Coroutines で実装する DDD の戦術的設計

`50분` `일본어` `기타`

**발표자** `Yuki Anzai`

DroidKaigi 2017 と 2018 でドメイン駆動設計（Domain Driven Design : DDD）に関する講演を行いました。本セッションはその続きです。
2017ではドメイン駆動設計とは何か、何をするのか、を解説し、戦略的設計について話しました。2018では gradle の module としてドメインの置き場を分けることでドメインを隔離できること、IDや数値や種類を値オブジェクトとして見つけ、Kotlin の data class や enum class として実装することを話しました。

今回は残りの戦術的設計（Entity や Service、Application Serviceなど）について解説し、実装の一例として Android Architecture Components と Kotlin の Coroutines を使った方法を紹介します。

ドメイン駆動設計の実装方法はドメインによって異なるため、既存のアプリ（Google I/Oアプリなど）を元にするか、ドメインを明示したサンプルアプリをあらかじめ用意することを予定しています。

これまで同様ドメイン駆動設計の内容については「エリック・エヴァンスのドメイン駆動設計」及び「実践ドメイン駆動設計」に準拠します。

本セッションはドメイン駆動設計の前提知識がない方にもわかるようお話ししますが、2017の講演内容をまとめたブログ http://y-anz-m.blogspot.jp/2017/03/droidkaigi-2017_9.html および2018の講演内容をまとめたブログ http://y-anz-m.blogspot.com/2018/02/android.html を読んでいただくことをおすすめします。

**발표대상**

Android アプリにドメイン駆動設計を取り入れたいと思っている方

---

### デザイナーとエンジニアの距離をより近づける Lottie 利用術

`30분` `일본어` `UI & Design`

**발표자** `bandwagondagon`

デザイナーとエンジニアの距離を近づける Lottie 利用術

Lottie の登場により、エンジニアによる実装コストを抑えながらも
デザイナーが意図したアニメーションをよりダイレクトに
Android を始めとした各種プラットフォームで表現できるようになりました。

しかし、各種プラットフォーム上で Lottie ライブラリが実装されているとはいえ、
プラットフォームごとに Adobe After Effects のプロパティの対応状況は異なり
望んだアニメーションをマルチプラットフォームで統一的に表現できない場合があるなど、まだまだ課題は残されています。

また、アニメーションの制作をデザイナー側で完結しやすくなった反面、アニメーションの表現を修正していくたびに

- AE でアニメーションを修正して Bodymovin ファイルを書き出し
- Bodymovin ファイルをデザイナーからエンジニアへ受け渡し
- エンジニアが新しい Bodymovin ファイルをアプリへ反映させる

などの作業が必要となる場合があり、デザイナー・エンジニア間のデータのやりとりの回数が多くなってしまう問題が起こりえます。

そこで本セッションでは、
デザイナーやエンジニアの両方が、プラットフォーム間の特性を踏まえながらも
より Lotiie の性質や仕組みより深く理解して利用できるようになるために
そもそもどのように Adobe After Effects (AE) で表現されるアニメーションが
Bodymovin ファイルに変換され、lottie-andoird を通してアニメーションを実現しているのか
を解説します。

さらに、 Hyperion-Android と Lottie Dynamic Properties を用いて
アニメーション個別にコードを書くことなくアプリ上の Lottie アニメーションの挙動を変化させていくことで
AE 上での編集回数を減らしながら、より効率的にデザイナーとエンジニアがアニメーションのブラッシュアップを実現できるような方法を紹介します。

**발표대상**

- デザイナーとして Bodymovin, Lottie を利用している、もしくは導入を検討している方
- エンジニアとして lottie-android を利用している、もしくは導入を検討している方

---

### いかにしてビットコインを扱うか

`30분` `일본어` `기타`

**발표자** `ゆいき`

昨今、ビットコインをはじめとする暗号通貨をアプリで用いる案件は増えてきており、ブロックチェーンやDApps(分散型アプリケーション)市場の成長により今後も更に増えていくと思われます。
Android端末上でトラストレスにビットコインの送付や着金などを行う方法としてSPV(Simplified Payment Verification)がありますが、これは実際にビットコインネットワークに参加する方法であるため、モバイル端末の過酷なネットワーク状況下で常時複数のピアとソケット通信をしければなりません。また、それに伴い通信量も通常のアプリと比べ大きくなってしまいます。
更には、ユーザのビットコインの秘密鍵をAndroid端末上でどのようにして安全に保持するのかという問題もあります。
本セッションでは、上記のようなビットコインなどの暗号通貨をAndroidで扱う際に発生する問題に対して、如何にして対処すべきかをbitcoinjと呼ばれるAndroidアプリでよく使われるビットコインライブラリの内部コードの解説を交えながら、実際のビットコインのウォレットアプリを作っている経験を元にお話します。

**발표대상**

- Android x ビットコインに興味がある方
- 暗号通貨に関連するプロジェクトに携わっている/携わる予定の方
- アプリ内でビットコインを使ってみたいと思っている方
- Android上で動くDAppsを作ってみたいと思っている方
- アプリでどのようにしてビットコインを扱っているのか気になる方

---

### Slice Your App: Inside Slices and How to build it

`30분` `일본어` `안드로이드 프레임워크 & JetPack`

**발표자** `Hiroyuki Mori`

**概要**

Google I/OでアナウンスされたSlicesは、Google検索やGoogle Assistantを利用してユーザーエンゲージメントを向上することができる、強力な機能です。
Slicesはまだ日本語に対応していませんが、そのため準備をしておくためのチャンスでもあります。
Slicesがいかにしてその機能を実現しているのか、その内部実装を概観したうえで、ダイナミックでインタラクティブなSlicesの作成を学び、Slicesの日本での公開に向けた準備を開始しましょう。

**話すこと**

- Slicesの内部実装
- Slicesとパーミッション
- Slicesの作成方法
- Slicesの更新とユーザーインタラクション
- SlicesとGoogle Assistant

**발표대상**

- ユーザーエンゲージメントを増やしたい人
- Slicesに興味のある人
- Jetpackの内部実装に興味のある人

---

### Wi-Fi RTTによる屋内測位アプリを作ろう

`30분` `일본어` `기타`

**발표자** `napplecomputer`

Android 9からWi-Fi RTT（Round-Trip-Time）に対応しました。
Wi-Fi RTTを使えばGPSの届かない屋内などの場所でも、Wi−Fiアクセスポイントとの距離から位置情報を取得することができます。

Wi-Fi RTTを使った屋内測位にはAndroidアプリだけでなくアクセスポイントなど様々な要素が登場します。
本セッションではWi-Fi RTTを使った屋内測位を行うには何を行えばいいか解説します。

**발표대상**

- 屋内測位に興味のある方
- Androidアプリ作成の基本的な知識を持っている方
- カンファレンスアプリを作っている方

---

### FlutterでのWidgetツリーへの状態伝播とアクセス制限の基本戦略

`30분` `일본어` `크로스플랫폼 개발`

**발표자** `robo`

Flutterは、アプリケーションもUIもWidgetであり、アプリから各画面のUIまでが「１つのWidgetツリー」に集約されます。
このセッションでは、Flutterの基本クラスやメソッドを応用して、アプリ全体や画面単位で共有する(伝播させる)状態のツリーへの提供方法と、提供する状態を誰もが利用可能なグローバル公開にならないよう、不要なアクセスを制限する戦略の基本を説明します。

画面レイアウトの Widgetツリー内で、複数の 子Widget から参照が必要な状態があったと思ってください。

手軽さを優先して、状態を直接伝播するために Lexical scope を使った場合は、スコープが絶たれないよう１つのクラス内で、画面レイアウト Widgetツリーの構築定義をすることになります。
「Flutterのツリー定義コードは、ネストが深い」「状態がツリー内のどの Widgetからも変更可能」「ツリー内にビジネスロジックまで書いてしまう」という問題は、このようにして発生します。

Google I/O 2018 セッション「Build reactive mobile apps with Flutter」では、Widgetツリーへの状態伝播の手段として、InheritedWidgetクラスや scoped_modelパッケージが、bloc(Business Logic Component)導入のための基礎知識として紹介されています。
リアクティブなアプリを作るためにも、Widgetツリーへの状態伝播とアクセス制限の基本戦略は必要でしょう。

併せて動作確認に使用する、機能限定ですが横断的関心事を扱ってくれる(手軽に動作確認ログ出力機能などを自動追加する)、内製AOP(Aspect Oriented Programming)も、開発の一助となるよう提供したいと思います。

**발표대상**

- Flutter初学者の方
- Widgetツリー構築コードのネストが深くなってしまうことや、
- ツリーからビジネスロジックを分離する基本を学びたい方。
- InheritedWidgetクラスを使ってみたいが、
- どのようなことに注意して、実装や応用したら良いのかを学びたい方。

---

### クロスプラットフォームモバイルアプリ開発ツール総ざらい2019 〜Titanium MobileからKotlin/Nativeまで〜

`30분` `일본어` `크로스플랫폼 개발`

**발표자** `amay077(あめい)`

**概要**
D.R.Y(Don't Repeat Yourself)を信条とするプログラマの夢であるクロスプラットフォームアプリ開発。
Android/iOS 向けの "ネイティブ" アプリを開発できるツールとしては、古くは Titanium Mobile や Adobe AIR Mobile、現在では Xamarin, React Native や Flutter が知られています。
このセッションでは主なモバイルクロスプラットフォーム開発ツールが「どのようにして共通化を実現しているか」あるいは「共通化できない事はなにか」を解説します。
それらを踏まえて、Kotlin でクロスプラットフォーム開発ができるという事で大きく注目される Kotlin/Native とそれらがもたらす未来の開発エコシステムについて、私個人の予想を語ってみます。

**登場予定の開発ツール**

- Titanium Mobile
- Adobe AIR Mobile
- Delphi
- RubyMotion
- Xamarin
- React Native
- Flutter
- Kotlin/Native, Kotlin Multiplatform

**話さないこと**

- ゲームアプリ開発ツールについて
- ガワネイティブ、Webアプリ開発ツールについて

**발표대상**

- Android / iOS 向けのネイティブアプリ + その他 でのアプリ開発を共通化したい方

---

### Exploring the Android Transform API

`30분` `영어` `개발툴 & 생산성`

**발표자** `Marcel Schnelle`

What do ProGuard, Multidex, Resource Merger and Realm have in common? Answer: All of these components owe key functionality to the Android Transform API. It is a centerpiece of the Android Gradle Plugin's internal architecutre, as it is responsible for processing intermediary build artifacts, and before the introduction of D8, it was even tasked with the bytecode transformation of Java 8 code for Android as well. To third-party developers, it offers a hook into the creation of an APK through a centralized concept, the Transform, which can inspect and modify classes or resources. Little documentation and a lack of accessibility to the topic have rendered the Transform API a "hidden gem" in the Android plugin infrastructure.

This talk will explore the Transform API, and introduce the required steps to register a custom transformation for a given scope to the audience, in a live coding session.

**발표대상**

Attendees are expected to be familiar with the concept of a Gradle plugin, however they do not need to have prior experience writing a plugin themselves.

---

### Google Play Consoleのリリーストラックを有効活用してリリースフローの最適化を行った話

`30분` `일본어` `개발 프로세스`

**발표자** `litmon`

Google Play Consoleにはアプリのリリースを行う際にいくつかのトラック(alpha, beta, production)を選択することができる。
また、2018年には新たにinternalトラックが開放された。

クックパッドアプリでは、これらのトラックを有効活用し、リリース自動化を行い、人間によるリリーススケジュールの管理をやめたときの話をする。
また、その際にぶつかった技術的制約などにどう対応したか、リリース自動化に向けて行った様々なTipsを紹介する。

- なぜクックパッドアプリは週次リリースを行うことを決めたのか
- Google Play Consoleのトラック紹介
  - 各トラックの違い、使い分け
  - リリース前レポートとは
- 週次リリースを支える技術紹介
  - fastlane, fastlane/supply
  - アプリのversionCode管理を自動化する

**발표대상**

- リリースフロー、リリーススケジュールを管理することに課題を抱いている人
- fastlaneによるリリース自動化に興味のある人

---

### React NativeとExpoを用いたクロスプラットフォーム開発入門

`30분` `일본어` `크로스플랫폼 개발`

**발표자** `mrtry`

近年、クロスプラットフォーム開発環境のひとつとしてReact Nativeに注目が集まっています。
2018年だけでも、React Native自体の大幅なアップデートや、react-native-domの登場、AirbnbのReact Nativeリプレイスなど、話題に事欠きません。
キャッチーな話題が多いReact Nativeですが、実際の開発まわりになると「触ったこと無いし、実際よくわからない」という方が多いのではないでしょうか。
そんな方に向けて、本セッションでは、React NativeとそのtoolchainであるExpoを用いたアプリ開発の実際について紹介します。
React Nativeを触ったことがない方が、実際にアプリを作るための足がかりになれば、と思っております。

**目次(仮)**

- React NativeとExpoのそれぞれの概要
- React NativeとExpoを用いたアプリ開発の利点/欠点とユースケース
  - 利点
    - 環境構築の容易さ、便利なライブラリ群、Build設定まわりの管理移譲、など
  - 欠点
    - apkサイズ、OSS選定のつらさ、ネイティブ実装による独自拡張ができない、など
  - React NativeとExpoを採用できるユースケース
- Hello, Worldから味わうExpoでの開発の雰囲気
  - プロジェクトの作成
  - 利用するエディタ
  - Reactの雰囲気
  - Hot Reloading
  - など
- 実際に開発する上で知っておきたいTips
  - TypeScriptの導入
  - よく使われるライブラリの紹介
  - ライブラリの探し方
  - CI上でのBuildやテスト、配信
  - パフォーマンスチューニングの基礎
  - Over The Air 
  - など

**발표대상**

- React Nativeを用いたクロスプラットフォームなアプリ開発に興味がある方
- Androidエンジニアの文脈で、React Nativeの良し悪しを知りたい方
- アプリエンジニアのリソースが不足しているチームでアプリ開発に取り組みたい方

---

### Androidエンジニアが抑えておくべきUnicode Emojiの知識

`30분` `일본어` `기타`

**발표자** `Takeichi Yuki`

絵文字がUnicode規格として正式に導入されてからというもの、今や世界中で利用されるなど、テキストコミュニケーションにおいてその役割は年々増加しています。

Unicode Emojiの規格(UTS51)は毎年改定され、その都度新たな文字や規則が追加されます。仕様は複雑化しており、今後もその傾向は続くでしょう。

そのためAndroid OSのバージョン間で差異が発生し、下位互換が必要になります。そのようなUnicode絵文字に関する様々な罠と対処法、メンテナンス性を高めるための設計戦略についてお話します。

目次(案):

- 絵文字テキストレンダリング概論
  - テキストレンダリングについて
  - その中でのUnicode Emoji処理の位置づけ
- UTS51の解説
  - Emoji Sequence
  - Grapheme Cluster
  - Presentation Style
- AndroidにおけるUnicode Emoji処理の実装戦略
  - Unicode Emojiの文字列処理
  - EmojiCompatの概要と利点
  - カスタム絵文字フォントの利用

**발표대상**

- Unicode Emojiを入力/表示可能なアプリの開発者
- OSやアプリを跨いだ際にUnicode Emojiがなぜ頻繁に壊れるのか気になるAndroidエンジニア
- Unicode Emojiが豆腐にならないようにするためにどうすればいいか知りたいAndroidエンジニア

---

### WebView+ViewGroupを実現するAOSPメールアプリの内部実装とニュースアプリへの応用

`30분` `일본어` `안드로이드 프레임워크 & JetPack`

**발표자** `ogapants`

AOSPで公開されている標準メールアプリのメッセージ詳細画面では、HTMLメールの表示のためにWebViewが使われています。
この画面はWebViewの他にタイトルや転送ボタンのViewGroupがヘッダー・フッターとして並び、同時にスクロールする構成です。このレイアウトはどう実装すべきでしょうか？
一案として ScrollView+ViewGroup+WebView の構成を思い浮かべますが、これを実装すると思わぬ重大なバグが発生します。
このセッションでは、AOSPメールアプリでWebView+ViewGroupのレイアウトを実現するための驚くべき内部実装を詳細に解説します。
また、このレイアウト構成を応用して弊社ニュースアプリを最適化させた経緯についても話します。
これによりリアルな現場で繰り広げられた問題発見・原因分析・動作検証のフローも参考になると思います。

**話さないこと**

- AOSPのメールアプリにおけるメッセージ詳細以外の画面仕様について
- WebViewの内部実装について

**발표대상**

- WebViewとViewGroupを組み合わせたい方
- AOSPのメールアプリにおけるメッセージ詳細画面の構成を知りたい方
- ViewGroupが好きな方
- 直面したバグの検証方法を知りたい方

---

### Sharing Code between iOS & Android with Rust

`50분` `영어` `크로스플랫폼 개발`

**발표자** `Benedikt Terhechte`

When having to share code between iOS and Android, most companies choose C++. It is a well known language with very good tooling, but it also has a lot of pitfalls. For one, it is a very complex language. It also makes it really easy to accidentally introduce memory leaks or segmentation faults; especially if you're used to automatic memory management via a GC (Kotlin) or Arc (Swift). It also looks quite different from modern language like Swift or Kotlin. Now that we iOS developers got (mostly) rid of Objective-C, and Android Developers got (mostly) rid of Java, it feels archaic having to go back to a language with an archaic Syntax like C++.
Rust looks and feels a lot like Kotlin or Swift, and it offers the same easy ways of sharing code as C++. In addition to that, Rust has a very safe memory management model, high performance, a way to do fearless concurrency, and a very rich package ecosystem. As a bonus, it compiles to WebAssembly, so the shared code could also be used in any HTML5 app. This talk showcases how one can share very performant cross platform code between iOS, Android and others by using Rust.

**발표대상**

People interested in sharing code cross platform. People interested in Rust, people that don't want to use C++. Also, comparisons between Kotlin and Rust

---

### Server-side Kotlin for Frontend: 複雑なAndroidアプリ開発に対するアプローチ

`50분` `일본어` `앱 아키텍처 디자인`

**발표자** `qsona`

マイクロサービスという開発手法が脚光を浴びて久しいですが、クライアントサイドから見ると複雑なものです。この複雑さを解消する手段の一つとして BFF (Backends for Frontends) という手法が注目されています。これはフロントエンドののためにマイクロサービスの情報を加工・集約するサーバーです。

FiNCはヘルスケアのプラットフォームとして30以上のマイクロサービスから成り立っています。その中心プロダクトであるFiNCアプリ (Android: Kotlin / iOS: Swift) は、多くの一般ユーザーの他、法人ユーザー、コンテンツ提供者、ダイエットの指導者など様々なエンドユーザーが利用し、機能も多く複雑なアプリケーションになっています。

この複雑さにより、Android/iOS間の複雑なコードの重複, パフォーマンスの低下などの問題が起きていました。これらに対処するために、クライアントサイドでのFiNCではAndroid/iOSアプリのためのBFFをKotlinで構築しました。そして、現在はクライアントエンジニアが自分たちでBFFの開発を進めています。

本セッションでは、主に以下の3点について紹介します。

1. 複雑なAndroid/iOSアプリ開発で起こった問題、それに対するクライアント/サーバーの包括的取り組みと、その中でBFFが問題をどう解決するのか
2. BFFの技術選定とその理由 (Kotlin, Spring Webflux, Coroutines, Protocol Buffers)、具体的な機能実装の例、その効果の計測
3. Future Planについて: 複雑なAndroidアプリにおけるユーザ体験・開発体験・素早い機能改善を維持するために、我々が取るべき技術戦略

**발표대상**

クライアントサイド開発者としてマイクロサービスの扱い方を理解したい人、サーバーサイド開発者としてクライアントサイド開発者の悩みを理解したい人
複雑なAndroid/iOSアプリ開発におけるコードの重複などに課題感を持っている人
Server-side KotlinやBackends for Frontendsに興味がある人

---

### Chrome Custom Tabsの仕組みから学ぶプロセス間通信

`30분` `일본어` `안드로이드 플랫폼`

**발표자** `OHMAE Ryosuke`

Chrome Custom Tabsを使うと簡単にそのアプリの一機能であるかのようにブラウザを呼び出すことができます。この仕組みはChromeだけの機能ではなくFirefoxなど多くのブラウザアプリで実装されています。
このセッションではChrome Custom Tabsで呼び出すことのできるブラウザアプリを作るというアプローチで、Chrome Custom Tabsの仕組みを通じ、アプリ同士を連携させるプロセス間通信の使い方についてじっくりと解説します。

**발표대상**

Androidアプリの開発経験のある方

---

### What is Navigation Architecture Component and Tips

`30분` `일본어` `안드로이드 프레임워크 & JetPack`

**발표자** `kettsun0123`

Google I/O 2018で紹介されたNavigation Architecture Componentはアプリ内の画面遷移をよりシンプルに記述可能になるライブラリです。SafeArgsを使えば型安全に値を渡し、画面遷移させることができます。DeepLinkもサポートしているため、

本セッションでは実プロダクトでNavigation Architecture Componentを導入した経験をもとに、使い方から気をつけることまでを発表します。

- Navigation Architecture Component Overview
  - 特徴について
  - 使い方
  - ToolbarやBottomNavigationとの連携
- SafeArgs
  - 導入方法、使い方
  - SafeArgsを使ったより安全な画面遷移
  - 自前のクラスを遷移先に渡す
- DeepLink
  - 使い方、内部実装
  - Deeplink時にどのようにしてBackstackがつまれるか
- Navigation Architecture Componentをより深く知ってみる
  - NavControllerのnavigateが呼ばれてから遷移するまで
  - Navigation Architecture ComponentとFragmentのLifecycleの関係
- Tips
  - LiveDataと併用したときに気をつけること
  - navigationのidの割り振り

**발표대상**

Navigation Architecture Componentの使ったことがない・使ってみたい人 

---

### Master of Android Theme

`30분` `영어` `UI & Design`

**발표자** `konifar`

Do you master Android theme? Do you set the view attributes in each styles or views instead of using `android:theme`?
I'll talk about the attributes you can set in `android:theme` and touch Material Theming a little bit.

AndroidのThemeを使いこなしていますか？本当はandroid:themeで設定できるものを、styleや各Viewのattributeで設定していませんか？
この発表では、AndroidのThemeで設定できる属性について体系立てて説明します。Material Themingについても触れる予定です。

**발표대상**

The people who doesn't use Android thene effectively
Androidのthemeをうまく活用できていない人

---

### FCMを使った用途に合わせたPush通知設計

`30분` `일본어` `앱 아키텍처 디자인`

**발표자** `Koji Okada`

Push通知はアプリ利用者に対する何らかのイベントの発生、フォローしている人の新着情報、あるいはサービスやアプリ内機能の宣伝など多岐に渡る用途で使われています。
Push通知の開発を始めると、サーバーサイドですべての通知を制御するかアプリ側で通知をフィルタリングするか、あるいは高速に通知を配信するためにはどうすればいいかなど、様々な悩みが出てきます。
Push通知は幅広い用途に使われるため、こうすればすべて解決！という設計はなく、ケースバイケースで適した設計を考えなければいけません。

本セッションでは、Firebase Cloud Messaging(FCM)を利用して、用途にあわせた設計をアプリだけではなくサーバーサイドも含めて考察します。
まずはFCMでできることをおさらいした上で、具体的な設計の話に入ります。
また、実際の例として発表者が業務で開発しているアプリにおけるPush通知の設計も紹介します。

**발표대상**

FCMでできることを知りたい方やPush通知をどのように実装するか悩んでいる方を対象としています。

---

### Animations in Flutter

`30분` `영어` `크로스플랫폼 개발`

**발표자** `Salih Guler`

If you are into mobile development, you probably heard of Flutter. It's the new kid in the block and offers you a native cross-platform development environment.

One of the biggest advertisements for the Flutter is "You won't say no to your UI/UX designer anymore" and one of the biggest reason for this is: Animations.

In this talk we will go through, how you can create the widely used animations in Flutter by explaining the key concepts of it and of course, we will see some code :)  

**발표대상**

It's for beginner and advanced developers who is into Flutter

---

### WebViewを守るSafe Browsingのコントロール

`30분` `일본어` `보안`

**발표자** `Akihiro Shiota`

現在、バージョン66以降のWebViewでは、Google Safe Browsingがデフォルトで有効となっており、フィッシングサイトなどの危険なサイトへのアクセス時に警告が表示されるようになっています。
もちろんそのままでも使えますが、WebView周りのクラスでは、Safe Browsingの挙動を制御するためのAPIが提供されています。
本セッションでは、Safe Browsingの基礎から、各APIの使い方を通して、WebViewを使うアプリをより安全にする方法をお伝えします。
なお、WebViewではありませんが、SafetyNet APIとして提供されているSafe Browsing APIについても触れる予定です。

**アジェンダ(予定)**

- Google Safe Browsingの基礎知識
- Safe Browsingを制御するためのAPI
- SafetyNet Safe Browsing API
- ユースケース

**話さないこと**

- Safe Browsing以外の、WebViewでのセキュリティ対策
- Safe Browsingの性能

**발표대상**

- WebViewを使ったアプリを開発している人
- セキュリティに興味のある方

---

### Building for next billion

`30분` `영어` `기타`

**발표자** `Neil Mathew`

This talk will focus on building apps for the next billion. We'll explore the market of these late adopters of Android smartphones and the conditions that differentiates them from most of our current target audience (Data affordability, Device affordability and Linguistic barriers).

We'll review the different steps taken by Google in bringing down the barriers including the introduction of Android Go. We'll discuss what Android Go is, why it was made, what changes it brings and its intended impact. We'll also cover the differences between Android Oreo (Go) and Android One and the impact of Android One so far since it's launch.

I'd also like to share a few experiences of mine while building Gramseva: Kisan, an app for farmers to inform them of the latest agricultural commodity prices, help them decide whether to stock or sell their produce, help them bargain with vendors and offer them an easy way to share and access this information at all times. I also had a chance to interview a few farmers from a village in Kalchinna, Uttar Pradesh, India and hope to share my experiences with them.

Then we'll look into a few steps we can take in building apps that are conscious of battery, memory, connectivity, localization and performance. The many considerations that developers need to take care while building apps for these smartphones and how the little things can make a difference. We'll explore tools we can use to profile our apps, simulate bad network connections and eventually optimize our apps. Alongside that, we'll also explore how to build Android Go compliant apps.

**발표대상**

Developers, Entrepreneurs and the like looking to build applications for farmers or late adopters of Android smartphones due to barriers in network connectivity, device affordability and linguistic barriers. 

---

### シームレスに遷移可能な画面を他のアプリに提供する方法

`30분` `일본어` `UI & Design`

**발표자** `Takaki Hoshikawa`

アプリの画面のように起動し、ユーザーの選択でシームレスにChromeに移ることもできるChrome Custom Tabsや、ランチャーアプリから横スワイプするだけで表示されるGoogle Nowのように、UXを損なうことなくアプリ間を遷移するためには、場合によって通常のIntentによるActivityの遷移とは異なる方法を取る必要があります。
本セッションでは、上で挙げた2つのアプリを始めとした、シームレスな連携をしているアプリの実装がどのようになっているのかを紐解き、その上で他のアプリに画面を提供する方法について考察します。

※ アプリ間連携のUX改善のために必要なAndroidの知識についての解説がメインであり、良いデザインについて解説するセッションではありません

**발표대상**

このセッションの内容の大部分はニッチ向きとなっています。その上で以下に当てはまる方にはよりお楽しみいただけると思います。

- 別アプリ同士の連携をまさにしようと考えている方
- AIDLを使ってAndroidのプロセス間通信を使ってデータのやり取りをした経験がない方
- ランチャーアプリとGoogle Nowがどのような仕組みで連携しているかについて知りたい方

---

### ExoPlayer in RecyclerView(*), a proposal

`30분` `영어` `기타`

**발표자** `eneim`

Media playback in Android is always a challenge. Not only because of the huge eco-system (many device resolutions and hardware variants), but also the nature of Media playback itself: codec, media standard, drm, performance, etc.

ExoPlayer made by Google is an elegant solution for many years. Though this issue has not been resolved yet, for years: https://github.com/google/ExoPlayer/issues/867 (How to use ExoPlayer in a ListvVew or RecyclerView?).

I address this request as the main concern of this talk, as well as discuss about related problems one may faces while solving them. The talk will be tentatively organized as follow:

- Quick intro about how Media playback is, in 2018.
- Quick intro: what is ExoPlayer and how good it is.
- Quick intro: what is RecyclerView and how good it is.
- Quick intro: what are other 'scrollable' view like ListView and why people still use them and want to play video on them.
- Why people want to make ExoPlayer works together with RecyclerView/ListView/etc?
- A common blueprint (list of problem) to solve the problem and what is the concern?
  - Limited resource in infinite collection of item.
  - SurfaceView versus TextureView.
  - Single ExoPlayer instance versus more than one.
  - From collection view to fullscreen and back.
  - Activity's configuration change (not just rotation).
  - Anything else?
- My proposal(s): a quick Demo (library name may included).
- The proposal in detail: implementation and how it could solve the problem(s).
- Other side-note about things one may not thought of. Future work.
- Wrap up and maybe something else interesting (eg: bring MotionLayout to the game).

**발표대상**

People who are interested in Media playback in Android, or RecyclerView, or both.

---

### ハマった時に役立つ通信系デバッグの話

`30분` `일본어` `개발툴 & 생산성`

**발표자** `inomata`

実業務開発・運用中によくあるAPI/Webの問題か、アプリの問題か、を解決するための通信周りのデバッグ手法について詳しくお話します。
アジェンダ:
- WebAPIで問題があったときにどちらの不具合かを突き止める
- SSL通信を改ざんして期待値の確認
- WebViewアプリデバッグテクニック
- モックを使ったWebAPIテスト手法

**발표대상**

Android/iOS開発の経験があり、実業務でTCP/I通信周りで困ったことがある方。

---

### multi-module Androidアプリケーション

`50분` `일본어` `앱 아키텍처 디자인`

**발표자** `Jumpei Yamamoto`

MonolithicなAndroidアプリのmoduleを分割し、multi-moduleなアプリケーションを実現することは、最近のAndroid開発において重要な関心事として取り上げられています。Sansan株式会社が提供する名刺管理サービスEightのAndroidアプリケーションでは単一moduleであったアプリケーションのmodule分割を推し進め、現在では数十のmoduleで構成されるアプリケーションとなりました。

このセッションでは実際のアプリケーションのmoduleを分割した経験から、multi-moduleアプリケーションの有用性、効果的な部分とそうでない部分、ベストプラクティスについて説明します。


Multi-moduleアプリケーションの意義とは？

 - ビルドの高速化
 - Kotlinとモジュールの関係
 - クリーンアーキテクチャとの関係
 - Dynamic feature module

ただ分割するだけじゃだめ？multi-moduleで効果的にビルドを高速化するテクニック

 - 並列処理を効果的に行う構造
 - Annotation processingやgradle pluginに気をつける
 - 高速化が効果的に行われないケース
 - Multi-module化によってビルドに時間がかかるケース

アプリの設計とMulti-module化

 - 横方向（レイヤ）でのmodule分割と縦方向（機能）でのmodule分割
 - Multi-module化によりクリーンアーキテクチャを促進する
 - DIを利用してより効果的なmodule間の依存関係を構築する

Multi-moduleアプリケーションを実装する

 - Multi-moduleでのgradleの設定Tips
 - 実装におけるハマりポイント
 - Multi-moduleとdagger2
 - dynamic deliveryが可能なmoduleとそうでないmodule
 - moduleをまたいだ画面遷移の実現方法

**발표대상**

アプリケーションのmulti-module化に興味がある人 | アプリケーションのビルド時間に問題を抱えている人 | アプリケーションのよりよいアーキテクチャに興味がある人
