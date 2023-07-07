# CHC101發起的專案說明文件

**CHC101好棒**


![markdown](https://www.mdeditor.tw/images/logos/markdown.png "markdown")


Markdown是一種可以使用普通文字編輯器編寫的標記語言，通過簡單的標記語法，它可以使普通文字內容具有一定的格式。它允許人們使用易讀易寫的純文字格式編寫文件，然後轉換成格式豐富的HTML頁面，Markdown檔案的字尾名便是“.md”


## MdEditor是一個線上編輯Markdown文件的編輯器

*MdEditor擴充套件了Markdown的功能（如表格、腳註、內嵌HTML等等），以使讓Markdown轉換成更多的格式，和更豐富的展示效果，這些功能原初的Markdown尚不具備。*

> Markdown增強版中比較有名的有Markdown Extra、MultiMarkdown、 Maruku等。這些衍生版本要麼基於工具，如~~Pandoc~~，Pandao；要麼基於網站，如GitHub和Wikipedia，在語法上基本相容，但在一些語法和渲染效果上有改動。

MdEditor源於Pandao的JavaScript開源專案，開源地址[Editor.md](https://github.com/pandao/editor.md "Editor.md")，並在MIT開源協議的許可範圍內進行了優化，以適應廣大使用者群體的需求。向優秀的markdown開源編輯器原作者Pandao致敬。


![Pandao editor.md](https://www.mdeditor.tw/images/editormd-logo-180x180.png "Pandao editor.md")



## MdEditor的功能列表演示

# 標題H1

## 標題H2

### 標題H3

#### 標題H4

##### 標題H5

###### 標題H5

### 字元效果和橫線等
----

~~刪除線~~ <s>刪除線（開啟識別HTML標籤時）</s>

*斜體字*      _斜體字_

**粗體**  __粗體__

***粗斜體*** ___粗斜體___

上標：X<sub>2</sub>，下標：O<sup>2</sup>

**縮寫(同HTML的abbr標籤)**
> 即更長的單詞或短語的縮寫形式，前提是開啟識別HTML標籤時，已預設開啟

The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.
### 引用 Blockquotes

> 引用文字 Blockquotes

引用的行內混合 Blockquotes

> 引用：如果想要插入空白換行`即<br />標籤`，在插入處先鍵入兩個以上的空格然後回車即可，[普通連結](https://www.mdeditor.tw/)。

### 錨點與連結 Links
[普通連結](https://www.mdeditor.tw/)
[普通連結帶標題](https://www.mdeditor.tw/ "普通連結帶標題")
直接連結：<https://www.mdeditor.tw>
[錨點連結][anchor-id]
[anchor-id]: https://www.mdeditor.tw/
[mailto:test.test@gmail.com](mailto:test.test@gmail.com)
GFM a-tail link @pandao
郵箱地址自動連結 test.test@gmail.com  www@vip.qq.com
> @pandao

### 多語言程式碼高亮 Codes

#### 行內程式碼 Inline code


執行命令：`npm install marked`

#### 縮排風格

即縮排四個空格，也做為實現類似 `<pre>` 預格式化文字 ( Preformatted Text ) 的功能。

    <?php
        echo "Hello world!";
    ?>
預格式化文字：

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

#### JS程式碼
```javascript
function test() {
    console.log("Hello world!");
}
```
