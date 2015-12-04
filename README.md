こまどり配列
========

キーボード中段（ホームポジション列）だけで日本語が入力ができ、拗音、促音、二重母音、撥音拡張機能を有する行段系日本語配列「こまどり配列」のGoogle日本語入力用設定ファイル（komadori.txt）。

入力方法の概要
--------

基本的な入力は、キーボードの中段（ホームポジション列）のみで行なう。

入力は２打鍵で行う。一打目で行（あかさたな）を指定し、二打目で段（あいうえお）を指定する。あ行の入力も二打鍵で行うことに注意。

二打目が一打目と異手の場合は清音が入力され、同手の場合は濁音（だくおん）、半濁音（はんだくおん）または捨て仮名（小書き文字）が入力される。

一打目で、ホームポジション列の代わりに、キーボード上の一列上、あるいは一列下のキーを打つことにより、それぞれ、拗音（ようおん）、促音（そくおん）を入力できる（拗音拡張、促音拡張）。

二打目で、ホームポジション列の一列上、あるいは一列下のキーを打つことにより、それぞれ、二重母音、撥音（はつおん）を入力できる（二重母音拡張、撥音拡張）。

一打目の拗音拡張・促音拡張はいずれも、二打目の二重母音拡張・撥音拡張と組み合わせることができるが、一打目の拗音拡張と促音拡張、二打目の二重母音拡張と撥音拡張はお互いと組み合わせることができない。

基本的な入力
------------

### 入力の基本

キーボード中段（ホームポジション列）にある、

       左手       |       右手
------------------|------------------
ａ　ｓ　ｄ　ｆ　ｇ|ｈ　ｊ　ｋ　ｌ　；

の１０文字のみで基本的な入力ができる。

一打目で、行（あ行～わ行）を指定し、２打目で、母音（あ段からお段）を指定する。

ａ  |ｓ  |ｄ  |ｆ  |ｇ  |ｈ  |ｊ  |ｋ  |ｌ  |；   
----|----|----|----|----|----|----|----|----|----
あ行|か行|さ行|た行|や行|わ行|な行|は行|ま行|ら行

や行とわ行のほかは、左手の小指から右手の小指へと「あかさたな」の順番で並んでいる。

ａ  |ｓ  |ｄ  |ｆ  |ｇ  |ｈ  |ｊ  |ｋ  |ｌ  |；
----|----|----|----|----|----|----|----|----|----
あ段|い段|う段|え段|お段|お段|え段|う段|い段|あ段

あ段からお段が小指から人差し指へと、「あいうえお」の順番で並んでいる。

### 清音の入力

二打目を一打目と異手にすることによって、清音を入力する。

例：　ｓ；　→　か    
　　　ｇｈ　→　よ    
　　　ｌｄ　→　む    
　　　ｋｆ　→　へ    
　　　ａｌ　→　い

### 濁音、小文字、半濁音の入力

二打目を一打目と同手にすることによって、濁音を入力する。

例：　ｓａ　→　が    
　　　ｋｊ　→　べ

あ行とや行には濁音がないが、代わりに捨て仮名が入力される。

例：　ｇｇ　→　ょ    
　　　ａｓ　→　ぃ

ま行（は行の一つ右）には濁音がないが、代わりに、ぱ行が入力される。

例：　ｌｋ　→　ぷ

###「ん」と「っ」の入力

「っ」は、「わ行う段の同手」で入力する。

例：　ｈｋ　→　っ

「ん」は「わ行う段の異手」で入力する。

例：　ｈｄ　→　ん

日本語を書くために必要な基本的な記号を「な行の同手」と「わ行の同手」に割り当てている。

