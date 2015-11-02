WLWブックマークレット
====

説明は[本家](https://github.com/syara-temp/wlw)をご覧ください。

## リリース情報

本ブックマークレットのリリース情報は次の通りです。

* Version 1.9.1 -> 2015.11.02 Released  
  * 全キャスト勝率(全員)に新キャスト「闇吉備津」までの新キャストの勝率が反映されるように変更しました。  
(以下本家ログ)  
* Version 1.9.0 -> 2015.08.30 Released  
  * 全キャスト勝率(全員)に新キャスト「大聖」と「かぐや」の勝率が反映されるように変更しました。  

## 注意制限

本ブックマークレットは、&copy;SEGA公式のツールではありません。Wonderland Warsのサービス提供ポリシー(ネガティブ要素の非公開)に反する可能性のあるツールです。

また、本機能を実現するために使用している技術から次のようなリスクがあります。内容を理解した上で、自己責任でご利用ください。何かトラブル等ありましても、こちらで責任を取ることはできません。

* JavaScriptによるHTMLの書き換えによるWonderland.NETの動作不良
* JavaScriptの本体が外部サイト(github)にあることから、利用者が認知し難いプログラムの改変  
* Cookieの書き換えによるWonderland.NETの動作不良  

## インストール  
    
<span style="color:red; font-size: 2rem;">本家wlwブックマークレットを利用していた方は再インストールが必要です。</span>

次の手順で、ブックマークを登録してください。

* 手順1. 適当なブックマークを作成します。
* 手順2. ブックマークの編集でURL部分を次のように書き換えてください。記述ミスを防止するため、コピー&ペーストを推奨します。  

(2015.11.02 Updated)  
```
javascript:(function(d,s){s=d.createElement('script');s.src='https://cdn.rawgit.com/Nucleareal/wlw-1/master/wlw-cast-custom.min.js';d.body.appendChild(s);})(document)
```  
* 手順3. [Wonderland.NET](https://wonderland-wars.net/)にアクセスし、マイキャスト> (キャスト選択)で全国対戦プレイデータの画面を表示してください。
* 手順4. 手順1,2で作成したブックマークを実行してください。  
* 手順5. 勝率や差分(赤字の括弧書き)が表示されたら準備完了です。※4,5  
※4: 初回は0を基準とした差分が値として表示され、0時でリセットされます。  
※5: ※4を回避したい人は、OSの日付を1日以上前に設定してから手順4を実施し、日付を元に戻してください。  

## 使い方

次の手順で、登録したブックマークを実行してください。

* 手順1. [Wonderland.NET](https://wonderland-wars.net/)にアクセスし、マイキャスト> (キャスト選択)で全国対戦プレイデータの画面を表示してください。  
* 手順2. インストールで登録したブックマークを実行してください。  
* 手順3. 勝率や差分(赤字の括弧書き)が表示されたら成功です。※6  
※6: 差分は毎日0時(正確には23時59分59秒)でリセットされます。

## モバイル版Chromeでのブックマークの実行方法

モバイル版Chromeでは、通常のブックマークからブックマークレットを実行することができません。  
次の手順で、登録したブックマークを実行してください。

* 手順1. URL欄に登録したブックマークの名称を入力してください。  
* 手順2. URLサジェストのリストに、登録したブックマーク名が表示されますので、登録したブックマーク名を選択してください。  

## 著者

(本家著者)
Wonderland Wars ワンダーランドウォーズ  
32ページ目 > [833 ID:GUHfLX0k0](https://github.com/syara-temp/wlw)

(引き継ぎ)
Nucleareal