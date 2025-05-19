---
layout: post
title:  "Terraformコード"
date:   2025-05-19 11:50 +0900
categories: Tenable 
---

*こちらがコードです。*

```
terraform {
  required_providers {
    aws = {
      source  = "hashicorp/aws"
      version = "~> 4.16"
    }
  }
  required_version = ">= 1.2.0"
}

provider "aws" {
  region = "ap-northeast-1"
}

resource "aws_instance" "example" {
  ami           = "ami-0c3fd0f5d33134a76"  # Amazon Linux 2のAMI ID（東京リージョン）
  instance_type = "t2.micro"

  tags = {
    Name = "MyExampleInstance"
  }
}
```