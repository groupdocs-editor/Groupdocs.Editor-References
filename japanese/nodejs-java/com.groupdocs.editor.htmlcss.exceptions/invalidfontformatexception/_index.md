---
title: "InvalidFontFormatException"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "開く、読み込む、保存する、または処理しようとした際に、サポートされている既知のフォーマットのフォントであると推測されるコンテンツを対象にしたが、実際にはサポート外または予期しないフォーマットのフォント、あるいはフォントではない場合にスローされる例外です。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

サポートされている（既知の）フォーマットのフォントであると推測されるコンテンツを開く、読み込む、保存する、または何らかの方法で処理しようとしたときにスローされる例外ですが、実際にはサポートされていない、または予期しないフォーマットのフォントであるか、フォント自体でない場合です。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | 指定されたエラーメッセージで新しいインスタンスを作成します。 |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | 指定されたエラーメッセージと、この例外の原因となる内部例外への参照で @see \"InvalidFontFormatException\" の新しいインスタンスを作成します。 |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


指定されたエラーメッセージで新しいインスタンスを作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | エラーを説明するテキストメッセージで、null または空にすることができます。 |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


指定されたエラーメッセージと、この例外の原因となる内部例外への参照で @see \"InvalidFontFormatException\" の新しいインスタンスを作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | エラーを説明するテキストメッセージで、null または空にすることができます。 |
|
|  | innerException | java.lang.RuntimeException | 現在の例外の原因となる例外、または内部例外が指定されていない場合は null 参照です。 |
|

