# 👋 こんにちは、関野 と申します — AIX / UNIX 基盤エンジニア

AIX / UNIX を中心に **20年以上**、エンタープライズ向けインフラの  
設計・構築・運用・更改プロジェクトに従事してきました。

PowerVM（LPAR / dLPAR / LPM）、HA、SAN、バックアップ、監視など  
ミッションクリティカルなシステムの安定稼働を支える基盤技術に強みがあります。

現在は AIX で培った深いインフラ知識をベースに、  
**AWS・自動化・クラウドネイティブ技術の習得**を進めており、  
レガシーとモダン基盤をつなぐ存在として価値提供を目指しています。

---

## 🧩 強み（Strengths）

### 🔹 AIX / PowerVM に関する深い専門性
20年以上の経験を通して、仮想化・HA・Storage・バックアップ・監視など  
**基盤全体を横断して理解し運用できる**エンジニアです。

### 🔹 SAP基盤を含む大規模システム運用保守の実績
通信・製造・金融などの基幹系プロジェクトに携わり、  
業務特性に応じた安定運用・更改支援を実施してきました。

### 🔹 次世代技術への積極的なキャッチアップ
AIX で培った深い基盤知識を活かしながら、  
**AWS・自動化・IaC・クラウド化** へとスキル領域を拡張しています。

---

## 🏗 インフラ構成イメージ（Mermaid 図）

AIX / PowerVM を中心にしたオンプレ基盤と、DR・ストレージ・バックアップの関係イメージです。

```mermaid
graph TD
  subgraph On-Prem DC
    AIX[AIX / PowerVM<br/>LPAR / VIOS]
    SAP[SAP Application Servers]
    MON[Monitoring<br/>Netcool / ITM]
    BK[Backup Server<br/>TSM]
    STG[(Storage Virtualization)]
  end

  subgraph DR Site
    DR_AIX[DR AIX Hosts]
    DR_STG[(DR Storage)]
  end

  AIX --> SAP
  AIX --> MON
  AIX --> STG
  AIX --> BK
  BK --> STG

  STG -- FC / SAN --> DR_STG
  DR_AIX --> DR_STG
🔧 技術スキル（Technical Skills）
■ OS

AIX / Linux（RHEL / SLES） / Windows Server

HP-UX / Solaris（経験）

■ 仮想化・HA

PowerVM（LPAR / dLPAR / LPM）

VIOS / IVM

PowerHA（HACMP）

■ ストレージ / SAN

Storage 仮想化構築・運用

SAN設計（Zoning / LUN）

Cisco MDS / FCIP 設計構築

■ 監視 / バックアップ

IBM Netcool / ITM

TSM（バックアップサーバ構築含む）

■ 自動化 / スクリプト

Shell / Bash / PowerShell

Python

Hinemos / Systemwalker

Subversion サーバ構築

🧭 スキルマップ（Mermaid 図）

専門領域と、今後注力している領域の関係を簡易的にマップ化しています。

graph LR
  CORE[AIX / UNIX<br/>Core Expertise]
  VIRT[PowerVM<br/>LPAR / dLPAR / LPM]
  HA[PowerHA / DR Design]
  STG[Storage & SAN<br/>Virtualization / FCIP]
  SAP[SAP Infrastructure<br/>Operations]
  MON[Monitoring / Backup<br/>Netcool / ITM / TSM]

  CLOUD[AWS / Cloud]
  AUTO[Automation<br/>n8n / Scripting]
  IAC[IaC / Containers]

  CORE --> VIRT
  CORE --> HA
  CORE --> STG
  CORE --> SAP
  CORE --> MON

  VIRT --> CLOUD
  STG --> CLOUD
  HA --> CLOUD

  CORE --> AUTO
  AUTO --> CLOUD
  CLOUD --> IAC

🔧 主なプロジェクト（Projects）
🔹 AIX 基盤更改プロジェクトにおける設計・構築

AIX バージョンアップ、更改、HWリプレイスに伴い
仮想化基盤（LPAR / VIOS / SAN / Backup）を総合的に設計・構築。

LPAR 設計・リソース配分

VIOS 構成

SAN / Storage / Backup 連携設計

更改・移行手順書の作成

🔹 DR環境構築と切替手順の標準化（スクリプト作成含む）

DRサイト構築における DR 構成設計、切替手順マニュアル化、
スクリプトによる作業の確実性向上を担当。

DRサイト側 AIX / Storage 設計

フェイルオーバー／フェイルバック手順の標準化

コマンド実行スクリプトの作成

DRリハーサル対応

🔹 Storage 仮想化環境の構築・運用

ストレージ仮想化製品を用いた仮想ストレージプールの設計・構築・運用を担当。

仮想ストレージプール構成

SAN zoning / FCポート設計

性能分析・キャパシティ管理

運用改善提案

🔹 SAP 基盤の運用保守

大規模業務システムの SAP 基盤（AIX）の運用保守に従事。

SAP連携サーバの運用・障害対応

パフォーマンス調査

更改・パッチ適用対応

監視・バックアップとの連携調整

🔹 Cisco MDS を用いた FCIP 設計構築

DR用途の SAN 延伸のため、Cisco MDS / FCIP を用いた
拠点間ストレージ接続の設計・構築を担当。

FCIPリンク設計（帯域・RTT 等の考慮）

MDS 設定・動作検証

DR要件を満たすスループット確認

🔹 Subversion サーバ構築

運用チーム向けの Subversion リポジトリサーバを構築。

Apache + SVN リポジトリ構築

認証／権限設定

バックアップ・リカバリ手順策定

🔹 Systemwalker ジョブから Hinemos への移行

既存の Systemwalker ジョブ群を Hinemos へ移行。

ジョブ依存関係の棚卸し

Hinemos ジョブ定義の再設計

テスト計画・実施

監視・運用フローへの統合

🚀 Now Learning / Challenging

AWS（EC2 / VPC / IAM / Route53 / S3）

自動化（n8n + 各種 API 活用）

ChatGPT API を用いたドキュメント自動生成

コンテナ / IaC（Terraform など）

📫 Contact

GitHub: https://github.com/TomomasaSekino