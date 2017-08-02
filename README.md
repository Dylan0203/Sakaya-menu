Sakya 操作手冊
---------------------------
*	[帳戶](#account)
	* [登入](#login)
	* [登出](#logout)
	* [變更密碼](#logout)
	* [操作記錄](#admin-log)
*	[訂單管理](#order-management)
	* [訂單搜尋](#order-search)
	* [訂單進階搜尋](#order-adv-search)
	* [訂單匯出](#order-export)
	* [訂單操作](#order-opration)
 	* [訂單狀態說明](#order-status)
 	* [訂單刷退](#order-refund)
*	[酒品](#sake)
	* [酒品管理](#sake-management)
		* [新增酒品](#sake-new)
		* [適飲溫度](#sake-drink-temp)
		* [編輯、刪除酒品](#sake-edit)
		* [新增酒品規格](#sake-variant)
		* [編輯、刪除酒品規格](#sake-variant-edit)
	* [酒造管理](#sake-institue)
	* [酒品分類管理](#sake-category)
*	[一般商品](#noraml)
	* [一般商品管理](#normal-management)
	* [一般商品規格管理](#normal-variant)
	* [一般商品分類](#normal-category)
*	[加購商品](#add-on-product)
	* [加購商品管理](#add-on-product-management)
*	[用戶](#users)
	* [手動付款](#mamual-payment)
*	[橫幅](#banners)
*	[新聞](#news)
*	[知識](#knowledge)
*	[購物須知](#shopping-terms)

[ＰＤＦ下載連結](https://github.com/Dylan0203/Sakaya-menu/raw/master/README.pdf)

--------------------------------------

<h2 id="account">帳戶</h2>

<h3 id='login'> 登入 </h3>

<img src='.\images\001.png' width="50%">

登入網址：[https://www.sakaya.life/admins/sign_in](https://www.sakaya.life/admins/sign_in)

---

<h3 id='logout'> 登出 與 變更密碼 </h3>

<img src='.\images\002.png' width="50%">

登入後點擊右上角的admin按鈕即可顯示變更密碼與登出按鈕

<img src='.\images\003.png' width="50%">

在輸入新密碼後，請在最下方欄位輸入當前密碼並按更新以完成操作

---

<h3 id='admin-log'>操作記錄</h3>

<img src='.\images\004.png' width="100%">

在首頁或左方資訊頁籤進入資訊頁面，點擊下方admin Logger視窗右上角即可打開操作記錄

---

<h2 id="order-management">訂單管理</h2>

<img src='.\images\005.png' width="70%">

訂單管理在左方頁籤『訂單』中，點擊打開分類列表

---

<h3 id='order-search'> 訂單搜尋 </h3>

訂單可在兩處搜尋，一是如下圖在頁籤最上方即可輸入訂單的

* 訂單編號
* 收件人
* 電話
* 手機

任一去快速搜尋符合條件的訂單

<img src='.\images\006.png' width="50%">

---

<h3 id='order-adv-search'> 訂單進階搜尋 </h3>

第二是進階搜尋：
訂單分類列表中的第一項『訂單管理』，點擊後即有訂單進階搜尋操作視窗

<img src='.\images\007.png' width="100%">

進階搜尋可定義多重搜尋條件，只有符合所有條件的訂單才會出現，
可搜尋條件分別為：

* 訂單編號 包含
* 訂單成立時間範圍
* 訂單收件人姓名 包含
* 訂單手機號碼 包含
* 訂單編號 包含
* 訂單狀態 必須為
* 商品規格編號 包含
* 酒品規格編號 包含

-
!! 注意 !! 酒類商品與一般商品不會出現在同一訂單內，同時輸入酒類規格編號與一般商品規格編號將不會得到任何結果。

---

<h3 id='order-export'>訂單匯出</h3>

在訂單頁籤內的訂單管理頁面，點擊搜尋按鈕旁的下載ＥＸＣＥＬ可匯出以目前搜尋結果的訂單列表與詳細資訊。

<img src='.\images\008.png' width="100%">

---

<h3 id='order-opration'>訂單操作</h3>

<img src='.\images\009.png' width="100%">

變更訂單狀態的按鈕，顯示在訂單列表中最右邊的欄位中，按下即可更新訂單狀態。

<img src='.\images\011.png' width="100%">

點擊查看詳細訂單內容按鈕後，在訂單詳細頁面裡的右上方也會出現訂單狀態轉換按鈕!


！！注意，訂單狀態變更後無法回復先前狀態，操作前請注意說明提示。
-

<img src='.\images\010.png' width="100%">

---

<h3 id='order-status'>訂單狀態說明</h3>



* 訂單成立後 狀態為 未付款
	*	當訂單成立但未付款前，一般使用者與管理員皆可自行取消訂單

		<img src='.\images\013.png' width="50%">

	--

	*	管理員可將未付款訂單轉換成已付款

		<img src='.\images\012.png' width="50%">

	--

* 訂單付款後 狀態為 待發貨
	*	管理員可將待發貨訂單轉換成已發貨

		<img src='.\images\014.png' width="50%">

	--

* 訂單發貨後 狀態為 已發貨
	*	管理員可將已發貨訂單轉換成已到貨

		<img src='.\images\015.png' width="50%">

	--

* 訂單到貨後 狀態為 已到貨
	*	當訂單已到貨後，一般使用者可申請退貨或是申請換貨

		<img src='.\images\016.png' width="50%">

	--

	*	當訂單已到貨後，管理員可手動轉換訂單狀態至申請退貨或是申請換貨

		<img src='.\images\017.png' width="50%">
	--

* 訂單 狀態為 申請退貨或是申請換貨
	*	當訂單已到貨後，管理員可手動轉換訂單狀態至已退貨或是已換貨

		<img src='.\images\018.png' width="50%">
	--

	黃色標籤為等待管理員處理的提示顏色

	<img src='.\images\019.png' width="50%">

---
<h3 id='order-refund'>訂單刷退</h3>

<img src='.\images\054.png' width="50%">

當訂單為信用卡付款時，在訂定單的詳細頁面裡就會出現“執行信用卡退款”的紅色按鈕，

- 如未請款，系統會取消授權

- 如已請款，系統會執行退款流程

執行完畢後，原本退款按鈕的位置則會顯示退款的結果如下圖:

<img src='.\images\055.png' width="50%">

---

<h2 id="sake">酒品</h2>

<h3 id='sake-management'>酒品管理</h3>

<img src='.\images\020.png' width="100%">

點擊左側酒品頁籤即可打開選單，點選第一項酒品管理即可進入酒品管理介面

<h3 id='sake-new'>新增酒品</h3>

點擊在酒品管理介面右上角新增酒品按鈕即可進入新增頁面

請依序選擇與填入：

* 所屬酒造
* 所屬酒類
* 品名
* 英文品名
* 封面圖片
* 米種
* 精米步合
* 酒精濃度
* 香氣
* 適飲溫度低
* 適飲溫度高
* 產品敘述（編輯器）
* 特別推薦（編輯器）
* 選擇 味
* 選擇 酒體

<img src='.\images\021.png' width="100%">

<img src='.\images\022.png' width="100%">

！！！注意 新增酒品之前請先新增所屬酒造，酒品分類可不選，但就不會出現在酒品分類的頁面中

<img src='.\images\023.png' width="100%">

---

<h3 id='sake-drink-temp'>適飲溫度</h3>

<img src='.\images\057.png' width="100%">

在填寫溫度時，

適飲溫度(一)會產生藍色的適飲溫度範圍

適飲溫度(二)會產生橘紅色的適飲溫度範圍

可以只填一種，請依照溫度範圍斟酌使用。


<img src='.\images\056.png' width="100%">


---

<h3 id='sake-edit'>編輯、刪除酒品</h3>

<img src='.\images\024.png' width="100%">

酒品 -> 酒品管理

點擊列表右側對應按鈕即可編輯與刪除酒品

！！！注意 刪除酒品，此酒品列表底下所有規格的產品也會一並刪除

---

<h3 id='sake-variant'>新增、編輯、刪除酒品規格</h3>

<img src='.\images\025.png' width="50%">

在酒品管理介面列表中先找到要新增或規格的酒品，點擊右方操作按鈕的『新增酒品規格』

<img src='.\images\026.png' width="70%">

在跳出的對話框依序輸入

* 產品編號
* 容量｜禮盒
* 價格
* 選擇可選購開關
* 選擇可顯示開關

！！注意 關閉可選購開關，產品規格依舊顯示，但無法加入購物車或是購買
**就算已經在購物車的產品，一但在未成立訂單前轉換為不可選購，系統會在送出訂單時自動把不可購買的規格從購物車中刪除）**

！！只關閉顯示，購物車裡已存在的商品規格依然可以跟訂單一起送出！！


---

<h3 id='sake-variant-edit'>編輯、刪除酒品規格</h3>

<img src='.\images\027.png' width="100%">

在酒品管理介面列表中先找到要編輯或刪除的規格的酒品，點擊右方操作按鈕的『編輯』or 『刪除』

<img src='.\images\028.png' width="100%">

不顯示於網站的商品規格將會如上圖分開表示

---

<h3 id='sake-institue'>酒造管理</h3>

<img src='.\images\029.png' width="100%">

點擊酒品頁籤內的酒造管理選單即可進入酒造管理介面
新增酒造請點擊畫面右上角的『新增酒造』按鈕

依序輸入：

* 酒造名稱
* 酒造圖示
* 酒造敘述

更新與編輯請選擇列表右方的對應按鈕

<img src='.\images\030.png' width="100%">

**！！注意 刪除酒造會讓全部所屬的酒類商品一併刪除，酒造刪除後無法回覆！**

---

<h3 id='sake-category'>酒品分類管理</h3>

<img src='.\images\031.png' width="100%">

* 點擊酒品頁籤內的酒品分類管理選單即可進入酒品分類管理介面
新增酒品請點擊畫面右上角的『新增酒品分類』按鈕

	輸入酒品類別的名稱ex. 啤酒

* 更新與刪除特定分類請選擇列表右方的對應按鈕

<img src='.\images\032.png' width="100%">

---

<h2 id="noraml">一般商品</h2>

<h3 id='normal-management'>一般商品管理</h3>

<img src='.\images\033.png' width="100%">

* 點擊一般商品頁籤內的一般商品管理選單即可進入一般商品管理介面
新增一般商品請點擊畫面右上角的『新增一般商品』按鈕

請依序輸入：

* 選擇商品類別
* 品名
* 英文品名
* 上傳封面
* 商品敘述（編輯器）
* 商品介紹（編輯器）

<img src='.\images\034.png' width="100%">

<img src='.\images\036.png' width="100%">

---

<h3 id='normal-variant'>新增、編輯、刪除酒品規格</h3>

請參考[酒品規格管理](#sake-variant)

<img src='.\images\037.png' width="100%">

---

<h3 id='normal-category'>一般商品分類</h3>

<img src='.\images\035.png' width="50%">

一般商品分類共有三大類
*美妝、食物、容器*
各自有自己的分頁方便管理，而第一個分頁列出所有的一般商品，方便快速操作所有商品。

---

<h2 id="add-on-product">加購商品</h2>

<h3 id='add-on-product-management'>加購商品管理</h3>

<img src='.\images\060.png' width="100%">

左方加購商品頁籤內有分

- 酒類加購
- 一般加購

兩種加購品個別只可以有三個商品同時上架

<img src='.\images\061.png' width="50%">

兩種加購品可分別設定顯示給不同身份的使用者購買共三種

- 『ＶＩＰ』，只有ＶＩＰ可加購
- 『一般會員』，只有一般會員可加購
- 『共通』，ＶＩＰ與一般會員都可加購

<img src='.\images\062.png' width="100%">

-
*注意，加購品新增後預設為下架狀態，請按上架按鈕開放加購*

---

<h2 id="users">用戶</h2>

<img src='.\images\038.png' width="100%">

點擊左側用戶頁籤即可進入用戶列表，列表右側會員詳細資料按鈕可進入查看用戶資訊

<img src='.\images\039.png' width="100%">

<h3 id='manual-payments'>手動付款</h3>

<img src='.\images\063.png' width="100%">

點擊消費紀錄按鈕即可進入該用戶手動付款頁面

其中畫面最上方會顯示該用戶 *一年內* 的消費總金額

其次為手動付款輸入框

新增手動付款記錄請依照需求填入相關資訊

- 發票/訂單號碼
- 金額
- 其他/備註


再來兩份列表記錄為：

- 信用卡付款紀錄
- 手動付款紀錄

兩份列表顯示 *所有* 歷史消費金額的紀錄，列表開頭顯示數字為金額加總

-

*手動付款無法刪除，如有金額輸入錯誤，請再新增一筆負數金額抵銷錯誤，或請聯絡網站管理員協助。*

*如有誤植金額造成用戶成為ＶＩＰ，請聯絡網站管理員重設該用戶ＶＩＰ到期時間*

*信用卡退款並不會自動扣除付款總金額，請使用手動付款將金額抵銷，如須重設ＶＩＰ到期時間，請聯絡管理員*

---

<h2 id="banners">橫幅</h2>

<img src='.\images\040.png' width="100%">

點擊左側橫幅頁籤即可進入橫幅管理介面，右上方按鈕可新增橫幅，列表右側為橫幅個別更新與刪除按鈕

**當橫幅在同一位置出現超過一個，版面會轉成SlideShow**

<img src='.\images\041.png' width="70%">

橫幅新增、修改視窗內請依序填入：

* 背景圖
* 位置
	* 網站首頁
	* 商品首頁
	* 一般商品
	* 酒類商品
	* 新聞首頁
	* 知識首頁

	<img src='.\images\042.png' width="70%">

	『位置』下拉選匡可選擇想要橫幅出現的頁面

* 標題一
* 標題二
* 連結網址

<img src='.\images\043.png' width="100%">

**連結網址留空則不會出現『了解更多』超連結按鈕**

<img src='.\images\044.png' width="50%">

<img src='.\images\045.png' width="50%">

---

<h2 id="news">新聞</h2>

<img src='.\images\046.png' width="100%">

點擊左側新聞頁籤即可進入橫幅管理介面，右上方按鈕可新增新聞，列表右側為新聞個別更新與刪除按鈕

新聞新增、修改視窗內請依序填入：

* 標題
* 上傳 文章封面
* 內容（編輯器）

<img src='.\images\047.png' width="70%">

<img src='.\images\048.png' width="100%">

---

<h2 id="knowledge">知識</h2>

<img src='.\images\050.png' width="100%">

點擊左側知識頁籤即可進入橫幅管理介面，右上方按鈕可新增知識，列表右側為知識個別詳細內容、更新與刪除按鈕

知識新增、修改視窗內請依序填入：

* 標題
* 上傳 文章封面
* 選擇知識種類
	* 清酒酒造
	* 糯米
	* 酒藏故事

	<img src='.\images\051.png' width="50%">

	『種類』下拉選框選擇知識種類

* 內容（編輯器）

<img src='.\images\053.png' width="100%">

<img src='.\images\049.png' width="100%">

<img src='.\images\052.png' width="100%">

---

<h2 id="shopping-terms">購物須知</h2>

<img src='.\images\058.png' width="100%">

點擊左側購物須知設定即可進入編輯器，更新完畢請務必至網站前端觀看排版效果，基於安全因素編輯器產生的部分效果可能會被自動過濾。

<img src='.\images\059.png' width="100%">