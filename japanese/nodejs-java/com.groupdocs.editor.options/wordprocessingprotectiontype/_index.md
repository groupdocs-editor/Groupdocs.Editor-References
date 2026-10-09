---
title: "WordProcessingProtectionType"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "WordProcessingドキュメントの利用可能なすべての保護タイプを表します。"
type: docs
weight: 47
url: /ja/nodejs-java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

WordProcessingドキュメントの利用可能なすべての保護タイプを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [NoProtection](#NoProtection) | ドキュメントは保護されていません。 |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | ユーザーはドキュメントに改訂マークのみを追加できます。 |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | ユーザーはドキュメント内のコメントのみを変更できます。 |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | ユーザーはドキュメントのフォームフィールドにデータのみ入力できます。 |
|
|  | [ReadOnly](#ReadOnly) | ドキュメントへの変更は許可されていません |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


ドキュメントは保護されていません。デフォルト値です。


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


ユーザーはドキュメントに改訂マークのみを追加できます。


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


ユーザーはドキュメント内のコメントのみを変更できます。


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


ユーザーはドキュメントのフォームフィールドにデータのみ入力できます。


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


ドキュメントへの変更は許可されていません


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
