---
title: "ドキュメント"
description: "Mizuameの使い方"
featured_image: "/images/MizuameLogo.png"
menu:
  main:
    weight: 3
---
- [クイックスタート](#クイックスタート)
- [基本的な使い方](#基本的な使い方)
- [ヒント](#ヒント)
- [トラブルシューティング](#トラブルシューティング)

# クイックスタート
### インストール
MizuameをMacにインストールする方法は２つあります。  
- AppStore(おすすめ)
   1. [ここ](https://apps.apple.com/jp/app/mizuame/id6458394832?mt=12)をクリックまたはAppStoreで「Mizuame」と検索します
   1. AppStoreからダウンロードしてインストールします
- プロジェクトをビルド
   1. `git clone https://github.com/3colorr/Mizuame.git`
   1. Xcodeでビルドする

# 基本的な使い方
### ノートを書く
1. Mizuameを起動します
   - 起動後、メニューバーにMizuameのアイコンが表示されます
1. メニューバーにあるMizuameのアイコンをクリックしてノートを開きます
1. あなたは文字入力やそれらのコピー＆ペーストができます
   - ノートは自動保存されます
1. ノート以外の部分をクリックするとノートは閉じられます
   - もしMizuameを終了したい場合は、Mizuameのメニューにある電源アイコンをクリックします
   - [設定](#設定)セクションも確認してください

### メニュー
{{< figure src="/Mizuame-pages/images/sample-bar-image.png" title="Menu" >}}
- 電源アイコン
   - Mizuameを終了できます
   - コンテキストメニューからも終了できます
- ピンアイコン
   - ノートを開いたままにできます
- 消しゴムアイコン
   - ノートの内容をすべて削除できます
- 歯車アイコン
   - 設定を開きます
   - [設定](#設定)セクションも確認してください
- 丸い3点リーダーアイコン
   - 隠しメニューです
   - 印刷やノートの書き出し、ノートの読み込みといったメニューリストが表示されます
   - こちらも参照 [その他の機能]({{< ref "/features#その他の機能" >}})

### 設定
以下のタブがあります。  
- 一般
- ノート
- 印刷
- ヘルプ
- 情報

#### 一般タブ
以下のMizuameの動作を変更できます。  
- 保存中のメッセージを表示する/しない
- ノートを開いたままにする`ピン`の有効/無効
- テキストの色を黒色にする
- `ノートアクション`の有効/無効
   - こちらも参照 [機能: ノートアクション]({{< ref "/features#ノートアクション" >}})

#### ノートタブ
フォントサイズやノートのサイズ、テーマなどを変更できます。  
もし設定をリセットしたい場合は、画面下にあるリセットボタンをクリックします。  

#### 印刷タブ
以下の印刷設定を変更できます。  
- 余白
- 倍率（スケール）
- 上下左右の中央揃え

「余白」と「上下左右の中央揃え」は、印刷タブからのみ変更できます。  

#### ヘルプタブ
基本的な使い方とメニューの説明が載っています。  

#### 情報タブ
ライセンスや利用規約、プライバシーポリシー、連絡先が載っています。  

# ヒント
- Macの起動時にMiauameを起動させたいです
   - Macの`ログイン項目` -> `ログイン時に開く`にMizuameを追加してください

# トラブルシューティング
まだ準備できていません。  