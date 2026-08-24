# 関野 智勝 / Tomomasa Sekino

**Enterprise Infrastructure Engineer**  
**AIX / PowerVM / SAN / HA・DR / SAP / Hybrid Cloud / Legacy Modernization**

AIX / Linux / SAN / HA / DR を中心としたエンタープライズ基盤の設計・構築・運用・改善を20年以上担当してきました。

AIX / PowerVM を中心としたオンプレミス基盤から、SAP基盤、DR、仮想化、AWSを含むハイブリッド環境まで、既存システムの構成・運用を理解したうえでの **基盤更改・移行・モダナイゼーション** を主な専門領域としています。

主な実績：

- **最大200LPAR規模** のAIX基盤構築と技術リード
- SLES / vSphere 上の **SAP基幹システム43サーバー** の運用保守・改善
- **Cisco MDS FCIP** を用いた広域DR基盤の詳細設計・構築・検証

---

## 専門領域

### レガシー基幹システム更改・基盤移行

- AIX / Linux を中心とした基幹インフラ更改
- オンプレミスからクラウドを含むハイブリッド基盤への移行
- 既存構成・運用・依存関係を踏まえた移行設計と導入支援
- 導入手順、確認観点、差分管理の標準化

### AIX / Power Infrastructure

- IBM AIX
- PowerVM
- LPAR / dLPAR / LPM
- VIOS / VIOC
- PowerHA
- NIM
- SAN / Storage
- HA / DR

### SAP Infrastructure

- SAP Basis運用
- SLES / vSphere
- SAP HANA 2.0
- SPS / note適用
- V2V移行支援
- Ansible Tower / JP1を用いた運用自動化

### 運用改善・SRE・自動化

- 障害の根本原因分析と恒久対策
- 監視設定改善
- DR切替手順標準化
- バックアップ復旧検証
- Shell / PowerShell / Pythonによる自動化
- Git / GitHubによる構成管理
- TerraformによるInfrastructure as Code

---

## 代表実績

### 自治体ガバメントクラウド更改・導入品質改善

AWS本番環境、Nutanix検証・交替機環境、オンプレミスが混在するハイブリッド構成で導入品質を担当。

- 手順書の分岐不足、資材世代差、OS・Edge差異、資材コピー不全などを検出
- **12種類のバッチ突合とサム値確認**により構成差異を抽出・是正
- 問題発生時の切り分けと追加回避策を提案
- 手順分岐、確認観点、差分管理を標準化
- 担当範囲の導入作業を約3週間で完遂

### SAP基幹システム基盤

SLES / vSphere上のSAP基幹システム **43サーバー** のインフラ運用保守を担当。

- HANA 2.0バージョンアップ、SPS・note適用
- vMotion / Veeam / ZertoによるV2V移行の既存基盤側支援
- Ansible Tower / ASI / JP1による運用自動化
- 再発障害の根本原因分析と恒久対策
- Netcool等の監視設定改善
- DR切替手順の標準化・定期検証
- バックアップ復旧検証の強化
- 運用スクリプトのGitHub管理

### Cisco MDS FCIP DR基盤

Cisco MDSを使用したFCIP接続インフラの詳細設計・構築・テストを担当。

- パラメータシート、ポート収容表、物理構成図、通信要件の作成
- 拠点別構築手順・タイムチャート・チェックリスト作成
- 単体・結合テスト
- 高トラフィック時の帯域・遅延を含む安定性検証
- DR切替時の影響範囲を設計へ反映

### AIX 大規模LPAR基盤

IBM p740 / p750環境で **200LPAR規模** のAIX基盤構築を担当。

- メンバー2名の技術リード
- LPAR環境構築・設定
- 設計書作成
- テスト仕様作成・テスト実施
- 運用手順書作成

### AIX / Storage / SAN基盤

IBM Power Systems環境でAIX基盤とStorage / SANの設計・構築を担当。

- s824 VIOS / VIOCによる **50LPAR環境構築**
- Storage / SAN環境の設計・構築
- バックアップデータ外部保管設計

### Subversion / ジョブ基盤更改

Subversionサーバー更改とSystemWalkerからHinemosへのジョブ移行を担当。

- Subversion移行手順・データ移行スクリプト作成
- スクリプト・ジョブの棚卸し
- ジョブ移行の置換方針策定
- 文字列置換スクリプト作成
- バッチスクリプト修正
- テストおよび結果整理

