# AWSコース第6回講義の受講

## CloudTrailのイベント
* イベント名:CreateTrail
* 含まれている内容:"eventTime": "2024-07-05T10:48:38Z" 
                   "eventSource": "cloudtrail.amazonaws.com"
                   "awsRegion": "ap-northeast-1"
![CloudTrailイベント](images6/picture01.png)

## CloudWatchアラームを使ってALBのアラーム設定
* 対象：ALB/UnhealtyHostCount
![CloudWatchアラーム設定](images6/picture02.png)gity

## CloudWatchアラームメール通知
* OK→Alarmメールの受信
  Railsアプリケーションが使えない状態
![Alarmメール](images6/picture03.png)

* Alarm→OKメールの受信
　Railsアプリケーションが使える場合
![OKメール](images6/picture04.png)

## AWS利用料の見積もり
（https://calculator.aws/#/estimate?id=39298e88fa6867e7ee350c1bd094a24735dfb412）

## マネジメントコンソールから、現在の利用料を確認
* 2024年6月請求金額
パブリックIPアドレスの使用が無料枠を超えていたためVPCの料金が発生している。
![6月利用料](images6/picture05.png)
![6月利用料内訳](images6/picture06.png)

