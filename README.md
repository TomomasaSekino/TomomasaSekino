<div align="right">
  <a href="#english-version">🇺🇸 English</a> | <a href="#japanese-version">🇯🇵 日本語</a>
</div>

---

<h2 id="english-version">🇺🇸 English Version</h2>

# Hi there 👋 I'm Tomomasa Sekino
**Infrastructure Engineer / Tech Lead (Individual Contributor)**

With over 20 years of hands-on experience in designing, building, and operating mission-critical, large-scale on-premises environments (expert in IBM AIX), I am an infrastructure engineer dedicated to driving legacy system modernization and Digital Transformation (DX). 

Rather than stepping away from technology into pure people management, I thrive as a lifelong **Individual Contributor (IC) and Tech Lead**. I solve complex technical challenges by actively writing code, automating operations through SRE approaches, and integrating modern cloud technologies (AWS, IaC, and Containers).

---

## 📌 Current Focus

I am currently focusing on building modern cloud infrastructure and Infrastructure as Code (IaC), continuously updating my skill set:

- **✔ AWS Infrastructure Design**
- **✔ Terraform (IaC / Modularity / Environment Isolation)**
- **✔ Containers (Docker / ECS Fargate)**
- **✔ Hybrid Architecture (Bridging On-Premises and Cloud)**

---

## ⭐ Featured Repositories

Personal projects and PoCs focusing on IaC and Hybrid Architecture:

