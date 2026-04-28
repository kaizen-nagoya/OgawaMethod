---
title: 小川清最終講義/最終講義(再)計画, Ethernet(100) 英語(100) 安全(100) 転職(53) SDV(5)
tags: DoCAP 安全 OSEK ethernet 英語
author: kaizen_nagoya
---
### The Qiita article cannot be updated due to system issues. Please refer to GitHub for the latest version.
普段、計画をたてないと誤解される私です。

2025年２月から３月にかけて、小川清最終講義を動画配信で計画していました。
諸般の事情から、2026年2月か3月に延期します。ごめんなさい。

見逃した方のために、2030年２月から３月にかけて、小川清最終講義（再）も計画します。

今から題材を磨いて、当日までに間に合うようにしようと思います。

開催条件は、参加者が２人いれば。三人よれば文殊の知恵という。
３０点をめざしていると、直交する方向で２人の意見が欲しいから。

Data Scientist, Marketerの誕生日市場調査:birthday marketing(ふたたび)
https://qiita.com/kaizen_nagoya/items/32589a0056954a89b5fc

<この項は書きかけです。順次追記します。>
This article is not completed. I will add some words in order.

# 1 自動車安全
題材の１番目は、自動車安全です。
それまでに自動車安全の規格のNWI（New Work Item)提案ができればそれもよい。
できなければ、NWIの骨子をまとめられればという感じです。

Network Designed Vehicle: Software Defined Vehicleの本当の目標(goal)
https://qiita.com/kaizen_nagoya/items/0d07e32299dcc040a89e

自動車安全資料を仮訳してみた。分析はこれから。安全(27)
https://qiita.com/kaizen_nagoya/items/c28c707ef226e65b780e

SDR:Software Defined Radioに習うSDV:Software Defined Vehicle
https://qiita.com/kaizen_nagoya/items/e244bba74f2a15154c5d

機械工学便覧＜エンジニア夏休み企画>【読書感想文】
https://qiita.com/kaizen_nagoya/items/629e9665e4df8207054b

ボッシュ自動車handbook(英語)11版(0) 課題と記事一覧
https://qiita.com/kaizen_nagoya/items/dfa35aa6f669e5df983e

輸送機器安全、自動車安全　制御（３）安全(41)
https://qiita.com/kaizen_nagoya/items/f2540c6ee1dd2dd098b3

## 1.1 Cyber security
自動車を乗っ取られたら安全は確保できない。

ISO/SAE 21434:2021 Road vehicles — Cybersecurity engineering

３さいじがわかるcyber security（サイバセキュリティ）Ethernet(90)
https://qiita.com/kaizen_nagoya/items/7a3ec58e81422a898fec

「５さいじがわかるcyber security（サイバセキュリティ）」のかんがえかた Ethernet(87)
https://qiita.com/kaizen_nagoya/items/f83394e4916760e2bae1

「標的型サイバー攻撃対策」では防げないかもしれない
https://qiita.com/kaizen_nagoya/items/c4068bdc7b519f0ecab1

## 1.2 SDV/SDM
Network Designed Vehicle: SDV(2)Software Defined Vehicleの本当の目標(goal)
https://qiita.com/kaizen_nagoya/items/0d07e32299dcc040a89e

SDR:Software Defined Radioに習うSDV(1) Software Defined Vehicle, Ethernet(93)
https://qiita.com/kaizen_nagoya/items/e244bba74f2a15154c5d

Network Designed Vehicle v.s. Software Defined Vehicle, Ethernet(38)
https://qiita.com/kaizen_nagoya/items/978403a5c3905ef0478a

Text: SDV(3)Software Defined Vehicle 構造の構想
https://qiita.com/kaizen_nagoya/items/286c74f32559543a850b

Software defined vehicle, references on a paper to be submitted., AUTOSAR(33)
https://qiita.com/kaizen_nagoya/items/230d61d1b3acda9480a0

