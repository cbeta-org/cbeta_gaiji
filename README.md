# cbeta_gaiji 

## CBETA 缺字資料庫

### 底下為缺字資料庫各欄位說明

* ID : CBETA 缺字代碼。

* unicode : Unicode 內碼。

* uni_char : Unicode 文字。此字內碼就是「Unicode 內碼」。

* norm_unicode : 通用 Unicode 內碼，此缺字在 [Unicode 網站](http://www.unicode.org/charts/unihan.html "Unicode UniHan") 的圖形與本字非常接近，但不完全相同，故列為通用的 Unicode。

* norm_uni_char : 通用 Unicode 文字，此字內碼就是「通用 Unicode 內碼」。

* composition : CBETA 缺字組字式。詳細說明請見 [CBETA 網站](http://www.cbeta.org/format/rare-rule.php "CBETA 組字式基本規則")的說明。

* norm_big5_char : 此缺字在 Big5 字集中的通用字。

* moe_variant_id : [教育部異體字字典網站](http://dict.variants.moe.edu.tw/variants/rbt/home.do "教育部異體字字典")的編號。

* pua : 預計使用 Unicode 私人用區的位置，內容為 0xF0000 + ID代碼。

### 備註說明：

* unicode 與 uni_char 為一組，norm_unicode 與 norm_uni_char 為一組，這二組不會同時有資料。

* 沒有呈現的欄位表示沒有資料。

---

# cbeta_sanskrit

## CBETA 梵字資料庫

### 底下為梵字資料庫各欄位說明

* ID : 梵字代碼。悉曇字格式為 SD-XXXX，蘭扎字格式為 RJ-XXXX。(XXXX 為16進位)。

* char : 直接呈現的字型 (此 char 即 XXXX 在 big5 字集的內碼所呈現的文字)。

* pua : 預計使用 Unicode 私人用區的位置。悉曇字為 0xFA000 + XXXX。蘭扎為 0x100000 + XXXX。

* romanized : 此梵字的羅馬拼音，此欄位不一定存在。

* symbol : 此梵字可以直接使用此 symbol 符號來表示，此欄位不一定存在。

### 備註說明：

* 沒有呈現的欄位表示沒有資料。