- **[Serverless WordPress on AWS (Terraform)](https://github.com/TomomasaSekino/aws-serverless-wordpress)**
  IaC sample deploying WordPress using ECS Fargate, ALB, and Aurora Serverless v2.
- **[AWS Terraform Foundation](https://github.com/TomomasaSekino/aws-terraform-foundation)**
  A foundational architecture with reusable Terraform modules and environment separation.
- **[Hybrid Architecture: AIX to AWS](https://github.com/TomomasaSekino/hybrid-architecture-aix-to-aws)**
  Design documentation and blueprints for migrating IBM PowerVM / AIX environments to AWS, focusing on hybrid networking.

---

## 🚀 Featured Achievements

### 1. Legacy Migration Automation & Modernization
Spearheaded the migration from a legacy commercial job management tool (SystemWalker) to Hinemos. I developed custom string-replacement and data-migration scripts from scratch, successfully automating the migration of 200 batch jobs and a Subversion environment (40 repositories, 100 users). 
**Result:** Reduced manual migration effort by approximately **6 man-months** and achieved **zero operational errors/incidents** during the cutover.

### 2. SRE Implementation & Toil Elimination in SAP Core Systems
Managed infrastructure operations for mission-critical SAP systems running on ~50 SLES12 VMs. I led the optimization of monitoring systems (Netcool) and transitioned the management of ~100 operational scripts to GitHub.
**Result:** **Reduced false-positive alerts by 98% (saving ~12 hours of manual troubleshooting per month)**, standardized operations, and completely eliminated toil and team silos.

### 3. Mission-Critical DR (Disaster Recovery) FCIP Infrastructure Build
To strengthen Business Continuity Planning (BCP), I led the detailed design, build, and testing of a large-scale DR network spanning 2 data centers using 29 FCIP routing devices.
**Result:** Successfully delivered the robust infrastructure on schedule over a 13-month project. Cleared stringent high-traffic stability tests, ensuring seamless data protection with zero major rollbacks during deployment.

---

## 🛠 Core Skills & Technologies

### Cloud & DevOps
- **Cloud**: AWS (VPC, ECS, ALB, RDS/Aurora, IAM)
- **IaC & Automation**: Terraform, Ansible (YAML)
- **Containers & CI/CD**: Docker, ECS Fargate, CI/CD concepts

### Automation, SRE & Tools
- **Scripting**: Shell Scripting (ksh / Bash), Python, PowerShell
- **Monitoring & Job Management**: Hinemos, Netcool
- **Version Control**: Git, GitHub (IaC / Script Management)

### Enterprise Infrastructure & OS
- **OS**: IBM AIX (pSeries, LPAR, PowerHA), SUSE Linux Enterprise Server (SLES), Windows Server
- **Virtualization**: PowerVM / VIOS
- **Enterprise Systems**: SAP Infrastructure, DR (Disaster Recovery) Architecture

### Storage, Backup & Network
- **Storage & SAN**: SAN (FC / FCIP), IBM Storage
- **Backup / DR**: TSM (Tivoli Storage Manager), Veeam, Zerto
- **Network**: Cisco Routing & Switching, TCP/IP

---

## 🏆 Certifications & 📈 Learning

**[ Certifications ]**
- AWS Certified Solutions Architect - Associate (SAA-C03)
- Cisco Certified Network Associate (CCNA)

**[ Currently Learning & Exploring ]**
- Advanced Security: CloudFront + WAF
- Secrets Management for IaC (AWS Secrets Manager)
- Logs & Monitoring Optimization
- Automated Documentation (via ChatGPT API)

---

## 📫 Contact

- **GitHub**: [@TomomasaSekino](https://github.com/TomomasaSekino)

---
<br> ---

<h2 id="japanese-version">🇯🇵 日本語版</h2>

# こんにちは 👋 関野 智勝です
**インフラエンジニア / テックリード（プレイングマネージャー・IC）**

20年以上にわたるミッションクリティカルな大規模オンプレミス環境（AIX等）の設計・構築・運用経験を土台に、レガシーシステムのモダナイゼーションとDX推進を牽引するインフラエンジニアです。
マネジメント専任ではなく、自ら手を動かして技術的な課題を解決する「生涯現役のスペシャリスト（IC）」として、SRE的アプローチによる運用自動化やクラウド技術（AWS / IaC / コンテナ）の導入に取り組んでいます。

---

## 📌 Current Focus

現在、モダンなクラウドインフラの構築とコード化（IaC）に注力し、継続的なスキルアップデートを行っています。

- **✔ AWS Infrastructure Design**
- **✔ Terraform (IaC / モジュール化・環境分離)**
- **✔ Containers (Docker / ECS Fargate)**
- **✔ Hybrid Architecture (On-Premises → Cloud)**

---

## ⭐ Featured Repositories

私が個人的に検証・実装しているIaCおよびハイブリッドアーキテクチャのサンプルです。

- **[Serverless WordPress on AWS (Terraform)](https://github.com/TomomasaSekino/aws-serverless-wordpress)**
  ECS Fargate + ALB + Aurora Serverless v2 で WordPress を動作させるIaCサンプル。
- **[AWS Terraform Foundation](https://github.com/TomomasaSekino/aws-terraform-foundation)**
  再利用可能なTerraformモジュールおよび環境分離のベースアーキテクチャ。
- **[Hybrid Architecture: AIX to AWS](https://github.com/TomomasaSekino/hybrid-architecture-aix-to-aws)**
  IBM PowerVM / AIX 環境からAWSへの移行、およびハイブリッド構成の設計書リポジトリ。

---

## 🚀 Featured Achievements

### 1. レガシー環境の移行自動化とモダナイゼーション
商用ジョブ管理ツール（SystemWalker）からHinemosへの移行において、文字列置換およびデータ移行スクリプトを自社開発。200本のジョブと40リポジトリ・100ユーザー規模の移行を自動化し、**約6人月の工数削減とオペレーションミス（障害件数）ゼロ**を達成しました。

### 2. SAP基幹システムにおけるSRE的アプローチとトイル撲滅
SLES12系で稼働する約50台のSAP基幹システム運用において、監視最適化（Netcool等）と運用スクリプト（約100本）のGitHub管理を主導。**不要なアラートを98%削減（月間約12時間の作業削減）**し、運用チームのトイル撲滅と属人化の排除を実現しました。

### 3. ミッションクリティカルなDR用FCIP接続基盤の構築
事業継続性（BCP）強化のため、2拠点間・計29台のFCIP装置からなるDR基盤の詳細設計・構築・テストを主導。13ヶ月のプロジェクトにおいて、高トラフィック時の安定性検証をクリアし、スケジュール遅延なく強固なインフラを確立しました。

---

## 🛠 Core Skills & Technologies

### Cloud & DevOps
- **Cloud**: AWS (VPC, ECS, ALB, RDS/Aurora, IAM)
- **IaC & Automation**: Terraform, Ansible (YAML)
- **Containers & CI/CD**: Docker, ECS Fargate, CI/CD concepts

### Automation, SRE & Tools
- **Scripting**: Shell Scripting (ksh / Bash), Python, PowerShell
- **Monitoring & Job Management**: Hinemos, Netcool
- **Version Control**: Git, GitHub (IaC / Script Management)

### Enterprise Infrastructure & OS
- **OS**: IBM AIX (pSeries, LPAR, PowerHA), SUSE Linux (SLES), Windows Server
- **Virtualization**: PowerVM / VIOS
- **Enterprise Systems**: SAP Infrastructure, DR (Disaster Recovery) Architecture

### Storage, Backup & Network
- **Storage & SAN**: SAN (FC / FCIP), IBM Storage
- **Backup / DR**: TSM (Tivoli Storage Manager), Veeam, Zerto
- **Network**: Cisco Routing & Switching, TCP/IP

---

## 🏆 Certifications & 📈 Learning

**【保有資格】**
- AWS Certified Solutions Architect - Associate (SAA-C03)
- Cisco Certified Network Associate (CCNA)

**【現在学習・検証中のテーマ】**
- CloudFront + WAF によるセキュリティ強化
- Secrets Manager for IaC
- Logs & Monitoring Optimization
- Automated Documentation (ChatGPT API)

---

## 📫 Contact

- **GitHub**: [@TomomasaSekino](https://github.com/TomomasaSekino)