### 1.2.1 Sotif etc
Sotif(ISO 21448:2022 Road vehicles — Safety of the intended functionality)

ISO/DIS 34505 Road vehicles — Test scenarios for automated driving systems — Scenario evaluation and test case generation

ISO/TR 23786:2019 Road vehicles — Solutions for remote access to vehicle — Criteria for risk assessment

###  1.2.2 AUTOSAR仕様体系提案
要求と仕様を別文書から統一した設計文書のみとし、場合によっては設計文書から仕様、要求を自動生成できるようにする。あるいは、２者間取引でなければ、要求は発行せず、仕様から自動生成する仕組みだけ定式化して、顧客の選択で要求が自動生成できるようにすればよい。顧客によって、安全、操縦安定性、燃費、価格など強化したい傾向が違うかもしれない。
ほぼすべての分野で、Adaptive Platform, Classic Platform固有ではなく、統合した仕様にする。
設計であるソースコードから仕様を自動生成するのが一番よいかも。

「あなたがAUTOSARのEditorだったらどの文書をどう書き換えたいか」選手権(0), OSEK(61)
https://qiita.com/kaizen_nagoya/items/0055bb88f43f98a61739

# 2.言語処理
## 2.1 自動生成/LLM/ 自然言語処理
LLM に取り組む背景、目的、目標
https://qiita.com/kaizen_nagoya/items/cfed9b4fbb2db49c76fb

文字鏡フォント。追悼　古家 時雄。日本語（２）
https://qiita.com/kaizen_nagoya/items/64c2ff25271ea8ebf2b0

日本語語彙大系　追悼：白井諭。Lisperへの敬意を込めて。
https://qiita.com/kaizen_nagoya/items/e41ed513c8686841399b

日本語語彙大系　白井 諭　<エンジニア夏休み企画>【読書感想文】
https://qiita.com/kaizen_nagoya/items/e59d6d37b35de929261a

からあげ機の発展 AI(3)
https://qiita.com/kaizen_nagoya/items/538dc2699cd37fa1f3eb

## 2.2 コンパイラ
電総研（現在の産総研この一部）で研修生でいたとき、Pascalで書かれたコンパイラをC言語で書き直し、Small Cコンパイラを写経し、OBJという抽象データ型言語のシンタックスチェッカを作成し、ソフトウェア技術者協会で発表した。

JAXA/IPA クリティカルソフトウェアワークショップ （WOCS）言語関連発表
https://qiita.com/kaizen_nagoya/items/3447b1bc4ee6014e6739

## 2.3 OSの統合または複数のOSを生成できる核の設計
POSIX系のLinuxとFreestanding環境のOSEK/VDXのOSを生成できる統合した環境を作る。
C++で書くか、RUSTで書くかは悩み中。

ISO OSEK/VDX and ISO Linux OS 同梱ソースをC++またはRUSTで書く企画　OSEK(7)
https://qiita.com/kaizen_nagoya/items/27899e936c90b415d700

# 3 博論指導方針
５年後までに３人の博論指導予定。
５年間の経験をもとに５年後は、大量に博論指導体制を構築する予定。

大学入試不合格でも筆記試験のない大学に入って卒業できる。卒業しなくても博士になれる。
https://qiita.com/kaizen_nagoya/items/74adec99f396d64b5fd5

全世界の不登校の子供たち「博士論文」を書こう。世界子供博士論文遠隔実践中心 安全(99)
https://qiita.com/kaizen_nagoya/items/912d69032c012bcc84f2

難病患者（工学博士）による医療系学生・医療従事者への３２講(0) 医工連携 安全(87)
https://qiita.com/kaizen_nagoya/items/84bbba518dd9ca0aad7c

からあげ機の発展
https://qiita.com/kaizen_nagoya/items/538dc2699cd37fa1f3eb

## 3.1 Youtube 
博論の乗りで、Youtube記事を論文にするには
https://qiita.com/kaizen_nagoya/items/05e4d2b121b6b80a5c6b

