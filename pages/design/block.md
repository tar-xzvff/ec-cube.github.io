---
title: ブロックの利用
keywords: design block customize
tags: [design]
sidebar: home_sidebar
permalink: design_block
summary: ブロックを利用したデザイン変更について説明します。
---

## ブロックの使い方
EC-CUBE3では2系と同様にブロック管理機能があり、用意されているブロックの配置を替えることでデザインの変更が可能です。  
また、新規にブロックを作成し、レイアウト管理から作成したブロックを配置することで容易にデザインの追加・修正を行うことが可能です。

1. ブロック管理の新規作成  
管理画面にログイン後、  
[コンテンツ管理] -> [ブロック管理] 画面より「新規入力」ボタンを押してブロックの内容を作成します。
![ブロック管理](/images/design/design-block-01.png) 
「新規入力」ボタンを押した後、
![ブロック管理](/images/design/design-block-02.png) 
ブロック名、ファイル名には任意の一意となる名称を入力し、ブロックデータには出力するhtmlを記述します。

1. ブロックの配置  
[コンテンツ管理] -> [ページ管理] 画面よりブロックを配置したいページの「レイアウト編集」を押して作成したブロックを配置します。
![ページ管理](/images/design/design-block-03.png) 
「レイアウト編集」を押した後、
![ページ管理](/images/design/design-block-04.png) 
未使用ブロック欄にある新しく作成したブロックをドラッグ&ドロップで適切な枠に配置します。

ブロックを作成、配置することによりデザインの変更が可能となります。  
ブロックの枠の位置をどのように定義されているかは[default_frame.twigの構成](/design_default-frame)を確認してください。