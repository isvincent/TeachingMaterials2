# TeachingMaterials2｜五分鐘視覺教室

七份高中教材各自改寫為 **300 秒、1080×1920（9:16）** 的互動教學網頁。每份簡報只有一個 `index.html`，包含 CSS、JavaScript、教材資料與內嵌 SVG，無外部套件或圖片依賴。

網站入口：https://isvincent.github.io/TeachingMaterials2/

## 教材目錄

| 科目 | 教材 | 資料夾 | 核心內容 |
| --- | --- | --- | --- |
| 物理 | [摩擦力](friction/index.html) | `friction` | 為什麼推不動？、靜摩擦力會調整、最大靜摩擦力 |
| 公民 | [所有權的物權特性](ownership/index.html) | `ownership` | 誰擁有這臺電腦？、使用、收益、處分、直接支配與保護絕對性 |
| 化學 | [化學式與百分組成](chemical-formulas/index.html) | `chemical-formulas` | 一種物質，四種表達、實驗式、質量百分比怎麼用？ |
| 地理 | [氣候系統](climate/index.html) | `climate` | 氣候是互相影響的系統、緯度與太陽照射、高度與氣溫 |
| 英文 | [The Lady or the Tiger?](lady-or-tiger/index.html) | `lady-or-tiger` | 兩扇相同的門、Lady 與 Tiger、身分差距引發衝突 |
| 國文 | [出師表](memorial/index.html) | `memorial` | 出征前的一封表、危急存亡之秋、廣開言路 |
| 數學 | [線性規劃](linear-programming/index.html) | `linear-programming` | 有限資源，最佳結果、平行直線系、不等式是一個半平面 |

## 播放與教學

- 點「開始有聲教學」後自動播放；10 張投影片各 30 秒，總時間軸精確為 300 秒。暫停、測驗或互動的探索時間不計入播放時間。
- 旁白採 Web Speech API，即時使用裝置／瀏覽器為 `zh-TW` 選擇的預設語音，`rate=1`、`pitch=1`。沒有外部音訊檔或固定音色。請開啟裝置音量並使用支援語音合成的瀏覽器。
- 每頁有獨立解說，切成五段短字幕；支援語音 boundary 事件時字幕跟隨朗讀，否則依六秒字幕提示。語音耗時受裝置影響；固定 30 秒切頁時會停止尚未完成的朗讀。若需逐字聽完較慢的裝置語音，可跳回該頁重播，或閱讀完整逐字稿。
- 可暫停、上一段、下一段、拖動時間軸、語音開關、重播、全螢幕；支援空白鍵播放／暫停與方向鍵跳段。
- 操作圖解或回答測驗會暫停，按播放繼續。離開背景頁面會自動暫停。
- 每頁有檢核題與即時解析。完整旁白可在頁面展開，或下載為 UTF-8 文字檔。
- 各頁以 1080×1920 設計座標縮放，保留 9:16；手機下方呈現互動與章節，桌面放於側欄。尊重 `prefers-reduced-motion`。

## 教材範圍與來源

五分鐘版為核心概念、代表例題與檢核的教學改寫，並非逐頁翻印全部 PDF。圖解為新繪示意，非實測資料；不預設取得原教材的再授權權利。原 PDF 連結維持 Google Drive 原權限，未公開複製原始 PDF。

- 物理《摩擦力》：[原 PDF](https://drive.google.com/file/d/16YybgjjfQe13Srn8Etcz5PgIVMrGotqb/view)；10 段內容：為什麼推不動？ → 靜摩擦力會調整 → 最大靜摩擦力 → 斜面上的平衡 → 即將滑下的角度 → 施力範圍 → 滑動後的動摩擦 → 摩擦力也能使物體前進 → 兩箱一起加速 → 90 N 拉力下的結果。
- 公民《所有權的物權特性》：[原 PDF](https://drive.google.com/file/d/1pUTXDTz-9NUQDQjUGMR_lkwN0U_iIcPb/view)；10 段內容：誰擁有這臺電腦？ → 使用、收益、處分 → 直接支配與保護絕對性 → 排他性與共有 → 一物二賣的優先性 → 權利受侵害時 → 物權法定主義 → 動產與不動產 → 保障也有界線 → 創作者與使用者。
- 化學《化學式與百分組成》：[原 PDF](https://drive.google.com/file/d/1r7kOOGU_47L6DT1PmzlN38uVHQ0d8D0F/view)；10 段內容：一種物質，四種表達 → 實驗式 → 質量百分比怎麼用？ → 氧化錫的實驗式 → 燃燒分析法 → 維生素 C 的實驗式 → 從實驗式到分子式 → 三聚氰胺計算 → 分子式相同，結構不同 → 示性式與結構式。
- 地理《氣候系統》：[原 PDF](https://drive.google.com/file/d/173iBeB-ACXNew29EwKmsxbgM0_JzbRk7/view)；10 段內容：氣候是互相影響的系統 → 緯度與太陽照射 → 高度與氣溫 → 海陸與洋流 → 氣壓與風 → 低壓與高壓 → 雨量不只看總數 → 四種雨，四種上升方式 → 冷鋒、暖鋒、滯留鋒 → 多雨的臺灣也會缺水。
- 英文《The Lady or the Tiger?》：[原 PDF](https://drive.google.com/file/d/17eGY9_nBDNipBVXFvuGfX1WLQ-R3s4sC/view)；10 段內容：兩扇相同的門 → Lady 與 Tiger → 身分差距引發衝突 → 公主的兩難 → 結局沒有揭曉 → 四種故事結尾 → 字彙放回情境 → 要求與建議的句型 → 雖然如此，卻…… → 用證據支持你的推論。
- 國文《出師表》：[原 PDF](https://drive.google.com/file/d/1lJfhjbRBWPMg7XFp3ycJc4sKOzNbBXme/view)；10 段內容：出征前的一封表 → 危急存亡之秋 → 廣開言路 → 秉公執法 → 親賢遠佞 → 從布衣到受命 → 古今詞義要辨清 → 北定中原的職分 → 情理並重，首尾呼應 → 如果你是劉禪。
- 數學《線性規劃》：[原 PDF](https://drive.google.com/file/d/1X8-Fv6lBW4euaTks3s9eL5zF1K60UOX6/view)；10 段內容：有限資源，最佳結果 → 平行直線系 → 不等式是一個半平面 → 限制條件的交集 → 平行線法 → 頂點法 → 學期成績的最佳安排 → 精油產量最大化 → 合金成本最小化 → 四步解題與邊界檢查。

細節處理：物權的絕對效力與權利限制分開說明；不動產登記原則限定於法律行為；開源軟體仍有授權條件；氣溫遞減率說明為近似；英文維持未揭曉的原文結局；線性規劃另提醒無解、無界、多重最佳解及整數限制。食品安全數值例題僅作教材計算，未當作現行安全建議。

## 本機使用與部署

直接開啟根目錄 `index.html`，或用 `python3 -m http.server 8000` 提供靜態網站。各教材單一 HTML 可獨立下載使用，返回首頁連結需保留資料夾結構。語音是否離線可用取決於裝置是否具本機語音。

GitHub Pages 使用 `main` 分支根目錄；`.nojekyll` 保留靜態檔案。首頁直接索引七個教材資料夾，新增教材時須同步更新首頁與本表。以瀏覽器開發工具檢查 console，並測試手機版、跳段、暫停、字幕與測驗。

製作日期：2026-10-11（Asia/Taipei）。
