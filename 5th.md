# 5章：FVセクション

## 🤔概要

この章では簡易的なFV（1st view)を作成します。


<br/>

## 🏁成果物の確認

(z-indexまだ指定できていない。)

[![Image from Gyazo](https://i.gyazo.com/8876d17ead458c7ed0ceda0745a0b184.png)](https://gyazo.com/8876d17ead458c7ed0ceda0745a0b184)

[![Image from Gyazo](https://i.gyazo.com/6680e467ac63c26f7876cc0cafc493dc.png)](https://gyazo.com/6680e467ac63c26f7876cc0cafc493dc)

↑要素の重なりは上記の順番になります

<br/>

## 🎚️難易度・目安時間

- 難易度：レベル1
- 目安時間：30分

<br/>

## ✏️手順書

### Step1.必要な要素をindex.htmlに記載する

**🏁ゴールイメージ**

  [![Image from Gyazo](https://i.gyazo.com/9580f4f91df191238321c552922260a6.png)](https://gyazo.com/9580f4f91df191238321c552922260a6)

※ background-colorは仮で灰色に設定しています。

<br/>

**💡手順ヒント**

  1. h2とspanタグを使いましょう。

    <br/>

### Step2.cssでレイアウトを整える

**🏁ゴールイメージ**
- この時点では真ん中のフィルターは設置していません。

[![Image from Gyazo](https://i.gyazo.com/9bf3f3a0b7c696d8241adb17b9255128.jpg)](https://gyazo.com/9bf3f3a0b7c696d8241adb17b9255128)

  <br/>

**💡手順ヒント**
  1. background-imageと親要素のheightを設定。
  - h2のフォントサイズを調整し、文字色を変更する。
  - h2を上下中央揃えにする
    - 親要素に対してflexboxを設定してみる
    - aligin-itemsやjustify-contentを使ってみましょう



<br/>

### Step3.擬似クラスで背景のオーバレイ加工をする。

**🏁ゴールイメージ**

[![Image from Gyazo](https://i.gyazo.com/89ca4859ce05841e5b6eff54c23ed9f1.jpg)](https://gyazo.com/89ca4859ce05841e5b6eff54c23ed9f1)

<br/>


**💡手順ヒント**
  1. 擬似クラス（::before）を使用する
    - contentがない場合はどう表記するか思い出しましょう。
    - background-colorで配色をrgbaで指定すると透過できる。
    - 画面一杯に表示するためにposition:abusluteを使う。

<br/>

###  4.z-indexで重なりの順番を指定

メンタリングの際に確認



----

## ✅チェック

- 

