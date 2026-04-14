# terraform-aws-basic

TerraformでAWSの基本インフラ（VPC）を構築するサンプルです。

## 構成
- VPC（10.0.0.0/16）
- Subnet（public）
- Internet Gateway

## 前提
- AWS CLI設定済み
- Terraformインストール済み

## 実行手順

```bash
terraform init
terraform plan