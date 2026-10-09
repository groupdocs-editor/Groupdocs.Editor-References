---
title: "TextLeadingSpacesOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "包含在打开纯文本文件 TXT 时可用的前导空格处理选项"
type: docs
weight: 40
url: /zh/nodejs-java/com.groupdocs.editor.options/textleadingspacesoptions/
---
**Inheritance:**
java.lang.Object
```
public final class TextLeadingSpacesOptions
```

包含在打开纯文本时可用的前导空格处理选项
文本文件 (TXT)

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [ConvertToIndent](#ConvertToIndent) | 将一个或多个连续空格转换为左缩进。 |
|
|  | [Preserve](#Preserve) | 将所有前导空格原样传递到输出的 HTML "as is"，不进行任何修改 |
|
|  | [Trim](#Trim) | 完全修剪（截断）所有前导空格 |
|
### ConvertToIndent {#ConvertToIndent}
```
public static final int ConvertToIndent
```


将一个或多个连续空格转换为左缩进。默认值。


### Preserve {#Preserve}
```
public static final int Preserve
```


将所有前导空格原样传递到输出的 HTML "as is"，不进行任何修改


### Trim {#Trim}
```
public static final int Trim
```


完全修剪（截断）所有前导空格


