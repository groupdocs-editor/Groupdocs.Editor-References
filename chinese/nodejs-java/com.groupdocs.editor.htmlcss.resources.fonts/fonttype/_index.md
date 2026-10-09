---
title: "FontType"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示一种可支持的字体类型。"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

表示一种可支持的字体类型。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontType()](#FontType--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | 特殊值，用于标记未定义、未知或不受支持的字体 |
资源
|
|  | [getWoff()](#getWoff--) | 表示一种 WOFF（Web Open Font Format）字体类型 |
|
|  | [getWoff2()](#getWoff2--) | 表示一种 WOFF2（Web Open Font Format version 2）字体类型 |
|
|  | [getTtf()](#getTtf--) | 表示一种 TTF（TrueType Font）字体类型 |
|
|  | [getOtf()](#getOtf--) | 表示一种 OTF（OpenType Font）字体类型 |
|
|  | [getTtc()](#getTtc--) | 表示一种 TrueType Collection（TTC）字体 |
|
|  | [getEot()](#getEot--) | 表示一种 EOT（Embedded OpenType）字体类型 |
|
|  | [getCssName()](#getCssName--) | 返回此字体类型的 CSS 兼容名称，用于在 |
|
|  | [getFormalName()](#getFormalName--) | 返回此字体类型的正式名称 |
|
|  | [getFileExtension()](#getFileExtension--) | 此字体类型的文件扩展名（不含点字符） |
|
|  | [getFontFormat()](#getFontFormat--) | @font-face 格式的字体格式 |
|
|  | [getMimeCode()](#getMimeCode--) | 特定字体类型的 MIME 代码 |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | 返回 FontType 值，它等同于指定的 CSS 兼容 |
字体类型的名称
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | 返回 FontType 值，它等同于文件扩展名， |
从指定的文件名中提取
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | 返回 FontType 值，它等同于指定的 MIME 代码 |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | 返回指定集合中的第一个字体类型，该类型不是 "Undefined" |
值；否则返回 "Undefined" 字体类型（当所有项为
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | 确定此实例是否等于指定的 "FontType" |
实例
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此实例是否等于指定的未转换对象， |
这可能是另一个 "FontType" 实例
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | 检查两个 "FontType" 值是否相等 |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | 检查两个 "FontType" 值是否不相等 |
|
|  | [hashCode()](#hashCode--) | 返回哈希码，该哈希码是此特定值的常数 |
类型
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


特殊值，用于标记未定义、未知或不受支持的字体
资源


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


表示一种 WOFF（Web Open Font Format）字体类型


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


表示一种 WOFF2（Web Open Font Format version 2）字体类型


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


表示一种 TTF（TrueType Font）字体类型


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


表示一种 OTF（OpenType Font）字体类型


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


表示一种 TrueType Collection（TTC）字体


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


表示一种 EOT（Embedded OpenType）字体类型


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


返回此字体类型的 CSS 兼容名称，用于在


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


返回此字体类型的正式名称


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


此字体类型的文件扩展名（不含点字符）


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


@font-face 格式的字体格式


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


特定字体类型的 MIME 代码


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


返回 FontType 值，它等同于指定的 CSS 兼容
字体类型的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 字体类型的 CSS 兼容名称 |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


返回 FontType 值，它等同于文件扩展名，
从指定的文件名中提取


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件名 | java.lang.String | 带扩展名的文件名，可能是完整名称 |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


返回 FontType 值，它等同于指定的 MIME 代码


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | mimeCode | java.lang.String | MIME 代码 |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


返回指定集合中的第一个字体类型，该类型不是 "Undefined"
值；否则返回 "Undefined" 字体类型（当所有项为
"Undefined")


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 一个或多个 FontType 值，不允许为 NULL 或空集合 |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


确定此实例是否等于指定的 "FontType"
实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 要与此检查的其他 FontType 实例 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此实例是否等于指定的未转换对象，
这可能是另一个 "FontType" 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 对象 | java.lang.Object | 其他实例可能是 FontType 结构体，已装箱为 System.Object |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


检查两个 "FontType" 值是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 要检查的第一个 FontType |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 要检查的第二个 FontType |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


检查两个 "FontType" 值是否不相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 要检查的第一个 FontType |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 要检查的第二个 FontType |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回哈希码，该哈希码是此特定值的常数
类型


**Returns:**
int - 4 字节有符号整数，0 表示未定义值

