本文档用于实现从xmind的anki的闭环操作。

### 实现步骤：

1. 制作Xmind思维导图（知识全景图）：按章节分sheet，按卡片建立层级。
2. Xmind2Anki转换：根据下面转换步骤，按章节分别转换成Anki卡片。
3. 打标签：按章节打标签。
4. 精简：在Anki只保留需要记忆的知识点卡片。
5. 以上，即全面（知识全景图），又突出重点（Anki），同时节省工作量。



### Xmind2Anki转换步骤：

1. Anki

下载anki-2.0.52.dmg

[Index of /downloads/archive/](https://apps.ankiweb.net/downloads/archive/)



2. xmind

下载

 [/XMind 6/3.5.1/xmind-macosx-3.5.1.201411201906.dmg](http://sourceforge.net/projects/xmind3/files/XMind 6/3.5.1/xmind-macosx-3.5.1.201411201906.dmg/download)

[XMind download | SourceForge.net](https://sourceforge.net/projects/xmind3/)



3.  xmind2anki

[Xmind2Anki download | SourceForge.net](https://sourceforge.net/projects/xmind2anki/)

[brumar/Xmind2Anki: Ankification of xmind files](https://github.com/brumar/Xmind2Anki)

转换方法

[Xmind2Anki-utilisation](http://cognitive-projects.com/Xmind2Anki/en_utilisation.html)



4. Sample



a. xmind

![image-20190611115438797](assets/image-20190611115438797.png)



b. 转换论证分析课程

![image-20190611115358345](assets/image-20190611115358345.png)

c. 用老版anki打开

![image-20190611115544435](assets/image-20190611115544435.png)

d. 将老的anki格式导出成apkg格式



![image-20190611115639637](assets/image-20190611115639637.png)

![image-20190611115659294](assets/image-20190611115659294.png)

e. 新版Anki导入

![image-20190611115800052](assets/image-20190611115800052.png)

f. 即可实现同步

![image-20190611120036510](assets/image-20190611120036510.png)

g. 同步云端和手机端即可

![4451560211543_.pic copy](assets/4451560211543_.pic copy.jpg)

### 参考

- [印象笔记+Anki+Forest+Xmind，打造完美考试闭环_复习](http://www.sohu.com/a/313339245_212759)

- [Chinese - AnkiWeb](https://ankiweb.net/shared/decks/chinese)



### Changelog

- 20190702 V1.2 增加实现步骤
- 20190611 V1.0 初稿