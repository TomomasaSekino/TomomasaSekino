<div align="right">
  <a href="#english-version">🇺🇸 English</a> | <a href="#japanese-version">🇯🇵 日本語</a>
</div>

---

<h2 id="japanese-version">🇯🇵 日本語版</h2>

# 関野 智勝（Tomomasa Sekino）

**エンタープライズ基盤エンジニア｜テックリード・インフラアーキテクトポジションを志向**

IBM AIX／SAN を中心としたエンタープライズ基盤の設計・構築・運用改善に **20年以上** 従事。  
物理層（SAN・ストレージ・筐体）から論理層（OS・仮想化・監視・バックアップ）まで横断的に対応し、  
銀行・保険・製造などミッションクリティカル環境で「止めない基盤」を設計してきました。

現在は **AWS（SAA-C03取得済）** および **Terraform（IaC）** を活用したモダンな構成管理を実践中。  
長年培ったレガシー基盤の深い理解を武器に、**レガシーシステムのモダナイゼーションをテックリード・アーキテクトの立場から牽引するポジション** を目指しています。

---

## 🎯 志向するキャリア

レガシー環境（AIX／SAN／PowerVM等）の複雑な仕様を紐解き、  
AWS・Terraform・コンテナ技術を活用した **ハイブリッドクラウド移行やモダナイゼーションを最上流から設計・推進** する立場を志向しています。

これまでの経験の中でも、以下のような **自ら提案・方針策定し推進した実績** があり、  
テックリード・アーキテクトとしての素地を築いてきたと考えています。

- 監視運用の抜本的見直しを自ら提案・主導し、アラート精度を約98%改善（SRE推進）
- ジョブスケジューラー更改（SystemWalker → Hinemos）におけるジョブ移行方針の策定・実行
- 運用スクリプトのGitHub管理を提案・導入し、属人化排除と変更履歴の可視化を実現

---

## 🔧 技術スタック

| カテゴリ | 技術・製品 |
|---|---|
| **OS** | AIX、Linux（RHEL／SLES）、Windows Server、HP-UX、Solaris |
| **仮想化** | PowerVM、LPAR／dLPAR、LPM、VIOS／VIOC、vSphere |
| **HA／DR** | PowerHA（HACMP）、Zerto、DR設計・切替手順標準化 |
| **ストレージ／SAN** | エンタープライズストレージ設計・構築・運用、SANゾーニング設計、Cisco MDS FCIP |
| **監視** | IBM Netcool、IBM Tivoli Monitoring（ITM） |
| **バックアップ** | ISP（TSM）、Veeam |
| **SAP** | SAP Basis運用（CCMS、tp移送、SPS適用、HANAバージョンアップ）、SAPインフラ基盤運用（SLES／vSphere） |
| **自動化** | Shell（ksh／bash）、PowerShell、バッチスクリプト |
| **クラウド** | AWS（SAA-C03）、VPC・EC2・IAM・RDS |
| **IaC** | Terraform |
| **構成管理** | GitHub（運用スクリプト・設計成果物の変更履歴管理） |

---

## 🏆 主な実績

### ✅ SRE推進：監視運用の抜本的改善を主体的にリード（2018〜2023年、製造業 SAP基盤）
SAP基幹システム（SLES12系）のインフラ運用保守において、**自ら提案・主導** する形でSRE的アプローチを推進。  
- IBM Netcool の監視設定を全面的に見直し、**誤検知アラートを約98%削減**（月12時間以上の対応工数削減）
- 繰り返し発生する障害の根本原因分析・恒久対策を実施
- DR切替手順の標準化・定期検証の仕組み化
- 運用スクリプトの **GitHub管理を提案・導入** し、属人化排除・変更履歴の可視化を実現

### ✅ ジョブスケジューラー更改に伴うジョブ移行の方針策定・実行（2025年、製造業）
SystemWalker → Hinemos へのジョブスケジューラー更改において、**ジョブ移行の置換方針策定** から文字列置換スクリプト設計・バッチスクリプト修正・テストまでを担当。  
同時期のSubversionサーバー更改では、移行スクリプトを自作し **約6人月分の工数を削減**、ゼロ障害での本番移行を達成。  
再現性確保と属人化排除を設計方針として組み込んだ。

### ✅ Cisco FCIP による広域DR基盤の設計・構築（2023〜2024年、都市銀行）
Cisco MDS を用いたFCIP接続インフラの詳細設計・構築・テストを13ヶ月で完遂。  
- パラメータシート・ポート収容表・概要物理構成図・通信要件シートの作成
- 拠点別構築手順書・タイムチャート・構築チェックリストの整備
- 高トラフィック時の帯域・遅延評価を含む安定性検証を実施

