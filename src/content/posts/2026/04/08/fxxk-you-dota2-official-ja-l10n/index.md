---
title: 最近Valveのゲームに追加された公式日本語訳からくるモヤモヤとした気持ち
published: 2026-04-08
description: ''
image: ''
tags: ['game', 'translation']
category: 'Diary'
draft: false
lang: 'ja'
---

# Dota2と公式日本語訳

今から約1年ほど前、あれは確か2025年2月7日にDota2というゲームに公式の日本語訳が追加されました。

<iframe src="https://store.steampowered.com/widget/570/" frameborder="0" width="646" height="190"></iframe>

自分は10年以上前からこのDota2というゲームを遊んでいます。

この記事を書いているときにはプレイ時間は9621時間となっております。

もうすぐで5桁時間ですね。

さて、このDota2というゲームを作ったValveという会社、皆さんも御存知Steamを運営しているところなのですが。

今までは一部の国を除くほとんどのローカライズをボランティアを募集して翻訳作業をさせていました。

ストーリーが重要な一部のゲームは外部のゲーム専門のローカライズチームに委託していたのですが、Dota2は長らくボランティアによる翻訳でした。

つまり、今までDota2の日本語版は素人による翻訳だったのです。

# Dota2非公式日本語MOD

しかし、自分は活発に更新されない準公式日本語版に嫌気が差していました。

<iframe class="note-embed" src="https://note.com/embed/notes/n1e937d715c18" style="border: 0; display: block; max-width: 99%; width: 494px; padding: 0px; margin: 10px 0px; position: static; visibility: visible;" height="400"></iframe><script async src="https://note.com/scripts/embed.js" charset="utf-8"></script>

幸い、自分には多少のプログラムの知識があり、Source Engineの仕様もある程度認知していたので完全非公式の日本語化MODを作る決意をしました。

<iframe class="note-embed" src="https://note.com/embed/notes/n6fb6c94da3cd" style="border: 0; display: block; max-width: 99%; width: 494px; padding: 0px; margin: 10px 0px; position: static; visibility: visible;" height="400"></iframe><script async src="https://note.com/scripts/embed.js" charset="utf-8"></script>

そしてそれは実りました。

<iframe class="note-embed" src="https://note.com/embed/notes/nd2b02c7fc52a" style="border: 0; display: block; max-width: 99%; width: 494px; padding: 0px; margin: 10px 0px; position: static; visibility: visible;" height="400"></iframe><script async src="https://note.com/scripts/embed.js" charset="utf-8"></script>

そしてこのMODの更新は今でも続いています。

あれ、公式日本語訳が出たのに非公式の翻訳作業が必要なんですか？

つづく...

# 公式日本語化のただの感想

つづき...

もし、あなたが好きなゲームやメディアが今までボランティアによる翻訳しかなかったのに突然公式が翻訳を追加したらどう思いますか?

喜びますよね?

ですが、今回の公式日本語訳が自分の心に生み出したのは悲しみでした。

## 翻訳がモヤモヤする理由

それは、明らかに翻訳者がゲームに対するリスペクトを一切持っていないと感じたからです。

それどころか翻訳者はまともにゲームをプレイしたことがないでしょう。

日本語を英語に翻訳する、という作業はかなりよくできています。プロの仕業でしょう。

しかし、明らかにこのゲームとマッチした訳し方ではないところがこれでもかと見つかります。

いくつか紹介しましょう。

なお、下に行くほど自分のエゴが強くなっていきます。

### 1. 一部のヒーロー名の翻訳を失敗して放置されている

Anti-Mage, Lina, Kunkka, Queen of Pain

これらの4体のヒーローは公式日本語訳が追加された当初から英語のまま放置されています。

正確には、翻訳ファイルに日本語の名前と英語の名前を記述する欄があるのですが、この5体はそれを逆さまに書いています。

ゲームデータ内の翻訳ファイルを一部引用してみます。

``` 
    // Hero Names
    // The "__en" versions are for the "Classic Hero Names" option.  These are still separate tokens for languages that want to add compatibility annotations
    "npc_dota_hero_none:n"                           "--"
    "npc_dota_hero_none__en:n"                       "--"
    "npc_dota_hero_queenofpain:n"                    "Queen of Pain"
    "npc_dota_hero_queenofpain__en:n"                "クイーン・オブ・ペイン"
    "npc_dota_hero_antimage:n"                       "Anti-Mage"
    "npc_dota_hero_antimage__en:n"                   "アンチメイジ"
    "npc_dota_hero_antimage_persona1:n"              "Anti-Mage (Wei)"
    "npc_dota_hero_antimage_persona1__en:n"          "アンチメイジ （ウェイ）"
    "npc_dota_hero_kunkka:n"                         "Kunkka"
    "npc_dota_hero_kunkka__en:n"                     "クンカ"
    "npc_dota_hero_lina:n"                           "Lina"
    "npc_dota_hero_lina__en:n"                       "リナ"
    "npc_dota_hero_mirana:n"                         "ミラーナ"
    "npc_dota_hero_mirana__en:n"                     "Mirana"
    "npc_dota_hero_mirana_persona1:n"                "ミラーナ（ドラゴンの血）"
    "npc_dota_hero_mirana_persona1__en:n"            "Mirana (Dragon's Blood)"
    "npc_dota_hero_slardar:n"                        "スラーダー"
    "npc_dota_hero_slardar__en:n"                    "Slardar"
    "npc_dota_hero_lion:n"                           "ライオン"
    "npc_dota_hero_lion__en:n"                       "Lion"
```

