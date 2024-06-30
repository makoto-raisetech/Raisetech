# AWSコース第5回講義の受講

## EC2上にサンプルアプリケーションのデプロイ

* 組み込みサーバーだけで動作確認
![組み込みサーバー](images05/picture1.png)

* 組み込みサーバーとUnix Socketを使ったRailsアプリの動作確認 
![Unix Socket](images05/picture2.png)

* Nginxの単体起動確認
![nginx](images05/picture3.png)

* Nginxと組み込みサーバー、Unix Socketを組み合わせてのRailsアプリケーション動作確認
![nginxとpuma](images05/picture4.png)

## ELB経由でEC2への接続
* ロードバランサーの作成
![ロードバランサー](images05/picture5.png)

* ターゲットグループの作成
![ターゲットグループ](images05/picture6.png)

* 動作確認
![ロードバランサー接続確認](images05/picture7.png)

## データ保存先をS3へ変更
* S3バケットの作成
![S3バケット](images05/picture8.png)

* IAMロールの作成、EC2インスタンスにアタッチ
![IAMロールアタッチ](images05/picture9.png)

* S3に画像保存確認
![S3画像保存](images05/picture10.png)
![S3画像保存](images05/picture11.png)

## AWS構成図の作成
![AWS構成図の作成](images05/picture12.png)