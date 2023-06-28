---
title: ゲームのプレビュー
---
# ゲームのプレビュー

プロジェクトを開いたあと、GDevelop のツールバーから再生ボタンを押すといつでもプレビューを起動できます。

![](/gdevelop5/interface/preview/pasted/20200628-132309.png)
_左から順にプロジェクトマネージャーボタン、エクスポートボタン、再生ボタン、デバッグボタンです。_

再生ボタンを右クリックすると、他のオプションを選ぶこともできます。右隣のデバッグボタンからはネットワークプレビューも開けます。

再生ボタンをクリックするとプレビューが起動し、別のウィンドウが開いてそこでゲームを実行します。

![](/gdevelop5/interface/preview/pasted/20200628-152852.png)

## シーンのプレビューを起動する

再生ボタンのクリックで、ゲームのプレビューを起動できます。デフォルトでは、現在編集中のシーンから（あるいは何のシーンも開いていなければ、最初のシーンから）プレビューを開始します。

![](/gdevelop5/preview-button.png)

プレビューを開始すると、別のウィンドウを開きます。プレビューウィンドウを閉じるとゲームも終了します。

### ライブプレビューで最新の変更を反映する

プレビューでゲームを実行している最中に、再生ボタンをもう一度クリックすることにより、エディターで編集した最新の状態をプレビューに反映することができます。これはゲームをプレイしながらレベルをデザインするときなどにとても便利です。何かを変更したあと、毎回ゲームを再スタートしてレベルの最初からプレイし直す必要はありません。変更をすぐに反映し、画面でそれを見て、テストできます。

プレビュー中は再生ボタンのアイコンが変わり、変更をプレビューに反映できることを示します（これを「ライブプレビュー」、またはより専門的にいうと「ホットリロード」と呼びます）。

![](/gdevelop5/interface/preview/pasted/20200628-154642.png)

これをクリックすると、GDevelop は内部的にゲームを再生成し、プレビューを置き換えます。オブジェクトであれシーンであれ、レイヤー、変数、拡張機能、何であれすべての変更が、プレビューに反映されます。

![](/gdevelop5/interface/editing_a_level_with_live_preview.gif)

!!! tip

    これはゲームの何かを微調整するときに特に便利です。たとえば何かのエフェクトのパラメーターや、オブジェクトに追加したビヘイビアのプロパティを変更して、その結果をすぐに確認できます。またプレビューを最初からやり直さずに、イベントがどのように動作するかをチェックするときにも役に立つでしょう。

エディターの中には、プレビューを起動するか変更を反映するためのボタンを備えているものもあります。

![](/gdevelop5/interface/preview/pasted/20200628-162346.png)

クリックすると、使用中のエディターでおこなった変更がプレビューに反映されます。

特殊な状況下では、まれに GDevelop が変更をプレビューに反映できない場合があります。そのような場合は、プレビューを閉じて新しいプレビューを起動し直すようにうながすダイアログが表示されます。それとは別に、最初からプレビューし直さないといけない状況も考えられます。たとえば敵を破壊してしまって、それをもう一度やりたいような場合です。その場合はただウィンドウを閉じて、もう一度再生ボタンを押してください。

### 複数のライブプレビューを開始する

プレビューを実行中に再生ボタンを右クリックすると、新しいウィンドウで他のプレビューを起動するメニューが表示されます。

![](/gdevelop5/interface/preview/pasted/20200628-161539.png)

複数のプレビューを起動している状態で、再生ボタンをクリックして最新の変更を反映すると、すべての実行中のプレビューが更新されます。

### プレビューを開始するシーンをオーバーライドする

デフォルトでは、現在編集中のシーンからプレビューを開始します。他のシーンから開始したい場合は、いったん目的のシーンをエディターで開き、再生ボタンを右クリックして［プレビューはすべて、このシーンから開始する］を選びます。

![](/gdevelop5/interface/preview/pasted/20200628-151214.png)

プレビューの開始シーンが固定されていることを示す赤い旗がアイコンに追加されます。これで、エディターでどのシーンを開いているかと関係なく、プレビューの開始シーンが決まります。

この設定は、同じメニューからオプションのチェックを外すことで、いつでも解除できます。

![](/gdevelop5/interface/preview/pasted/20200628-152054.png)

## ネットワークプレビュー（WiFi/LAN 越しプレビュー）を起動する

［ネットワークプレビューを起動（WiFi/LAN 越しプレビュー）］ボタンを押すと、エディターと同じネットワークに接続したモバイル端末（あるいは他のコンピューター）上でゲームをプレビューできます。

![](/gdevelop5/interface/preview/pasted/20200628-133253.png)

ボタンをクリックすると、プレビューを起動する IP アドレスを示すウィンドウが表示されます。
![](/gdevelop5/preview-wifi-window.png)

この IP アドレスをスマートフォンのブラウザー（あるいは他のコンピューターのブラウザー）に入力します。するとプレビューが読み込まれます。

![](/gdevelop5/interface/preview-wifi-running.png)

これで IP アドレス用のポップアップウィンドウを閉じて、ゲームの編集に戻れます。プレビューを更新ボタンをクリックすると、ローカルコンピューター、他のコンピューター、タブレット、スマートフォンなど、すべての端末のプレビューが更新されます。

また端末のブラウザーの再読み込みボタンを押すと、プレビューを最初からやり直せます。


## デバッガーとプロファイラーを有効にしてプレビューを起動する

**デバッガー**はゲームの内容（変数の値、存在するインスタンスとそのプロパティなど）を調査するためのツールです。実行中のゲームのリアルタイム編集も可能です。**プロファイラー**はゲームのパフォーマンスを測定するツールです。

デバッガーは次のアイコンから起動できます。

![](/gdevelop5/interface/preview/pasted/20200628-133103.png)

デバッガーとプロファイラーの使い方について、くわしくは[このページを参照](/ja/gdevelop5/interface/debugger)してください。