---
title: "TextResourceBase"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "任何具有文本内容和编码的受支持文本资源的基类。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

任何具有文本内容和编码的受支持文本资源的基类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | 从指定的带编码的文本内容创建新的文本资源 |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | 从指定的字节流和编码创建新的文本资源 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [Disposed](#Disposed) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 返回此文本资源的名称（不含文件扩展名） |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 返回此文本资源的正确文件名，由名称组成 |
以及扩展名
|
|  | [getEncoding()](#getEncoding--) | 返回此文本资源的编码。 |
|
|  | [getByteContent()](#getByteContent--) | 以原始字节流返回此文本资源的内容 |
编码
|
|  | [getTextContent()](#getTextContent--) | 以标准字符串返回此文本资源的内容 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 将此文本资源保存到指定文件 |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | 检查此实例与指定对象的相等性。 |
|
|  | [dispose()](#dispose--) | 释放此文本资源，释放其内容并使大多数 |
方法和属性无法工作。
|
|  | [isDisposed()](#isDisposed--) | 确定此文本资源是否已被释放 |
|
|  | [getType()](#getType--) | 在实现类型时应返回关于文本类型的信息 |
资源
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


从指定的带编码的文本内容创建新的文本资源


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 资源的强制名称，作为其唯一标识符。通常是文件名。 |
|
|  | textualContent | java.lang.String | 资源的文本内容，不能为空或为 NULL |
|
|  | originalEncoding | java.nio.charset.Charset | 资源的原始编码，不能为空或为 NULL |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


从指定的字节流和编码创建新的文本资源


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 资源的强制名称，作为其唯一标识符。通常是文件名。 |
|
|  | 二进制内容 | java.io.InputStream | 资源的二进制内容，以字节流形式。不能为空、已释放，且应可读取和可定位。 |
|
|  | originalEncoding | java.nio.charset.Charset | 资源的原始编码，不能为空或为 NULL |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


返回此文本资源的名称（不含文件扩展名）


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


返回此文本资源的正确文件名，由名称组成
以及扩展名


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


返回此文本资源的编码。通常返回 UTF-8。


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


以原始字节流返回此文本资源的内容
编码


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


以标准字符串返回此文本资源的内容


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


将此文本资源保存到指定文件


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件完整路径 | java.lang.String | 文件的完整路径，如果已存在将被创建或覆盖 |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


检查此实例与指定对象的相等性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | 其他未知类型的 HTML 资源，可能是 TextResourceBase 的继承者 |
|

**Returns:**
boolean - 如果相等返回 true，否则返回 false

### dispose() {#dispose--}
```
public final void dispose()
```


释放此文本资源，释放其内容并使大多数
方法和属性不可用。对多次调用保持容错。


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


确定此文本资源是否已被释放


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


在实现类型时应返回关于文本类型的信息
资源


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
