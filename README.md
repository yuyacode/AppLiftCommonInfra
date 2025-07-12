# Common Infrastructure

## 概要 (Overview)

本アプリケーションの全サービスが依存する、共有の基盤インフラを管理するリポジトリです。

## 管理している主要リソース (Managed Resources)

- ネットワーク
    - VPC
    - サブネット
    - インターネットゲートウェイ
    - NATゲートウェイ
    - Elastic IP
    - ルートテーブル
    - セキュリティグループ

- コンピューティング基盤
    - ECSクラスター

- ロードバランシング & DNS
    - Application Load Balancer (ALB)
    - ACM (SSL/TLS証明書)
    - Route53

- Database
    - RDS（Aurora MySQL）

- その他
    - 各種デプロイ用ロール

---

## 📗 Supplementary Material

-   [**設計に関する意思決定の記録 (Design Decisions)**](./DESIGN_DECISIONS.md)