# terraform-aws-basic

Terraformを用いてAWSの基本的なネットワーク構成（VPC）を構築するサンプルです。

## 構成
- VPC（10.0.0.0/16）
- Public Subnet（ap-northeast-1a）
- Internet Gateway
- Route Table
- インターネット向けルート（0.0.0.0/0）
- Route Table Association

※ EC2を配置すればインターネット接続可能な構成

---

## 対象
- Terraformを学習中の方
- AWS環境をコード化（IaC）したい方
- 手動構築からTerraformへ移行したい方

---

## 実行手順
```bash
terraform init
terraform plan