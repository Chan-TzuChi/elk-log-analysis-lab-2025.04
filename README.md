# ELK Log Analysis Lab-2025.04

## 🔍 專案簡介 | Project Description

本專案旨在實作與學習 ELK Stack（Elasticsearch、Logstash、Kibana）於日誌分析、視覺化、查詢與雲端整合的完整流程。  
亦涵蓋基本 SIEM 概念與 log pipeline 架構，並提供儀表板展示與查詢語法範例，作為面試或學習記錄之用。

> A hands-on project to explore ELK Stack for log collection, visualization, cloud log integration, and basic SIEM concepts.

---

## 🛠 使用技術 | Tech Stack

- **ELK Stack**
  - Elasticsearch
  - Logstash / Filebeat
  - Kibana
- **Cloud Integration**
  - AWS CloudWatch Logs
- **Log Sources**
  - Nginx / Syslog / JSON Logs
- **工具與環境**
  - Docker & docker-compose
  - Linux (Ubuntu)
  - KQL (Kibana Query Language)

---

## 📁 專案架構 | Project Structure

```bash
elk-log-analysis-lab/
├── docker-compose.yml            # ELK stack 部署設定
├── filebeat.yml                  # Filebeat 設定檔
├── dashboard/
│   └── dashboard_screenshot.png  # Kibana 視覺化成果圖
├── cloudwatch_to_elk/
│   └── integration_steps.md      # 雲端日誌整合教學
├── queries/
│   └── queries.kql               # KQL 查詢語法範例
├── data_samples/
│   └── sample_logs.json          # 測試用 log 資料
├── elk-architecture-diagram.png  # 系統架構圖
└── README.md