---

## 現在の研究プロジェクト

### [AIX Engineering Intelligence Platform](https://github.com/TomomasaSekino/AIX-IaC-project)

AIX / PowerVM / VIOS / SAN / PowerHA を対象に、IaC・NIM・Promotion Pipeline・Evidence RAG・LLMを組み合わせ、AIX基盤エンジニアリングを **再現可能かつ学習可能なプロセス** へ変換する個人研究プロジェクトです。

**仮説 → 設計 → 実装 → 実機検証 → Evidence → 評価 → 設計更新**

というサイクルを基本とし、単なるIaCによる構築自動化ではなく、Power基盤の設計意図、AIXライフサイクル、検証Evidence、リリース昇格、LLMによる分析・学習までを一つのエンジニアリングプロセスとして扱います。

---

## その他の公開リポジトリ

<details>
<summary>Cloud / IaC 検証</summary>

### [hybrid-architecture-aix-to-aws](https://github.com/TomomasaSekino/hybrid-architecture-aix-to-aws)

IBM PowerVM / AIX環境からAWSへの移行を題材としたハイブリッドクラウドアーキテクチャ設計。

### [aws-terraform-foundation](https://github.com/TomomasaSekino/aws-terraform-foundation)

AWS基盤をTerraformで構成するIaC検証。

### [aws-serverless-wordpress](https://github.com/TomomasaSekino/aws-serverless-wordpress)

ECS Fargate / Aurora Serverless v2を利用したWordPress基盤アーキテクチャ検証。

</details>

---

## コア技術

| 領域 | 技術・製品 |
|---|---|
| Enterprise UNIX | AIX / Linux（RHEL / SLES） |
| Power Platform | PowerVM / LPAR / VIOS / NIM |
| HA / DR | PowerHA / Zerto / FCIP |
| Storage / SAN | Enterprise Storage / SAN / Cisco MDS |
| SAP | SAP Basis / SLES / HANA / vSphere |
| Cloud | AWS |
| IaC | Terraform |
| Automation | Shell / PowerShell / Python / Ansible Tower / JP1 |
| Configuration Management | Git / GitHub |

---

## 保有資格

- AWS Certified Solutions Architect – Associate（SAA-C03, 2026）
- Cisco CCNA

---

## 稼働条件

**2026年10月1日以降 稼働可能**

- 業務委託
- フルリモート
- 週4日または週5日

主な対象領域：  
**基幹システム更改 / 基盤移行 / レガシーモダナイゼーション / AIX / SAP基盤 / HA・DR / 運用改善・自動化**

---

## Contact

業務委託・技術案件に関するお問い合わせは、GitHub Issues からご連絡ください。

---

<details>
<summary>English</summary>

# Tomomasa Sekino

**Enterprise Infrastructure Engineer**  
**AIX / PowerVM / SAN / HA & DR / SAP / Hybrid Cloud / Legacy Modernization**

Enterprise infrastructure engineer with more than 20 years of experience designing, building, operating, and improving enterprise infrastructure centered on AIX, Linux, SAN, HA and DR.

My primary focus is modernization and migration of mission-critical legacy infrastructure, spanning AIX / PowerVM, SAP infrastructure, disaster recovery, virtualization and hybrid cloud environments.

### Highlights

- Built AIX infrastructure at **up to 200 LPAR scale** and served as technical lead
- Operated and improved a **43-server SAP infrastructure** environment on SLES / vSphere
- Designed, built and tested wide-area DR infrastructure using **Cisco MDS FCIP**

### Current Research

[AIX Engineering Intelligence Platform](https://github.com/TomomasaSekino/AIX-IaC-project) combines AIX / PowerVM / VIOS / SAN / PowerHA with IaC, NIM, promotion pipelines, Evidence RAG and LLM-assisted engineering.

### Core Expertise

AIX / PowerVM / VIOS / PowerHA / SAN / Storage / SAP / SLES / HANA / vSphere / AWS / Terraform / Shell / PowerShell / Python

### Certifications

- AWS Certified Solutions Architect – Associate (SAA-C03, 2026)
- Cisco CCNA

### Availability

Available from **October 1, 2026**  
Freelance / Full Remote / 4–5 days per week

### Contact

Please contact me through GitHub Issues.

</details>
