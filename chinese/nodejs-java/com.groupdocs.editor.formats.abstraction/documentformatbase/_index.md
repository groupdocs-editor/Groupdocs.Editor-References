---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示文档格式的基类，为格式实例提供通用功能。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

表示文档格式的基类，提供格式实例的通用功能。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getMime()](#getMime--) | 获取文档格式的 MIME 类型。 |
|
|  | [getExtension()](#getExtension--) | 获取文档格式的文件扩展名。 |
|
|  | [getFormatFamily()](#getFormatFamily--) | 获取文档格式所属的格式族。 |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | 检索指定类型的实例 |
T
具有指定的 MIME 类型。
|
|  | [hashCode()](#hashCode--) | 返回当前对象的哈希码。 |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | 确定此实例是否等于指定的 [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) 实例。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此实例是否等于指定的 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 实例。 |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | 将 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 实例隐式转换为字符串。 |
|
### getMime() {#getMime--}
```
public final String getMime()
```


获取文档格式的 MIME 类型。


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


获取文档格式的文件扩展名。


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


获取文档格式所属的格式族。


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


检索指定类型的实例
T
具有指定的 MIME 类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | 文档格式的 MIME 类型。 |


T
: 文档格式的类型。
|

**Returns:**
T - 指定类型 T 的实例，具有指定的 MIME 类型。

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回当前对象的哈希码。


**Returns:**
int - 当前对象的哈希码，结合基对象、MIME 类型、文件扩展名和格式族的哈希码。

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


确定此实例是否等于指定的 [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | 用于与当前实例比较的 [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) 实例。 |
|

**Returns:**
boolean -  true  如果指定的 [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) 等于当前实例；否则为  false 。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此实例是否等于指定的 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | obj | java.lang.Object | 用于与当前实例比较的 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 实例。 |
|

**Returns:**
boolean -  true  如果指定的 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 等于当前实例；否则为  false 。

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


将 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 实例隐式转换为字符串。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | 用于转换的 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 实例。 |
|

**Returns:**
java.lang.String - [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 实例的文件扩展名。