博論の乗りで「電子ピアノ」を論文にするには 音楽(20)
https://qiita.com/kaizen_nagoya/items/58113ac4b8e28ccbd16c

博論の乗りで「にほんのうた」を論文にする 音楽(5)
https://qiita.com/kaizen_nagoya/items/4b40d8b8873aa7649a85

## 3.2 LLMを利用した自動指導システム
MCP入門 〜面倒なことはAIエージェントにやらせよう〜 by からあげ を聞きながら
https://qiita.com/kaizen_nagoya/items/54b648c838fae8d57e38
【松尾研LLMコミュニティ】面倒なことはLLMにやらせよう "Beginning LLM"2024年10月17日 AI(9)
https://qiita.com/kaizen_nagoya/items/efdc23fbe67cdae2126e
設計:ChatGPTで特異解か一般解を求める AI(1)
https://qiita.com/kaizen_nagoya/items/4dec580e16a7c84b0ec4
AI・機械学習　昨日、今日、明日
https://qiita.com/kaizen_nagoya/items/adb184c8fc7a65ac9756
DNA LLM and genome for survey 2200 papers by name.
https://qiita.com/kaizen_nagoya/items/ce8a28d6072f340a9d59

# 最終講義（再）
2025年にはまとめきれなかった事項を、2030年までにはまとめなおしますという納期延長方法。
2025年には、３０点の案しかしめさず、2030年には90点になっているはずっていう。

## 退官記念講演会 2015/3/13
10:00- 10:30「要求逸脱に基づく例外試験項目の作成実験」名古屋大学 山本修一郎 教授
10:30-11:00 「D-Case を用いたレビューを見える化する方法の導入事例」（株）デンソークリエイト小林 展英 氏
11:00-11:30 MISRA-C2004から2012への移行の課題」（株）ヴィッツ 萩原勝 氏
11:30-12:00 「SPEAK-IPAを用いた設計指向による公開アセスメントの試行」（株）A&D 佐藤克 氏
13:00-14:00　電子国土功績賞2014 「MapMakerの開発手法・帳票の設計」名古屋港管理組合　総合開発部長　森田伸二　氏
14:10-14:45 TOPPERS/SSPを用いた教育訓練カリキュラムカーネルの自作およびカスタマイズ アライブビジョンソフトウェア株式会社 高橋和浩　氏
14:40-15:10 Toppers_ASPカーネルとScilab による組込みメカトロニクス制御シミュレーション 塩出武　氏
15:20-15:50 .AUTOSAR開発体験キット　富士ソフト株式会社　鴫原一人 氏
15:50-16:20組込みソフトウェア学習用教材ボードNCES TRAINING BOARDと教材 松浦光洋　氏
16:30-17:00 VZエディタ・MINIXからA-SPICE, MISRA-C, TOPPERS, WOCSまで 名古屋市工業研究所　小川清

## 第2回退官記念講演会 2020/2/28
13:30-14:00 「github/docker 作業の診断・改善」 名古屋市工業研究所 小川清
14:00-14:30 「アセスメントの国際動向」 近藤聖久
14:30-15:00 「グローバル大規模 SCRUM 事例紹介」日本マイクロソフト 小泉浩
15:00-15:10 休憩
15:10-15:30 「プロセスアセスメント事例紹介」 JAXA 片平真史
15:30-17:00 パネル「なぜ日本がITで生き残れるか」 NSSLCサービス北野敏明

## 第３回退官記念講演会 2030/2 or 3
1) Robot
2) LLM/MCP
3) CAD/CAM/CAE
4) OS unification
5) Language unification
6) Model Based Design
7) Safety and Security

# 前職
水道局10年(1976,4-1986,3)を振り返る
https://qiita.com/kaizen_nagoya/items/707fcf6fae230dd349bf

水の資料集(0)　方針と成果
https://qiita.com/kaizen_nagoya/items/f5dbb30087ea732b52aa

