---
title: "FontResourceBase"
second_title: "GroupDocs.Editor for Java API 参考"
description: "任何受支持字体类型的基类，作为 HTML 文档的资源，包含其所有属性"
type: docs
weight: 11
url: /zh/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

任何受支持字体类型的基类，作为 HTML 文档的资源
包含其所有属性

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Disposed](#Disposed) | 事件，当此字体被释放时触发 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 返回此字体资源的名称。 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 返回此字体资源的正确文件名，由名称组成 |
以及扩展名。
|
|  | [getByteContent()](#getByteContent--) | 以字节流返回此字体的内容 |
|
|  | [getTextContent()](#getTextContent--) | 返回此字体的内容，以 base64 编码字符串形式。 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 将此字体保存到指定文件 |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | 检查此实例与指定的 HTML 资源的引用相等性 |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | 检查此实例与指定的字体资源的引用相等性 |
|
|  | [dispose()](#dispose--) | 释放此字体资源，释放其内容并使大多数 |
方法和属性不可用
|
|  | [isDisposed()](#isDisposed--) | 确定此字体是否已被释放 |
|
|  | [getType()](#getType--) | 在实现类型时应返回特定类型的相关信息 |
字体资源作为特定 FontType 类型的实例，
封装所有类型特定的信息
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


事件，当此字体被释放时触发


### getName() {#getName--}
```
public final String getName()
```


返回此字体资源的名称。通常不包含文件名
扩展名，理论上可能与文件名不同。


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


返回此字体资源的正确文件名，由名称组成
以及扩展名。理论上可能与名称不同。


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


以字节流返回此字体的内容


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


返回此字体的内容，以 base64 编码字符串形式。此值是
在首次调用后缓存的。


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


将此字体保存到指定文件


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 将要创建或重写的文件的完整路径 |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


检查此实例与指定的 HTML 资源的引用相等性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource 接口的其他实现者 |
|

**Returns:**
boolean - 如果相等则为 True，若不相等则为 false

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


检查此实例与指定的字体资源的引用相等性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | FontResourceBase 抽象类的其他继承者 |
|

**Returns:**
boolean - 如果相等则为 True，若不相等则为 false

### dispose() {#dispose--}
```
public final void dispose()
```


释放此字体资源，释放其内容并使大多数
方法和属性不可用


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


确定此字体是否已被释放


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


在实现类型时应返回特定类型的相关信息
字体资源作为特定 FontType 类型的实例，
封装所有类型特定的信息


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
