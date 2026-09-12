# Campus Parking Risk Prediction

中山大學機器學習作業。

利用歷史違規紀錄、時間與氣象特徵，預測校園各區域在特定時段出現違規停車取締紀錄的風險。

專案以 15 分鐘為單位建立時空資料，比較 XGBoost、Logistic Regression 與 Random Forest，並依預測結果產生區域風險排序。

## 組員
- B123040048 吳紹彰
- B123040049 劉育希
- B123040053 張承勛
- B122045016 謝承哲

## 專案結構

```text
.
├── src/                   # 模型訓練、評估與資料處理工具
├── data_after_process/    # 處理後資料
├── rain_data/             # 降雨資料
└── temp_data/             # 氣溫資料
```

## 開始使用

建議使用 [uv](https://docs.astral.sh/uv/) 管理環境。

下載環境：
```bash
uv sync
```
