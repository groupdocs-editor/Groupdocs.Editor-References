---
title: "MetaImageBase"
second_title: "GroupDocs.Editor for Java API 参考"
description: "用于 WMF 和 EMF 图像格式的基抽象类"
type: docs
weight: 11
url: /zh/java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object，[com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

用于 WMF 和 EMF 图像格式的基抽象类

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | 公共构造函数，用于准备创建 WMF 或 EMF 实例 |
base64 编码的字符串
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | 公共构造函数，用于准备创建 WMF 或 EMF 实例 |
字节流
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | 确定指定的字节流是否包含有效的 WMF 图像 |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | 确定指定的字符串是否包含有效的 WMF 图像，具体为 |
使用 base64 编码
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | 确定指定的字节流是否包含有效的 EMF 图像 |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | 确定指定的字符串是否包含有效的 EMF 图像，具体为 |
使用 base64 编码
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | 在实现类型时应将当前矢量元图像保存到 |
矢量 SVG 格式到指定的字节流中
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


公共构造函数，用于准备创建 WMF 或 EMF 实例
base64 编码的字符串


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 必填名称 |
|
|  | contentInBase64 | java.lang.String | 内容为 base64 字符串。不能为空或为空。 |
|
|  | isWmf | boolean | WMF 为 true，EMF 为 false |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


公共构造函数，用于准备创建 WMF 或 EMF 实例
字节流


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 必填名称 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。应为有效的。 |
|
|  | isWmf | boolean | WMF 为 true，EMF 为 false |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


确定指定的字节流是否包含有效的 WMF 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 输入字节流。应为有效的。 |
|

**Returns:**
boolean - 如果有效返回 'true'，如果无效返回 'false'

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


确定指定的字符串是否包含有效的 WMF 图像，具体为
使用 base64 编码


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String，假定包含 base64 编码的 WMF 图像 |
|

**Returns:**
boolean - 如果有效返回 'true'，如果无效返回 'false'

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


确定指定的字节流是否包含有效的 EMF 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 输入字节流。应为有效的。 |
|

**Returns:**
boolean - 如果有效返回 'true'，如果无效返回 'false'

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


确定指定的字符串是否包含有效的 EMF 图像，具体为
使用 base64 编码


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String，假定包含 base64 编码的 EMF 图像 |
|

**Returns:**
boolean - 如果有效返回 'true'，如果无效返回 'false'

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


在实现类型时应将当前矢量元图像保存到
矢量 SVG 格式到指定的字节流中


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | 字节流，SVG 版本的此向量元图像将存储在其中。不得为 NULL，并且应支持写入。 |
|

