# TMS_flame_simulation

本程式模擬TMS版本的「星火」強化系統。使用者可以模擬不同等級、不同類型 (Boss 裝備或一般裝備)進行強化，計算強化結果的等效主屬性，並且以視覺化圖表呈現多次模擬的數值分佈，方便玩家了解不同強化數值的機率分佈。

![image](https://i.imgur.com/yimohRe.png)

## 功能特色
- 支援Boss裝備和一般裝備的強化模擬。
- 支援不同裝備等級的強化數值設定，方便開發者添加未來擴充。
- 可自訂等效主屬性換算數值，適用於不同玩家裝備機體。
- 自動生成 Reverse CDF 圖表，標記出 0.1、0.02 和 0.001 累積機率對應的等效主屬性值。

## 使用說明

**安裝依賴套件**：
本專案依賴 `matplotlib` 和 `numpy` 套件，請確保已安裝。

```bash
pip install matplotlib numpy
```

## 懶人表
我將實驗結果整理總結為下表，方便懶人快速瞭解星火素質好壞

![image](https://i.imgur.com/hb2oKQc.png)

本表亦發布在巴哈姆特 新楓之谷哈啦板 [文章連結](https://forum.gamer.com.tw/Co.php?bsn=7650&sn=6482250)

## ChatGPT輔助程式開發紀錄
程式內的邏輯架構主要由CahtGPT產生，我只手動修改了數值部分 (各等級T1星火數值、等效主屬性換算)

[對話紀錄](https://chatgpt.com/share/671b282a-0d60-8003-98e2-216fdb283e72)

![image](https://i.imgur.com/FXyrZyu.png)


