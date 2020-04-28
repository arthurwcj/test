
# 目錄{#top}

* [1.強調](#1.)

* [2.表格](#2.)

* [3.跳轉](#3.)

* [4.圖形與符號](#4.)

* [5.實例](#5.)
---

## 1.強調{#1.}

<table><tr><td bgcolor=orange><font size="5"><font color="#dd00dd">
字體顏色與背景調整</font></font></td></tr></table>


1.	登入選擇「以PTT帳號登入」

- 內文(變更遠端Git主機文件內容測試，PULL後，再上傳PUSH)

- 增加一句話，，，，

- 2^8^=256

*斜體* ， **粗體** ， ~~***刪除線***~~ ， <u>底線</u>   

>輕量級
>
>        文字內容
>文字內容
>>文字內容
>
>>>文字內容

- [X]A任務
- [ ]B任務     
- [ ] 


[回目錄](#top)

---

## 2.表格{#2.}

|公司分級評級等級|公司等級參數||
|:-:|--:|
|S級、A級|0.4|
|B級|0.3|
|
|

<table><tbody>
    <tr>
        <th>方法說明</th><th>顏色名稱</th><th>顏色</th>
    </tr>
    <tr>
        <td><font color="Coral">此處實現方法利用Markdown內嵌html語言的優勢</font>
        </td>
        <td><font color="Coral">Coral</font>
        </td>
        <td bgcolor="Coral">rgb(255, 127, 80)
        </td>
    </tr>
    <tr>
        <td><font color="CornflowerBlue">借助 table, tr, td 等表格標籤的 bgcolor 屬性</br>實現背景色設置</font>
        </td>
        <td><font color="CornflowerBlue">AntiqueWhite</font>
        </td>
        <td bgcolor="CornflowerBlue">rgb(100, 149, 237)
        </td>
    </tr>
</table>

<table><tbody>
    <tr>
        <th rowspan="3" bgcolor="Coral">合併三行</th>
        <th>第一列</th>
        <th bgcolor="CornflowerBlue"><font color="grey">第二列</th>
        <th>第三列</th>
    </tr>
    <tr>
        <td>第二行</td>
        <td>第二行</td>
        <td>第二行</td>
    </tr>
    <tr>
        <td>第三行</td>
        <td>第三行</td>
        <td>第三行</td>
    </tr>
</table>

[回目錄](#top)

---

## 3.跳轉{#3.}

連結[Google](https://www.google.com/ "google")網頁

使用 ^[[註1]](https://www.pts.org.tw/ "公視")^ 可以連結到公視

使用 ^[1](#1. "1.強調")^ 可以跳到1.

[回目錄](#top)

---

## 4.圖形與符號{#4.}

![](C:/Users/art/Pictures/伺服器主機惡意活動檢視.PNG "伺服器")
![](C:/Users/art/Pictures/特殊符號-1.PNG )
![](C:/Users/art/Pictures/特殊符號-2.PNG )
![](C:/Users/art/Pictures/特殊符號-3.PNG )

[回目錄](#top)

----

## 5.實例{#5.}


```# 公服暨行銷部收益分成結算系統」資料庫(拿掉前面三個小點就會正常呈現)

## 資料庫表格

### 節目相關產品資料

|欄位|說明|鍵值|備註
|:--|:-:|
|ProductID|進銷存系統中產品的料號<br/>，第一碼為 'R' 為版權收入<br/>，其他為視聽產品|PK
|ProgramID|節目管理系統中的節目編號|PK
|Ratio|節目結構比例</br> (該產品中該節目所佔比例)
|Memo|備註
|Updator|資料最後異動者的使用者帳號| FK|tblUser:Account
|UpdateTime|資料最後異動時間

[回目錄](#top)

2020.03.06
