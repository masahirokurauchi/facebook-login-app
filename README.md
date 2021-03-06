# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

# Note
 
-OmniAuthのGithub
https://github.com/plataformatec/devise/wiki/OmniAuth:-Overview

-google-oauth2のGithub
https://github.com/zquestz/omniauth-google-oauth2
 
# Information
  
手順	処理内容

* ①	Facebook（またはGoogle）での認証が開始される
* ②	Facebook（またはGoogle）側にリクエストが送られる
* ③	認証を経て、コントローラーにSNSに登録されている情報が返される
* ④	SNSの情報から、ユーザー情報のみを取得して、既存のユーザー情報と照合を行う
* ⑤	その照合結果から、今回SNSで認証されたユーザーが、すでにアプリケーションに登録されているユーザーなのか判断する
* ⑥	照合の結果、既存のユーザーが存在しない場合は、新規登録画面に遷移する
* ⑦	すでに同じ情報のユーザーがアプリケーションのDBに存在している場合は、ログイン処理を行う









