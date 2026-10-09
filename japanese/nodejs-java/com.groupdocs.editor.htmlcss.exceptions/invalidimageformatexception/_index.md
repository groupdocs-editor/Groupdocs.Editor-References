---
title: "InvalidImageFormatException"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "開く、読み込む、保存する、または処理しようとした際に、画像（ラスターまたはベクター）であると推測されるコンテンツを対象にしたが、実際には予期しないタイプの画像、あるいは画像ではない場合にスローされる例外です。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

開く、読み込む、保存する、または処理しようとした際にスローされる例外です。
何らかの方法で、画像（ラスターまたはベクター）であると推測されるコンテンツ、
しかし実際には予期しないタイプの画像、あるいは画像ではありません。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | 指定されたエラーメッセージで InvalidImageFormatException の新しいインスタンスを作成します。 |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | 指定されたエラーメッセージと、この例外の原因となる内部例外への参照で InvalidImageFormatException の新しいインスタンスを作成します。 |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


指定されたエラーメッセージで InvalidImageFormatException の新しいインスタンスを作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | エラーを説明するテキストメッセージで、null または空にすることができます。 |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


指定されたエラーメッセージと、この例外の原因となる内部例外への参照で InvalidImageFormatException の新しいインスタンスを作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | エラーを説明するテキストメッセージで、null または空にすることができます。 |
|
|  | innerException | java.lang.RuntimeException | 現在の例外の原因となる例外、または内部例外が指定されていない場合は null 参照です。 |
|

