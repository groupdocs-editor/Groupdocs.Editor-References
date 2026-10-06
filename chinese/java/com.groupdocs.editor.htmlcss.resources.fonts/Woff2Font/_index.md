---
title: "Woff2Font"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示 WOFF2 Web Open Font Format 格式中的一种字体"
type: docs
weight: 16
url: /zh/java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

表示一种 WOFF2（Web Open Font Format）格式的字体。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | 从内容（以 base64 编码表示）创建新的 Woff2Font 类 |
字符串，并使用指定的名称
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | 从内容（以字节流表示）创建新的 Woff2Font 类，并 |
使用指定的名称
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | WOFF2 标头大小（以字节为单位），此项是验证所必需的 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 检查指定的流是否为有效的 WOFF2 字体 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 检查指定的 base64 编码字符串是否为有效的 WOFF2 字体 |
|
|  | [getType()](#getType--) | 返回 FontType.Woff2 |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


从内容（以 base64 编码表示）创建新的 Woff2Font 类
字符串，并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | WOFF2 字体的名称。不能为空、空字符串或仅包含空白字符。 |
|
|  | contentInBase64 | java.lang.String | 内容为 base64 编码字符串。不能为空、空字符串或仅包含空白字符。如果不是 WOFF2 内容，将抛出异常。 |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


从内容（以字节流表示）创建新的 Woff2Font 类，并
使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | WOFF2 字体的名称。不能为空、空字符串或仅包含空白字符。 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，该流也将被释放。 |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF2 标头大小（以字节为单位），此项是验证所必需的


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


检查指定的流是否为有效的 WOFF2 字体


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 字节流，可能包含 WOFF2 资源 |
|

**Returns:**
布尔值 - 如果指定的流包含有效的 WOFF2 字体则为 True，否则为 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


检查指定的 base64 编码字符串是否为有效的 WOFF2 字体


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 可能的 WOFF2 字体内容，以 base64 编码字符串形式呈现 |
|

**Returns:**
布尔值 - 如果指定的字符串包含有效的 WOFF2 字体则为 True，否则为 false

### getType() {#getType--}
```
public FontType getType()
```


返回 FontType.Woff2


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
