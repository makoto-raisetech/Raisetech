# AWSコース第10回講義の受講

## CloudFormationを利用して第5回課題で作成した環境のコード化を行う。
- VPC,EC2,RDS,ALB,S3のテンプレートファイルを作成
- テンプレートはVSCodeを使用してYAML形式で作成
![CloudFormation](images10/CloudFormation1.png)

## テンプレートファイル
- ［VPC］(lecture10template/lecture10-VPC.yml)
- ［EC2］(lecture10template/lecture10-EC2.yml)
- ［RDS］(lecture10template/lecture10-RDS.yml)
- ［ALB］(lecture10template/lecture10-ALB.yml)
- ［S3］(lecture10template/lecture10-S3.yml)


## VPC、ネットワークの構築
- VPC
![VPC](images10/VPC1.png)
![VPC](images10/VPC2.png)

## EC2の構築
- EC2
![EC2](images10/EC2-1.png)
- EC2 SecurityGroup　
![EC2](images10/EC2-SG.png)

## RDSの構築
- RDS
![RDS](images10/RDS1.png)
- RDS SecurityGroup
![RDS](images10/RDS-SG-1.png)

## ALBの構築
- ALB
![ALB](images10/ALB1.png)
- TargetGroup
![TargetGroup](images10/TargetGroup1.png)

## S3の構築
- S3
![S3](images10/S31.png)