例：　ｊｈ　→　「    
　　　ｊｊ　→　」    
　　　ｊｋ　→　、    
　　　ｊｌ　→　。    
　　　ｊ；　→　ー　（長音）　    
　　　ｈｈ　→　（    
　　　ｈｊ　→　）    
　　　ｈｌ　→　…   
　　　
> 基本的な入力方法については、キーボードの中段のみで日本語を入力できる「つばめ配列」( http://layout.kachoufuugetu.net/original/tsubame/ ）の考え方を全面的に採用しています。ただし、具体的な配置は異なります。

拗音拡張
--------

一打目で、ホームポジション列の代わりに、キーボード上の一列「上」のキーを打つことにより、拗音や外来音を入力できる。

例：　ｗ；　→　きゃ    
　　　ｏｄ　→　みゅ    
　　　ｗａ　→　ぎゃ    
　　　ｏｋ　→　ぴゅ

外来音の「ファ行」は、ら行拗音拡張の同手（りゃ行の同手）で入力できる。
「ティ」はた行拗音拡張異手の「い」の段、「ディ」と「デュ」はた行拗音拡張同手の「い」と「う」の段で入力できる。
「ヴァ行」と「ヴ」は、わ行拗音拡張の同手、「ウィ行」は、わ行拗音拡張の異手、「ツァ行」と「トゥ」は、や行拗音拡張の異手（た行拗音拡張の一つ右）、「ヅァ」行と「ドゥ」はや行拗音拡張の異手で入力できる。
外来音の「イェ」は拗音拡張ではなく、「や行え段」に配置している。

> 拗音拡張は、しゃ行とちゃ行について拗音拡張を備えるQWERTY系拡張ローマ字入力「AZIK」( http://hp.vector.co.jp/authors/VA002116/azik/azikinfo.htm )の仕様を参考にしています。

> 「ぢゅ」は現代仮名遣いでの入力には必須ではないため、定義していません。必要な場合は、「デュ」の位置を置き換えて定義するのが良いでしょう。

促音拡張
--------

一打目で、ホームポジション列の一列「下」のキーを打つことにより、促音「っ」を前置できる。

例：　ｘ；　→　っか    
　　　ｘａ　→　っが    
　　　．ｋ　→　っぷ

拗音拡張とは組み合わせることができない。

> 促音拡張は、か行、が行、さ行、ざ行、た行、だ行、は行、ば行、ぱ行でのみ定義しています。

二重母音拡張
--------

二打目で、ホームポジション列の一列「上」のキーを打つことにより、使用頻度の高い二重母音を入力できる。

入力される二重母音：    
　　　あ段　→　あい    
　　　い段　→　いい    
　　　う段　→　うう    
　　　え段　→　えい    
　　　お段　→　おう    

例：　ｓｐ　→　かい    
　　　ａｏ　→　いい    
　　　ｋｕ　→　べい    
　　　ｇｔ　→　ょう    
　　　ｌｉ　→　ぷう

拗音拡張、促音拡張と組み合わせることができる。

例：　ｗｐ　→　きゃい    
　　　ｘｐ　→　っかい
　　　
> 二重母音拡張は、母音用のキーの近くに二重母音拡張を配置しているAZIKの仕様を参考にしました。SKY配列も母音用のキーの上に二重母音拡張を配置しています。

撥音拡張
--------

二打目で、ホームポジション列の一列「上」のキーを打つことにより、「ん」を後置できる。

例：　ｇｎ　→　よん    
　　　ｋｍ　→　べん    
　　　ｇｂ　→　ょん

拗音拡張、促音拡張と組み合わせることができる。

例：　ｗ／　→　きゃん    
　　　ｘ／　→　っかん

二重母音拡張とは組み合わせることができない。

> 撥音拡張は、母音用のキーの一つ下に撥音拡張を備えるAZIKの仕様を採用しました。SKY配列も同様の仕様です。

単打拡張
--------
下段のキーのうち、撥音拡張で使わないもの（ｚｂｎｍ／）を使って、句読点、長音、撥音、促音を１打で入力することができる。句読点と長音は二打でも打ちやすく、撥音と促音は専用の拡張があるので、そこまで頻繁には使う必要はない。

例：　ｚ　→　ん  
　　　ｂ　→　、  
　　　ｎ　→　っ  
　　　ｍ　→　。  
　　　／　→　ー  

その他の入力
--------
### その他の記号類の入力

な行え段、お段同手（「」）の上下に引用に使用する括弧２種を配置している。

例：　ｊｙ　→　『  
　　　ｊｕ　→　』  
　　　ｊｎ　→　“  
　　　ｊｍ　→　”

わ行え段、お段同手「（）」の上下にその他の括弧２種を配置している。

例：　ｈｙ　→　【  
　　　ｈｕ　→　】  
　　　ｈｎ　→　［  
　　　ｈｍ　→　］


な行い段、う段同手（、。）の上下に各種の句読点を配置している。

例：　ｊｉ　→　！  
　　　ｊｏ　→　？  
　　　ｊ，　→　，  
　　　ｊ．　→　．

な行い段、う段同手（、。）の上下に各種の記号を配置している。

例：　ｈｉ　→　・  
　　　ｈｏ　→　：  
　　　ｈ，　→　←  
　　　ｈ．　→　→

な行お段及びわ行お段の上下に各種のダッシュと郵便記号を配置している。

例：　ｊｐ　→　〜　（波ダッシュ）  
　　　ｊ／　→　～  （全角チルダ）  
　　　ｈｐ　→　―　 （和文ダッシュその１(U+2015)）     
　　　ｈ／　→　――　（和文倍角ダッシュその１(U+2015 ２つ)）    

Uから始まる組み合わせにも若干の記号を配置している。

例：　ｕｈ　→　〈　（山括弧）  
　　　ｕｊ　→　〉  
　　　ｕｙ　→　《  
　　　ｕｕ　→　》  
　　　ｕｉ　→　⁉  
　　　ｕｏ　→　⁈  
　　　ｕｐ　→　—　（和文ダッシュその２(U+2014)）  
　　　ｕｎ　→　〔  
　　　ｕｍ　→　〕  
　　　ｕ／　→　—— （和文倍角ダッシュその２(U+2014 ２つ)）  

Qから始まる同手の組み合わせに、数学関連の記号を中心に収録している。

例：　ｑａ　→　＝　  
　　　ｑｓ　→　－  
　　　ｑｄ　→　＋  
　　　ｑｆ　→　＜  
　　　ｑｇ　→　＞  
　　　ｑｑ　→　≠  
　　　ｑｗ　→　／　  
　　　ｑｅ　→　×  
　　　ｑｒ　→　↑  
　　　ｑｔ　→　↓   
　　　ｑｚ　→　≒  
　　　ｑｘ　→　÷　  
　　　ｑｃ　→　＊  
　　　ｑｖ　→　≦   
　　　ｑｂ　→　≧   


### 特殊な数字の入力
一打目に特定の文字を打った後に、キーボード最上段の数字キーを打つことで、特殊な数字類を入力することができる。

#### 丸数字
ま行の「ｌ」（エル）を打った後に数字キーを打つことで、丸数字を入力できる。

例：　ｌ１　→　①  
　　　ｌ２　→　②  
　　　ｌ０　→　⑩
#### 漢数字
か行の「ｓ」を打った後に数字キーを打つことで、漢数字を入力できる。

例：　ｓ１　→　一  
　　　ｓ２　→　二  
　　　ｓ０　→　十
#### ローマ数字
ら行の「；」を打った後に数字キーを打つことで、全角のローマ数字を入力できる。

例：　；１　→　Ⅰ  
　　　；２　→　Ⅱ  
　　　；０　→　Ⅹ
#### かっこ付き数字
parenthesisの「ｐ」を打った後に数字キーを打つことで、全角の括弧のついた全角数字を入力できる。

例：　ｐ１　→　（１）  
　　　ｐ２　→　（２）  
　　　ｐ０　→　（１０）

### 漢字の直接入力拡張（漢直）

一打目をシフトして大文字を入力することで読みが該当する漢字を何十個か入力できる。音読みが多いが訓読みの場合もある。

例：　Ａｍ（えん）　→　円    
　　　Ｅ；（しゃ）　→　社  
　　　Ｐｔ（りょう）→　両  
　　　Ｓｐ（かい）　→　階

１音では表現できない漢字を、一打目と二打目を両方シフトし、複数の音の行をそれぞれとったキーを打つことで入力できる。

例：　ＤＬ（さま）　→　様  
　　　ＡＦ（あて）　→　宛

> 漢字の直接入力拡張を利用するとシフトキーを多用することになります。シフトキーは押しやすいキーではなく、ホームポジションも崩れてしまいますので、スペースバーにシフトキーを兼用させる（ http://semialt.hatenablog.com/entry/2014/04/26/022124 ）と良いでしょう。

### 単語，短文の直接入力

一打目と二打目を両方シフトすることにより入力できる、頻出単語や文字列、短文も若干ある。

例：　ＫＤ　→　平成  
　　　ＥＧ　→　昭和    
　　　ＳＥ　→　会社    
　　　ＬＤ　→　ます    
　　　＋Ｄ　→　お世話になっております。
　　　
###漢字等定義一覧

A; 亜, Ay 王, Au 英, Ap 愛, An 御, Am 円, A, 運, A. 印, A/ 案, Sa 我, Ss 偽, Sd 具, sf 下, Sg 後, Sh 個, Sj ヶ, Sk 区, Sl 貴, S; 可, Sq 外, Se 宮, Sr 芸, St 号, Sy 項, Su 計, Si 空, Sp 階, Sx 銀, Sc 郡, Sv 現, Sn 婚, Sm 件, S, 君, S. 金, S/ 感, Wg 魚, Wh 許, We 牛, Wt 行, Wu 強, Wi 級, Da 座, Ds 時, Dd 図, Df 是, Dk 酢, Dl 氏, D; 差, Dq 罪, Dr 税, Dt 増, Dt 総, Du 生, Di 数, Dp 才, Dz 残, Dx 人, Dv 前, Db 損, Dn 村, Dm 千, D. 新, D/ 産, Ed 樹, Eg 所, Eh 書, Ek 酒, E; 社, Ee 十, Et 条, Ey 証, Ei 州, Ec 準, E, 旬, Fa 打, Ff 出, Fg 度, Fh 都, Fj 手, F; 他, Fq 第, Ft 同, Fy 等, Fu 低, Fi 通, Fp 対, Fz 段, Fv 殿, Fb 丼, Fn 豚, Fm 点, F/ 単, R; 茶, Ry 町, Ri 中, Hz 湾, G; 屋, Gk 湯, Gi 有, Gy 用, Jf 根, Jg 野, Jq 内, Jt 能, Jz 何, Jx 人, Jv 年, Ka 派, Ks 非, Kd 付, Kg 補, Kk 部, K; 場, Kq 廃, Ke 風, Kt 法, Ky 某, Ku 米, Kp 倍, Kz 半, Kx 品, Kc 分, Kv 編, Kb 本, Kn 凡, Km 弁, K, 文, K. 便, K/ 番, It 表, Iy 秒, La 間, Ls 未, Ld 無, Lf 目, Lh 歩, Ll 否, Lq 枚, Lr 名, Lt 毛, Ly 方, Lp 杯, Lz 万, Lx 民, Lv 面, Lb 門, L/ 版, +a 裸, +s 里, +g 路, +q 来, +r 例, +z 欄, +v 連, +b 論, DL 様, FJ 殿, LJ 者, GY 頁, HF 私, KF 物, AS 億, AF 宛, GK 〒, S+ 頃, Qf 乙, SF 月, JF 日, SY 甲, GJ 乙, KR 丙, WS 局, G+ €, KD 平成, EH 昭和, SE 会社, DU 先生, DT 製造, KP 販売, SG 契約, SK 株式, DK 製品, EK 商品, KS 本件, F+ ドル, SD 漢字, SV 午前, SS 午後, FF 通知, DF 相当, EL 署名, JS 納期, FH 電話, SL 件名, AD 宛先, SV 貴殿, EJ	承認, SD 口座, LD ます, SH こと, FD です, D+ する, HD お世話になっております。

> 漢字や単語、文字列、短文の配置は実験的なものであり、変更されることがあります。ユーザーはこの定義にこだわる必要はありませんので、自分が使いやすい位置に頻繁に使う漢字を配置すると良いでしょう。

文責 semialt

ご意見・ご質問はGit Hub ( https://github.com/semialt/komadori )のIssuesかtwitter(@semi_alt)へどうぞ。
