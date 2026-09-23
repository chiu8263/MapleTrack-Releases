# MapleTrack

MapleTrack 是專為 **MapleStory Worlds／Artale** 設計的練功效率追蹤工具。  
透過畫面辨識讀取 EXP 與楓幣，協助你查看即時效率、升級進度及每日練功紀錄。

## 下載最新版

### MapleTrack v2.2.1

- [下載 Windows 版本](https://drive.google.com/file/d/1nPTQVv6VUZlyAD3mWtROAz0NtkKLyn4y/view?usp=sharing)
- [下載 macOS 版本](https://drive.google.com/file/d/1S_V6_bQ2Lp92uo_zM7YX3hvQqyvi0Pyq/view?usp=sharing)

### v2.2.1 更新項目

- **Windows 10 擷取相容性**：缺少無邊框擷取元件時，改用一般視窗擷取。
- **版本檢查**：改從 GitHub 讀取最新版本，修正更新後仍顯示舊版本的問題。
- **簡易視窗圖釘**：簡易數值與簡易圖表可各自固定上方工具列，重新開啟後會保留設定。
- **工具列外觀**：固定時維持視窗圓角並沿用視窗底色與透明度；未固定時，滑出的工具列使用不透明白底，方便閱讀。

> Windows 支援 Windows 10／11 x64。  
> macOS 支援 macOS 14 以上的 Apple Silicon（M 系列）Mac。

<details>
<summary>下載舊版 v2.2.0</summary>

- [Windows 版本](https://drive.google.com/file/d/14cyLdNJsY-G8MJ8XUubDLPt_tvh3tEUg/view?usp=sharing)
- [macOS 版本](https://drive.google.com/file/d/1LtI34X549Xenpbi1IDkS06SHrv3VC6ra/view?usp=share_link)

</details>

<details>
<summary>下載舊版 v2.1.0</summary>

- [Windows 版本](https://drive.google.com/file/d/1Q0KGCewqcO8O1p-HlGTrrtoGsZzcKB8T/view?usp=share_link)
- [macOS 版本](https://drive.google.com/file/d/1pjyiyBD_k3SyRK3zUMbGIRvyxwjpIms-/view?usp=share_link)

</details>

## 程式特色

### 即時經驗效率

顯示本次累計 EXP、近 1 分鐘與近 10 分鐘效率、整場平均、最高效率及每小時推估。

<img src="https://github.com/user-attachments/assets/ebc3f8bc-95a0-4d98-8b05-f7030c335403" alt="即時經驗效率數值" width="574">

### 升級進度預估

顯示角色等級、開始與目前 EXP、經驗增加百分比，以及預計升級時間。

<img src="https://github.com/user-attachments/assets/a298c91b-1c03-44f4-8c19-481a6f67569c" alt="角色升級進度" width="760">

### 每日角色報表

每個角色擁有獨立報表，可查看每日等級、經驗百分比及當日獲得 EXP。

<img src="https://github.com/user-attachments/assets/30107689-071c-49ba-93d0-bbe27ac0a005" alt="角色每日 EXP 報表" width="760">

### 角色管理

可建立、重新命名及刪除角色，練功紀錄會依角色分開保存。

<img src="https://github.com/user-attachments/assets/1e1c0c43-1ebc-43c6-b7a4-2bbd56e42da3" alt="角色管理畫面" width="480">

### 即時效率圖表

同時觀察短期與長期效率，方便比較不同地圖或練功方式。

<img src="https://github.com/user-attachments/assets/68e98189-60e8-42d1-9a53-58bec04d6ab7" alt="簡易效率圖表" width="298">

### 簡易數值與圖表視窗

視窗可置頂、拖曳及調整大小，並能分別設定字級、顏色、透明度與顯示項目。

<img src="https://github.com/user-attachments/assets/d816bebd-3e43-4873-ab6f-75aa1ccfa7b0" alt="簡易視窗設定" width="760">

### 辨識設定群組

儲存遊戲視窗的大小、螢幕位置、EXP／楓幣辨識框，以及簡易視窗位置。

<img src="https://github.com/user-attachments/assets/26f87a19-72e4-4ccf-bf36-651aefd8e229" alt="辨識設定群組" width="420">

### 練功紀錄

保存開始與結束時間、角色、等級、累計 EXP 及整場效率，支援重新命名、排序、修改與多選刪除。

<img src="https://github.com/user-attachments/assets/fa336ac5-5401-48b4-b7df-b65d1341e4a7" alt="練功紀錄列表" width="760">

## 首次使用

1. 開啟 MapleStory Worlds／Artale 與 MapleTrack。
2. 跟著新手引導連接遊戲視窗。
3. 進入「辨識設定」，輸入名稱並新增一組視窗設定。
4. 選擇辨識項目後，依畫面範例圈選 EXP 與楓幣數字。
5. 按下「測試讀值」，確認 MapleTrack 顯示的數字與遊戲一致。
6. 回到狀態總覽，按下「開始」或 `F7` 開始記錄。
7. 練功結束後按下 `F8`，紀錄會自動儲存並建立新場次。

### 辨識範圍

| 項目 | 建議圈選內容 |
| --- | --- |
| EXP | 只包含經驗數字與百分比，例如 `12891755[1.42%]` |
| 楓幣 | 只包含數字與千分位逗號，避開圖示、文字與邊框 |

辨識圖片可放大、縮小及拖曳，方便精確圈選。

## 快捷鍵

| 按鍵 | 功能 |
| --- | --- |
| `F7` | 開始／暫停，再按一次繼續 |
| `F8` | 結束並儲存，接著建立新場次 |
| `F9` | 顯示／隱藏簡易數值與簡易圖表 |
| `F10` | 套用目前視窗設定的遊戲大小、位置與辨識框 |

套用辨識設定會暫停監控，完成後請按 `F7` 繼續。

## 安裝與更新

### Windows

下載 Windows 安裝檔後，依照安裝程式指示完成安裝。第一次安裝請保持網路連線。

### macOS

1. 下載並解壓縮 macOS 版本。
2. 將 MapleTrack 放入「應用程式」資料夾。
3. 第一次開啟時，依提示允許「螢幕錄製」權限。
4. 若要自動套用遊戲視窗位置與大小，還需要允許「輔助使用」權限。
5. 授權後請完全關閉 MapleTrack，再重新開啟。

更新前請先按 `F8` 儲存目前場次，並完全關閉 MapleTrack：

- Windows：執行新版安裝程式。
- macOS：使用新版 MapleTrack 替換「應用程式」中的舊版。

原有辨識設定與練功紀錄會保留，不需要手動刪除舊資料。

## 使用提醒

- 更改遊戲視窗大小、解析度或介面位置後，請重新測試辨識結果。
- 換到另一台電腦時，需要重新設定遊戲視窗與辨識範圍。
- 楓幣統計包含撿取、交易與消費，代表餘額淨變化，不是純打怪收入。
- 經驗效率與升級時間皆為推估值，請以遊戲內實際數值為準。
- 畫面辨識可能受到特效、讀取畫面、介面遮擋及解析度影響。

## 聲明

MapleTrack 是非官方玩家工具，與 MapleStory Worlds、Artale 及其營運團隊無關。  
使用前請自行確認遊戲的最新使用規範。
