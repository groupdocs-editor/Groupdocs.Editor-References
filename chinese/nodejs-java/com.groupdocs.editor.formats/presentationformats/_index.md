---
title: "PresentationFormats"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "封装所有演示文稿格式。"
type: docs
weight: 14
url: /zh/nodejs-java/com.groupdocs.editor.formats/presentationformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class PresentationFormats extends DocumentFormatBase
```

封装所有 Presentation 格式。包括以下格式：
[Odp](../../com.groupdocs.editor.formats/presentationformats#Odp),
[Otp](../../com.groupdocs.editor.formats/presentationformats#Otp),
[Pot](../../com.groupdocs.editor.formats/presentationformats#Pot),
[Potm](../../com.groupdocs.editor.formats/presentationformats#Potm),
[Potx](../../com.groupdocs.editor.formats/presentationformats#Potx),
[Pps](../../com.groupdocs.editor.formats/presentationformats#Pps),
[Ppsm](../../com.groupdocs.editor.formats/presentationformats#Ppsm),
[Ppsx](../../com.groupdocs.editor.formats/presentationformats#Ppsx),
[Ppt](../../com.groupdocs.editor.formats/presentationformats#Ppt),
[Ppt95](../../com.groupdocs.editor.formats/presentationformats#Ppt95),
[Pptm](../../com.groupdocs.editor.formats/presentationformats#Pptm),
[Pptx](../../com.groupdocs.editor.formats/presentationformats#Pptx).
了解更多关于 Presentation 格式的信息，请点击 [here](../https://wiki.fileformat.com/presentation)。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Ppt](#Ppt) | Microsoft PowerPoint 97-2003 演示文稿 (PPT)。 |
|
|  | [Ppt95](#Ppt95) | Microsoft PowerPoint 95 演示文稿 (PPT)。 |
|
|  | [Pptx](#Pptx) | Microsoft Office Open XML PresentationML 无宏文档 (PPTX)。 |
|
|  | [Pptm](#Pptm) | Microsoft Office Open XML PresentationML 含宏文档 (PPTM)。 |
|
|  | [Pps](#Pps) | Microsoft PowerPoint 97-2003 幻灯片放映 (PPS)。 |
|
|  | [Ppsx](#Ppsx) | Microsoft Office Open XML PresentationML 无宏幻灯片放映 (PPSX)。 |
|
|  | [Ppsm](#Ppsm) | Microsoft Office Open XML PresentationML 含宏幻灯片放映 (PPSM)。 |
|
|  | [Pot](#Pot) | Microsoft PowerPoint 97-2003 演示文稿模板 (POT)。 |
|
|  | [Potx](#Potx) | Microsoft Office Open XML PresentationML 无宏模板 (POTX)。 |
|
|  | [Potm](#Potm) | Microsoft Office Open XML PresentationML 含宏模板 (POTM)。 |
|
|  | [Odp](#Odp) | OpenDocument 演示文稿 (ODP)。 |
|
|  | [Otp](#Otp) | OpenDocument 演示文稿模板 (OTP)。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAll()](#getAll--) | 获取所有 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) 的可枚举集合。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 检索具有指定文件扩展名的指定类型 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) 实例。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 将表示文件扩展名的字符串转换为 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) 对象。 |
|
### Ppt {#Ppt}
```
public static final PresentationFormats Ppt
```


Microsoft PowerPoint 97-2003 演示文稿 (PPT)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/ppt)
.


### Ppt95 {#Ppt95}
```
public static final PresentationFormats Ppt95
```


Microsoft PowerPoint 95 演示文稿 (PPT)。


### Pptx {#Pptx}
```
public static final PresentationFormats Pptx
```


Microsoft Office Open XML PresentationML 无宏文档 (PPTX)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/pptx)
.


### Pptm {#Pptm}
```
public static final PresentationFormats Pptm
```


Microsoft Office Open XML PresentationML 含宏文档 (PPTM)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/pptm)
.


### Pps {#Pps}
```
public static final PresentationFormats Pps
```


Microsoft PowerPoint 97-2003 幻灯片放映 (PPS)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/pps)
.


### Ppsx {#Ppsx}
```
public static final PresentationFormats Ppsx
```


Microsoft Office Open XML PresentationML 无宏幻灯片放映 (PPSX)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/ppsx)
.


### Ppsm {#Ppsm}
```
public static final PresentationFormats Ppsm
```


Microsoft Office Open XML PresentationML 含宏幻灯片放映 (PPSM)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/ppsm)
.


### Pot {#Pot}
```
public static final PresentationFormats Pot
```


Microsoft PowerPoint 97-2003 演示文稿模板 (POT)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/pot)
.


### Potx {#Potx}
```
public static final PresentationFormats Potx
```


Microsoft Office Open XML PresentationML 无宏模板 (POTX)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/potx)
.


### Potm {#Potm}
```
public static final PresentationFormats Potm
```


Microsoft Office Open XML PresentationML 含宏模板 (POTM)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/potm)
.


### Odp {#Odp}
```
public static final PresentationFormats Odp
```


OpenDocument 演示文稿 (ODP)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/odp)
.


### Otp {#Otp}
```
public static final PresentationFormats Otp
```


OpenDocument 演示文稿模板 (OTP)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/presentation/otp)
.


### getAll() {#getAll--}
```
public static List<PresentationFormats> getAll()
```


获取所有 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) 的可枚举集合。
值：一个 IEnumerable{PresentationFormats}，包含所有 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) 实例。


**Returns:**
java.util.List<com.groupdocs.editor.formats.PresentationFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static PresentationFormats fromExtension(String extension)
```


检索具有指定文件扩展名的指定类型 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 文档格式的文件扩展名。 |
|

**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) - An instance of the specified type [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static PresentationFormats fromString(String extension)
```


将表示文件扩展名的字符串转换为 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 要转换的文件扩展名。如果扩展名包含多个句点，则使用最后一个句点后的部分。 |
|

**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) - A [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) object corresponding to the specified file extension.

