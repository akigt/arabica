# Welcome to the arabica wiki!

## 概要

twitterのユーザが見ているタイムラインから、URLを抜き出して一覧表示するサービスを作ります。

## 背景

twitterは140文字の文化でさくっと確認できますが、中にURLが含まれているものはリンク先まで辿ってみるのは時間がかかり、大抵そのままスルーするか、starを付けるなりして後で参照します。
そこで、URLのみを収集して一覧表示することで、そのあたりの面倒さを解消します。

## 類似サービス

- retime.me
-- ネタ元
-- Oauth認証は一覧からユーザのツイートに対し更新処理ができるため?
- readtwit
-- 未使用 URLをあつめるだけなのに面倒そう。あと日本語じゃない
-- RSS出力してくれる
- tubuclip
-- メンテナンス中でUI確認できず→メンテナンスからは復帰。ホームは自分のタイムラインからURL付きのtweetを抽出して表示してるだけなので、一見ただのtwitterクライアント。スポーツとかカテゴリに分類してあるのが売りっぽいけど現状404となった。

## target browser

https://github.com/u1tnk/arabica/issues/8

chrome, firefoxではきちんと見えるようにする。
それ以外は余裕のあるとき。
