# Financial-Big-Data_NTHU 金融大數據分析報告

## 市場背景：
#### 在這個科技日新月異的時代，人們開始更注重生活品質與便利，再加上前段時間疫情的影響，大衆開始對餐點外送這個服務有了大規模的需求，在街上時常都會看見不同外送平台的外送員在努力的工作趕往餐廳或送餐地點。隨著各種外送平台的不斷增加，市場上的競爭也越來越激烈，本篇分析報告將著重於研究FoodPanda外送平台並透過該平台上的數據進行分析。

## 研究動機：
#### foodpanda是德國的外賣企業Delivery Hero旗下的線上餐飲外送服務平台，於2012年創立，營業範圍覆蓋亞洲和歐洲等多個國家和地方。在台灣市場中foodpanda原本占據了大部分的外送市場份額，但隨後另一外送平台佼佼者Ubereats後來居上，在台灣市場中將foodpanda收購於其公司之下。這也就讓我更好奇foodpanda在這場競爭中落敗的原因。因此，本篇報告主要對從kaggle上獲取的foodpanda平台數據進行分析，並尋找出訂單量減少的原因及影響訂單量的因素、變量等，藉此探討影響foodpanda競爭力的原因。

## 資料集來源：https://www.kaggle.com/datasets/hashiromer/all-foodpanda-restaurants/data

## 數據字典：
#### budget：餐廳的預算等級，通常是數字表示，可能反映餐廳的價格範圍。
#####             1 - 代表低價位或經濟型選擇。
#####             2 - 代表中等價位，適合大部分顧客。 
#####             3 - 代表高價位或高端選擇。
#### is_new_until：餐廳被視為新店面的截止日期，通常使用日期时间格式。 （改成當作訂單時間？）
#### latitude：餐廳地理位置的緯度。 
#### longitude：餐廳地理位置的經度。 
#### minimum_delivery_time：完成送餐的最短時間，通常以分鐘或秒計。
#### minimum_order_amount：客戶需達到的最小訂單金額，以便進行送餐。
#### minimum_pickup_time：顧客在餐廳自取餐點的最短等待時間，通常以分鐘計。 
#### name：餐廳的名稱。 
#### post_code：餐廳所在地區的郵遞區號。 
#### rating：餐廳的平均評分，通常基於顧客評價。
#### review_number：餐廳收到的評論數量。 
#### review_with_comment_number：含有文字評論的評論數量。 
#### vertical：餐廳的業務類型或特定垂直市場類別。 
#### vertical_parent：餐廳業務類型的上一級分類。
#### delivery_provider：提供送餐服務的外部供應商或平台。
#####                   dine_in（内用）
#####                   platform_delivery(foodpanda送餐）
#####                   vendor_delivery （商家自家送餐服務） 
#### is_active：表示餐廳是否仍在營運的布林值。
#### is_new：表示餐廳是否為新開業的布林值。
#### is_promoted：表示餐廳是否進行過推廣活動的布林值。 
#### city：餐廳所在的城市。 
#### timezone：餐廳所在地的時區。
#### dine_in：表示餐廳是否提供堂食服務的布林值。
#### main_cuisine：餐廳主要提供的菜系類型。 
#### country：餐廳所在的國家。

