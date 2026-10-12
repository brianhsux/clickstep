---
title: Clickstep 隱私權政策 / Privacy Policy
permalink: /privacy/
---

<!-- 來源：AiClick repo 的 docs/privacy-policy.md，修改時請改來源再複製過來。 -->

# Clickstep 隱私權政策

生效日期：2026 年 10 月 12 日

Clickstep（以下稱「本 App」）由 brianhsux 開發。本政策說明本 App 如何處理你的資料。

## 摘要

- 本 App **不蒐集、不上傳、也不分享**任何個人資料。
- 本 App **沒有申請網路權限**，技術上無法把任何資料傳出你的手機。
- 沒有帳號、廣告、數據分析或第三方追蹤工具。

## 本 App 存取哪些資料、用來做什麼

### 無障礙服務（AccessibilityService API）

本 App 使用 Android 無障礙服務，**只**用於以下兩件事：

1. **自動點擊**：依照你事先排好的座標與順序，在畫面上執行點擊手勢。
2. **截取畫面比對顏色**：當你的步驟設定了「色點」或「畫面狀態」條件時，本 App 會截取當下畫面，比對你指定位置的顏色，判斷要不要點擊或該點哪裡。

截圖只存在手機記憶體中，比對完就立即丟棄，不會存檔，也不會傳出手機。
本 App 不會讀取畫面上的文字內容，也不會讀取你的帳號、密碼或你輸入的文字。

只有在你看過 App 內的說明並同意後，本 App 才會引導你到系統設定開啟無障礙服務。你可以隨時在系統設定中關閉它。

### 你建立的流程與畫面範本

你建立的流程、任務、點擊座標、延遲時間與色點設定，會存在本 App 的私有儲存空間中。
如果你使用「畫面」或「看到這塊圖再點」步驟並框選了畫面區域，本 App 會把該區域縮小後的小圖（最長邊 96 像素）存成範本，同樣只存在手機中。

這些資料只有本 App 能讀取。解除安裝本 App 時，這些資料會一併刪除。

### 匯出與匯入

你可以在 App 裡把資料匯出成一個 zip 檔，存放位置由你在系統視窗中選擇（例如手機的下載資料夾或你的雲端硬碟）。匯出與匯入都只在你操作時進行，開發者無法取得這些檔案。

### Android 系統備份

如果你在手機上開啟了 Android 的系統備份功能，Android 可能會把本 App 的資料（上述流程設定與範本）備份到**你自己的** Google 帳號。這是由 Android 系統與你的帳號設定處理，開發者無法存取這些備份。

### 付費功能（Clickstep Pro）

Clickstep Pro 的訂閱與一次買斷都由 **Google Play** 處理，付款資料（例如信用卡）由 Google 保管，本 App 和開發者都拿不到。
本 App 透過 Google Play 帳款服務程式庫（Google Play Billing Library），向手機上的 Play 商店 App 查詢你是否擁有 Pro，只取得「擁有哪一種方案、是否有效」，並把結果存在手機裡，讓沒有連線時也能使用。
這個查詢只在手機內進行，本 App 仍然沒有網路權限。Google Play 如何處理你的付款資料，適用 Google 的隱私權政策。

### 其他權限

- **顯示於其他應用程式上層**：用來在畫面上顯示可拖移的步驟圓圈和執行中的停止按鈕。
- **前景服務**：在你排列步驟或執行流程時保持運作，並顯示通知讓你隨時停止。
- **通知**：顯示「正在排列」或「正在回放」的狀態，以及停止按鈕。

## 兒童隱私

本 App 並非以兒童為對象，也不會蒐集任何人的個人資料，包括兒童。

## 政策變更

如果本 App 日後的資料處理方式有所改變（例如加入當機回報），我們會更新本政策並修改上方的生效日期。重大變更會在 App 更新說明中告知。

## 聯絡我們

如果對本政策有任何問題，請來信：brianhsudev@gmail.com

---

# Clickstep Privacy Policy

Effective date: October 12, 2026

Clickstep ("the app") is developed by brianhsux. This policy explains how the app handles your data.

## Summary

- The app **does not collect, upload, or share** any personal data.
- The app **does not request the Internet permission**, so it cannot send any data off your device.
- There are no accounts, ads, analytics, or third-party trackers.

## What the app accesses and why

### Accessibility Service (AccessibilityService API)

The app uses the Android Accessibility Service **only** to:

1. **Perform taps** at the positions and in the order you have set up.
2. **Capture the screen to compare colors**, when a step uses a "color point" or "screen state" condition, to decide whether or where to tap.

Screenshots are kept in memory only and discarded immediately after comparison. They are never saved or sent off the device.
The app does not read on-screen text, and does not read your accounts, passwords, or anything you type.

The app only takes you to the system settings to enable the service after you have read the in-app explanation and agreed. You can turn it off at any time in system settings.

### Flows and screen templates you create

Flows, tasks, tap positions, delays, and color settings you create are stored in the app's private storage.
If you use "screens" or a "Tap when image matches" step and select a screen region, a downscaled image of that region (at most 96 pixels on the longest side) is saved as a template, also only on your device.

Only the app can read this data. It is deleted when you uninstall the app.

### Export and import

You can export your data as a zip file from within the app and choose where to save it (for example, your device's Downloads folder or your own cloud drive). Export and import only happen when you choose to, and the developer cannot access these files.

### Android system backup

If you have enabled Android system backup, Android may back up the app's data (the flows and templates above) to **your own** Google account. This is handled by Android and your account settings; the developer cannot access these backups.

### Paid features (Clickstep Pro)

Clickstep Pro subscriptions and the one-time purchase are handled by **Google Play**. Payment details (such as your card) are kept by Google; neither the app nor the developer can see them.
The app uses the Google Play Billing Library to ask the Play Store app on your device whether you own Pro. It only receives which plan you own and whether it is active, and stores that result on your device so Pro works offline.
This check happens on your device, and the app still has no Internet permission. Google's privacy policy applies to how Google Play handles your payment information.

### Other permissions

- **Display over other apps**: shows draggable step markers and a stop button while running.
- **Foreground service**: keeps arranging or playback running and shows a notification so you can stop at any time.
- **Notifications**: shows arranging or playback status and a stop button.

## Children's privacy

The app is not directed at children and does not collect personal data from anyone, including children.

## Changes

If the way the app handles data changes (for example, adding crash reporting), this policy will be updated along with the effective date above.

## Contact

Questions about this policy: brianhsudev@gmail.com
