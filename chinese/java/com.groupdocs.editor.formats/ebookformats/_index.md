---
title: "EBookFormats"
second_title: "GroupDocs.Editor for Java API 参考"
description: "封装所有电子书格式。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

封装所有电子书格式。包括以下文件类型：
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
了解更多关于 Mobi 格式的信息请点击[here]，以及关于 ePub 格式的信息请点击[here]。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI 是为 MobiPocket Reader 开发的格式的名称。 |
|
|  | [Epub](#Epub) | Electronic Publication（IDPF ePub）格式是一种电子书文件格式，为出版商和消费者提供标准的数字出版格式。 |
|
|  | [Azw3](#Azw3) | AZW3，也称为 Kindle Format 8（KF8），是为 Amazon Kindle 设备开发的 AZW 电子书数字文件格式的改进版。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAll()](#getAll--) | 获取所有 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) 的可枚举集合。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 检索具有指定文件扩展名的指定类型 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) 实例。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 将表示文件扩展名的字符串转换为 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) 对象。 |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI 是为 MobiPocket Reader 开发的格式的名称，也称为 PRC、AZW。
它目前被亚马逊使用，采用略有不同的 DRM 方案，称为 AZW。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Electronic Publication（IDPF ePub）格式是一种电子书文件格式，为出版商和消费者提供标准的数字出版格式。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3，也称为 Kindle Format 8（KF8），是为 Amazon Kindle 设备开发的 AZW 电子书数字文件格式的改进版。
该格式是对旧 AZW 文件的增强。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


获取所有 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) 的可枚举集合。
值：一个包含所有 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) 实例的 IEnumerable{EBookFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


检索具有指定文件扩展名的指定类型 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 文档格式的文件扩展名。 |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


将表示文件扩展名的字符串转换为 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 要转换的文件扩展名。如果扩展名包含多个句点，则使用最后一个句点之后的部分。 |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

