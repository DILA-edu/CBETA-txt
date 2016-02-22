**CBETA-txt**
=============

**內容(Content)：**

 - 由CBETA_TAFxml repo 內容所轉置的純文字內容，內容包含「一經一檔」與「各卷一檔」等兩種格式
 - This respository contains the plain txt files that are transforming from the XML files in CBETA_TAFxml repo. Two different formats of text files are generated: "whole text of a scripture in one file" and "text of a scripture is splitted by fascicles". 

**內容範圍(Scope)：**

 - Taisho vol.1 - vol.55 + vol.85   
 - Taisho No. T0001-T2184, T2732-T2920

** 注意事項 (Notices): **

 - 因為經文之中，經常含有序跋文字或梵文文字，(序：&lt;div type="xu"&gt;, 跋：&lt;div type="w"&gt;) 這些都不該納入文字分析的範圍，因此在轉換存文字檔時，這些區段會略過。

- There is a possiblilty that the text of a scripture may consist of introduction(序) or postscript(拔), which was composed by other people rather than the original author. (in xml files: 序 is markuped as &lt;div type="xu"&gt;, 跋 is markuped as &lt;div type="w"&gt;). For servering the propose of the text analysis, those parts are exclueded in these text files.  

**資料檔案(Files)：**

 - 資料依經號，分不同子資料夾存放
 - 資料夾內 *_000.txt 為"整經不分卷"之文字檔   
 - 資料夾內 *_nnn.txt 為"該經第nnn卷"之單卷文字檔
 - Each directory represents a scripture in CBETA. 
 - Inside the directory, the filename ends with _000.txt denotes the file that containing the complete text of a scripture.
 - The filename ends with _NNN.txt denotes file consisting of the text of NNN-th fascicle of that scripture. 

**製作團隊(Our Team)**

 - 法鼓文理學院/佛教學系   
 - 佛典數位研究學習平台專案   
 - 專案主持人：洪振洲   
 - 資料整理：董惠珠、李慧萍
