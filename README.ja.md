[en](./README.md)

# Shell.StudentNameListGenerator.20200919160912

　クラス名簿をランダム生成する。性別も出力する。

# デモ

```sh
$ sn.sh
あおかわ	ひろのり	青川	拡規	M
あきみつ	たみ	秋光	多観	F
あらぜき	けんいちろう	荒関	腎一郎	M
いなわか	じゅんいち	稲若	純壱	M
いのした	しゅうき	伊下	秀騎	M
いやがわ	らくと	袰川	樂音	M
いりの	りわこ	入野	理和子	F
うつみ	よしのり	宇津美	啓典	M
えびす	まなは	胡	茉南葉	F
おかのはら	れいみ	岡野原	鈴心	F
おだて	しんご	小達	鎮吾	M
かくたに	いちたか	角谷	市多可	F
かわしり	まち	川尻	茉地	F
きたかみ	ひさの	北上	寿乃	F
きたもり	みすず	北守	實鈴	F
ぎおん	きりか	祇園	綺里香	F
こまいた	りみ	駒板	莉弥	F
さきにし	げんとく	崎西	源德	M
さばえ	れいな	鯖江	令依菜	F
さわら	たいぞう	佐原	太三	M
しのざき	ないる	篠崎	那伊留	M
しもきはら	さくほ	下木原	桜穂	F
しらにた	みなつ	白仁田	美菜津	F
すぎのした	しんぺい	杉之下	津平	M
すなわたり	きさら	砂渡	葵咲良	F
せいわ	みつる	生和	みつる	M
そとばた	ひわこ	外畑	陽和子	F
たにだ	とうしろう	谷田	登志朗	M
たのはら	らいな	田野原	来菜	F
ちくだ	つきみ	竹田	月弥	F
ぬのべ	にしき	布部	虹樺	F
ほうさか	めり	芳坂	愛里	F
ほそじま	しゅうほ	臍島	柊穂	F
まきじま	はやせ	牧島	颯瀬	M
まつしげ	じろう	松重	慈郎	M
みなみざわ	ひろのぶ	南澤	大伸	M
もなか	ともあき	茂中	朋明	M
ももじま	ともさと	百嶋	知郷	M
ゆみざ	しゅんのすけ	弓座	俊之亮	M
わりざや	げんすけ	割鞘	玄亮	M
```
```sh
$ time sn.sh
...
real	0m1.523s
user	0m0.047s
sys	0m0.048s
```

# 特徴

* 40人分の名前を出力する
    * フルネームである
    * 男女比1:1である
    * 性別を出力する

# 開発環境

* <time datetime="2020-09-19T16:09:10+0900">2020-09-19</time>
* [Raspbierry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 4 Model B Rev 1.2
* [Raspbian](https://ja.wikipedia.org/wiki/Raspbian) buster 10.0 2019-09-26 <small>[setup](http://ytyaru.hatenablog.com/entry/2019/12/25/222222)</small>
* bash 5.0.3(1)-release

```sh
$ uname -a
Linux raspberrypi 4.19.97-v7l+ #1294 SMP Thu Jan 30 13:21:14 GMT 2020 armv7l GNU/Linux
```

# インストール

```sh
git clone https://github.com/ytyaru/Shell.StudentNameListGenerator.20200919160912
```

# 使い方

```sh
cd Shell.StudentNameListGenerator.20200919160912/src
./run.sh
```

# 著者

　ytyaru

* [![github](http://www.google.com/s2/favicons?domain=github.com)](https://github.com/ytyaru "github")
* [![hatena](http://www.google.com/s2/favicons?domain=www.hatena.ne.jp)](http://ytyaru.hatenablog.com/ytyaru "hatena")
* [![mastodon](http://www.google.com/s2/favicons?domain=mstdn.jp)](https://mstdn.jp/web/accounts/233143 "mastdon")

# ライセンス

　このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