bookmeter 改善書房【水】
https://bookmeter.com/users/121023/bookcases/11094536

booklog 水・水道・環境・ごみ
https://booklog.jp/users/kaizen?category_id=1788864&display=front

<この項は書きかけです。順次追記します。>
This article is not completed. I will add some words and/or centences in order.
Este artículo no está completo. Agregaré algunas palabras en orden.
# Qiita Calendar 2024
祝休日・謹賀新年 2025年の目標
https://qiita.com/kaizen_nagoya/items/dfa34827932f99c59bbc

Qiita 1年間をまとめた「振り返りページ」＠2024
https://qiita.com/kaizen_nagoya/items/ed6be239119c99b15828

2024 参加・主催Calendarと投稿記事一覧 Qiita(248)
https://qiita.com/kaizen_nagoya/items/d80b8fbac2496df7827f

主催Calendar2024分析 Qiita(254)
https://qiita.com/kaizen_nagoya/items/15807336d583076f70bc

Calendar 統計
https://qiita.com/kaizen_nagoya/items/e315558dcea8ee3fe43e

LLM 関連 Calendar 2024 
https://qiita.com/kaizen_nagoya/items/c36033cf66862d5496fa

Large Language Model Related Calendar 
https://qiita.com/kaizen_nagoya/items/3beb0bc3fb71e3ae6d66

博士論文 Calendar 2024 を開催します。 
https://qiita.com/kaizen_nagoya/items/51601357efbcaf1057d0

博士論文(0)関連記事一覧
https://qiita.com/kaizen_nagoya/items/8f223a760e607b705e78

# 関連資料
' @kazuo_reve 私が効果を確認した「小川メソッド」
https://qiita.com/kazuo_reve/items/a3ea1d9171deeccc04da

' @kazuo_reve 新人の方によく展開している有益な情報
https://qiita.com/kazuo_reve/items/d1a3f0ee48e24bba38f1

' @kazuo_reve Vモデルについて勘違いしていたと思ったこと
https://qiita.com/kazuo_reve/items/46fddb094563bd9b2e1e

# 自己記事一覧
Qiitaで逆リンクを表示しなくなったような気がする。時々、スマフォで表示するとあらわっることがあり、完全に削除したのではなさそう。

４月以降、せっせとリンクリストを作り、統計を取って確率を説明しようとしている。
2025年２月末を目標にしている。

一覧の一覧( The directory of directories of mine.) Qiita(100)
https://qiita.com/kaizen_nagoya/items/7eb0e006543886138f39

仮説（0）一覧（目標100現在40）
https://qiita.com/kaizen_nagoya/items/f000506fe1837b3590df

Qiita(0)Qiita関連記事一覧（自分）
https://qiita.com/kaizen_nagoya/items/58db5fbf036b28e9dfa6

Error一覧 error(0)
https://qiita.com/kaizen_nagoya/items/48b6cbc8d68eae2c42b8

C++ Support(0)　
https://qiita.com/kaizen_nagoya/items/8720d26f762369a80514

Coding(0) Rules, C, Secure, MISRA and so on
https://qiita.com/kaizen_nagoya/items/400725644a8a0e90fbb0

Ethernet 記事一覧　Ethernet(0)
https://qiita.com/kaizen_nagoya/items/88d35e99f74aefc98794

Wireshark 一覧 wireshark(0)、Ethernet(48) 
https://qiita.com/kaizen_nagoya/items/fbed841f61875c4731d0

線網（Wi-Fi）空中線(antenna)(0) 記事一覧(118/300目標)
https://qiita.com/kaizen_nagoya/items/5e5464ac2b24bd4cd001

なぜdockerで機械学習するか 書籍・ソース一覧作成中 (目標100)
https://qiita.com/kaizen_nagoya/items/ddd12477544bf5ba85e2

