```mermaid
gantt
dateFormat  YYYY-MM-DD
title 任務結構時程表
excludes weekdays 

section A分項
研擬計畫   :         des1, 2025-10-06,2025-10-07
任務分配   :         des2, after des1, 4d
取得硬體   :         des3, after des1, 17d
程式開發   :         des4, after des2, 70d
安裝硬體   :         des5, after des3, 10d
程式測試   :         des6, after des4, 30d
撰寫使用手冊   :      des7, after des5, 25d
轉換檔案   :         des8, after des5, 20d
系統測試   :         des9, after des6, 25d
使用者訓練   :       des10, after des7 des8, 20d
使用者測試 :         des11, after des9 des10, 25d
```
