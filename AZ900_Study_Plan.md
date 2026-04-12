# AZ-900: Microsoft Azure Fundamentals 学習計画

---

## 1. クラウドの概念 (25~30%)

### 1.1 クラウドコンピューティングとは
- [ ] クラウドコンピューティングの定義
- [ ] 共有責任モデル
- [ ] クラウドモデルの定義（パブリック、プライベート、ハイブリッド）
- [ ] 各クラウドモデルの適切なユースケース
- [ ] 従量課金モデル（消費ベースモデル）
- [ ] クラウドの価格モデルの比較（CapEx と OpEx）

### 1.2 クラウドサービスを使用する利点
- [ ] 高可用性（High Availability）
- [ ] スケーラビリティ（垂直スケーリングと水平スケーリング）
- [ ] 信頼性（Reliability）
- [ ] 予測可能性（Predictability）
- [ ] セキュリティとガバナンス
- [ ] 管理容易性（Manageability）

### 1.3 クラウドサービスの種類
- [ ] IaaS（Infrastructure as a Service）
- [ ] PaaS（Platform as a Service）
- [ ] SaaS（Software as a Service）
- [ ] IaaS / PaaS / SaaS の比較と適切なユースケース
- [ ] 各サービスモデルにおける共有責任モデル

---

## 2. Azure のアーキテクチャとサービス (35~40%)

### 2.1 Azure の主要なアーキテクチャコンポーネント
- [ ] Azure リージョン、リージョンペア、ソブリンリージョン
- [ ] 可用性ゾーン（Availability Zones）
- [ ] Azure データセンター
- [ ] Azure リソースとリソースグループ
- [ ] サブスクリプション
- [ ] 管理グループ（Management Groups）
- [ ] リソースグループ・サブスクリプション・管理グループの階層構造

### 2.2 Azure のコンピューティングサービスとネットワークサービス
#### コンピューティング
- [ ] Azure Virtual Machines（VM）
- [ ] Azure Virtual Machine Scale Sets
- [ ] Azure Virtual Desktop
- [ ] Azure Containers（Azure Container Instances）
- [ ] Azure Kubernetes Service（AKS）
- [ ] Azure Functions（サーバーレス）
- [ ] Azure App Service
- [ ] コンピューティングの種類の比較（VM / コンテナ / サーバーレス）

#### ネットワーク
- [ ] Azure Virtual Network（VNet）とサブネット
- [ ] Azure VNet ピアリング
- [ ] Azure VPN Gateway
- [ ] Azure ExpressRoute
- [ ] Azure DNS
- [ ] パブリックエンドポイントとプライベートエンドポイント
- [ ] Azure ネットワークセキュリティグループ（NSG）

### 2.3 Azure のストレージサービス
- [ ] Azure Storage アカウント
- [ ] Azure Storage の冗長性オプション（LRS / ZRS / GRS / RA-GRS / GZRS / RA-GZRS）
- [ ] Azure Blob Storage
- [ ] Azure Blob のアクセス層（ホット / クール / コールド / アーカイブ）
- [ ] Azure Files
- [ ] Azure Queue Storage
- [ ] Azure Table Storage
- [ ] Azure Disk Storage
- [ ] Azure のデータ移行オプション（AzCopy / Azure Storage Explorer / Azure File Sync）
- [ ] Azure Migrate
- [ ] Azure Data Box

### 2.4 Azure の ID、アクセス、セキュリティ
- [ ] Microsoft Entra ID（旧 Azure Active Directory）
- [ ] Microsoft Entra ID の認証方法（SSO / MFA / パスワードレス）
- [ ] Microsoft Entra External ID（B2B / B2C）
- [ ] Microsoft Entra 条件付きアクセス
- [ ] Azure のロールベースアクセス制御（RBAC）
- [ ] ゼロトラストモデル
- [ ] 多層防御（Defense in Depth）
- [ ] Microsoft Defender for Cloud

---

## 3. Azure の管理とガバナンス (30~35%)

### 3.1 コスト管理
- [ ] Azure のコストに影響する要因
- [ ] 料金計算ツール（Azure Pricing Calculator）
- [ ] 総所有コスト（TCO）計算ツール
- [ ] Azure Cost Management and Billing
- [ ] タグ（Tags）によるコスト管理
- [ ] Azure のコスト最適化の目的（Azure Reservations / Azure Spot VM など）

### 3.2 Azure のガバナンスとコンプライアンス機能
- [ ] Azure Blueprints
- [ ] Azure Policy
- [ ] リソースロック（Resource Locks）
- [ ] Microsoft Purview（Service Trust Portal）
- [ ] Azure のコンプライアンスとデータ保護の標準

### 3.3 Azure リソースの管理とデプロイのためのツール
- [ ] Azure Portal
- [ ] Azure Cloud Shell（Bash / PowerShell）
- [ ] Azure CLI
- [ ] Azure PowerShell
- [ ] Azure Arc
- [ ] Azure Resource Manager（ARM）
- [ ] ARM テンプレート / Bicep
- [ ] Infrastructure as Code（IaC）の概念

### 3.4 Azure の監視ツール
- [ ] Azure Advisor
- [ ] Azure Service Health
- [ ] Azure Monitor
- [ ] Azure Monitor アラート
- [ ] Application Insights
- [ ] Azure Log Analytics

---

## 試験直前チェックリスト

### 全体確認
- [ ] クラウドの概念（第1章）の全トピックを復習した
- [ ] Azure のアーキテクチャとサービス（第2章）の全トピックを復習した
- [ ] Azure の管理とガバナンス（第3章）の全トピックを復習した

### 重要ポイント
- [ ] 共有責任モデルの各レイヤーの責任範囲を説明できる
- [ ] IaaS / PaaS / SaaS の違いと具体例を説明できる
- [ ] リージョン・可用性ゾーン・リソースグループ・サブスクリプション・管理グループの階層を説明できる
- [ ] ストレージ冗長オプション（LRS / ZRS / GRS / GZRS）の違いを説明できる
- [ ] Microsoft Entra ID の主要機能（認証・条件付きアクセス・RBAC）を説明できる
- [ ] Azure Policy とリソースロックの違いを説明できる
- [ ] Azure Monitor / Advisor / Service Health の違いを説明できる
- [ ] コスト管理ツール（Pricing Calculator / TCO Calculator / Cost Management）の使い分けを説明できる

### 模擬試験
- [ ] Microsoft Learn の模擬試験を受験した
- [ ] 間違えた問題を復習した
- [ ] 苦手分野を特定し、再度学習した
