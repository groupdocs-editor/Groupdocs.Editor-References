---
title: "IHtmlResource"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示未知 HTML 资源（光栅或矢量图像、样式表、字体、文本资源、CSS、XML 等）的一实例"
type: docs
weight: 12
url: /zh/java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

表示未知 HTML 资源（光栅或矢量图像，
样式表、字体、文本资源（CSS、XML）等）

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | HTML 资源的名称 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 指定资源的正确文件名和相应的文件 |
扩展名
|
|  | [getType()](#getType--) | HTML 资源的类型 |
|
|  | [getByteContent()](#getByteContent--) | HTML 资源的内容，以字节流形式 |
|
|  | [getTextContent()](#getTextContent--) | HTML 资源的内容，以 base64 编码的文本字符串形式 |
用于二进制资源或文本资源的简单文本
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 将当前资源保存到指定文件 |
|
### getName() {#getName--}
```
public abstract String getName()
```


HTML 资源的名称


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


指定资源的正确文件名和相应的文件
扩展名


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


HTML 资源的类型


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


HTML 资源的内容，以字节流形式


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


HTML 资源的内容，以 base64 编码的文本字符串形式
用于二进制资源或文本资源的简单文本


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


将当前资源保存到指定文件


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 文件的完整路径，将使用当前资源的内容创建或重写该文件 |
|

