---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "字体提取选项控制应从何处提取哪些字体"
type: docs
weight: 18
url: /zh/nodejs-java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

字体提取选项控制应从哪里提取哪些字体
何处

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [NotExtract](#NotExtract) | 既不从文档也不从 |
系统。
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | 提取所有嵌入到输入 Word |
文档中的字体资源，无论它们是自定义的还是系统的。
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | 仅提取那些嵌入的自定义字体资源（不是 |
系统的）
|
|  | [ExtractAll](#ExtractAll) | 尝试提取输入 WordProcessing 中使用的所有字体 |
文档，包括系统字体。
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


既不从文档也不从
系统。默认值。


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


提取所有嵌入到输入 Word
文档中的字体资源，无论它们是自定义的还是系统的。


*** ** * ** ***

Converter 查找并提取所有 100% 的字体资源，这些资源嵌入在输入的 WordProcessing 文档中，但它不确定它们是系统字体还是自定义字体；它根本不触碰 Windows Registry 或系统文件夹。

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


仅提取那些嵌入的自定义字体资源（不是
系统的）


*** ** * ** ***

Converter 查找并提取所有嵌入的字体资源，然后尝试确定这些字体中哪些是系统字体，哪些不是。为实现此目的，converter 通过使用 Windows Registry 和系统文件夹获取所有系统字体的列表，然后将该列表与嵌入字体集合进行比较。结果是，仅返回那些未在系统中找到的嵌入字体子集。

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


尝试提取输入 WordProcessing 中使用的所有字体
文档，包括系统字体。


*** ** * ** ***

Converter 正在分析输入的 WordProcessing 文档并查找其中使用的所有字体。如果这些字体全部嵌入到输入文档中，converter 将提取并返回它们。否则，如果嵌入字体的集合未覆盖文档中使用的所有字体，或为空，converter 将尝试通过使用 Windows Registry 和系统文件夹从系统中提取这些字体资源。

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
