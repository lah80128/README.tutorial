# Markdown.tutorial
### Markdown學習筆記

## 目錄
  * [標題](#2)
  * [分隔線](#3)
  * [字體變化](#4)
  * [清單列表](#5)
  * [引言區塊](#6)
  * [連結](#7)
  * [參考網站](#8)

===========================================

### <a name="2"/>標題 
Markdown支援的標題語法有兩種,一種為在行首加上\#字號

\#越多代表標題大小越小,可以放入1-6個\#字號

    # 標題一
    ## 標題二
    ### 標題三
另一種為,加上底線的形式,`=`或者`-`

    標題一
    ======
    標題二
    ------
### <a name="3"/>分隔線 
由三個(含)以上的`*`或`-`來製造一個橫軸直線

    ***
    * * *
    ---
    --------
上面四種表示方式,呈現出一樣的結果

---
### <a name="4"/>字體變化 

    *斜體*
    **粗體**
    ~~刪除線~~
    ***斜粗體***
*斜體*
**粗體**
~~刪除線~~
***斜粗體***
### <a name="5"/>清單列表
清單列表除了使用`*`作為清單標記之外,也可以使用`+`或者`-`,呈現出相同結果

    * 項目一
    + 項目一
    - 項目一
        * 項目一
          * 項目一 
 * 項目一
 + 項目一
 - 項目一
    * 項目一
      * 項目一

還有順序性的數字列表

    1. 項目一
    2. 項目二
1. 項目一
2. 項目二

### <a name="6"/>引言區塊 
當文章中引用經典名言時可以在行首加上`>`
多個`>`代表不同引言層

    > 一閃一閃亮晶晶
    >> 滿天都是小星星
    
> 一閃一閃亮晶晶         
>> 滿天都是小星星

### <a name="7"/>連結 

    I get 10 times more traffic from [Google] [1] than from
    [Yahoo] [2] or [MSN] [3].
      [1]: http://google.com/        "Google"
      [2]: http://search.yahoo.com/  "Yahoo Search"
      [3]: http://search.msn.com/    "MSN Search"
I get 10 times more traffic from [Google] [1] than from [Yahoo] [2] or [MSN] [3].
  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"
另外插入圖片的用法也是差不多的

    TAIWAN FLAG ![flag][id]
    [id]: http://thumbs.dreamstime.com/t/taiwan-flag-6333294.jpg "No.1"
 TAIWAN FLAG ![flag][id]
 [id]: http://thumbs.dreamstime.com/t/taiwan-flag-6333294.jpg "No.1"
### <a name="8"/>參考網站 
Markdown官方中文介紹: <http://markdown.tw/>
