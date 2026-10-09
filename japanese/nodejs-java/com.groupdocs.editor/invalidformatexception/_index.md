---
title: "InvalidFormatException"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "ユーザーが元のドキュメント形式と互換性のないフォーマット固有のオプションでドキュメントを開こうとしたときにスローされる例外です。"
type: docs
weight: 15
url: /ja/nodejs-java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

ユーザーがドキュメントを開こうとしたときにスローされる例外は
元のドキュメント形式と互換性のないフォーマット固有のオプション。


*** ** * ** ***

例えば、Spreadsheet ドキュメントを WordProcessing ドキュメントのオプションで開こうとすると、この例外がスローされます。

<br />


## コンストラクタ

| コンストラクタ | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String |  |
| 内部 | java.lang.RuntimeException |  |

