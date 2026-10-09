---
title: "FormFieldCollection"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "フォームフィールドのコレクションを表します"
type: docs
weight: 15
url: /ja/nodejs-java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

フォームフィールドのコレクションを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | 新しい [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) クラスのインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | コレクションにフォームフィールドを挿入します。 |
|
|  | [get(String name)](#get-java.lang.String-) | 指定された名前のフォームフィールドを取得します。 |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | 指定された名前とタイプのフォームフィールドを取得します。 |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


新しい [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) クラスのインスタンスを初期化します。


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


コレクションを反復処理する列挙子を返します。


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - コレクションを反復処理できる列挙子です。

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


コレクションにフォームフィールドを挿入します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | 挿入するフォームフィールド。 |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


指定された名前のフォームフィールドを取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドの名前。 |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


指定された名前とタイプのフォームフィールドを取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドの名前。 |


T
: フォームフィールドのタイプ。
|
| 型 | java.lang.Class<T> |  |

**Returns:**
T - 指定された名前とタイプのフォームフィールド（見つかった場合）。見つからない場合は、そのタイプのデフォルト値です。

