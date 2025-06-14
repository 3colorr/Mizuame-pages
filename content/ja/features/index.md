---
title: "機能"
description: ""
featured_image: "/images/MizuameLogo.png"
menu:
  main:
    weight: 2
---
# 目次
- 基本
  - [ノート](#ノート)
  - [ピン](#ピン)
  - [文字を黒くする](#文字を黒くする)
  - [ショートカットキーで開く](#ショートカットキーで開く)
- デザイン
  - [テーマ](#テーマ)
  - [ライトモード/ダークモード](#ライトモードダークモード)
- ノートアクション
  - [計算する](#計算する)
  - [Markdownで書く](#markdown)
- [その他の機能](#その他の機能)

# 基本

{{< figure src="/Mizuame-pages/images/demo-gif.gif" title="サンプル" >}}

# ノート
書いたノートはあなたのPCに保存されます。そのため、書いたノートはあなたの他のPCと共有できません。なぜなら、このアプリは高機能なノートアプリではないからです。

# ピン
あなたは「ピン」を使うことで、ノートを固定できます。  
これにより、ノートは常に他のウィンドウの前面に表示されます。

# 文字を黒くする
アプリのテーマによっては、ノートの文字色が黄色や緑色となり、人によっては文字が見えづらいときがあります。  
中には、文字の色が黒色となっているテーマもありますが、ほんの少しグレーとなっています。また、ノートの文字色は絶対にグレーが良いと考える方もいることでしょう。  
この設定では、アプリのテーマを無視して、ノートの文字色を黒色や暗いグレー、ふつうのグレーに変えることができます。  

# ショートカットキーで開く
ショートカットキーを使って、Mizuameを開くことができます。  

ショートカットキーは`デフォルトで無効`となっているので、必要な場合は設定の一般タブで利用したいショートカットキーを選択してください。  
次に、`[設定] > [プライバシーとセキュリティ] > [アクセシビリティ]`にMizuameを追加して、アクセシビリティ権限を許可してください。  
最後に、`Mizuameを再起動`してください。  

もしMizuameにアクセシビリティ権限を許可すると、キーが押されたかどうかを検出できるようになります。しかし、Mizuameはキー入力の履歴を一切保存せず、ネットワークを通じて送信することもありません。  

# デザイン

# テーマ
アプリのテーマを選ぶことができます。  
例えば、"White and Blue"、"White and Pink", "Light(Gray) and Mint" などです。
{{< figure src="/Mizuame-pages/images/sample-theme-image-blue.png" title="White and Blue" >}}
{{< figure src="/Mizuame-pages/images/sample-theme-image-pink.png" title="White and Pink" >}}
{{< figure src="/Mizuame-pages/images/sample-theme-image-gray.png" title="Light(Gray) and Mint" >}}

# ライトモード/ダークモード
{{< figure src="/Mizuame-pages/images/sample-light.png" title="ライトモード" >}}
{{< figure src="/Mizuame-pages/images/sample-dark.png" title="ダークモード" >}}

# ノートアクション
最初、ノートアクションはすべて無効になっています。  
あなたが使いたいと思ったノートアクションは、設定の一般タブで有効にできます。逆に、ノートアクションを使いたくなくなったときは、同じく一般タブで無効にできます。  

# 計算する
ノートに入力した数式を自動で計算します。  
ただし、`(`と`=)`で囲われた数式にしなければなりません。  
例えば`(1+2+3-6=)`と入力すると`(1+2+3-6= 0 )`と自動で計算されます。  
足し算以外にも、以下のような数式を計算できます
- 2+3-4+5
- 5*5-25
- 1+2*(3+4)/0.1
- (2+2)^2

初期設定では、数値は小数点以下3桁に四捨五入されます。四捨五入する桁数は0から9桁、または全て（38桁）の範囲で指定できます。これも設定の一般タブで変更できます。  

{{< figure src="/Mizuame-pages/images/demo-calculation.gif" title="'(' と '=)' で囲われた数式を自動で計算する" >}}

数式を再計算させたいときは、`=`と`)`の間にある計算結果を消してください。  
例えば`(1+2+3-6= 0 )`を`(1+2+3-7= 0 )`と数式を変えても自動で再計算されません。この場合は`(1+2+3-7=)`のように`0`とその前後の空白を消してください。  
なぜなら、このアプリが`(`と`=)`で囲われた部分を数式と判断し、自動で計算を行うためです。  
また、自動計算が行われるとカーソルの位置がノートの最後尾に移動するので、注意してください。これはアプリが抱えている問題の１つです。すぐに解決できないので、しばらくお待ちください。

最後に、すべての数式は計算できません。例えば、あなたが数学の宿題に取り組んでいて、0.3の0.5乗を計算しなければならないとしても、このアプリでは計算できません。  
数学の教科書かインターネット、関数電卓を使ってください。  

# Markdown
Mizuameは一部のMarkdown記法をサポートしています。  
つまり、利用できる記法と利用できない記法があります。  

{{< figure src="/Mizuame-pages/images/demo-markdown.gif" title="" >}}

「Markdownビュー機能」を有効にすると、メニューバーからノートを開いた際にMarkdownビューで表示されます。Markdownビューはプレビュー専用であり、ノートの編集はできません。  

編集を行うには、`メニューバーの「編集」（四角にペンのアイコン）`をクリックするか、Markdownビューの余白をダブルクリックしてください。  

{{< figure src="/Mizuame-pages/images/sample-markdown-menu-2.png" title="編集アイコン" >}}
{{< figure src="/Mizuame-pages/images/sample-markdown-double-click.png" title="Markdownビューの余白をダブルクリックする" >}}

編集が終わり再びMarkdownビューに戻るには、メニューバーの`「Markdownビュー」（Mの文字のアイコン）`をクリックします。  

{{< figure src="/Mizuame-pages/images/sample-markdown-menu-1.png" title="Markdownビューアイコン" >}}

**サポートしているMarkdown記法** 
以下のMarkdown記法はMizuameの「設定」>「ヘルプタブ」でも確認できます。

{{< figure src="/Mizuame-pages/images/header.png" title="ヘッダー" >}}
{{< figure src="/Mizuame-pages/images/bold-itaric-codeblock.png" title="太字、イタリック、コードブロック" >}}
{{< figure src="/Mizuame-pages/images/formula.png" title="数式" >}}
{{< figure src="/Mizuame-pages/images/list.png" title="リスト" >}}
{{< figure src="/Mizuame-pages/images/ordered-list.png" title="順序付きリスト" >}}

**サポートしていないMarkdown記法**
- サポートしているMarkdown記法に載っていない記法は、すべてサポートしていません。

**サンプル**
{{< figure src="/Mizuame-pages/images/sample-markdown-note.png" title="Markdownでノートを書く" >}}

{{< figure src="/Mizuame-pages/images/sample-markdown-view.png" title="Markdownビュー" >}}

# その他の機能
アプリの`「設定」（歯車のアイコン）`から、ノートのサイズや文字の大きさを変更できます。
{{< figure src="/Mizuame-pages/images/sample-bar-image.png" title="ピン、消しゴム、設定のアイコン" >}}

「隠しメニュー」（丸い3点リーダーのアイコン」からは、印刷やノートの書き出し、ノートの読み込みといったメニューリストが表示されます。
{{< figure src="/Mizuame-pages/images/hidden-menu.png" title="隠しメニュー" >}}

**ノートの書き出し**は、ノートの内容をファイルに書き出し、Macに保存することができます。  
このメニューを選択するとファイル保存画面が表示されるので、好きな場所に保存してください。  

**ノートの読み込み**は、Mizuameのノートの書き出し機能で書き出されたファイルを読み込むことができます。  
このメニューを選択するとファイル選択画面が表示されるので、読み込みたいファイルを選択してください。  

:bulb::bulb::bulb:  
ノートの読み込みを行うと、読み込んだ内容が現在のノートの最後に追加されます。  
