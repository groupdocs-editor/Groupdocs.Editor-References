---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "当尝试打开、加载、保存或处理某些内容时抛出的异常，该内容原本假定为图像（光栅或矢量），但实际上是意外类型的图像或根本不是图像。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

当尝试打开、加载、保存或处理时抛出的异常
某些内容，原本假定为图像（光栅或矢量），
但实际上是意外类型的图像或根本不是图像。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | 使用指定的错误消息创建 InvalidImageFormatException 的新实例 |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | 使用指定的错误消息和导致此异常的内部异常引用创建 InvalidImageFormatException 的新实例 |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


使用指定的错误消息创建 InvalidImageFormatException 的新实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 描述错误的文本消息，可以为 null 或空 |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


使用指定的错误消息和导致此异常的内部异常引用创建 InvalidImageFormatException 的新实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 描述错误的文本消息，可以为 null 或空 |
|
|  | innerException | java.lang.RuntimeException | 导致当前异常的异常，如果未指定内部异常，则为 null 引用 |
|

