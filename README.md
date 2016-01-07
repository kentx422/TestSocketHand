現在の研究（内蔵照度センサを用いた複数モバイル端末間のハンドジェスチャインターフェイス）
====

![logo](https://github.com/kentx422/Resource/blob/master/img/hgili.png)
スマートフォンやタブレットなどに内蔵されている照度センサでハンドジェスチャインターフェイスを実現するシステム

## Description

ユーザは，拡張現実を用いた本システムを用いることで直感的に綺麗な字を書くことができるようになる．   
拡張現実は，HMDとモーションセンサ，ステレオカメラを用いて実現する． 
今回はHMDとしてOculus Rift，モーションセンサとしてLeap Motion，ステレオカメラとしてOvervisionを用いている．
  
拡張現実として表示する「手本となる文字」はモーションセンサで取得した腕を基準に表示位置を決め，ステレオカメラで取得した映像に重ねあわせてHMDに表示している．
Android Studioを用いており，主にjavaでプログラムの実装を行っている．

## Demo

[![demo](http://img.youtube.com/vi/B5FtMjj4ZDs/0.jpg)](https://www.youtube.com/watch?v=B5FtMjj4ZDs)

画像をクリックするとYoutubeに飛びます

##Equipment

* Android
* コンピュータ  

## Usage

1. モバイル端末を設置
2. モバイル端末の上でハンドジェスチャを実行
3. 他のモバイル端末と連動

## Author

松井健人
<kmatsui@mikilab.doshisha.ac.jp>
