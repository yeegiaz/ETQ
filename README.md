# Energy Time Widget

這是一個原生 Android 首頁 widget：

- 白底黑字
- 可在手機桌面調整大小
- 四象限排列
  - 左到右：花費時間少到多
  - 下到上：能量低到高
- 每個象限有 4 個可編輯文字格
- 點任一格即可開啟編輯畫面，儲存後 widget 會立即更新

## 使用方式

1. 用 Android Studio 開啟這個資料夾。
2. 讓 Android Studio 同步 Gradle 專案。
3. 執行到 Android 手機或模擬器。
4. 在手機桌面長按，加入「Energy Time Matrix」widget。
5. 長按 widget 可調整大小；點格子可編輯內容。

## 專案重點檔案

- `app/src/main/java/com/example/energytimewidget/EnergyTimeWidgetProvider.java`
- `app/src/main/java/com/example/energytimewidget/EditCellActivity.java`
- `app/src/main/res/layout/widget_energy_time.xml`
- `app/src/main/res/xml/energy_time_widget_info.xml`