プログラムちょい替え（0）一覧:4件
https://qiita.com/kaizen_nagoya/items/296d87ef4bfd516bc394

言語処理100本ノックをdockerで。python覚えるのに最適。:10+12
https://qiita.com/kaizen_nagoya/items/7e7eb7c543e0c18438c4

Python(0)記事をまとめたい。
https://qiita.com/kaizen_nagoya/items/088c57d70ab6904ebb53

安全（0）安全工学シンポジウムに向けて: 21
https://qiita.com/kaizen_nagoya/items/c5d78f3def8195cb2409

プログラマによる、プログラマのための、統計(0)と確率のプログラミングとその後
https://qiita.com/kaizen_nagoya/items/6e9897eb641268766909

転職(0)一覧
https://qiita.com/kaizen_nagoya/items/f77520d378d33451d6fe

技術士(0)一覧
https://qiita.com/kaizen_nagoya/items/ce4ccf4eb9c5600b89ea

Reserchmap(0) 一覧
https://qiita.com/kaizen_nagoya/items/506c79e562f406c4257e

物理記事　上位100
https://qiita.com/kaizen_nagoya/items/66e90fe31fbe3facc6ff

量子(0) 計算機, 量子力学 
https://qiita.com/kaizen_nagoya/items/1cd954cb0eed92879fd4

数学関連記事１００
https://qiita.com/kaizen_nagoya/items/d8dadb49a6397e854c6d

coq(0) 一覧
https://qiita.com/kaizen_nagoya/items/d22f9995cf2173bc3b13

統計(0)一覧
https://qiita.com/kaizen_nagoya/items/80d3b221807e53e88aba

図(0) state, sequence and timing. UML and お絵描き 
https://qiita.com/kaizen_nagoya/items/60440a882146aeee9e8f

色(0) 記事100書く切り口 
https://qiita.com/kaizen_nagoya/items/22331c0335ed34326b9b

品質一覧 
https://qiita.com/kaizen_nagoya/items/2b99b8e9db6d94b2e971

言語・文学記事　１００
https://qiita.com/kaizen_nagoya/items/42d58d5ef7fb53c407d6

医工連携関連記事一覧
https://qiita.com/kaizen_nagoya/items/6ab51c12ba51bc260a82

水の資料集(0)　方針と成果
https://qiita.com/kaizen_nagoya/items/f5dbb30087ea732b52aa

自動車　記事　１００
https://qiita.com/kaizen_nagoya/items/f7f0b9ab36569ad409c5

通信記事１００
https://qiita.com/kaizen_nagoya/items/1d67de5e1cd207b05ef7

日本語（０）一欄
https://qiita.com/kaizen_nagoya/items/7498dcfa3a9ba7fd1e68

英語(0) 一覧
https://qiita.com/kaizen_nagoya/items/680e3f5cbf9430486c7d

音楽　一覧(0) 
https://qiita.com/kaizen_nagoya/items/b6e5f42bbfe3bbe40f5d

「@kazuo_reve 新人の方によく展開している有益な情報」確認一覧 
https://qiita.com/kaizen_nagoya/items/b9380888d1e5a042646b

鉄道（０）鉄道のシステム考察はてっちゃんがてつだってくれる
https://qiita.com/kaizen_nagoya/items/faa4ea03d91d901a618a

OSEK OS設計の基礎　OSEK(100)
https://qiita.com/kaizen_nagoya/items/7528a22a14242d2d58a3

coding (101) 一覧を作成し始めた。omake:最近のQiitaで表示しない5つの事象
https://qiita.com/kaizen_nagoya/items/20667f09f19598aedb68

官公庁・学校・公的団体（NPOを含む）システムの課題、官（０）
https://qiita.com/kaizen_nagoya/items/04ee6eaf7ec13d3af4c3

「はじめての」シリーズ　 ベクタージャパン　
https://qiita.com/kaizen_nagoya/items/2e41634f6e21a3cf74eb

