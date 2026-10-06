---
title: "Mp3Audio"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示一种任意格式的音频资源。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

表示一种任意格式的音频资源。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | 从 MP3 内容（以字节流表示）创建新的 Mp3Audio 类，并使用指定的名称 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | 检查指定的流是否为有效的 MP3 内容 |
|
|  | [getName()](#getName--) | 返回此 MP3 内容的名称。 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 返回此 MP3 内容的正确文件名，该文件名由名称和扩展名组成。 |
|
|  | [getType()](#getType--) | 返回一个 AudioFormat.Mp3（也通过协变返回满足 IHtmlResource.getFormat()） |
|
|  | [getByteContent()](#getByteContent--) | 以字节流返回此字体的内容 |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | 以字节流（保持原始位置）返回此 MP3 音频资源的内容 |
|
|  | [getTextContent()](#getTextContent--) | 以 Base64 编码的字符串返回此 MP3 资源的内容。 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 将此 MP3 资源保存到指定文件 |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | 检查此实例与指定的 HTML 资源的引用相等性 |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | 检查此实例与指定的字体资源的引用相等性 |
|
|  | [dispose()](#dispose--) | 释放此 MP3 资源，释放其内容并使大多数方法和属性不可用 |
|
|  | [isDisposed()](#isDisposed--) | 确定此 MP3 内容是否已被释放 |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


从 MP3 内容（以字节流表示）创建新的 Mp3Audio 类，并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | MP3 内容的名称。不能为空、空字符串或仅包含空白字符。 |
|
|  | 二进制内容 | com.aspose.ms.System.IO.Stream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，则此流也将被释放。 |
|
|  | 保持打开 | boolean | 确定在 Mp3Audio 实例被释放时是否释放指定的流 |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


检查指定的流是否为有效的 MP3 内容


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | com.aspose.ms.System.IO.Stream | 字节流，可能包含 MP3 内容 |
|

**Returns:**
布尔值 - 如果指定的流包含有效的 MP3 内容则为 True，否则为 false

### getName() {#getName--}
```
public String getName()
```


返回此 MP3 内容的名称。通常不包含文件扩展名，理论上可能与文件名不同。


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


返回此 MP3 内容的正确文件名，由名称和扩展名组成。理论上可能与名称不同。


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


返回一个 AudioFormat.Mp3（也通过协变返回满足 IHtmlResource.getFormat()）


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


以字节流返回此字体的内容


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


以字节流（保持原始位置）返回此 MP3 音频资源的内容


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


以 base64 编码字符串返回此 MP3 资源的内容。此值在首次调用后会被缓存。


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


将此 MP3 资源保存到指定文件


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 将要创建或重写的文件的完整路径 |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


检查此实例与指定的 HTML 资源的引用相等性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource 接口的其他实现者 |
|

**Returns:**
boolean - 如果相等则为 True，若不相等则为 false

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


检查此实例与指定的字体资源的引用相等性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Mp3Audio 类的其他实例 |
|

**Returns:**
boolean - 如果相等则为 True，若不相等则为 false

### dispose() {#dispose--}
```
public void dispose()
```


释放此 MP3 资源，释放其内容并使大多数方法和属性不可用


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


确定此 MP3 内容是否已被释放


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

