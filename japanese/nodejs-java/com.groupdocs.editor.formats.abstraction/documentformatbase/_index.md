---
title: "DocumentFormatBase"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "ドキュメント形式の基本クラスを表し、形式インスタンスに共通の機能を提供します"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

ドキュメント形式の基本クラスを表し、形式インスタンスに共通の機能を提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getMime()](#getMime--) | ドキュメント形式の MIME タイプを取得します |
|
|  | [getExtension()](#getExtension--) | ドキュメント形式のファイル拡張子を取得します |
|
|  | [getFormatFamily()](#getFormatFamily--) | ドキュメント形式が属するフォーマットファミリーを取得します。 |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | 指定された型のインスタンスを取得します |
T
指定された MIME タイプを持ちます。
|
|  | [hashCode()](#hashCode--) | 現在のオブジェクトのハッシュコードを返します。 |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | このインスタンスが指定された [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) インスタンスと等しいかどうかを判断します。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) インスタンスと等しいかどうかを判断します。 |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) インスタンスを暗黙的に文字列に変換します。 |
|
### getMime() {#getMime--}
```
public final String getMime()
```


ドキュメント形式の MIME タイプを取得します


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


ドキュメント形式のファイル拡張子を取得します


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


ドキュメント形式が属するフォーマットファミリーを取得します。


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


指定された型のインスタンスを取得します
T
指定された MIME タイプを持ちます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | ドキュメント形式の MIME タイプです。 |


T
: ドキュメント形式のタイプです。
|

**Returns:**
T - 指定された型 T のインスタンスで、指定された MIME タイプを持ちます。

### hashCode() {#hashCode--}
```
public int hashCode()
```


現在のオブジェクトのハッシュコードを返します。


**Returns:**
int - 現在のオブジェクトのハッシュコードで、ベースオブジェクト、MIME タイプ、ファイル拡張子、フォーマットファミリーのハッシュコードを組み合わせたものです。

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


このインスタンスが指定された [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) インスタンスと等しいかどうかを判断します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | 現在のインスタンスと比較するための [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) インスタンスです。 |
|

**Returns:**
boolean - 指定された [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/iddocumentformat) が現在のインスタンスと等しい場合は true、そうでない場合は false です。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) インスタンスと等しいかどうかを判断します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | 現在のインスタンスと比較するための [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) インスタンスです。 |
|

**Returns:**
boolean - 指定された [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) が現在のインスタンスと等しい場合は true、そうでない場合は false です。

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) インスタンスを暗黙的に文字列に変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | 変換対象の [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) インスタンスです。 |
|

**Returns:**
java.lang.String - [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) インスタンスのファイル拡張子です。