### ✅ AIX 大規模LPAR環境の設計・構築（2014〜2015年、ネット銀行）
p740/p750 LPAR **200台規模** のエンタープライズ基盤を設計・構築。  
Storage SAN 環境設計・構築、バックアップデータ外部保管設計まで一貫して担当。

### ✅ NIM/TSMサーバー運用方式の最適化提案（2008〜2010年、公益法人）
NIM/TSMサーバーについて、**現行運用の方式から仮想化環境に最適化した方式に変更することを提案**。  
新方式の実装・運用手順書の作成まで一貫して担当。

---

## 📂 公開リポジトリ

### [🔗 hybrid-architecture-aix-to-aws](https://github.com/TomomasaSekino/hybrid-architecture-aix-to-aws)
IBM PowerVM／AIX 環境から AWS への移行設計書。  
20年以上のオンプレ経験を活かした **レガシー→クラウド移行のアーキテクチャ設計** の実践例。

### [🔗 aws-terraform-foundation](https://github.com/TomomasaSekino/aws-terraform-foundation)
再利用可能な Terraform モジュール集（VPC・サブネット・IAM）。  
エンタープライズ基盤設計のノウハウを **IaC として体系化** した実践例。

### [🔗 aws-serverless-wordpress](https://github.com/TomomasaSekino/aws-serverless-wordpress)
ECS Fargate + Aurora Serverless v2 を活用したサーバーレス WordPress 構成。  
コンテナ・マネージドDBを組み合わせたモダンなウェブ基盤の検証成果物。

### [🔗 Automation-Script](https://github.com/TomomasaSekino/Automation-Script)
インフラ運用における自動化スクリプト集（Shell／PowerShell）。  
属人化排除・再現性確保を意識した実用スクリプトを公開。

---

## 📜 保有資格

| 資格名 | 備考 |
|---|---|
| AWS Certified Solutions Architect - Associate（SAA-C03） | 取得済 |
| Cisco CCNA | 取得済 |

---

## 💼 キャリアサマリ

- **経験年数**：インフラエンジニアとして20年以上（2002年〜）
- **コア領域**：IBM AIX／SAN／PowerVM を中心としたエンタープライズ基盤の設計・構築・運用改善
- **強み**：レガシー環境の深い理解に基づくモダナイゼーション推進、HA/DR設計、SRE的アプローチによる運用改善
- **経験業種**：銀行・保険・製造・鉄道・通信（ミッションクリティカル環境）
- **志向**：テックリード・アーキテクトとして、レガシーシステムのモダナイゼーションと運用自動化を最上流から牽引

---

## 📬 お問い合わせ

転職・業務委託のご相談は、GitHub の Issue またはプロフィールページよりお気軽にどうぞ。

---
<br>

---

<h2 id="english-version">🇺🇸 English Version</h2>

# Tomomasa Sekino｜関野 智勝

**Enterprise Infrastructure Engineer｜Aspiring Tech Lead / Infrastructure Architect**

20+ years of hands-on experience designing, building, and improving enterprise infrastructure centered on **IBM AIX / SAN**.  
Proven ability to work across the full stack — from physical layer (SAN, storage, chassis) to logical layer (OS, virtualization, monitoring, backup) —  
delivering "zero-downtime" infrastructure in mission-critical environments such as banking, insurance, and manufacturing.

Currently practicing modern configuration management with **AWS (SAA-C03 certified)** and **Terraform (IaC)**.  
Leveraging deep legacy infrastructure expertise to pursue a **Tech Lead / Infrastructure Architect role driving legacy system modernization**.

---

## 🎯 Career Direction

Aiming to lead **hybrid cloud migration and modernization** from the most upstream design phases,  
drawing on deep knowledge of legacy environments (AIX / SAN / PowerVM) combined with AWS, Terraform, and container technologies.

Throughout my career, I have built a foundation for a Tech Lead / Architect role through **proactive proposals and initiative-driven execution**:

- Proposed and led a comprehensive overhaul of monitoring operations, achieving ~98% false-positive alert reduction (SRE initiative)
- Defined the job migration strategy for a job scheduler migration (SystemWalker → Hinemos) and executed end to end
- Proposed and introduced GitHub-based management of operational scripts, eliminating knowledge silos and enabling full change history visibility

---

## 🔧 Tech Stack

