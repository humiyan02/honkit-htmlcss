# 4章： ヘッダーセクション

---



### 🤔概要

この章では簡易的なヘッダーの作成をしていきます。

- ul/liの横並び
- boxモデル（margin/padding)
- flexbox
- 擬似クラス（hover）

等を実践できます。



### 🏁成果物の確認



[![Image from Gyazo](https://i.gyazo.com/b7e1a6999eded1b15bba6492e30fa505.gif)](https://gyazo.com/b7e1a6999eded1b15bba6492e30fa505)



- シンプルなヘッダーを作成できます

- ナビゲーションにカーソルを当てると色が変わります。



### 🎚️難易度・目安時間

- 難易度：レベル1
- 目安時間：30分
  



### ✏️手順書

-----



**1.必要な要素をindex.htmlに記載する**

- ゴールイメージ

  [![Image from Gyazo](https://i.gyazo.com/2f23946a792bcb23f3404624d9832616.png)](https://gyazo.com/2f23946a792bcb23f3404624d9832616)

- 手順ヒント

  - header内にはタイトルとナビゲーションの2週類のまとまりあります。後々レイアウトを整えるために

    - タイトルをdivで囲いましょう。

    - divに対して任意のclass名を指定しましょう。

    - ナビゲーションをnavで囲いましょう。 

      ```html
      <header>
      　<div class="header_title">
      　</div>
      　<nav>
      　</nav>
      </header>
      ```

    - タイトルをh1とaで記入しましょう。
      - a要素を使うのはタイトルを押すとホームに戻るようにするためです。
      - この時点でhref属性は#で大丈夫です。
    - ナビゲーションをul/li/aで記入しましょう





-----

 **2.cssでレイアウトを整える**

- ゴールイメージ

[![Image from Gyazo](https://i.gyazo.com/0253ff847e59ccf0f5c1c70447f28a5b.png)](https://gyazo.com/0253ff847e59ccf0f5c1c70447f28a5b)

※都合上background-colorを灰色にしています。



- 手順ヒント
  - headerに対してpaddingで左右の余白を調整 
  - headerに対してflexboxを使用し子要素（タイトルとナビゲーション）を左右に横並びにする。
  - ulに対してflexboxを使用し、子要素（li要素）を横並びにする
  - liststyleを無くす
  - li間の余白をmarginで調整し、テキストスタイルを整える。 
    - margin-leftにするか？margin-rightにするか考えてみてください。



----

**3.その他の設定**

- ゴールイメージ

[![Image from Gyazo](https://i.gyazo.com/b7e1a6999eded1b15bba6492e30fa505.gif)](https://gyazo.com/b7e1a6999eded1b15bba6492e30fa505)



- 手順ヒント
  - li aに対してホバー時に色を変更する
  - ヘッダーを固定化する
  - ページ内リンクを設定する index.html（例）





### ✅チェック

- 
- 

