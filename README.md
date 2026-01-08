# Walmart データセットサンプル

<h2>1001件のWalmart商品のサンプルデータセット</h2>

![Walmart dataset header](https://github.com/bright-jp/Walmart-dataset-samples/blob/main/walmart-datasets.PNG)

1000件以上の商品のWalmartデータセットサンプルです。データセットは<b>Bright Data API</b>を使用して抽出されました。

<h2>この無料データセットに含まれるデータポイント:</h2>

* ```product_id```: 商品の一意識別子
* ```url```: 商品リンクを表すURL
* ```product_name```: 商品名
* ```final_price```: 商品価格
* ```currency```: 商品価格に使用される通貨
* ```sku```: 商品識別のためのStock Keeping Unit（SKU）
* ```image_urls```: 商品画像を表すURLの配列
* ```main_image```: メインの商品画像
* ```rating_stars```: 1つ星から5つ星までの評価分布を表すオブジェクト
* ```top_reviews```: ネガティブおよびポジティブレビューを含むトップレビューを表すオブジェクト。各レビューには評価とレビュー本文が含まれます
* ```available_for_delivery```: 配送可否を示すBoolean
* ```available_for_pickup```: 店頭受け取り可否を示すBoolean
* ```brand```: 商品ブランドを表すテキスト
* ```description```: 商品説明を表すテキスト
* ```specifications```: 商品仕様を表すオブジェクトの配列。各オブジェクトにはnameとvalueが含まれます
* ```category_name```: 商品に関連付けられたカテゴリ名
* ```category_url```: 商品に関連付けられたカテゴリリンクを表すURL
* ```root_category_name```: 商品に関連付けられたルートカテゴリ名
* ```root_category_url```: 商品に関連付けられたURLリンク
* ```related_pages```: 商品に関連付けられた関連ページの配列
* ```breadcrumbs```: パンくずリンクを表すオブジェクトの配列。各オブジェクトにはURLとnameが含まれます

ほかにも多数あります。

これは「Walmart Products (public data)」データセットから派生したサンプルサブセットです。このデータセットには<b>371,000,000社以上の企業</b>が含まれます。

利用可能なデータセットのファイル形式: <b>JSON, NDJSON, JSON Lines, CSV, またはParquet。必要に応じて、ファイルを.gzに圧縮できます</b>。

データセットの配信タイプの選択肢: <b>Email, API download, Webhook, Amazon S3, Google Cloud storage, Google Cloud PubSub, Microsoft Azure, Snowflake, SFTP</b>。

更新頻度: <b>単発、日次、週次、月次、四半期、またはカスタム</b>。

抽出されたデータポイントに追加できるデータエンリッチメント: <b>リクエストに基づきます。</b>

<b>[Walmartの完全なデータセットを入手する](https://brightdata.jp/products/datasets/walmart)</b>。

![Walmart dataset visual](https://github.com/bright-jp/Walmart-dataset-samples/blob/main/walmart-datasets-image.PNG)

<h2>Walmartデータセットのユースケースは何ですか？</h2>

<h3>1. 消費者市場インサイト</h3>

在庫不足、商品需要の急増、消費者の間での新たなトレンドを明らかにします。Walmartデータセットを活用することで、企業は在庫管理の最適化、補充プロセスの効率化、サプライチェーン全体の有効性向上につながる戦略的意思決定を行えます。

<h3>2. 競合ベンチマーキング</h3>

競合他社間で類似商品やカテゴリを比較することで、効果的な価格戦略を策定し、適応型の価格モデルを開発できます。Walmartデータセットは、最適価格の特定、価格差異の発見、データに基づく価格戦略の立案を導くための重要なインサイトを提供します。

<h3>3. ブランド認識分析</h3>

商品レビューと評価を分析して消費者のフィードバックを把握し、商材が市場の期待に合致していることを確認します。Walmartデータセットにより、企業は特定の商品やブランド全体に対する消費者センチメントを捉え、マーケティングおよび販売戦略の的確な調整を促進できます。

<h2>学術研究者およびNGO向けのWebスクレイピングツールとデータセットへの無料アクセス</h2>

Bright Initiativeは、さまざまな環境・社会的課題の推進に取り組む主要な大学・学部および研究者、NGOやNPOに対し、Bright Dataの<b>[Web Scraper APIs](https://brightdata.jp/products/web-scraper)</b>と<b>[すぐに使えるデータセット](https://brightdata.jp/products/datasets)</b>へのアクセスを提供しています。申請は<b>[こちら](https://brightinitiative.com)</b>から送信できます。