| Category | Technologies & Products |
|---|---|
| **OS** | AIX, Linux (RHEL / SLES), Windows Server, HP-UX, Solaris |
| **Virtualization** | PowerVM, LPAR / dLPAR, LPM, VIOS / VIOC, vSphere |
| **HA / DR** | PowerHA (HACMP), Zerto, DR design & failover procedure standardization |
| **Storage / SAN** | Enterprise storage design, build & operations, SAN zoning design, Cisco MDS FCIP |
| **Monitoring** | IBM Netcool, IBM Tivoli Monitoring (ITM) |
| **Backup** | ISP (TSM), Veeam |
| **SAP** | SAP Basis operations (CCMS, tp transport, SPS patching, HANA version upgrade), SAP infrastructure operations (SLES / vSphere) |
| **Automation** | Shell (ksh / bash), PowerShell, batch scripting |
| **Cloud** | AWS (SAA-C03), VPC / EC2 / IAM / RDS |
| **IaC** | Terraform |
| **Config Management** | GitHub (versioning of operational scripts and design artifacts) |

---

## 🏆 Key Achievements

### ✅ SRE Initiative: Proactively Led Monitoring Operations Overhaul (2018–2023, Manufacturing / SAP)
Proactively **proposed and led** an SRE-driven approach to infrastructure operations for an SAP core system (SLES12-based).  
- Overhauled IBM Netcool monitoring rules, reducing false-positive alerts by approximately **98%** (saving 12+ hours/month)
- Conducted root cause analysis and implemented permanent fixes for recurring incidents
- Standardized DR failover procedures and established a regular validation cycle
- **Proposed and introduced** GitHub-based management of operational scripts, eliminating knowledge silos and enabling change history visibility

### ✅ Job Scheduler Migration: Strategy Definition & Execution (2025, Manufacturing)
Defined the **job migration strategy** for a SystemWalker → Hinemos job scheduler migration, covering string replacement script design, batch script modifications, and testing.  
Concurrently led a Subversion server migration, building custom migration scripts that **eliminated ~6 man-months of manual work** and achieved zero-incident go-live.  
Designed with reproducibility and knowledge-sharing as core principles.

### ✅ Cisco FCIP Wide-Area DR Infrastructure Design & Build (2023–2024, Major City Bank)
Delivered full detail design, build, and testing of FCIP-based DR infrastructure using Cisco MDS over 13 months.  
- Created parameter sheets, port allocation tables, physical topology diagrams, and communication requirement documents
- Developed site-specific build procedures, time charts, and build checklists
- Conducted stability testing including bandwidth and latency evaluation under high-traffic conditions

### ✅ Large-Scale AIX LPAR Environment Design & Build (2014–2015, Internet Bank)
Designed and built an enterprise AIX environment with **200 LPARs** (p740 / p750).  
Covered Storage SAN design & build through to off-site backup data retention design — end to end.

### ✅ NIM/TSM Server Operations Optimization Proposal (2008–2010, Public Interest Corporation)
**Proposed a transition** from the existing NIM/TSM operations model to a new model optimized for virtualized environments.  
Handled implementation of the new model and creation of updated operations procedures end to end.

---

## 📂 Featured Repositories

### [🔗 hybrid-architecture-aix-to-aws](https://github.com/TomomasaSekino/hybrid-architecture-aix-to-aws)
Migration design reference for IBM PowerVM / AIX workloads to AWS.  
A practical **legacy-to-cloud architecture design** drawing on 20+ years of on-premises expertise.

### [🔗 aws-terraform-foundation](https://github.com/TomomasaSekino/aws-terraform-foundation)
Reusable Terraform modules for AWS infrastructure foundations (VPC, subnets, IAM).  
Enterprise infrastructure design know-how **systematized as IaC**.

### [🔗 aws-serverless-wordpress](https://github.com/TomomasaSekino/aws-serverless-wordpress)
Serverless WordPress architecture using ECS Fargate + Aurora Serverless v2.  
A validated modern web platform combining containers and managed databases.

### [🔗 Automation-Script](https://github.com/TomomasaSekino/Automation-Script)
Operational automation script collection (Shell / PowerShell).  
Practical scripts built to eliminate knowledge silos and ensure reproducibility.

---

## 📜 Certifications

| Certification | Status |
|---|---|
| AWS Certified Solutions Architect – Associate (SAA-C03) | Active |
| Cisco CCNA | Active |

---

## 💼 Career Summary

- **Experience:** 20+ years as an infrastructure engineer (2002–present)
- **Core Expertise:** Enterprise infrastructure centered on IBM AIX / SAN / PowerVM — design, build, and operations improvement
- **Strengths:** Driving modernization grounded in deep legacy knowledge, HA/DR design, SRE-driven operations improvement
- **Industries:** Banking, insurance, manufacturing, railway, telecommunications (mission-critical environments)
- **Direction:** Leading legacy system modernization and operational automation from the most upstream phases as a Tech Lead / Architect

---

## 📬 Contact

For job opportunities or consulting engagements, please reach out via GitHub Issues or my profile page.
