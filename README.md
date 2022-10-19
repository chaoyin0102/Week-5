# Week-5

### 要求⼆：建立資料庫和資料表
![request-2](/week5-img/request-2.png)

<hr/>

### 要求三：SQL CRUD
1. 使⽤ INSERT 指令新增⼀筆資料到 member 資料表中，這筆資料的 username 和 password 欄位必須是 test。接著繼續新增⾄少 4 筆隨意的資料。<br/>
![request-3-1](/week5-img/request-3-1.png)

2. 使⽤ SELECT 指令取得所有在 member 資料表中的會員資料。<br/>
![request-3-2](/week5-img/request-3-2.png)

3. 使⽤ SELECT 指令取得所有在 member 資料表中的會員資料，並按照 time 欄位，由近到遠排序。<br/>
![request-3-3](/week5-img/request-3-3.png)

4. 使⽤ SELECT 指令取得 member 資料表中第 2 ~ 4 共三筆資料，並按照 time 欄位，由近到遠排序。( 並非編號 2、3、4 的資料，⽽是排序後的第 2 ~ 4 筆資料 )<br/>
![request-3-4](/week5-img/request-3-4.png)

5. 使⽤ SELECT 指令取得欄位 username 是 test 的會員資料。<br/>
![request-3-5](/week5-img/request-3-5.png)

6. 使⽤ SELECT 指令取得欄位 username 是 test、且欄位 password 也是 test 的資料。<br/>
![request-3-6](/week5-img/request-3-6.png)

7. 使⽤ UPDATE 指令更新欄位 username 是 test 的會員資料，將資料中的 name 欄位改成 test2。<br/>
![request-3-7](/week5-img/request-3-7.png)

<hr/>

### 要求四：SQL Aggregate Functions
1. 取得 member 資料表中，總共有幾筆資料 ( 幾位會員 )。<br/>
![request-4-1](/week5-img/request-4-1.png)

2. 取得 member 資料表中，所有會員 follower_count 欄位的總和。<br/>
![request-4-2](/week5-img/request-4-2.png)

3. 取得 member 資料表中，所有會員 follower_count 欄位的平均數。<br/>
![request-4-3](/week5-img/request-4-3.png)

<hr/>

### 要求五：SQL JOIN (Optional)
1. 在資料庫中，建立新資料表紀錄留⾔資訊，取名字為 message。資料表中必須包含以下欄位設定：<br/>
![request-5-1](/week5-img/request-5-1.png)
2. 使⽤ SELECT 搭配 JOIN 語法，取得所有留⾔，結果須包含留⾔者會員的姓名。<br/>
![request-5-2](/week5-img/request-5-2.png)
3. 使⽤ SELECT 搭配 JOIN 語法，取得 member 資料表中欄位 username 是 test 的所有留⾔，資料中須包含留⾔者會員的姓名。<br/>
![request-5-3](/week5-img/request-5-3.png)
4. 使⽤ SELECT、SQL Aggregate Functions 搭配 JOIN 語法，取得 member 資料表中欄位 username 是 test 的所有留⾔平均按讚數。<br/>
![request-5-4](/week5-img/request-5-4.png)
