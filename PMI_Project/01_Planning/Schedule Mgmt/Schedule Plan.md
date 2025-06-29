
# Schedule Plan

## Project Schedule Overview
本計畫以WBS與專案目標為基礎，規劃明確的里程碑、負責人、依賴關係與風險管理，確保專案如期高品質完成。

## Key Milestones

- **Project Kickoff**: 2025-07-10
- **Completion of Planning Phase**: 2025-07-10
- **Execution Phase Start**: 2025-07-10
- **Mid-Project Review**: 2025-08-15
- **Project Completion**: 2025-09-10

## Schedule Management Approach

- **Scheduling Tool**: Excel, Jira, Gantt Chart (MS Project/Notion/ClickUp)
- **Frequency of Updates**: Weekly (with daily standups and milestone reviews)
- **Responsibility**: Project Scheduler / Project Manager
- **Progress Monitoring**: Real-time dashboard, weekly status meetings, milestone reviews，並設置專案狀態頁面供全員查閱
- **Resource Management**: 專案啟動時明確分配人力、設備、預算，並於每週檢查調整，避免資源衝突，並針對並行任務設置協作機制
- **Change Management**: 變更申請需經專案負責人審核，所有依賴與時程需即時更新，並於會議中同步，建立清晰的變更流程與影響評估
- **Risk Management**: 針對影像品質、設備反應、外部供應商等風險，設置應急預案與緊急聯絡人，並於每週檢討，並建立全面風險清單與應對策略
- **Quality Control**: 模型訓練與部署階段設置交叉驗證、獨立測試，定期回顧模型效能，並於用戶訓練後進行成效評估
- **Communication**: 每日簡報、每週會議、Jira/Teams/Slack同步，建立定期溝通機制與彙報頻率，並設置專案狀態頁面
- **User Training**: 培訓內容涵蓋所有操作人員，提供教材與實作，結束後進行成效評估，並針對培訓對象設計差異化內容
- **Budget & Resource Confirmation**: 專案啟動時明確各階段預算分配，並根據進展調整，確保關鍵路徑資源充足



| Task Name                            | Start Date | End Date   | Duration | Responsible Party    | Dependencies |
| ------------------------------------ | ---------- | ---------- | -------- | -------------------- | ------------ |
| Project Kickoff                      | 2025-07-10 | 2025-07-10 | 1        | Project Sponsor/Lead | -            |
| Raspberry Pi Capture System Complete | 2025-07-10 | 2025-07-20 | 10       | IoT計畫負責人             | Project Kickoff |
| YOLO Model Ready                     | 2025-07-10 | 2025-08-05 | 20       | 機器學習工程師              | Project Kickoff |
| Cloud API & Dashboard Online         | 2025-07-15 | 2025-08-15 | 15       | 解決方案架構師/資料工程師        | Raspberry Pi Capture System Complete, YOLO Model Ready |
| MLOps Retraining Pipeline Ready      | 2025-07-20 | 2025-08-25 | 10       | 機器學習工程師/資料工程師        | YOLO Model Ready |
| System Deployed On-site              | 2025-08-26 | 2025-08-28 | 3        | IoT計畫負責人             | Cloud API & Dashboard Online, MLOps Retraining Pipeline Ready |
| Model Go-live & Alarm Activated      | 2025-08-29 | 2025-09-01 | 4        | 資料科學家                | System Deployed On-site |
| User Training Complete               | 2025-09-02 | 2025-09-03 | 2        | 專案負責人                | Model Go-live & Alarm Activated |
| Project Closure Report Approved      | 2025-09-04 | 2025-09-10 | 7        | 專案負責人                | User Training Complete |
| Project Complete                     | 2025-07-10 | 2025-09-10 | 63       | 全體專案團隊               | Project Closure Report Approved |



## Dependencies & Critical Path

- 關鍵路徑（Critical Path）：
  Project Kickoff → Raspberry Pi Capture System Complete & YOLO Model Ready → Cloud API & Dashboard Online → System Deployed On-site → Model Go-live & Alarm Activated → User Training Complete → Project Closure Report Approved → Project Complete

- 主要依賴關係已於表格中標註，確保每個里程碑的最小路徑與專案進度連貫。

## Risk & Resource Considerations

- **Resource Allocation**: 並行任務需確認人力、設備、預算充足，避免資源衝突，並於每週檢查調整，針對跨部門協作設置協調流程
- **Risk Response**: 針對影像品質、設備反應延遲、外部供應商、技術難題等風險，設置備用計畫與緊急聯絡人，並建立風險清單與應對策略
- **Change Management**: 變更流程明確，所有變更需評估對時程與依賴的影響，並即時同步至全體成員，並於會議中審查
- **Quality Control**: 模型訓練與部署設置交叉驗證、獨立測試，定期回顧模型效能，並於用戶訓練後進行成效評估
- **Communication**: 設置每日/每週會議、專案狀態頁面，確保資訊同步，並建立溝通回饋機制
- **User Training**: 培訓內容與教材完整，結束後進行成效評估，並針對不同角色設計差異化訓練
- **Budget & Resource**: 專案啟動時明確各階段預算分配，並根據進展調整，確保關鍵路徑資源充足


## Conclusion

This schedule plan will be reviewed and updated regularly to reflect the current status of the project and to accommodate any changes that may arise during execution.