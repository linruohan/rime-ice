# 自用 Rime 配置

![demo](./others/demo.jpeg)



## 基本套路

-   简体全拼
    - 鼠须管 Squirrel 0.15.2 
    - 小狼毫 Weasel 0.14.3
-   「[袖珍简化字方案](https://github.com/rime/rime-pinyin-simp)」作为基础
    -   [melt_eng](https://github.com/tumuyan/rime-melt) 英文输入
    -   简繁切换
    -   日期、时间、星期
    -   自整理的 Emoji
    -   [以词定字](https://github.com/BlindingDark/rime-lua-select-character)
    -   [长词优先](https://github.com/tumuyan/rime-melt/blob/master/lua/melt.lua)
    -   [两分输入法](http://cheonhyeong.com/Simplified/download.html)（拼字）
    -   所有标点符号直接上屏，「/」模式改为「v」模式，「/」直接上屏
    -   增加了许多拼音纠错
-   简体字表、词库
    -   [《通用规范汉字表》的 8105 字字表](https://github.com/iDvel/The-Table-of-General-Standard-Chinese-Characters)
    -   [华宇野风系统词库](http://bbs.pinyin.thunisoft.com/forum.php?mod=viewthread&tid=30049)
    -   [清华大学开源词库](https://github.com/thunlp/THUOCL)
    -   [《现代汉语常用词表》](https://gist.github.com/indiejoseph/eae09c673460aa0b56db)
    -   [《现代汉语词典》](https://forum.freemdict.com/t/topic/12102)
    -   [《同义词词林》](https://forum.freemdict.com/t/topic/1211)
    -   [《新华成语大词典》](https://forum.freemdict.com/t/topic/11407)
    -   [腾讯词向量](https://ai.tencent.com/ailab/nlp/zh/download.html)
-   词库更新
    - 已经校对了大量词汇，主要参考[校对网](http://www.jiaodui.com/bbs/)
    - 长期对词库进行更新、修订、调频

<br>

## 使用说明

请先将 `pinyin_simp.dict.yaml` 中的  `- cn_dicts/private` 这行删除，这是我自己的私人词库（联系人之类的），否则鼠须管无法部署，小狼毫只能输入英文。

<br>

## 长期维护词库

主要维护的词库：

- `8105.dict.yaml` 字表。
- `main.dict.yaml` 基础词库。
- `sogou.dict.yaml` 搜狗流行词。
- `ext.dict.yaml` 扩展词库。
- `tencent.dict.yaml` 扩展词库，大词库。

维护内容主要是异形词、错别字的校对，错误注音的修正，缺失的常用词汇的增添，词频的调整。

欢迎在词库方面提 issue，我会及时更新修正。

<br>

---

详细介绍：[我的 Rime 配置 2022](https://dvel.me/posts/my-rime-setting-2022/)
