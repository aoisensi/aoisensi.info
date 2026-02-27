---
title: OMORIのMODのインストール方法
published: 2026-02-27
description: ''
image: ''
tags: ['Game', 'OMORI', 'Mod']
category: 'Info'
draft: false
lang: 'ja'
---

# 必要なもの

OMORIのMODで遊ぶには必ず[Steam版のOMORI](https://store.steampowered.com/app/1150690/OMORI/)が必要です。

他のSwitch版やXBox版では不可能です。

# MODのダウンロード

[mods.one](https://mods.one)から必要なMODファイルをダウンロードします。

[OneLoader](https://mods.one/oneloader)はMODローダーなので必ず必要です。

基本的に最新版を使うようにしてください。

<video controls preload="metadata" playsinline>
  <source src="/public/video/how-to-install-omori-mod/sb01.mp4" type="video/mp4"/>
</video>

# OneLoaderのインストール

ダウンロードしたOneLoaderのzipファイルを開きます。

SteamからOMORIを右クリックして「プロパティ」を開き、「インストール済み」タブから「参照...」ボタンを押してOMORIフォルダを開きます。 (以降このフォルダをゲームフォルダと呼びます)

OneLoaderのzipファイルの中身をゲームフォルダに貼り付けます。

ゲームフォルダの中の別のフォルダに貼り付けてしまわないように注意してください。

「ファイルを上書きするか」の警告が出れば正しい位置に貼り付けできています。

出てこなければなにか間違えています。

<video controls preload="metadata" playsinline>
  <source src="/public/video/how-to-install-omori-mod/sb02.mp4" type="video/mp4"/>
</video>

# OneLoader以外のMODファイルのコピー

OneLoader以外のあなたが入れたいMODファイルをゲームフォルダの`www/mods`の中に入れます。

元々`oneloader`フォルダが入っているはずです。

基本的には`.zip`ファイルをそのままコピーすればOKです。

MODを外したいときはその`.zip`ファイルをここから取り除くだけでOKです。

<video controls preload="metadata" playsinline>
  <source src="/public/video/how-to-install-omori-mod/sb03.mp4" type="video/mp4"/>
</video>

# 注意点

MODデータを遊ぶ前にかならず元のセーブデータをバックアップしてください。

セーブデータはゲームフォルダの`www/save`に保存されています。

もとの一切MODが入っていない状態に戻したいときはSteamからOMORIのプロパティを開き、「インストール済みファイル」から「ゲームファイルの整合性を確認」で元に戻すことができます。