人間なので失敗は誰にでもあります。 そこを攻めるつもりはありません。

ただ、こんな完全に初歩的なミス、1回だけでもゲームを起動してヒーロー一覧を見るだけで気づきますよね？

翻訳者はそれすらしていない証拠になります。

### 2. 公式翻訳なのに新パッチの日本語訳が当日に来ない

公式翻訳の一番のメリットであるゼロデイパッチがされません。

なんのためのお墨付きですか？

### 3. ゲームエンジンが日本語表記を完全にサポートしていない

悪いのは翻訳者だけでなくValve側にもあります。

完全に[これ](https://heistak.github.io/your-code-displays-japanese-wrong/)と同じ問題がDota2のゲームエンジンに長期間残っています。

これのせいで日本語でプレイしてもすべての漢字は中国語のものが表示されるし、一部の記号は正常に表示されません。

公式でサポートするならこれも解決してほしい。

### 4. コミュニティが築き上げてきた用語を完全に無視した

いくつか例を上げます。

| オリジナル		| 公式			|
|-----------------------|-----------------------|
| チャネリング		| 詠唱			|
| イリュージョン	| 分身			|
| 基本/強化ディスペル	| 通常/強ディスペル	|

__強ディスペルってなんやねん語感終わってるだろ。__

他にもたくさんあります。

これらを安易に変えることは既存のプレイヤーと新規プレイヤーとの間で語彙に差が生まれ混乱の元となります。

### 5. どうせ翻訳するのにカタカナばっかりはどうなの？

ヒーロー名をカタカナに翻訳するのはまだ良しとしましょう。

それでもスキル名をほぼ全部カタカナにするのはどうなんでしょうか。

__「エイコーンショット」ってなんだよどう考えても「どんぐりショット」のほうがいいだろ。__

__フードウィンクがどういうヒーローか知ってる？ エイコーンの日本人の認知率知ってる？__

### 6. カタカナばっかりはどうなの？と言ったな、あれは嘘だ。

絶対にDota2のヒーロー名アイテム名スキル名は**英語のまま**のほうがいいと思っている。

完全にこれは自分のエゴなんですが、100%これを推しているので、公式日本語訳が追加された今でも非公式のMODの作業を続けています。

#### カタカナ語は横に長い

カタカナは横に長い言葉です。

英語で1番横に長いヒーローは何だと思いますか。

`Keeper of the Light` です。長いですね。これをカタカナにしてみましょう。

`キーパー・オブ・ザ・ライト` 長すぎて税金を払う必要が出てきそうです。

`キーパー・オブ・ライト` 公式日本語訳では節税のためにこれになりました。

#### カタカナ語は通じない。

Dota2には日本人口がほとんどいません。

一緒の試合に日本人がいることはごくごく僅かです。

つまり、コミュニケーションの手段として日本語が使えないことが確定しているのです。

もし、日本語でプレイしているプレイヤーがこんなチャットを受け取ったらどうなるでしょうか。

**"hey cm can you buy eul?"**

辛うじて**cm**はクリスタルメイデンのことであるとわかるかもしれませんが**eul**が**ユールの聖セプター**であることには気付けないでしょう。

#### カタカナ語はダサい

突然ですが、日本人のあなたに聞きます。

どちらのほうがかっこよさそうに見えますか？

1. トレントの守護者

2. Treant Protector

自分は圧倒的にBです

古来より日本人は英語のままの固有名詞をデザインとして扱うことを受け入れて創作をしてきました。

たくさんの日本産のゲームが日本での発売向けにデザインとして英語を使って販売しています。

#### Dota2には一般的な名称が多い

たとえヒーロー名、アイテム名、スキル名であっても、Dota2には一般的な単語がそのまま

#### 英語のほうがイイ

他のゲームでも一部を英語のまま維持するゲームも存在します。

例えばRainbow Six Siegeなど。

Dota2も同様の理由で英語のほうが適切だと思います。

# とまあこんな感じで

この日本語翻訳のやる気のなさが続くようならば自分も非公式日本語訳をメンテし続けます

せめてどこが翻訳業務をしているかわかればなんとかコンタクトを取っていろいろできるのに...

それではこの変で

お暇～
S