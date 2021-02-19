#アプリ名：Maps.Backpackers(http://ec2-52-195-10-177.ap-northeast-1.compute.amazonaws.com/)

・ガイドブックに載っていないローカル情報を共有できる旅アプリです。

#制作背景/問題意識

・個人的に自転車一人旅が好きなので、旅好きな人達がガイドブックに載っていないローカル情報を共有でき、コロナ禍で移動が制限された中でもオンラインで旅を追体験できるSNS型アプロケーションを制作しました。

#拘ったポイント

・「ユーザーがどうやったら使いやすいか」を考え、地図を使って感覚的に操作出来る工夫をしました。JavaScriptを用いて詳細画面に遷移した際に地名/住所から緯度経度を取得し、自動で地図上にピンを表示させる処理を取り入れました。

#使用技術

・PHP 

・Laravel

・JavaScript

・Vue.js

・MySQL

・Pusher

・AWS

・Google API ( Maps Javascript API / Geocoding API )

・Git / GitHub

#機能

・ゲストログイン

・管理ユーザ登録

・管理ユーザログイン

・いいね機能

・フォロー機能

・記事投稿

・記事一覧表示

・記事詳細表示

・地図情報表示(地名/住所からピンを自動検索)

・画像アップロード

・コメント機能

・編集/削除機能

・リアルタイムチャット機能

・レスポンシブデザイン(スマートフォン / タブレット)
