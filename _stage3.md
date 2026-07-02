# Stage 3 Demo Walkthrough · 抵Buy 原型示範

## Opening
「接下來，讓我們看看抵Buy 的兩個核心功能實際運作。」

> Next, let’s see how 抵Buy’s two core features work in action.

---

## 1. 餐廳優惠搜尋 · Restaurant Discount Search

**導頁：** 打開 `discounts.html`

> 「抵Buy 第一個功能，是幫你集中搜羅身邊的餐廳優惠。」

>抵Buy’s first feature is a one-stop restaurant discount search.

**頁面介紹：**
- 頂部有 抵Buy 品牌標誌與「餐廳優惠 · Restaurant Deals」主題標籤。
- 中央是一個大搜尋框，提示用戶可以輸入菜式或餐廳名稱。
- 下方以卡片形式展示 20 間示範餐廳，分為意大利菜、日本菜、墨西哥菜三大類。

> The page shows the 抵Buy brand, a large search box, and 20 sample restaurant cards across Italian, Japanese, and Mexican cuisines.

**示範步驟：**
1. **清空搜尋：** 頁面載入後，會顯示全部 20 間餐廳。標註為「推薦 Suggested」的餐廳會以黃色底、皇冠貼紙突顯，方便用戶快速識別精選商戶。
2. **搜尋菜式：** 在搜尋框輸入 `Italian`。結果會即時篩選，並把意大利菜類別中的「推薦」餐廳 `Mamma Mia Pizzeria` 排在最頂。
3. **搜尋特定餐廳：** 輸入 `Mamma Mia`。除了找到該餐廳，系統還會在同類別中推薦另一間精選意大利餐廳，讓用戶有替代選擇。
4. **點擊卡片：** 每張卡片顯示餐廳名稱、菜式、評分、地區，以及優惠類型，例如 `20% off`、`$20 off` 或 `Buy 2 Get 1 Free`。

> Demo steps:
> 1. Show all 20 restaurants on load; suggested picks are highlighted in yellow with a crown badge.
> 2. Type `Italian` — the suggested Italian restaurant is pinned to the top.
> 3. Type `Mamma Mia` — the exact match appears first, plus a similar suggested alternative.
> 4. Each card shows name, cuisine, rating, location, and discount type.

**重點：**
- AI 會根據關鍵字、菜式標籤和優惠內容進行相關性排序。
- 即使輸入模糊的關鍵字，「推薦」商戶也會優先顯示，幫用戶省時決策。

> The AI ranks results by keyword, cuisine tags, and discount labels, always pinning the suggested pick for the matched cuisine.

---

## 2. 網購比價守護 · Online Shopping Price Guard

**導頁：** 打開 `shopping.html`

> 「抵Buy 第二個功能，是當你網上購物時，自動幫你格價。」

>抵Buy’s second feature automatically compares prices while you shop online.

**頁面介紹：**
- 畫面中央是一個 20:9 的手機外框，模擬真實購物 App。
- 首頁是「每日用品 · Daily Essentials」商品列表，包括牙刷、長褲、洗髮水、電飯煲等。

> The screen shows a 20:9 phone mockup with a shopping-app home page listing daily essentials.

**示範步驟：**
1. **選擇商品：** 點擊任何商品，例如「軟毛牙刷」。畫面會進入該商品的結賬頁面，顯示：
   - 商品名稱與圖示
   - 價格 Price
   - 運費 Shipping
   - 預計到貨時間 ETA
   - 送貨地址與倉庫地址
   - 總計 Total
2. **按下 Checkout 結賬：** 當用戶準備付款時，抵Buy 的 AI 價格守護會即時彈出 iPhone 風格通知。
3. **通知內容：** 通知會顯示 Daibuy 圖示，並清楚寫出：
   - 發現更抵價！Cheaper price found
   - 更便宜來源，例如 Pinduoduo / Taobao
   - 更便宜價格，例如 HK$19
   - 用戶可節省的金額

> Demo steps:
> 1. Tap a product, e.g., the toothbrush, to open its checkout page with price, shipping, ETA, addresses, and total.
> 2. Tap **Checkout 結賬**.
> 3. An iPhone-style Daibuy notification slides down showing a cheaper source and price.

**重點：**
- 這個功能模擬了抵Buy 如何在用戶結賬前一刻介入，避免他們買貴。
- AI 會比較不同平台價格、運費，並考慮送貨時間，給出真正最划算的選擇。

> This demonstrates how 抵Buy intervenes right before checkout to stop users from overpaying, comparing platform prices, shipping, and delivery time.

---

## Closing

> 「透過這兩個原型，你可以看到抵Buy 如何同時照顧線下優惠與線上購物，讓慳錢變得簡單。」

> With these two prototypes, you can see how 抵Buy handles both offline discounts and online shopping, making saving money simple.
