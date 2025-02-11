---
title: ビットコインを交換手段に進化させるライトニングネットワーク②
taxonomy:
    category:
        - lightning
        - bitcoin
        - money
    post_tag:
        - beginner
        - economics
---

## ビットコインの交換手段への進化は、ビットコインの他に選択肢のない途上国の人々が推し進める

|  ![Category](/_images/category.png)  |  ライトニング、ビットコインは最強のお金 |  ![Tag](/_images/tag.png)  |  初級、経済学  | ![Time](/_images/timer.png)  |  15分  |
| ---- | ---- | ---- | ---- | ---- | ---- |

*本記事は2022年8月6日に[Lyn Alden](https://twitter.com/LynAldenContact) 氏が発表した「[A Look At the Lightning Network](https://www.swanbitcoin.com/a-look-at-the-lightning-network/)」を [@slashweb3_mk](https://twitter.com/slashweb3_mk) さんが翻訳、[@Haruko_Maruyama](https://twitter.com/Haruko_Maruyama) さんが一部加筆修正したものです。*

本記事では、[ビットコインを交換手段に進化させるライトニングネットワーク①](http://lostinbitcoin.jp.testrs.jp/staging/bitcoin/a_look_at_the_lightning_network/)に引き続き、貨幣の機能である価値貯蔵手段と交換手段を考察します。

### ビットコイン以外の暗号資産の致命的欠陥

新しい貨幣財が交換手段へと進化するには、まず価値貯蔵手段としての普及が進み、リーチ可能な最大市場規模の大半を掌握することが求められます。しかし、ライトコイン、ドージコイン、ビットコインキャッシュ、ビットコインサトシビジョンなど最初から交換手段となることを目指した暗号資産は、交換手段としての最適化を急ぐあまり、価値貯蔵手段に必要な特性を犠牲とした結果、貨幣化プロセスの第1フェーズでつまずきました。

価値貯蔵手段として普及していない段階で、ネットワークの安定性、分散性、不変性、検証性よりも、交換手段としてトランザクションの処理件数と速度の最適化を優先したためです。数人で立ち上げたフィンテックスタートアップが、決済処理能力も使い勝手もVisaなどの既存サービスに劣るという致命的欠陥を抱えるにも関わらず、対等に競争できると思い込んでいました。

そもそも、これらの暗号資産プロジェクトは、なぜ交換手段としてVisaに取って代わることを目指したのでしょうか。サトシ・ナカモトがホワイトペーパーでビットコインをP2P電子キャッシュシステムと説明したからです。ただ「キャッシュ」には交換手段以外の意味もあります。サトシはブロックサイズに上限を設定しましたが、2010年には、上限を徐々に引き上げることでネットワークをスケールする方法を書き残しています。サトシがビットコインの開発コミュニティを去った後、一部の人はスケーリングの必要性を訴え、賛否両論あったハードフォークを十分な議論もコンセンサスも経ずに早急に実行しようとしました。結局、彼らはハードフォークを強行してビットコインネットワークから離脱しましたが、多数のノードに支えられた分散ネットワークの強みと、ビットコインに不要な変更を加えるのは不可能なことを後に思い知ることになります。

ビットコインの初期参加者の多くは、「電子キャッシュ」をベースレイヤーでの簡単かつ迅速な日常的決済手段と解釈したようです。しかし、今日におけるキャッシュ、つまり現金は検閲耐性と決済完了性を備えた決済手段と考える方が妥当だと思います。物理的な現金は必ずしも最も使い勝手の良い決済手段ではありませんし、あらゆる取引に適した万能な交換手段でもありません。しかし、最もプライバシーが尊重され、差し止めが困難な決済手段です。

したがって、物理的な現金と同様、「電子キャッシュ」が最適化すべきは、少なくともベースレイヤーでのトランザクションについては、スピードと効率ではなく、プライバシーと検閲耐性と決済完了性です。用途も日常的な決済ではなく、こうした特性が求められる取引限定でよいと考えています。

ビットコインのアーリーアダプターの中には、対面だけでなく、ネット上の取引にも使えるプライバシーを考慮した決済手段を求めていた人たちがいます。ビットコインは当初から彼らのニーズに最適化されていました。また、プライバシーを基本的人権と見なし、電子キャッシュのプライバシー技術が独裁政権下で暮らす人々に役立つ可能性を見出した人もいました。利用可能な決済手段がなかったために、ビットコインを使い始めた人もいました。例えば、女性が銀行口座を開設するのが難しいアフガニスタンで、ソフトウェア開発会社Citadel Softwareを創設したロヤ・マハブーブは、女性従業員への給与の支払いにビットコインを利用しました。ビットコインはインターネットの闇市場での決済手段としても頻繁に使われました。これを理由に、ビットコインという技術が犯罪を助長すると考えるのは短絡的です。ポケベルなど新技術を早期に採用するのは犯罪者というケースは多々あります。

当初からビットコインに理想的な交換手段としての有用性を見出していたアーリーアダプターにとって、ビットコインの処理能力はすでに十分なものでした。サトシは、自身を含むサイファーパンクたちが重視する匿名性、検閲耐性、ピアツーピアという特性を備えたデジタル交換手段を開発すべく、変数を慎重に選択しました。このサトシによる設計チョイスが、ビットコインを当初から極めて有用な電子キャッシュたらしめたと言えます。

サイファーパンクは決済完了までに30分要することや、複数回の承認を待たなければならないことを意に介さないでしょうし、自らすすんでノードも運用するでしょう。ビットコインの購入や売却の際はプライバシー技術も用いるはずです。当時のビットコインは若干の貨幣プレミアムを有するユーティリティネットワークだったのです。比較的少数の人々の需要を満たす貨幣を提供することで、その価値は利用者だけでなく、投機家にも認識されるようになりました。歴史上、貨幣として採用されたコモディティと同様に、ビットコインは初めから実用的であり、その実用性が貨幣プレミアムの源泉となったのです。ビットコインの実用性とは、中央集権的な仲介機関を通さずに国境を超えてグローバルに価値を交換できる堅牢なネットワークを提供した点、無数の模倣コインよりも貨幣としての不変性、検閲耐性、流動性が優れている点です。

しばらくすると、大きく変動するビットコインの価格、すなわちビットコインの貨幣プレミアムが投機家や投資家を引きつけるようになりました。彼らにはビットコインを交換手段として使用する意図は皆無でした。金の投資家が金を交換手段として利用しないのと同じです。オーストリア学派の経済学者の中には、総供給が2,100万に限られていること着目し、興味深い貨幣財として注目した人もいました。また、ビットコインネットワークの合意規則が変更不可能なこと、安全性、流動性、非中央集権性が他のプルーフオブワークとは比較にならないくらい高いことが広く理解されるようになると、ビットコインを健全な貨幣とみなす人が増えました。さらに、人権活動家の間では検閲耐性という観点からビットコインを理想的な反体制テクノロジーとの認識が広がり、利用が拡がりました。

ライトコインやビットコインキャッシュなどの敗因は、市場形成を待たずに非中央集権性を犠牲にしてスケーリングを急いだことです。ビットコインベースレイヤーのトランザクション処理能力は、ビットコインの特性を必要とする数千万人が必要な時に利用するには十分なのです。

ベースレイヤーであるビットコインネットワークは、検閲耐性の高さ、グローバルに価値を保持・移転できるという点で、決済・貯蓄システムの重装甲戦車に例えることができます。行く手を阻むあらゆるものを爆破しながら敵地を進むには戦車が適しています。しかし、通勤など日常的な移動手段には向きません。ベースレイヤーでのビットコイン決済を日々の買い物での交換手段に使うのは、戦車で通勤するようなものです。意図された用途ではないので、使い勝手が悪く、市場に受け入れられるはずはありません。すべての決済をベースレイヤーで処理すべくスケーリングに成功したとしても、本来の優位性が失われてしまいます。1秒間に数万トランザクションを処理可能なベースレイヤーは、データストレージを毎日1テラバイト以上増設する必要があります。

ビットコインネットワークのポテンシャルを最も早く見抜いたハル・フィニーらは、ネットワークの成長が階層化によってもたらされると予測していました。

### ビットコイン対ドル

2021年の時点で、全世界のビットコイン保有者は1億人以上と推定されています。取引所や調査機関が公表した検証不能なデータに基づく推測であり、正確性には議論の余地がありますが、これは世界人口の1〜2％に相当します。ビットコインの普及率が2桁台前半に達する国もあります。

普及実態を測るには幅と深さを考慮する必要があります。幅はビットコイン保有者数、深さは彼らの流動資産に占めるビットコインの割合です。現状は流動資産に占めるビットコイン比は小さい、つまり「浅い」と言わざるを得ません。

例えば、暗号通貨取引所の実質休眠状態の口座に264.34ドル相当のビットコインを放置している人は、経済的意義のあるレベルでビットコインを「採用」したとは言えません。

思考実験として、人々が流動資産をビットコインとドルの両方またはいずれかで保有する世界を想像してみてください。

ビットコインのインフレ率（通貨膨張率、マネーサプライの伸び率）はドルのインフレ率に比べて大幅に低いです。ビットコインについて学び、インフレ率の低さに引かれて購入、保有を考える人が増えると、ドル建てのビットコイン価格は激しい変動を繰り返しながらも、長期的には上昇トレンドを維持するとします。この想定が正しければ、ビットコインを少量購入した人は、その後一切買い増さなくても、流動資産に占めるビットコインの割合は年々大きくなります。

仮にビットコイン保有者が人口の1%、かつ彼らの流動資産に占めるビットコイン比率が平均3%だとします。この場合、ビットコインの普及率は 1% x 3% = 0.03% で、普及は取るに足らないものです。新し物好き、あるいは顧客にサイファーパンクが多いなど特別な理由がない限り、商店や企業がわざわざビットコイン決済に対応することはないでしょう。

ビットコイン保有者が人口の 10%、流動資産に占めるビットコイン比率が平均 5% の場合はどうでしょう？普及率は 0.5% とまだまだ低いですが、数百万人規模のニッチ市場と言えます。

ビットコイン保有者が人口の 30%、流動資産に占めるビットコイン比率が 10% になると普及率は 3% です。決して小さくはないニッチな購買力を持つマイノリティといったところです。

ビットコイン保有者が人口の 50%、流動資産に占めるビットコイン比率が 20% に達すると普及率は 10%、大きな市場です。

ビットコイン保有者が人口の 70%、流動資産に占めるビットコイン比率 30% では普及率は 21%、巨大市場です。

保有者は何を契機にビットコインを交換手段として使おうと思うのでしょうか？おそらく、何年も前にビットコインを購入し、場合によってはその後も買い増し、その間にビットコイン価格が上昇したことで、流動資産に占めるビットコインの割合がある程度の大きさになった時です。ビットコインの一部を売って現金化するか、直接交換手段として使うこともあり得ます。

もちろん、実際の普及プロセスはこれほど直線的ではありません。アーリーアダプターの一部はビットコインの値上がりで資産を大幅に増やし、比較的早期にニッチビジネスの魅力的なターゲット顧客となる富裕層を新たに形成します。社会が本格的にビットコインを採用するには時間を要する一方で、この新たな富裕層の需要を捉えて売上を増やしたいと考えるアーリーアダプターの事業者も当然出現します。

### まずは途上国

上記の想定を非現実的だと感じる人は少なくないでしょう。ビットコインがドルから流動資産市場のシェアを20%以上も奪うなどあり得ないと思う人のために、今度はドルではなく、途上国の通貨で考えてみましょう。

設定を米国からナイジェリア、通貨をドルからナイラに置き換えてみます。ナイジェリアでは、ナイラ崩壊を防ぐために銀行から暗号通貨取引所への入金が禁止されているにもかかわらず、ビットコインの普及率は世界最高水準にあります。

自国通貨の供給が下図のように増加の一途をたどると、国民はさまざまな障害を乗り越えて他の通貨に避難します：

![図 ナイジェリアのマネーサプライ M2](/_images/a_look_at_the_lightning_network2_1.png)

こうした人たちには、まだ貨幣化プロセスの初期段階にあるビットコインが、日常的な決済にまつわる問題の有望な解決策として映ります。インフレ率が高く、決済システムが脆弱な途上国では、ビットコインがライトニングネットワークを介して交換手段として急速にスケールする可能性は大きいです。

ビットコインを実際に利用する人と、経済的に恵まれた国で暮らすビットコイン批判家の認識のズレは、これに起因します。そのため、Lightning Labs の CEO エリザベス・スタークは「ビットコインをビリオネア（数十億ドルの資産を持つ一部の富裕層）だけでなく、数ビリオン（数十億の一般市民）の手に」届けることをミッションに掲げ、ビットコインは単なるデジタルゴールドではなく、世界中の人々をエンパワーするツールであることを強調するのです。

ビットコインネットワークが成長を続けて貨幣化への道を順調に歩んでいるのは、国際基軸通貨である米ドルやスイスフランを侵食したからではありません。インフレ率が高く、財産権が尊重されない、かつ決済システムが脆弱な国々の通貨、いわゆる周辺的な通貨を代替する形でまず普及し、そこから中核的な国々へと広がっていきます。ビットコインの時価総額は、すでに全ての途上国の広義のマネーサプライを追い抜き、途上国通貨（発行国内でしか使えないか、国外では少数の限られた場所でしか交換できない）よりも世界中で広く受け入れられています。もちろん、国内の商店や企業による受容性は各国法定通貨には到底及びませんが、グローバルでの受容性はビットコインの方が勝っています。

ビットコインネットワークが長期にわたって成長を続ければ、商店や企業にとって、ビットコインを受け取ることが合理的選択となります。そして、商店や企業によるビットコインの受容性が高まるにつれ、ビットコインネットワークはより堅牢になります。ビットコインを使うために、中央集権的な銀行と提携する取引所で法定通貨に戻す必要がなくなるからです。商店や企業によるビットコイン採用の広がりは、ある意味、検閲耐性の向上とみなすこともできます。先進国ではなく、途上国の商店や企業で考えてみてください。

事業者によるビットコイン決済の導入ハードルを下げるサービスは年々増えるでしょう。ビットコインを受け取った商店は、そのまま保有、あるいは即時に法定通貨に交換することを選べます。ビットコインを決済手段として導入する上での技術的ハードルは、時間の経過とともに確実に低下し続けます。

### グレシャムの法則

「悪貨は良貨を駆逐する」というのを聞いたことはありませんか？これがグレシャムの法則です。良貨（価値貯蔵機能に優れた貨幣）と悪貨（価値貯蔵機能に劣る貨幣）が併存する場合、人々は良貨を手元に残し、悪貨を使用する傾向があります。すると皮肉なことに、良貨は退蔵されるため、市場に流通するのは悪貨ばかりになります。

この現象は金銀複本位制の時代に何度も繰り返されました。金と銀の交換レートは国が定める固定レートでしたが、需給は刻一刻と変化します。需給に基づく市場レートから国定レートが乖離する度、一方が市場から姿を消しました。

具体例で見てみましょう：

「米国が金または銀の重量および純度で通貨ドルを定義する金銀複本位制を導入した当初、金と銀の交換レートは1対15と定められた。国際市場では、金 1 に対して銀 15.5 であったため、金の大半が国外に流出し、銀が事実上の本位貨幣となった。1834年、ドル金貨の金含有率が削減され、交換レートが 1 対 16 になると、今度は銀が国外に流出し、金が事実上の本位貨幣となった。」 

— 米国における金本位制の略史
<figcaption>議会調査局、2011</figcaption>

併存する貨幣の一方が市場から消える現象の裏では、2つの事象が起きています。

1つ目は、人は過小評価されているものは手放さない傾向があるため、国民による良貨（過小評価されている貨幣財）の貯め込みです。この場合、良貨は国内に留まりますが、日常の決済からは姿を消します。

2つ目は、海外の投資家による裁定取引です。例えば、国際市場での金と銀の交換レート金銀が 1 対 15.5 にも関わらず、米国では 1 対 15（銀に対して金がわずかに過小評価）の場合、ヨーロッパの投資家はアメリカ人に銀を売り、アメリカ人から金を買います。この取引はレートの乖離が是正されるまで続きます。数年後、数十年後には、米国は金の保有量を大幅に減らし、銀の保有量を大幅に増やすことになります。

1970年以降、米国の広義のマネーサプライは年率7%以上のペースで膨張しており、先進国はどこも同じような状況です。新興国の通貨膨張率（インフレ率）はこれよりはるかに高い傾向があります。

![図 米国の広義のマネーサプライ M2](/_images/a_look_at_the_lightning_network2_2.png)
<figcaption>セントルイス連邦準備銀行</figcaption>

一方、ビットコインのインフレ率は 1.8% を下回っており、数年後には 0.9% 未満、さらにその 4 年後には 0.4% 程度にまで低下します。ビットコインネットワークは、インフレ率が 0% になるまで 4 年毎に供給量を半減することで、規定の総供給量である 2,100 万ビットコインに徐々に近づくよう設計されています。また、他のブロックチェーンとは異なり、ビットコインブロックチェーンのノードは世界中に分散しています。このネットワークの分散性は、中央集権的な勢力がビットコインの供給スケジュールを変更することを極めて困難にしています。さらに、ビットコインのネットワーク効果はプルーフオブワークを採用するブロックチェーンの中でも群を抜いて高いことから、51% 攻撃やチェーンの巻き戻しのリスクは他のチェーンより低いです。

![ 図 ビットコイン総供給量とブロック報酬の年次推移](/_images/a_look_at_the_lightning_network2_3.jpg)
<figcaption>コインデスク</figcaption>

金やビットコインを蓄え、ドル、ポンド、円、ユーロ、元、ペソ、ナイラ、ルピーを使いたいと思うのはごく自然なことです。その結果、市場では減価する貨幣が流通する一方、増価する希少性の高い貨幣は退蔵され、ほとんど流通しなくなります。

この傾向は、自国通貨よりも健全な貨幣が資産とみなされ、こうした財に関するすべての取引が課税対象となる国ではより顕著です。実際、大半の国で、金やビットコインの交換手段としての利用は課税対象とされ、取得原価を上回る利益に税金がかかります。したがって、インフレ率が低く、取引に税金が課せられる金やビットコインは手元に置いておき、課税されない法定通貨を使うインセンティブが働きます。ただし、検閲耐性に優れた決済手段というビットコインの特性を活用したい場合は別です。

例えば、銀行口座を持てないアフガニスタンの女性たち、銀行口座が凍結されたロシアの反体制勢力、ナイジェリアの商人や活動家、資本を国外逃避させる中国の人々、ベネズエラ、イラン、パレスチナなどの難民、人口の 3 割しか銀行口座を持たないエルサルバドルの人々は、ビットコインを交換手段として使っています。先進国でも、Substack の有料購読や VPN の購入などオンラインサービスの決済で使用されています。そしてご存知の通り、初期の頃はダークウェブでの違法ドラッグの購入やランサムウェア攻撃の身代金支払いに用いられることもありました。

ビットコインを日常的に使う人権活動家の話を聞く機会が何度かありましたが、中でも、ナイジェリアの Feminist Coalition の共同創設者イレ・アデリノクンが2022年初めにノルウェーの国会議事堂で行ったスピーチは特に印象的でした。警察による暴力に抗議したことで銀行口座が凍結された際、自己管理可能で検閲耐性の高いビットコインに助けられたという内容でした。この件はニュースで知っていたものの、当事者本人が語る体験談はとても興味深く、彼女が置かれた状況をリアリティを持って感じることができました。

本来、グレシャムの法則は為替相場が人為的に操作されると出現する事象ですが、取引への課税など使用時のフリクションで使い勝手が悪くなる場合にも起き得ます。つまり、検閲耐性などビットコインの特性が求められない場面では、利便性の高い悪貨から使われます。

ビットコインのような自己管理可能な価値貯蔵手段、オープンかつ検閲耐性の高い決済システムは社会で有用であることは間違いありませんが、実際のアダプションは個々人が置かれた状況に依存します。ビットコインの交換手段への進化は、それ以外に選択肢がないためにビットコインを使わざるを得ない人々が推し進めることになるでしょう。

### 貨幣化プロセスと価格変動

財が貨幣へと進化する過程で、激しい価格変動を避けて通ることはできません。定義上、暴騰を経ずに財が時価総額をゼロから100万ドル、10億ドル、1兆ドル、数兆ドルに増やすことは不可能です。なぜなら、暴騰はユーザーベースの拡大、すなわち普及による財の増価そのものだからです。

暴騰は投機家を引きつけ、レバレッジ取引を増やし、需要を急増させます。新規参入者が途絶え、ハイレバレッジ投機家が投げ売りを余儀なくされると、価格は暴落に転じます。

ビットコイン保有者が人口の 0.001％ だった頃は、先行きが非常に不透明だった上、少数の大口保有者の売買が価格に多大な影響を与えたため、値動きが極めて荒く、投資には高リスクが伴いました。0.1% の人が保有するようになると、価格変動やリスクはやや低下したものの、依然高いことには変わりありませんでした。1% 以上の人が何らかの形で保有するようになった現在では、リスクや価格変動はまだ大きいものの、縮小傾向にあります。10% の人が保有する頃には、さらに小さくなるでしょう。

ビットコインのアーリーアダプターとは、ビットコインの特性を分析し、ネットワークに有用性を見出した人々です。第三者を信用する必要がないP2Pネットワークで自己管理可能な財、長期的な価格上昇が見込める財への投資と引き換えに、激しい価格変動を受け入れた人たちです。そして、ネットワーク参加者が増えるにつれ、財は徐々に貨幣へと進化します。

時折、「ビットコインへの新規参入者が途絶えたらどうなるのか？ねずみ講では？」と問われることがあります。

ビットコインがねずみ講に該当しないことは、以前こちらの記事で示した通りです。本来問うべきは、自己管理可能で希少性が高い、現在インフレ率 1.8% かつ将来それが指数関数的に低下する貨幣（ビットコイン）を、インフレ率 7% を上回る不健全な貨幣（法定通貨）に換えて半永久的に保有したいと考える人がどのくらいいるか、です。

ビットコインネットワークが稼働している限り、そのような人はごく少数でしょう。

むしろ、ビットコインを売却せず、もっと買い増したいと考える人が多いはずです。商店や企業でビットコインの受け入れが進めば、蓄えの一部を使うかもしれません。ビットコインが普及し、法定通貨とする法域が増えれば、ハードルはさらに下がります。将来的に安定収入が見込める人であれば、供給が無制限に急拡大するリスクのある法定通貨ではなく、供給上限のあるビットコインを貯めることを選ぶでしょう。

つまり、ビットコインネットワークが成功すれば、ビットコインを稼いで貯めて、たまに使う人が増えるはずです。これを実践する人は、もっと稼ぎたい、もっと貯めたいと思うようになり、また使う機会も増えるでしょう。こうして、ビットコインの自律的かつグローバルな経済圏が形成されます。これは、ビットコインが「貨幣」になることに他なりません。

ビットコイナーがよく使うミームが意味するのは正にこれです：

![図 ビットコインエコシステムで人気のミーム画像](/_images/a_look_at_the_lightning_network2_4.jpg)

ネオ：ビットコインを数百万ドルで売れる日が来るということか？
モーフィアス：そうではない。その時がくれば、もはや売る必要もないということだ。

ここまで理解できれば、ビットコインネットワークのリスクを分析、評価するために問うべき質問も自ずと分かるはずです。貨幣化プロセスを停止に追い込むような事象とは？保有者が長期的な価値貯蔵手段としてビットコインより他の財を選好するようになる要因は？保有者が売却を余儀なくされる状況とは？ネットワークの検閲や稼働停止につながる脅威とは？堅牢な交換手段、自己管理可能で携帯性に優れた価値貯蔵手段という機能を無効にする脅威とは？

「ビットコインを交換手段に進化させるライトニングネットワーク③」に続く。

### 著作権等について
[利用規約 A](http://lostinbitcoin.jp.testrs.jp/staging/copyright/#uaa)
