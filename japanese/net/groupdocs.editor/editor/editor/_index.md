---
title: "Editor"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Editorgroupdocs.editor/editor クラスの新しいインスタンスを初期化し、指定された形式に基づく新しい空のドキュメントを作成します。"
type: docs
weight: 10
url: /ja/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

指定された形式に基づいて、新しい空のドキュメントを作成し、[`Editor`](../../editor) クラスの新しいインスタンスを初期化します。

```csharp
public Editor(DocumentFormatBase format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 形式 | DocumentFormatBase | 作成されるドキュメントのファイル形式を表します。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### 例

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // エディタのインスタンスを使用してドキュメントを編集および保存します。
}
```

### 参照

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

指定された入力ドキュメント（ストリームとして）で新しい Editor インスタンスを初期化します。

```csharp
public Editor(Stream document)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ドキュメント内容を含むストリームです。null であってはなりません。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### 例

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // エディタのインスタンスを使用してドキュメントを編集および保存します。
    }
}
```

### 参照

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

指定された入力ドキュメント（ストリームとして）とそのロードオプションで新しいEditorインスタンスを初期化します。

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ドキュメント内容を含むストリームです。null であってはなりません。 |
| loadOptions | ILoadOptions | ドキュメントのロードオプションです。null の場合があります。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | ドキュメントストリームが null の場合にスローされます。 |
| ArgumentException | ドキュメントストリームが無効な場合にスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### 例

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // エディタのインスタンスを使用してドキュメントを編集および保存します。
    }
}
```

### 参照

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

指定された入力ドキュメント（完全なファイルパスとして）とそのロードオプションで新しいEditorインスタンスを初期化します。

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | ファイルへの完全パスです。null、空、または空白文字のみであってはなりません。有効なパスであり、ファイルが存在する必要があります。 |
| loadOptions | ILoadOptions | ドキュメントのロードオプションです。null の場合があります。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | ファイルパスが無効な場合にスローされます。 |
| FileNotFoundException | ファイルが存在しない場合にスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### 例

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // エディタのインスタンスを使用してドキュメントを編集および保存します。
}
```

### 参照

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

指定された入力ドキュメント（完全なファイルパスとして）とEditor設定で新しいEditorインスタンスを初期化します

```csharp
public Editor(string filePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | ファイルへの完全パスです。NULL であってはなりません。有効であり、ファイルが存在する必要があります。 |

### 参照

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
