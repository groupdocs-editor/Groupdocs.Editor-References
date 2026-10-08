---
title: "GetCssContent"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "すべての外部スタイルシートの内容を文字列のリストとして返します。各文字列は 1 つのスタイルシートを表します。ドキュメントに CSS がない場合は空のリストを返します。"
type: docs
weight: 140
url: /ja/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

すべての外部スタイルシートの内容を文字列のリストとして返します。1 つの文字列が 1 つのスタイルシートを表します。ドキュメントに CSS がない場合は空のリストを返します

```csharp
public List<string> GetCssContent()
```

### 戻り値

各文字列が 1 つの CSS ドキュメントの内容を保持する文字列のリストです。

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

すべての外部スタイルシートの内容を文字列のリストとして返します。1 つの文字列が 1 つのスタイルシートを表します。指定されたプレフィックスが各外部リソースへのリンクに適用されます。ドキュメントに CSS がない場合は空のリストを返します

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| externalImagesPrefix | 文字列 | このパラメーターを使用して、結果の CSS 文字列の CSS 宣言に含まれるすべての外部画像へのリンクに付加されるプレフィックスを指定できます。NULL または空の場合、プレフィックスは追加されません。 |
| externalFontsPrefix | 文字列 | このパラメータを使用すると、プレフィックスを指定できます。このプレフィックスは、結果の CSS 文字列内の @font-face ルールにあるすべての外部フォントへのリンクに追加されます。NULL または空の場合、プレフィックスは追加されません。 |

### 戻り値

各文字列が 1 つの CSS ドキュメントの内容を保持する文字列のリストです。

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
