---
title: "InvalidFormatException"
second_title: "GroupDocs.Editor for Java API 参考"
description: "当用户尝试使用与原始文档格式不兼容的特定格式选项打开文档时抛出的异常。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

当用户尝试打开某个文档时抛出的异常，使用
与原始文档格式不兼容的特定格式选项。


*** ** * ** ***

例如，如果尝试使用 WordProcessing 文档选项打开 Spreadsheet 文档，则会抛出此异常。

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [InvalidFormatException()](#InvalidFormatException--) |  |
| [InvalidFormatException(String message)](#InvalidFormatException-java.lang.String-) |  |
| [InvalidFormatException(String message, RuntimeException inner)](#InvalidFormatException-java.lang.String-java.lang.RuntimeException-) |  |
### InvalidFormatException() {#InvalidFormatException--}
```
public InvalidFormatException()
```


### InvalidFormatException(String message) {#InvalidFormatException-java.lang.String-}
```
public InvalidFormatException(String message)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String |  |
| 内部 | java.lang.RuntimeException |  |

