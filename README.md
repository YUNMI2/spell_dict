# pinyin-data 

汉字拼音数据。


## 数据介绍
数据主要来自于[mozillazg/pinyin-data] (https://github.com/mozillazg/pinyin-data/)

拼音数据的格式：

    {hanzi}: {pinyins}  

* `{pinyins}` 中使用逗号分隔多个拼音
* 示例：

       中: zhōng,zhòng  


[Unihan Database][unihan] 数据版本：

* `kHanyuPinyin.txt`: [Unihan Database][unihan] 中 [kHanyuPinyin](http://www.unicode.org/reports/tr38/#kHanyuPinyin) 部分的拼音数据（来源于《漢語大字典》的拼音数据）
* `kXHC1983.txt`: [Unihan Database][unihan] 中 [kXHC1983](http://www.unicode.org/reports/tr38/#kXHC1983) 部分的拼音数据（来源于《现代汉语词典》的拼音数据）
* `kHanyuPinlu.txt`: [Unihan Database][unihan] 中 [kHanyuPinlu](http://www.unicode.org/reports/tr38/#kHanyuPinlu) 部分的拼音数据（来源于《現代漢語頻率詞典》的拼音数据）
* `kMandarin.txt`: [Unihan Database][unihan] 中 [kMandarin](http://www.unicode.org/reports/tr38/#kMandarin) 部分的拼音数据（普通话中最常用的一个读音。zh-CN 为主，如果 zh-CN 中没有则使用 zh-TW 中的拼音）
* `GBK_PUA.txt`: [Private Use Area](https://en.wikipedia.org/wiki/Private_Use_Areas) 中有拼音的汉字，参考 [GB 18030 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/GB_18030#PUA)
* `nonCJKUI.txt`: 不属于 [CJK Unified Ideograph](https://en.wikipedia.org/wiki/CJK_Unified_Ideographs) 但是却有拼音的字符
* `overwrite.txt`: 手工纠正的拼音数据
* `kMandarin_8105.txt`: [《通用规范汉字表》](https://zh.wikipedia.org/wiki/通用规范汉字表)里 8105 个汉字最常用的一个读音 (**可以修改**)
* `one_word_with_spell.txt`: 合并上述文件后的拼音数据
* `zdic.txt`: [汉典网](http://zdic.net) 的拼音数据
* `words_with_spell.txt` : 词语和对应的拼音数据


## 参考资料

* [Unihan Database Lookup](http://www.unicode.org/charts/unihan.html)
* [汉典 zdic.net](http://www.zdic.net/)
* [字海网，叶典网](http://zisea.com/)
* [国学大师_国学网](http://www.guoxuedashi.com/)
* [Unicode、GB2312、GBK和GB18030中的汉字](http://www.fmddlmyy.cn/text24.html)
* [GB 18030 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/GB_18030#PUA)
* [通用规范汉字表 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E9%80%9A%E7%94%A8%E8%A7%84%E8%8C%83%E6%B1%89%E5%AD%97%E8%A1%A8)
* [China’s 通用规范汉字表 (Tōngyòng Guīfàn Hànzìbiǎo)](https://blogs.adobe.com/CCJKType/2014/03/china-8105.html)

[unihan]: http://www.unicode.org/charts/unihan.html
