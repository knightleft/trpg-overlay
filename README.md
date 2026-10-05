# TRPG 跑團介面產生器

給 TRPG（CoC）實況用的 OBS 畫面外框產生器。左邊編輯、右邊即時預覽 1920×1080。

## 使用方式

1. 打開網頁，在左邊編輯標題、劇情筆記、配色、角色等內容（自動存在瀏覽器裡）。
2. 按「複製 OBS 網址」，在 OBS 新增「瀏覽器」來源，網址貼上，寬 1920、高 1080。
3. 之後每次修改，都要重新按「複製 OBS 網址」貼回 OBS。

- 劇情畫面是挖空透明的，把圖片或遊戲畫面放在這個來源的下面就會透出來。
- 角色欄是空格，給 OBS 疊上 CCFOLIA 的瀏覽器來源。每個角色的 CSS、網址、OBS 位置與大小都在編輯器的角色區。

## 檔案

| 檔案 | 內容 |
| --- | --- |
| `trpg-overlay.html` | 產生器本體（編輯器＋輸出畫面） |
| `index.html` | 首頁，直接轉到產生器 |
| `statusbar/` | CCFOLIA 狀態條 CSS 產生模組 |

## 授權

`statusbar/` 內的模組改作自 shiki365「[ステータスバーメーカー](https://shiki365.github.io/status-bar-maker/)」（MIT License，見 `statusbar/LICENSE`）。本工具為非官方工具，與 CCFOLIA 無關。
