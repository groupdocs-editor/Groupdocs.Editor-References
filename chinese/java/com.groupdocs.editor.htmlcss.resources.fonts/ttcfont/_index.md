---
title: "TtcFont"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示 TTC TrueType 集合格式中的一种字体"
type: docs
weight: 14
url: /zh/java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

表示一种 TTC（TrueType Collection）格式的字体。


查看更多：https://docs.fileformat.com/font/ttc/

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | 从内容创建新的 TtcFont 类，内容以 base64 编码表示 |
字符串，并使用指定的名称
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | 从内容创建新的 TtcFont 类，内容以字节流表示，并 |
使用指定的名称
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTC 标头大小（字节），此项为其验证所必需 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 检查指定的流是否为有效的 TTC 字体 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 检查指定的 base64 编码字符串是否为有效的 TTC 字体 |
|
|  | [getType()](#getType--) | 返回 FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | TTC 标头版本，可能为 "1" 或 "2" |
|
|  | [getFontsNumber()](#getFontsNumber--) | 此 TTC 中的字体数量 |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | 指示此 TTC 是否具有 DSIG 表。 |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


从内容创建新的 TtcFont 类，内容以 base64 编码表示
字符串，并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | TTC 字体的名称。不能为空、空字符串或仅包含空白字符。 |
|
|  | contentInBase64 | java.lang.String | 内容为 base64 编码字符串。不能为空、空字符串或仅包含空白字符。如果不是 TTC 内容，将抛出异常。 |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


从内容创建新的 TtcFont 类，内容以字节流表示，并
使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | TTC 字体的名称。不能为空、空字符串或仅包含空白字符。 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，则此流也将被释放。 |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTC 标头大小（字节），此项为其验证所必需


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


检查指定的流是否为有效的 TTC 字体


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 字节流，可能包含 TTC 资源 |
|

**Returns:**
布尔值 - 如果指定的流包含有效的 TTC 字体则为 True，否则为 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


检查指定的 base64 编码字符串是否为有效的 TTC 字体


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 可能的 TTC 字体内容，以 base64 编码字符串形式 |
|

**Returns:**
布尔值 - 如果指定的字符串包含有效的 TTC 字体则为 True，否则为 false

### getType() {#getType--}
```
public FontType getType()
```


返回 FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


TTC 标头版本，可能为 "1" 或 "2"


**Returns:**
字节
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


此 TTC 中的字体数量


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


指示此 TTC 是否具有 DSIG 表。DSIG 表可能存在
仅当 TTC 具有 2.0 版标头时。


**Returns:**
boolean
