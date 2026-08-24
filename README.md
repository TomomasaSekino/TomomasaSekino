# 関野 智勝 / Tomomasa Sekino

**Enterprise Infrastructure Engineer**  
**AIX / PowerVM / SAN / HA・DR / SAP / Hybrid Cloud / Legacy Modernization**

IBM AIX / SAN を中心に、20年以上にわたりエンタープライズ基盤の設計・構築・移行・運用改善に携わってきました。  
AIX / PowerVM / SAN / PowerHA などのオンプレミス基盤を中核に、SAP基盤、DR、仮想化、AWS、Terraformまでを対象として、既存基幹システムを理解した上での **基盤更改・移行・モダナイゼーション** を専門領域としています。

主な実績：

- **最大200LPAR規模** のAIX基盤を設計・構築
- SAP基盤の監視運用を見直し、**誤検知アラートを約98%削減**
- Subversion更改で移行スクリプトを作成し、**約6人月相当の作業を削減**

---

## 専門領域

### レガシー基幹システム更改・基盤移行・モダナイゼーション

長期間稼働してきた基幹システムについて、既存構成・運用・依存関係を把握した上で、基盤更改、クラウド移行、ハイブリッド構成への移行を設計・支援します。

### AIX / Power Infrastructure

- IBM AIX
- PowerVM
- LPAR / dLPAR / LPM
- VIOS / VIOC
- PowerHA
- NIM
- SAN / Storage
- HA / DR設計

### SAP Infrastructure

SLES / vSphere 上のSAP基幹システムで5年以上のインフラ運用保守経験があります。

- SAP Basis運用
- CCMS
- tp移送
- SPS適用
- HANA 2.0 バージョンアップ
- SAP基盤V2V移行支援

### 運用改善・SRE・標準化・自動化

- 障害の根本原因分析・恒久対策
- 監視設定改善
- DR手順標準化
- Git / GitHubによる構成管理
- Shell / PowerShell / Pythonによる自動化
- Terraform / AnsibleによるInfrastructure as Code

---

## 主要実績

### ガバメントクラウド更改案件（2026年）

NutanixとAWSを含むハイブリッド環境の更改案件において導入品質を担当。  
バッチ突合による構成差異の検出・是正、手順・確認観点・差分管理の標準化に取り組みました。

### SAP基盤運用改善 / SRE（2018〜2023年）

SAP基幹システムのインフラ運用保守において、監視運用の抜本的見直しを提案・実施。

- IBM Netcoolの監視設定を見直し、**誤検知アラートを約98%削減**
- 繰り返し障害の根本原因分析と恒久対策
- DR切替手順の標準化と定期検証
- 運用スクリプトのGitHub管理を提案・導入

### ジョブスケジューラー / Subversion更改（2025年）

SystemWalker → Hinemos のジョブ移行において、移行方針策定、置換スクリプト設計、バッチ修正、テストまでを担当。  
同時期のSubversionサーバー更改では移行スクリプトを作成し、**約6人月相当の作業を削減**、ゼロ障害で本番移行しました。

### Cisco MDS FCIP 広域DR基盤（2023〜2024年）

Cisco MDSを用いたFCIP接続インフラの詳細設計・構築・テストを担当。  
SAN、通信要件、拠点別構築手順、高トラフィック時の帯域・遅延を含む安定性検証まで実施しました。

### 大規模AIX基盤（2014〜2015年）

IBM Power Systems上で、p740 / p750を用いた **最大200LPAR規模** のAIX基盤を設計・構築。  
SAN / Storage、バックアップデータ外部保管設計まで担当しました。

### NIM / TSM運用方式最適化（2008〜2010年）

NIM / TSMサーバーについて、従来運用から仮想化環境に適した方式への変更を提案し、実装・運用手順作成まで担当しました。

---

## 現在の研究プロジェクト

### [AIX Engineering Intelligence Platform](https://github.com/TomomasaSekino/AIX-IaC-project)

AIX / PowerVM / VIOS / SAN / PowerHA を対象に、IaC・NIM・Promotion Pipeline・Evidence RAG・LLMを組み合わせ、AIX基盤エンジニアリングを **再現可能かつ学習可能なプロセス** へ変換する個人研究プロジェクトです。

研究サイクルは、

**仮説 → 設計 → 実装 → 実機検証 → Evidence → 評価 → 設計更新**

を基本としています。

単純にAIXをTerraformやAnsibleで操作することではなく、Power基盤全体の設計意図、AIXライフサイクル、リリース昇格、Evidence、LLMによる分析・学習を一つのエンジニアリングプロセスとして扱うことを目的としています。

---

## その他の公開リポジトリ

<details>
<summary>Cloud / IaC 検証</summary>

### [hybrid-architecture-aix-to-aws](https://github.com/TomomasaSekino/hybrid-architecture-aix-to-aws)

IBM PowerVM / AIX環境からAWSへの移行を題材としたハイブリッドクラウドアーキテクチャ設計。

### [aws-terraform-foundation](https://github.com/TomomasaSekino/aws-terraform-foundation)

AWS基盤をTerraformで構成するためのIaC検証。

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
| IaC | Terraform / Ansible |
| Automation | Shell / PowerShell / Python |
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

業務委託・技術案件に関するお問い合わせは、GitHubプロフィールよりお願いいたします。

---

<details>
<summary>English</summary>

# Tomomasa Sekino

**Enterprise Infrastructure Engineer**  
**AIX / PowerVM / SAN / HA & DR / SAP / Hybrid Cloud / Legacy Modernization**

Enterprise infrastructure engineer with more than 20 years of experience in designing, building, migrating, and improving mission-critical systems.

My core expertise is IBM AIX and enterprise infrastructure, including PowerVM, SAN, PowerHA, SAP infrastructure, DR, AWS and Infrastructure as Code. My primary focus is modernization and migration of legacy mission-critical infrastructure while preserving existing design intent and operational knowledge.

### Highlights

- Designed and built AIX infrastructure at **up to 200 LPAR scale**
- Reduced false-positive monitoring alerts by **approximately 98%** in SAP infrastructure operations
- Automated a Subversion migration and reduced work by **approximately six person-months**

### Current Research

[AIX Engineering Intelligence Platform](https://github.com/TomomasaSekino/AIX-IaC-project) combines AIX / PowerVM / VIOS / SAN / PowerHA with IaC, NIM, promotion pipelines, Evidence RAG and LLM-assisted engineering.

### Core Expertise

AIX / PowerVM / VIOS / PowerHA / SAN / Storage / SAP / SLES / HANA / vSphere / AWS / Terraform / Ansible / Shell / PowerShell / Python

### Certifications

- AWS Certified Solutions Architect – Associate (SAA-C03, 2026)
- Cisco CCNA

### Availability

Available from **October 1, 2026**  
Freelance / Full Remote / 4–5 days per week

</details>
