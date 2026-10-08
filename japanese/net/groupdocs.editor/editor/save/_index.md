---
title: "Save"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された編集済みドキュメント（EditableDocumentgroupdocs.editor/editabledocument のインスタンスで表される）を、指定されたフォーマットの結果ドキュメントに変換し、その内容を指定されたストリームに保存します。"
type: docs
weight: 80
url: /ja/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

指定された編集済みドキュメント（'[`EditableDocument`](../../editabledocument)' のインスタンスで表される）を、指定されたフォーマットの結果ドキュメントに変換し、その内容を指定されたストリームに保存します。

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputDocument | EditableDocument | WYSIWYG HTML エディタで編集され、'[`EditableDocument`](../../editabledocument)' クラスのインスタンスとして保存された入力ドキュメントのバージョンで、特定のフォーマットの出力ドキュメントに変換する必要があります。null または破棄されていてはいけません。 |
| outputDocument | Stream | 出力ストリームは、結果ドキュメントの内容が記録されるストリームです。null であってはならず、破棄されてはいけません。書き込みをサポートしている必要があります。 |
| saveOptions | ISaveOptions | ドキュメント保存オプションは、結果ドキュメントの形式を定義し、一般的および形式固有の保存オプションも含みます。null であってはなりません。 |

### 備考

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### 参照

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

指定された編集済みドキュメント（'[`EditableDocument`](../../editabledocument)' のインスタンスで表される）を、指定された形式の結果ドキュメントに変換し、指定されたファイルパスでファイルにその内容を保存します。

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputDocument | EditableDocument | WYSIWYG HTML エディタで編集され、'[`EditableDocument`](../../editabledocument)' クラスのインスタンスとして保存された入力ドキュメントのバージョンで、特定のフォーマットの出力ドキュメントに変換する必要があります。null または破棄されていてはいけません。 |
| filePath | 文字列 | 出力ドキュメントが保存されるファイルへのパスです。同名のファイルが存在する場合、完全に上書きされます。パス文字列は null、空、または空白のみであってはなりません。 |
| saveOptions | ISaveOptions | ドキュメント保存オプションは、結果ドキュメントの形式を定義し、一般的および形式固有の保存オプションも含みます。null であってはなりません。 |

### 備考

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### 参照

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

指定された編集済みドキュメント（'[`EditableDocument`](../../editabledocument)' のインスタンスで表される）を、ファイル名拡張子から決定される形式の結果ドキュメントに変換し、指定されたファイルパスでファイルにその内容を保存します。

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputDocument | EditableDocument | WYSIWYG HTML エディタで編集され、'[`EditableDocument`](../../editabledocument)' クラスのインスタンスとして保存された入力ドキュメントのバージョンで、特定のフォーマットの出力ドキュメントに変換する必要があります。null または破棄されていてはいけません。 |
| filePath | 文字列 | 出力ドキュメントが保存されるファイルへのパスです。同名のファイルが存在する場合、完全に上書きされます。パス文字列は null、空、または空白のみであってはなりません。このファイル名からデフォルトの保存オプションと出力形式が決定されるため、有効な拡張子が必要です。 |

### 参照

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

変更後の元ドキュメント（例: [`FormFieldManager`](../formfieldmanager)）を、指定された形式の結果ドキュメントに変換し、提供されたストリームにその内容を保存します。

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputDocument | Stream | 出力ドキュメントが保存されるストリームです。このストリームは書き込み可能で、ドキュメント内容の開始位置に設定されている必要があります。null であってはなりません。 |
| saveOptions | WordProcessingSaveOptions | 結果ドキュメントの形式を定義し、一般的および形式固有の保存オプションも含むドキュメント保存オプションです。null であってはなりません。 |

### 戻り値

保存されたドキュメント内容を含むストリームです。

### 備考

*outputDocument* または *saveOptions* が null の場合、ArgumentNullException がスローされます。保存するドキュメントが存在しない場合も、ArgumentNullException がスローされます。

*outputDocument* または *saveOptions* が null の場合、または保存するドキュメントが存在しない場合にスローされます。**Learn more:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### 参照

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

現在のドキュメント内容を指定された出力ストリームに保存します。

```csharp
public Stream Save(Stream outputDocument)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputDocument | Stream | ドキュメント内容が保存されるストリームです。null にすることはできません。 |

### 戻り値

保存されたドキュメント内容を含むストリームです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *outputDocument* が null の場合、またはドキュメント内容が存在しない場合にスローされます。 |

### 備考

このメソッドは内部ドキュメント表現から提供された出力ストリームへ内容をコピーします。保存操作後もストリームの元の位置は保持されます。

### 参照

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
