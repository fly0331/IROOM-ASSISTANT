# IROOM-ASSISTANT

[iRoom Assistant Report]([http://dillinger.io/](https://github.com/fly0331/IROOM-ASSISTANT/blob/main/iRoom%20Assistant%20Report.pdf) "link")
## 專題動機：
1. 社會疫情時期，點名與打卡重要但難確實記錄。
2. 以人臉辨識替代不確實的點名方式，提高人員掌控。
3. 環境因素如溫度、二氧化碳濃度影響工作效率，尤其在COVID-19時期。

## 目標：
創建智能監測系統 "IROOM ASSISTANT"，結合人臉辨識、溫濕度、二氧化碳、光感測器。
提高點名、打卡確實性，智能提醒室內狀況，調整環境以提高效率。

## 問題解決方法：
使用感測器如DHT11、CCS811，樹莓派連接進行環境監測。
人臉辨識初嘗試 YOLO 模型，改用 OpenCV 搭配 Dlib 提高精準度。
將感測器數據與人臉辨識整合，建立資料庫，以Python和Flask實現網頁控制。

## 目標成果：
提供兼顧人員與環境的網頁應用，應對COVID-19並提高工作效率。
透過邊緣運算，統計最佳工作及學習環境，具AIoT應用潛力。

## 問題與解決：
感測器操作中遇到溫度問題，謹慎使用及備用感測器解決。
感測器顯示數據問題，透過網路經驗和嘗試指令解決。
二氧化碳濃度感測器選擇 CCS811 解決問題。
人臉辨識初嘗試 YOLO 模型，改用 OpenCV 搭配 Dlib 提高精準度。
整合感測器數據與人臉辨識，以Python和Flask實現網頁控制。
