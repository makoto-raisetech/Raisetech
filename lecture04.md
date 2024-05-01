# AWSコース第3回講義の受講

## VPCの作成
![VPC](images2/VPC.png)

## EC2の作成
![EC2](images2/EC2.png)

## RDSの作成
![RDS](images2/RDS.png)

## EC2インスタンスへのSSH接続
![EC2ssh](images2/EC2ssh.png)

## EC2からRDS(Mysql)への接続
![RDSconnect](images2/RDSconnect.png)

## セキュリティグループ
 1 EC2 セキュリティグループ
 * インバウンドルールでssh接続の許可
 * EC2からMYSQLへの接続許可
 ！[EC2-SG](images2/EC2-sg.png)

 2 RDS セキュリティグループ
 ![RDS-SG](images2/RDS-sg.png)


## サブネットグループ
 * RDSはプライベートサブネットに設定し、外部からのアクセスができないようにする。
 * パブリックサブネットにあるEC2からRDSにアクセスしてDBを操作する。
 ![RDS-subnet-gr](rds-ec2-db-subnet-group-4.png)
 ![subnet-gr1](subnet-group-4-1.png)
 ![subnet-gr2](subnet-group-4-2.png)
 ![subnet-gr3](subnet-group-4-3.png)
 
## 講義の感想
 * VPC、EC2、RDS の作成においてそれぞれ関連性のあるものを作成するのに時間を費やしてしまった。
 * 上記以外にもネットワーク関係の用語が多く出てきたため関連付けて把握する必要がある。