AUTOSAR(0)Qiita記事一覧, OSEK(75)
https://qiita.com/kaizen_nagoya/items/89c07961b59a8754c869

プログラマが知っていると良い「公序良俗」
https://qiita.com/kaizen_nagoya/items/9fe7c0dfac2fbd77a945

LaTeX(0) 一覧　
https://qiita.com/kaizen_nagoya/items/e3f7dafacab58c499792

自動制御、制御工学一覧（０）
https://qiita.com/kaizen_nagoya/items/7767a4e19a6ae1479e6b

Rust(0) 一覧　
https://qiita.com/kaizen_nagoya/items/5e8bb080ba6ca0281927

programの本質は計画だ。programは設計だ。
https://qiita.com/kaizen_nagoya/items/c8545a769c246a458c27

登壇直後版 色使い(JIS安全色) Qiita Engineer Festa 2023〜私しか得しないニッチな技術でLT〜 スライド編 0.15
https://qiita.com/kaizen_nagoya/items/f0d3070d839f4f735b2b

プログラマが知っていると良い「公序良俗」
https://qiita.com/kaizen_nagoya/items/9fe7c0dfac2fbd77a945

逆も真：社会人が最初に確かめるとよいこと。OSEK(69)、Ethernet(59)
https://qiita.com/kaizen_nagoya/items/39afe4a728a31b903ddc

統計の嘘。仮説（127）
https://qiita.com/kaizen_nagoya/items/63b48ecf258a3471c51b

自分の言葉だけで論理展開できるのが天才なら、文章の引用だけで論理展開できるのが秀才だ。仮説（136）
https://qiita.com/kaizen_nagoya/items/97cf07b9e24f860624dd

参考文献駆動執筆(references driven writing)・デンソークリエイト編
https://qiita.com/kaizen_nagoya/items/b27b3f58b8bf265a5cd1

「何を」よりも「誰を」。１０年後のために今見習いたい人たち
https://qiita.com/kaizen_nagoya/items/8045978b16eb49d572b2

Qiitaの記事に３段階または５段階で到達するための方法
https://qiita.com/kaizen_nagoya/items/6e9298296852325adc5e

出力(output)と呼ばないで。これは状態(state)です。
https://qiita.com/kaizen_nagoya/items/80b8b5913b2748867840

coding (101) 一覧を作成し始めた。omake:最近のQiitaで表示しない5つの事象
https://qiita.com/kaizen_nagoya/items/20667f09f19598aedb68

あなたは「勘違いまとめ」から、勘違いだと言っていることが勘違いだといくつ見つけられますか。人間の間違い(human error(125))の種類と対策
https://qiita.com/kaizen_nagoya/items/ae391b77fffb098b8fb4

プログラマの「プログラムが書ける」思い込みは強みだ。３つの理由。仮説（168）統計と確率(17) , OSEK(79)
https://qiita.com/kaizen_nagoya/items/bc5dd86e414de402ec29

出力(output)と呼ばないで。これは状態(state)です。
https://qiita.com/kaizen_nagoya/items/80b8b5913b2748867840

これからの情報伝達手段の在り方について考えてみよう。炎上と便乗。
https://qiita.com/kaizen_nagoya/items/71a09077ac195214f0db

ISO/IEC JTC1 SC7 Software and System Engineering
https://qiita.com/kaizen_nagoya/items/48b43f0f6976a078d907

アクセシビリティの知見を発信しよう！（再び）
https://qiita.com/kaizen_nagoya/items/03457eb9ee74105ee618

統計論及確率論輪講（再び）
https://qiita.com/kaizen_nagoya/items/590874ccfca988e85ea3

読者の心をグッと惹き寄せる7つの魔法
https://qiita.com/kaizen_nagoya/items/b1b5e89bd5c0a211d862

「@kazuo_reve 新人の方によく展開している有益な情報」確認一覧
https://qiita.com/kaizen_nagoya/items/b9380888d1e5a042646b

