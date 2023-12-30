# Final Report - UML

# 第一章 問題定義

### 1.1 業務調查

隨著社會的發展和人民生活水準的提高，擁有車輛成為了人們奮鬥的目標之一。然而，隨著車輛數量的增加，相應的停車問題也隨之出現。人們的生活方式正在發生深刻的變化，城市的交通流量也因此而增加。這導致了交通擁擠和混亂，給人們的生活帶來了極大的不便。為了解決這種不便，人們需要尋求高技術的有效手段，並使停車場管理系統更加先進和完善，為車主提供方便。因此，開發了停車場管理系統。

### 1.2 需求陳述

#### 1）車主進入停車場

- 車主在停車場外，停車場外的顯示幕上顯示空餘停車位的數量。
- 若有空餘，車主來到擋車器前，系統自動識別車牌號，記錄車輛進入停車場的時間與車牌號，擋車器放行，車主進入停車場。
- 若系統無法識別，如車輛還未上牌或使用臨時車牌，由管理員手動錄入車輛資訊。

#### 2）車主離開停車場

- 車主再次來到擋車器前，系統自動識別車牌號，記錄車輛離開停車場的時間，計算停車費用。
- 車主支付完成後，擋車器放行，車主離開停車場。
- 若有特殊情況，由管理員手動處理錄入信息，費用由系統完成計算。

#### 3）管理員查看車輛資訊

- 管理員登陸系統，可以對車輛資訊進行管理。
- 可查詢、添加、刪除車輛資訊，包括車牌號、進出時間、停車費用和特殊情況備註。

 ### 1.3 業務模型

#### 1.3.1 業務模型
![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/6eeef1f7-beb9-4908-877f-d801e6e39814)

*圖1-1 業務用例模型*

#### 1.3.2車主商務活動圖
![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/fe5e90af-c6b8-49d2-a707-723a744ee6a6)

*圖1-2車主商務活動圖*

#### 1.3.3管理員商務活動圖
![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/e65d2c73-c082-4098-9794-18692151779b)

*圖1-3管理員商務活動圖*

# 第二章 需求分析

## 2.1 系統用例建模

### 2.1.1 參與者概述

1. **車主** - 使用停車服務的個體。

2. **管理員** - 負責管理車輛進出相關信息的操作者。

### 2.1.2 用例概述

1. **車主進出停車場**
   - 車主來到有空餘車位的停車場。
   - 進入停車場停車。
   - 支付停車費用後離開停車場。

2. **管理員管理車輛進出資訊**
   - 管理員輸入正確的賬號和密碼登陸系統。
   - 管理車輛進出的資訊，包括車牌號、進出時間、停車費用。

### 2.1.3 用例關係

![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/14699c03-5bd2-4ba9-809b-94997d26ecd2)


# 第三章 面向物件分析

## 3.1用例實現
  使用順序圖，按B-C-E架構實現每一個用例

![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/698e4c33-8806-48b3-a4bf-3bbe96d9fb34)

*圖3-1登陸時序圖*

![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/828ec306-236b-4113-a7a8-3b9af0babce0)


*圖3-2刪除車輛資訊時序圖*

![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/30f38b42-b27c-4a6b-a42b-d7be0c3f7032)


*圖3-3添加車輛資訊時序圖*

![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/93c7ada6-c9dc-4b9f-8de7-92981c91e53e)


*圖3-5查找車輛資訊時序圖*

![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/37620657-c666-406a-b4e0-2a28d7a264f0)

*圖3-6查看車輛資訊時序圖*

## 3.2分析類模型
  建立系統的分析類圖，為每個類分配職責、屬性，及對類之間的關係建模

![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/3f713d31-8a5b-4a70-a00c-2cb9ec249045)

## 第四章實例介紹
現在已有實例:鼎高科技-智慧停車場管理系統 和 123股份有限公司-智能化停車場系統

## 1-1鼎高科技-智慧停車場管理系統

![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/8c3d577c-1420-414f-983e-35dd2a91f0ba)


    可利用車牌、車位、入場時間查詢停車位置並快速導引路線圖，節省尋車時間
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/0df82c33-85c7-47f7-838e-8ea54f803fcc)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/0edb7247-7c6d-4879-b54b-f313925f3884)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/6f6aed88-6e9e-4321-a05a-7dbf30a055f8)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/b4bfd21d-45a1-4b11-840b-a08da522075c)

## 1-2系統整合服務

全面網路化的智慧停車場系統，透過與緊急求救系統的結合，提升管理人員的機動性，並可快速排除現場狀況。當緊急狀況發生，可利用數位廣播系統即時宣導疏散位置。完整的安全監控系統，將有效提升顧客的回流率以及停管單位的管理效率。
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/b1bf6618-ca09-44fa-824a-0356a60867ba)
## 1-3 電動車停車位監控系統
每一電動車車位配置一支IP Cam 及地鎖。
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/31ab1fda-0d47-4d93-802b-652930cf779f)
1.利用車牌辨識，判別要停車之車輛是否是電動車，及時降下地鎖，讓車輛進入。
2.當車輛離開時也要偵測，及時將地鎖升起。 
3.車輛的進出照片，車牌號碼及時間皆紀錄在資料庫，提供查詢。
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/cb11ba68-374d-4765-bc67-183591cf1741)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/b486fc72-a216-4027-bfe6-a359ba1dd09c)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/344b8675-d0d8-40fe-9a6d-3a2826e8b26c)

## 1-4產品特色

1.結合傳統演算法及AI深度學習技術所開發的 LPR 及 AI LPR ‚可供各種場域使用的 AI智慧空車位偵測導引‚
2.AI智慧尋車 , AI自動空車位偵測,車牌辨識查詢。 
3.可與各家的停車場設備整合,例如IP Cam 、柵欄機、字幕機、查詢機、收費機等。
4. 除了收費停車場外 , 針對廠辦 、大樓、飯店、遊樂場等提供客製化服務。
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/5789dcf6-493a-4e1c-a3af-f14f87014733)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/4220dab8-8177-4a9b-ba85-200fd0ba0514)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/14edbd70-4d81-4970-bfad-0c1af69baa34)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/2bc866cc-f5ad-424e-a4a8-3a84c2b73a9d)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/6f9edeab-ce79-460c-b4ee-e3952c9e5c69)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/8a792490-4784-4e33-8924-adc889c55e7b)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/5df868d3-1554-4ee7-b738-721b3bf30c95)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/e79b425e-60ed-437d-92bb-e7424ede6a89)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/dcb12b0e-c7f5-4b61-a18d-f03fb9b1bfa1)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/556f6be4-10d3-4a39-ac9d-0608e4ce9a22)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/6a5ae7f4-a19b-484f-99d4-8bb9ae70ab85)
![image](https://github.com/BAGLE102/final-report-UML/assets/149245212/73a14b5a-f186-4fb0-8c4b-1b196f832ecd)



