# detergentlist
消毒に有効な家庭用洗剤のリスト

## これは何？
このリポジトリでは独立行政法人 製品評価技術基盤機構（NITE）が5月22日に発表した「[新型コロナウイルスに有効な界面活性剤を公表します。](https://www.nite.go.jp/information/osirase20200522.html)」の資料、および以後更新されている[リスト](https://www.nite.go.jp/information/osirasedetergentlist.html)をもとに有効と判断された界面活性剤を含む家庭用洗剤のリストを独自に[Googleスプレッドシートにしたもの](https://docs.google.com/spreadsheets/d/1YAuQPf4zmUP64ChGPbhTAuMqqsmbRy6T_R9jD16tyRA/edit?usp=sharing)から、簡易版をCSV形式にして公開しています。

Googleスプレッドシート版は価格やリンク先、リンク先へのQRコード、有効成分一覧などを行っていますので、合わせてご覧ください。  
https://docs.google.com/spreadsheets/d/1YAuQPf4zmUP64ChGPbhTAuMqqsmbRy6T_R9jD16tyRA/edit?usp=sharing

## 意義は何？
厚生労働省・経済産業省・消費者庁の特設ページでは、新型コロナウイルスの消毒（不活化）には、熱水やアルコール消毒液、次亜塩素酸ナトリウム水溶液、次亜塩素酸水などとともに、家庭用洗剤に使われる一部の界面活性剤が有効であることが紹介されています。  
流通量が多く、価格も抑えられ、入手性の高い家庭用洗剤を利用することは、家庭内感染や施設内感染を防ぐための消毒作業をコスト・入手可能性の点から容易にすると考えられます。  

## 内容
* forHomeFurniture_ja.csv
  * 住宅用洗剤のリストです
  * https://github.com/porolakka/detergentlist/blob/main/forHomeFurniture_ja.csv
* forKitchen_ja.csv
  * 台所洗剤のリストです
  * https://github.com/porolakka/detergentlist/blob/main/forKitchen_ja.csv

## 何を工夫した？
商品名と流通経路等の補足情報を分離、結合したセルの解除など（力技）

## 有効な界面活性剤とは？
* 直鎖アルキルベンゼンスルホン酸ナトリウム（0.1%以上）
* アルキルグリコシド（0.1%以上）
* アルキルアミンオキシド（0.05%以上）
* 塩化ベンザルコニウム（0.05%以上）
* 塩化ベンゼトニウム（0.05%以上）
* 塩化ジアルキルジメチルアンモニウム（0.01％以上）
* ポリオキシエチレンアルキルエーテル（0.2%以上）
* 純石けん分（脂肪酸カリウム）（0.24％以上）
* 純石けん分（脂肪酸ナトリウム）（0.22％以上）

※上記とは別に、次亜塩素酸水も有効と判断されています。   
> ・次亜塩素酸水（電解型/非電解型）は有効塩素濃度35ppm以上  
> ・ジクロロイソシアヌル酸ナトリウムは有効塩素濃度100ppm以上  
>　なお、今回の検証結果を踏まえると、  
>　次亜塩素酸水の利用に当たっては以下の注意が必要であることが確認されました。  
>　①汚れ（有機物：手垢、油脂等）をあらかじめ除去すること  
>　②対象物に対して十分な量を使用すること  
*出典：[NITE「新型コロナウイルスに対する消毒方法の有効性評価について最終報告をとりまとめました。～物品への消毒に活用できます～」](https://www.nite.go.jp/information/osirase20200626.html)*  

※アルコール消毒液は、当然ながら新型コロナウイルスに対しても有効です。
> ＜使用方法＞濃度70％以上95%以下（※）のエタノールを用いて拭き取ります。  
> (※) 60％台のエタノールによる消毒でも一定の有効性があると考えられる報告があり、70％以上のエタノールが入手困難な場合には、60％台のエタノールを使用した消毒も差し支えありません  
> ＜注意事項＞※アルコール過敏症の人は使用を控えてください。  
> ※引火性があります。空間噴霧は絶対にやめてください。  
*出典：[厚生労働省・経済産業省・消費者庁特設ページ「新型コロナウイルスの消毒・除菌方法について」](https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/syoudoku_00001.html)*

## 資料の更新日は？
10/15

## ライセンスは？
CC-BY-SA 4.0 国際  
ただし、リンク先のコンテンツは、リンク先の著作権表記に従ってください。

## 利用上の注意点は？
企業（メーカー、販売元、通販サイト）についての確認は行っておりません。  
ご自身で信用できる商品・価格であるかを確かめて購入してください。  
商品購入に伴うトラブルについての責任を資料作成者は負いません。

## 作業したのは？
Akira Ochiai (@porolakka)

## 変更履歴
v2の変更点は？	価格コムのアドレス、最安値、販売サイト、価格(欄のみ)を追加。価格コム最安値はスクレイピング。  
v3の変更点は？	NITEのリストが随時更新されたため、9月30日に公表されたリストをもとに再編集。商品画像列を削除、列順を変更、リスト追加日列を追加。  
v3.1の変更点は？	有効成分の列を作り、製品に該当する成分があれば確認できるよう変更。QRコード等を省略し、フィルターによる並べ替えができるシートを作成。  
v3.2の変更点は？	タイトルを変更。補足を追加。
