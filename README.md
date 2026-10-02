# AWS Architecture Overview

AWSインフラ/クラウドシステムの紹介資料リポジトリです。

## 概要

本リポジトリでは、個人で利用しているAWSアーキテクチャの構成・設計に関するドキュメントや図を共有します。

## フォルダ構成

```
aws-architecture-overview/
├── README.md          # 本ファイル（リポジトリ全体のインデックス）
└── docs/
    └── <システム識別子>/ # システム毎の設計ドキュメントと構成図
        ├── README.md  # アーキテクチャ説明
        └── *.png      # 画面イメージ・AWS構成図
```

`<システム識別子>` は、下記「システム一覧」の「システム識別子」列の値（例: `django-so`）です。

## システム一覧

| 名称 | システム識別子 | 主な AWS サービス|
| --- | --- | --- |
| 共通費申請アプリ | [django-so](docs/django-so/) | EC2, S3, Lambda, CloudFront, Route53 など |

## 免責事項

本リポジトリに含まれる内容はあくまで個人に依るものであり、所属する組織、および団体とは無関係です。

---

🤖 Generated with [Claude Code](https://claude.ai/claude-code)
