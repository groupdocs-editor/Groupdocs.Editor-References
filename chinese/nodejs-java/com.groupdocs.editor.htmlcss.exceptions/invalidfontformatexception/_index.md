---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "当尝试打开、加载、保存或处理某些内容时抛出的异常，该内容原本假定为受支持的已知字体格式，但实际上是不受支持或意外格式的字体，或根本不是字体。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

当尝试打开、加载、保存或以其他方式处理某些内容时抛出的异常，该内容原本被认为是受支持（已知）格式的字体，但实际上是不受支持或意外格式的字体，或根本不是字体。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | 使用指定的错误消息创建新实例 |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | 使用指定的错误消息和导致此异常的内部异常引用创建 @see "InvalidFontFormatException" 的新实例 |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


使用指定的错误消息创建新实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 描述错误的文本消息，可以为 null 或空 |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


使用指定的错误消息和导致此异常的内部异常引用创建 @see "InvalidFontFormatException" 的新实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 描述错误的文本消息，可以为 null 或空 |
|
|  | innerException | java.lang.RuntimeException | 导致当前异常的异常，如果未指定内部异常，则为 null 引用 |
|

