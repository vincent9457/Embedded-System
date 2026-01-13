# 出勤系統與燈光控制
![](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) | ![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) | ![](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white) | ![](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white) | ![](https://img.shields.io/badge/espressif-E7352C?style=for-the-badge&logo=espressif&logoColor=white) | ![](https://img.shields.io/badge/Node--Red-8F0000?style=for-the-badge&logo=nodered&logoColor=white) | ![](https://img.shields.io/badge/Arduino_IDE-00979D?style=for-the-badge&logo=arduino&logoColor=white)

## 選擇實現的論文
https://www.irjmets.com/uploadedfiles/paper//issue_4_april_2025/71732/final/fin_irjmets1744021013.pdf

## 系統情境
管理員欲掌握辦公室的即時出勤狀況、環境溫濕度、目前人數。

每位員工持有 RFID 卡，每次刷卡即自動記錄進出、觸發即時拍照。

刷卡成功顯示 SUCCESS，發出成功音效；刷卡失敗顯示 ERROR，發出失敗音效。

人員進入，燈光即開啟；人員全數離開時，則自動關燈。

現場溫濕度感測器定時上傳數據。

## 成果展示
1. 初始畫面

![image1](https://github.com/vincent9457/Embedded-System/blob/main/README_imgs/Picture1.png)

2. 人員進入，紀錄刷卡時間和拍照(失敗也會記錄和拍照)

![image2](https://github.com/vincent9457/Embedded-System/blob/main/README_imgs/Picture2.png)

3. 人員離開，計算今日上班時數

![image3](https://github.com/vincent9457/Embedded-System/blob/main/README_imgs/Picture3.png)
