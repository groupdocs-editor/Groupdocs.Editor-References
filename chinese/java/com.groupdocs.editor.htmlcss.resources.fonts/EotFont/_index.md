---
title: "EotFont"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示 EOT Embedded OpenType 格式中的一种字体"
type: docs
weight: 10
url: /zh/java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

表示一种 EOT（嵌入式 OpenType）格式的字体。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | 从内容创建新的 EotFont 类，内容以 base64 编码表示 |
字符串，并使用指定的名称
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | 从内容创建新的 EotFont 类，内容以字节流表示，并 |
使用指定的名称
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | EOT 标头大小（以字节为单位），用于其验证 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 检查指定的流是否为有效的 EOT 字体 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 检查指定的 base64 编码字符串是否为有效的 EOT 字体 |
|
|  | [getType()](#getType--) | 返回 FontType.Eot |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


从内容创建新的 EotFont 类，内容以 base64 编码表示
字符串，并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | EOT 字体的名称。不能为空、为空或仅包含空白字符。 |
|
|  | contentInBase64 | java.lang.String | 内容为 base64 编码的字符串。不能为空、为空或仅包含空白字符。如果它不是 EOT 内容，将抛出异常。 |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


从内容创建新的 EotFont 类，内容以字节流表示，并
使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | EOT 字体的名称。不能为空、为空或仅包含空白字符。 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，则此流也将被释放。 |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


EOT 标头大小（以字节为单位），用于其验证


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


检查指定的流是否为有效的 EOT 字体


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 字节流，可能包含 EOT 资源 |
|

**Returns:**
布尔值 - 如果指定的流包含有效的 EOT 字体，则为 True；否则为 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


检查指定的 base64 编码字符串是否为有效的 EOT 字体


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 可能的 EOT 字体内容，以 base64 编码字符串的形式 |
|

**Returns:**
布尔值 - 如果指定的字符串包含有效的 EOT 字体，则为 True；否则为 false

### getType() {#getType--}
```
public FontType getType()
```


返回 FontType.Eot


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
