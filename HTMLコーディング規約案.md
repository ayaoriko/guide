# HTMLコーディング規約案

## 環境
- PC:FireFox最新バージョン・Chrome最新バージョン・Internet Explorer 11~

- SP:Android 最新バージョン・iOS safari最新バージョン

- 
## コーディング

- インデントは半角スペース二個

- エンコーディングはBOMなしのUTF-8

- １行１要素

- 要素・属性・属性値は常に小文字

- 全角の空白を使わない

- `<!DOCTYPE html>`をつける

- `<p>`タグの中に`<h1>`タグなどのヘッダーを使わない

- クラスはタグのすぐ後ろ

- HTML内でスタイリングしない

  ```
  <p style="color:red;">あああ</p>
  ```

- マルチメディアにはaltをつける

  ```
  <img src="spreadsheet.png" alt="Spreadsheet screenshot.">

  ```

- 命名規則：悩んだ場合は_(アンダーバー)で。

- コメントは基本下の二つの形式。


  ```
  /*******************
  
    大コメント
    
  ********************/
  
  // 小コメント(スラッシュの前には空白)
  
  ```
  
- ヘッダーには以下のコードを最低限入れる。

  ```
  <head>
  <meta charset="UTF-8">
  <meta name="format-detection" content="telephone=no,address=no,email=no">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="description">
  <link rel="stylesheet" type="text/css" href="css/xxx.css">
  <title>タイトル</title>
   </head>
  ```




## 参考URL

[こんなHTMLとCSSのコーディング規約で書きたい](https://qiita.com/pugiemonn/items/964203782e1fcb3d02c3)

[ファイル名参考](https://html-coding.co.jp/cheatsheet/name/files.php)

## 


