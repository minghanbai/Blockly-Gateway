# Blockly-Gateway 🚪

Blockly-Gateway 是一個專為程式設計初學者設計的視覺化過渡工具。

它的目標是作為一座「閘道」，幫助學生從圖形化積木（Blockly）無痛跨越到純文字編碼（Visual Studio / Unity）。

## ✨ 主要功能

* 雙模式輸出：一鍵切換 Visual Studio (Console) 與 Unity (MonoBehaviour) 兩種 C# 格式，適應不同課程需求。

* 即時代碼預覽：拖拉積木的同時，右側即時顯示對應的標準 C# 語法，強化語法記憶。

* 瀏覽器模擬執行：內建 JavaScript 模擬引擎，免安裝 IDE 即可在網頁上驗證邏輯（支援輸入/輸出/亂數）。

* 防呆與容錯：

  * 變數採用 dynamic 型別，避免初學者因型別錯誤受挫。

  * 智慧偵測：僅在需要時才顯示輔助函式（如 Input 或 Random），保持代碼介面整潔。

## 🚀 線上試用

* [點擊這裡使用工具](https://minghanbai.github.io/Blockly-Gateway/)

🛠️ 教學應用場景

## 本工具特別適合 CS101 (程式設計導論) 的前兩週課程：

* 邏輯建立：利用積木學習迴圈、判斷式、變數與函式。

* 語法對照：觀察積木如何轉換為 C# 的 { } 與 ;。

* 信心建立：在面對 IDE 的語法錯誤挫折前，先體驗程式運作的樂趣。

## 📦 技術棧

* Google Blockly (v10.4.3)

* HTML5 / CSS3 / JavaScript (Single File Application)

## 📄 授權

* MIT License. 歡迎教育工作者自由使用與擴充。
