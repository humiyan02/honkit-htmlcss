# 3章： 初期設定

---

### 🤔概要

このパートでは、サイト模写をするにあたって必要なvs codeの初期設定を行います。cssのメタ言語であるscssを利用することを推奨しています。



### 🎚️難易度・目安時間

- 難易度：レベル0
- 目安時間：20分
  



### ✏️手順書

-----



**1. githubでレポジトリの作成をする**

- 手順
  - （アカウント登録していない人は）[github](https://github.com/)に登録する
  - Create a new repositoryボタンを押す
  - Repository nameを記載
  - Privateを選択
  - Create repositoryを押し、レポジトリの作成完了



----



**2. git cloneする**

- 手順
  - vs codeでターミナルを開く
  - $ cd（ホームディレクトリへ移動）
  - $ cd desktop（デスクトップへ移動）
  - $ mkdir clone-web-site（フォルダを作成）
  - $ clone-web-site
  - 作成したレポジトリからURLをコピー
  - $ git clone URL（コピーしたURLを貼り付ける）
  - cloneしたフォルダをvs codeで開く



----





**3. 作業に必要なファイルやフォルダを作成する**

今回はあえてターミナルを使ってみましょう



- 手順
  - index.htmlの作成（index.htmlはレポジトリ直下に置きます）
  - cssフォルダの作成（この配下に.cssを格納します）
  - imgフォルダの作成（この配下に画像を格納します）



- ヒント
  - ターミナル上でフォルダを作成する時は、$ touch [フォルダ名]



----



**4.index.htmlの初期設定**

- 手順
  - Doctypeの宣言
  - htmlタグ・headタグ・bodyタグの記載
  - <html lang="ja>に設定
  -  head内でcharsetとtitleの指定
  - ブラウザを開き、タイトルが反映されているか確認



▼サンプルコード

```html
<!DOCTYPE html>
<html lang="ja">
  <head>
     <meta charset="UTF-8">
     <title>山田太郎のポートフォリオサイト</title>
   </head>
  <body>
  </body>
</html>
```



-----

**5.git add/push/commitする**

- 手順
  - $ git add .
  - $ git commit -m 'first commit!'
  - $ git push -u origin master
  - githubでpushされているか確認する



- 補足
  - commitは最初はなるべく細かく行いましょう。

----

**6.sassの導入**

- 手順
  - vs codeの拡張機能欄で「Sass」と検索しダウンロード
  - css/styles.scssを作成。styles.cssとstyles.min.scssが自動生成されます
  - head内に<link rel="stylesheet" href="css/styles.min.css">を指定

----

**7.画像アセットの準備**

- 手順

  - 事前にダウンロードした画像アセットをimg配下に格納

    

----

**手順8.セクションをdivやheaderでラップする**

- 手順
  - body内でセクション（大きなまとまり）をdivで囲う
    - headerとfooterはdivではなく、headerタグとfooterタグを使用する
  - ​	コードの視認性を上げるためにセクションの上下にコメントを記載する（任意）
  - divに対してはそれぞれclass名を記載する
  - heightとbackground-colorを仮で指定する
  - cssでそれぞれのセクションに対してbackground-colorとheightを指定するbodyに対してmargin: 0;を設定する。



### ✅チェック

- 
- 

