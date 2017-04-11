# Python 介紹
## Python 是互動式語言
1. Interactive mode
* 像 command line，輸入指令後馬上執行

2. Script mode
* 也能先將指令都寫成 script 後再執行
* 將下列指令寫入 test.py
```Python 
for x in range(2):
  print x
```

## Interactive mode
* 在終端機輸入 Python (如果你已安裝好 Python )，就能開始使用 Python 
* 出現 ... 表示 Python 還在等你輸入，只要輸入空白行就能讓它知道你已輸入完畢。
* 按 `Ctrl-D` 離開 Python，回到終端機。

## Script mode
* 預先將指令都寫入 test.py
* 在終端機輸入 `python test.py`
* 就會執行 test.py 內的指令
* 輸出結果為
```
0
1
```

## *Everything* is an object*
* function and data 都視為 object
* Dynamic type binding (動態型態繫結)
>> 不用先宣告型態，執行時才將變數名稱跟型態做連結，甚至同一個變數的形態可以變動。反之， Static type binding 的繫結時間是編譯階段。
```
x=5
x='string'
```
>> x 原本是整數型態，但之後丟入字串卻不會有錯誤訊息。
