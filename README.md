\# IT Automation



這是公司 IT 自動化與基礎設施即程式碼（IaC）的執行層。



\## 原則



\- 所有伺服器與雲端設定優先使用 Terraform 或 Ansible

\- 所有變更必須有 Git branch、PR、測試與 review

\- 生產部署只可透過 CI/CD pipeline 執行

\- 禁止在未經批准下直接修改生產環境

\- 每個變更必須包含回滾方案

