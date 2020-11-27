# 7章：スキル・経験セクション

## 🤔概要
この章では、テーブルレイアウトを実践します。


<br/>

## 🏁成果物の確認
[![Image from Gyazo](https://i.gyazo.com/5576f7d11bbc949430a48fada78e7de0.gif)](https://gyazo.com/5576f7d11bbc949430a48fada78e7de0)


<br/>

## 🎚️難易度・目安時間

難易度：レベル1<br/>
目安時間：60分

<br/>

## ✏️手順書



### Step1.必要な要素をindex.htmlに記載する

**🏁ゴールイメージ**
[![Image from Gyazo](https://i.gyazo.com/1037686368849166557bf226903e8414.png)](https://gyazo.com/1037686368849166557bf226903e8414)


<br/>

**💡手順ヒント**
  1. 余白の調節をするため、セクションタイトルとテーブルをラップするためのdivを2つ用意する
  2. セクションタイトルをh2で記載
  3. テーブルの内容の記載
   - 全体をtableで囲う
   - trで列を作る
   - １列目のtrの中にthを作成し、行の見出しを作る
   - ２列目以降のtrの中に、tdでデータを入れる

 <br/> 

**📰参考記事**
https://developer.mozilla.org/ja/docs/Web/HTML/Element/table

<br/>

 <br/>

### Step2.セクションタイトルの上下やセクションの両端の余白を調整する

**🏁ゴールイメージ**
[![Image from Gyazo](https://i.gyazo.com/2eb39ae90f6a5452ca061244f87a2613.png)](https://gyazo.com/2eb39ae90f6a5452ca061244f87a2613)


<br/>

**💡手順ヒント**

  1. 一番外側のdivに対して、余白を調節する
  2. セクションタイトルを中央に配置する
  3. セクションタイトルの上下の余白を調節する


<br/>

### Step3.テーブルのレイアウトを作成する

**🏁ゴールイメージ**
[![Image from Gyazo](https://i.gyazo.com/f63aeea45af52938d8292ed4178eaadb.png)](https://gyazo.com/f63aeea45af52938d8292ed4178eaadb)


<br/>

**💡手順ヒント**
  1. tableのレイアウト調整
   - widthを100％で指定
   - 背景色を指定
   - border-collapseで隣接するセルのボーダーを重ねて表示（http://www.htmq.com/style/border-collapse.shtml）
  2. trのレイアウト調整
   - borderの指定
   - hoverしたときの色を指定
  3. tdのレイアウト調整
   - 1行の幅を指定（100%/4）
   - テキストを中央揃え

  <br/>  

**📰参考記事**
<br/>
表（table）の作り方と装飾の変え方【HTML＆CSS】(https://saruwakakun.com/html-css/basic/table)



### Step4.それぞれの技術に対してアイコン画像を設置

**🏁ゴールイメージ**
[![Image from Gyazo](https://i.gyazo.com/5576f7d11bbc949430a48fada78e7de0.gif)](https://gyazo.com/5576f7d11bbc949430a48fada78e7de0)
<br/>

**💡手順ヒント**
  1. index.htmlで一つ目のtdに対してクラス名を振る
   - 共通のクラス名（レイアウト用）と個別のクラス名（画像指定用）の2つのクラス名
   - クラス名を2つするには？？
  2. 個別のクラス名に対してはbackground-imageを指定
  3. 共通のクラス名で余白やアイコンのサイズを指定
   - background-size: // 大きさを調整する
   - background-positon: // 位置を調節する
   - background-repeat: // 繰り返し表示しない様にする

  <br/>  

**📰参考記事**
<br/>
cssで見出しにアイコン画像を表示させる方法いろいろ（mhttps://www.emuramemo.com/entry/2014/09/13/145432）





## ✅チェック

- 
