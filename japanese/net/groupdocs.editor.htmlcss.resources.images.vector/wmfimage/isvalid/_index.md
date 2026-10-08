---
title: "IsValid"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定されたストリームが有効な WMF 画像かどうかをチェックします"
type: docs
weight: 90
url: /ja/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid/
---
## IsValid(Stream) {#isvalid}

指定されたストリームが有効な WMF 画像かどうかをチェックします

```csharp
public static bool IsValid(Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| binaryContent | Stream | 入力バイトストリーム。NULL であってはならず、読み取りとシークをサポートする必要があります。 |

### 戻り値

指定されたストリームが有効な WMF 画像を保持している場合は true、そうでない場合は false

### 参照

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

指定された base64 エンコード文字列が有効な WMF 画像かどうかをチェックします

```csharp
public static bool IsValid(string contentInBase64)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| contentInBase64 | 文字列 | 入力文字列。WMF 画像の内容が Base64 エンコードで格納されています。NULL または空文字列であってはなりません。 |

### 戻り値

指定された文字列が有効な WMF 画像を保持している場合は true、そうでない場合は false

### 参照

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
