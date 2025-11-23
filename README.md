## **English README (README.md)**

# **🧠 K-Map Master: Logic Simplification Game**

K-Map Master is an interactive educational tool designed to help users practice and master Boolean Algebra simplification using Karnaugh Maps (K-Maps). This single-file web application features an internationalized UI supporting both English and Traditional Chinese.

## **✨ Features**

* **Interactive K-Maps:** Click cells (minterms) to select them and create visual groupings (implicants).  
* **Variable Support:** Practice with 2, 3, and 4-variable K-Maps.  
* **Campaign Mode (Stages 1-3):** Progressively challenging levels to test your skills.  
* **Practice Mode:** Customize your game by selecting variables and including 'Don't Care' conditions.  
* **Optimal Solution Checking:** The app verifies your solution for correctness and optimality (Quine-McCluskey logic).  
* **Hint System:** Get targeted hints to identify uncovered minterms.  
* **Language Selection:** Seamlessly switch the entire UI between English and Traditional Chinese.

## **🌐 Language Selection**

The application supports two languages: **English (EN)** and **Traditional Chinese (繁體中文 / zh-TW)**.

### **How to Switch Languages**

1. Locate the dropdown menu in the top-right corner of the header.  
2. The dropdown is labeled with the currently active language (e.g., "English" or "繁體中文").  
3. Click the dropdown and select your preferred language. The entire application text, including button labels, titles, messages, and objective text, will instantly update.

## **🛠️ How to Play**

### **1\. Start a Game**

Choose between:

* **Campaign Mode:** Start at Stage 1 and unlock more complex maps (up to 4 variables).  
* **Practice Mode:** Configure the number of variables (2, 3, or 4\) and choose whether to include **Don't Care (X)** terms.

### **2\. Group the Minterms**

* **Objective:** The goal is to cover all of the **'1'** cells on the K-Map using the largest possible groups that are powers of two (1, 2, 4, 8, etc.).  
* **Selection:** Click on the cells you wish to include in a group.  
* **Create Group:** Once your cells are selected, click the **"Add"** button in the control bar to formalize the group. The cells will be visually highlighted.  
* **Valid Groups:** Groups must be rectangular (or square) and can wrap around the edges of the map. They cannot contain any **'0'** cells.

### **3\. Enter and Check the Solution**

* **Equation Input:** In the control panel, enter the simplified Boolean expression corresponding to your groupings.  
  * Use **'** for NOT (e.g., A')  
  * Use **\+** for OR (e.g., A'B \+ CD)  
* **Verification:** Click **"CHECK SOLUTION"** to evaluate your work. The system will check:  
  1. If all '1's are covered.  
  2. If the groupings are valid.  
  3. If the solution is the *most optimal* (minimal number of Prime Implicants).

## **💻 Tech Stack**

* **HTML5**  
* **Tailwind CSS:** Used for all styling and responsiveness.  
* **Vanilla JavaScript:** Used for game logic, DOM manipulation, and the full Internationalization (i18n) system.  
* **No External Frameworks:** All code is contained within a single index.html file for simplicity and portability.

---
---

## **Traditional Chinese README (README\_zh\_tw.md)**

# **🧠 K-Map 大師：邏輯簡化遊戲**

K-Map 大師是一個互動式的教育工具，旨在幫助使用者透過卡諾圖（Karnaugh Maps，簡稱 K-Map）來練習和掌握布林代數的簡化。這個單一檔案的網路應用程式具有國際化的使用者介面，支援英文和繁體中文。

## **✨ 主要特色**

* **互動式卡諾圖：** 點擊方格（最小項）進行選擇，並建立視覺化的分組（基本含義項）。  
* **變數支援：** 可練習 2、3 和 4 個變數的卡諾圖。  
* **闖關模式（第 1-3 關）：** 逐步提高難度，考驗你的技能。  
* **練習模式：** 自訂你的遊戲，選擇變數數量並納入「隨意項」（Don't Care）。  
* **最佳解檢查：** 應用程式會驗證你的解是否正確和最佳（使用 Quine-McCluskey 演算法邏輯）。  
* **提示系統：** 獲取有針對性的提示，以識別未覆蓋的最小項。  
* **語言選擇：** 使用者介面可在英文和繁體中文之間無縫切換。

## **🌐 語言選擇**

本應用程式支援兩種語言：**英文 (EN)** 和 **繁體中文 (繁體中文 / zh-TW)**。

### **如何切換語言**

1. 找到位於標頭右上角的下拉式選單。  
2. 選單會顯示目前使用的語言（例如：「English」或「繁體中文」）。  
3. 點擊下拉選單並選擇你偏好的語言。所有應用程式文字，包括按鈕標籤、標題、訊息和目標文字，將會立即更新。

## **🛠️ 遊戲方式**

### **1\. 開始遊戲**

請在以下模式中選擇：

* **闖關模式：** 從第 1 關開始，解鎖更複雜的卡諾圖（最多 4 個變數）。  
* **練習模式：** 設定變數數量（2、3 或 4），並選擇是否納入**隨意項 (X)**。

### **2\. 分組最小項**

* **目標：** 目的是使用 2 的次方（1、2、4、8 等）的組，覆蓋卡諾圖上所有\*\*「1」\*\*的方格。  
* **選取：** 點擊你希望包含在群組中的方格。  
* **建立群組：** 選定方格後，點擊控制列中的\*\*「新增」\*\*按鈕來正式建立群組。被選中的方格將會被視覺化突出顯示。  
* **有效群組：** 群組必須是矩形（或方形），並且可以環繞地圖邊緣。它們不能包含任何\*\*「0」\*\*的方格。

### **3\. 輸入並檢查答案**

* **方程式輸入：** 在控制面板中，輸入與你的分組相對應的簡化布林表達式。  
  * 使用 **'** 代表反相 NOT（例如：A'）  
  * 使用 **\+** 代表 OR（例如：A'B \+ CD）  
* **驗證：** 點擊\*\*「檢查答案」\*\*來評估你的作業。系統將會檢查：  
  1. 是否所有「1」都已被覆蓋。  
  2. 分組是否有效。  
  3. 答案是否為*最佳解*（最少數量的重要基本含義項）。

## **💻 技術棧**

* **HTML5**  
* **Tailwind CSS：** 用於所有樣式和響應式設計。  
* **原生 JavaScript：** 用於遊戲邏輯、DOM 操作和完整的國際化（i18n）系統。  
* **無外部框架：** 為求簡潔和可攜性，所有程式碼都包含在單一的 index.html 檔案中。