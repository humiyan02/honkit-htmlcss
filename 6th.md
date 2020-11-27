# 6章：自己紹介セクション

## 🤔概要

この章では、自己紹介セクションを作成します。ヘッダーでは文字をホバーすると色が変わるCSSを設定しましたが、今回は画像をホバーすると色が変わる方法を実践できます。



<br/>

## 🏁成果物の確認
[![Image from Gyazo](https://i.gyazo.com/1e9f7b4936bae20e2c602ad91e63c3c1.gif)](https://gyazo.com/1e9f7b4936bae20e2c602ad91e63c3c1)
上のgihの様に画像にホバーすると色が変わるアイコンを作成しましょう。

<br/>

## 🎚️難易度・目安時間

難易度：レベル1<br/>
目安時間：30分

<br/>

## ✏️手順書



### Step1.必要な要素をindex.htmlに記載する

**🏁ゴールイメージ**

 [![Image from Gyazo](https://i.gyazo.com/fb162fbe29ce5668d7ea48941bb484b6.png)](https://gyazo.com/fb162fbe29ce5668d7ea48941bb484b6)


<br/>

**💡手順ヒント**

  1. 左右に配置するためにdivを2つ作りましょう。
  - 1つ目のdivはimgタグを入れ、src属性で画像を指定しましょう
  - 2つ目のdivはテキストとアイコン画像を挿入しましょう
    - アイコン画像はsvg画像をhtmlで設定しましょう。
    - 模写サイトのでィベロッパーツールからコピーできます。


 <br/>

### Step2.cssでレイアウトを整える

🏁ゴールイメージ
[![Image from Gyazo](https://i.gyazo.com/feb1ec037bb03df52066eff8599d27e6.png)](https://gyazo.com/feb1ec037bb03df52066eff8599d27e6)


<br/>

**💡手順ヒント**

  1. 親要素の余白を設定
  - 子要素のwidthとheightを指定
  - 親要素でflexboxを指定し、子要素を両端横並べにする
   - 両端にするにはjustify-contentで値を何にすればいいか？
  - アイコン画像を横並べにする
  - アイコン画像と画像の位置を揃える


<br/>

### Step3.svg画像の色をホバー時に変更する

**🏁ゴールイメージ**
[![Image from Gyazo](https://i.gyazo.com/1e9f7b4936bae20e2c602ad91e63c3c1.gif)](https://gyazo.com/1e9f7b4936bae20e2c602ad91e63c3c1)


<br/>

**💡手順ヒント**
  1. a要素がhoverしたときに色を変更する
   - 色の塗り潰しにはfill属性を使用する
  2. a要素にtransitionを設定し滑らかな滑らかなアニメーションにする
   - 構成要素
      1. transition-duration：○秒間かけて変化する？（単位はs/ms）
      2. transition-property：どこを変化させる？（ all / none / プロパティ名。）
      3. transition-timing-function ：どうやって変化させる？(ease-in-out etc..) 
      4. transition-delay：いつから変化させる？（ 単位はs/ms。）
         - transitionは上記4つを一括で指定できる

  <br/>  

**📰参考記事**
<br/>
https://developer.mozilla.org/ja/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions
https://qiita.com/7968/items/812d6a21fc4dd9ae9c75




 




## ✅チェック

- 