ソースコードで議論しよう。日本語で議論するの止めましょう（あるプログラミング技術の議論報告）
https://qiita.com/kaizen_nagoya/items/8b9811c80f3338c6c0b0

脳内コンパイラの3つの危険
https://qiita.com/kaizen_nagoya/items/7025cf2d7bd9f276e382

心理学の本を読むよりはコンパイラ書いた方がよくね。仮説（34）
https://qiita.com/kaizen_nagoya/items/fa715732cc148e48880e

NASAを超えるつもりがあれば読んでください。
https://qiita.com/kaizen_nagoya/items/e81669f9cb53109157f6

データサイエンティストの気づき!「勉強して仕事に役立てない人。大嫌い!!」『それ自分かも?』ってなった!!! 
https://qiita.com/kaizen_nagoya/items/d85830d58d8dd7f71d07

「ぼくの好きな先生」「人がやらないことをやれ」プログラマになるまで。仮説（37）　
https://qiita.com/kaizen_nagoya/items/53e4bded9fe5f724b3c4

なぜ経済学徒を辞め、計算機屋になったか（経済学部入学前・入学後・卒業後対応） 転職(1)  
https://qiita.com/kaizen_nagoya/items/06335a1d24c099733f64    

プログラミング言語教育のXYZ。 仮説（52） 
https://qiita.com/kaizen_nagoya/items/1950c5810fb5c0b07be4

【24卒向け】9ヶ月後に年収１０００万円を目指す。二つの関門と三つの道。
https://qiita.com/kaizen_nagoya/items/fb5bff147193f726ad25

「【25卒向け】Qiita Career Meetup for STUDENT」予習の勧め
https://qiita.com/kaizen_nagoya/items/00eadb8a6e738cb6336f

大学入試不合格でも筆記試験のない大学に入って卒業できる。卒業しなくても博士になれる。
https://qiita.com/kaizen_nagoya/items/74adec99f396d64b5fd5

全世界の不登校の子供たち「博士論文」を書こう。世界子供博士論文遠隔実践中心 安全(99)
https://qiita.com/kaizen_nagoya/items/912d69032c012bcc84f2

小川メソッド　覚え（書きかけ）
https://qiita.com/kaizen_nagoya/items/3593d72eca551742df68

DoCAP（ドゥーキャップ）って何ですか？
https://qiita.com/kaizen_nagoya/items/47e0e6509ab792c43327

views 20,000越え自己記事一覧
https://qiita.com/kaizen_nagoya/items/58e8bd6450957cdecd81

Views１万越え、もうすぐ１万記事一覧 最近いいねをいただいた213記事
https://qiita.com/kaizen_nagoya/items/d2b805717a92459ce853

amazon 殿堂入りNo1レビュアになるまで。仮説(102)
https://qiita.com/kaizen_nagoya/items/83259d18921ce75a91f4

100以上いいねをいただいた記事16選
https://qiita.com/kaizen_nagoya/items/f8d958d9084ffbd15d2a

小川清最終講義、最終講義（再）計画, Ethernet(100) 英語(100) 安全(100)
https://qiita.com/kaizen_nagoya/items/e2df642e3951e35e6a53

＜この記事は個人の過去の経験に基づく個人の感想です。現在所属する組織、業務とは関係がありません。＞
This article is an individual impression based on my individual experience. It has nothing to do with the organization or business to which I currently belong.
Este artículo es una impresión personal basada en mi experiencia personal. No tiene nada que ver con la organización o empresa a la que pertenezco actualmente.
### 文書履歴(document history)
ver. 0.01 初稿 　20240430
### 最後までおよみいただきありがとうございました。
いいね　💚、フォローをお願いします。
#### Thank you very much for reading to the last sentence.
Please press the like icon 💚　and follow me for your happy life.
### Muchas gracias por leer hasta la última oración.
Por favor, haz clic en el ícono Me gusta 💚 y sígueme para tener una vida feliz.
