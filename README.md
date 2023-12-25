# Final Report - UML

## 第一章 問題定義

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

### 1.3業務模型

#### 1.3.1業務模型
  ![image](https://github.com/BAGLE102/final-report-UML/assets/146699756/6eeef1f7-beb9-4908-877f-d801e6e39814)


---



