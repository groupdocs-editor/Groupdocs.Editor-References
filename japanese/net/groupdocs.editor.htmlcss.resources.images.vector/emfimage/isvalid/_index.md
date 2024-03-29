---
title: IsValid
second_title: GroupDocs.Editor for .NET API リファレンス
description: 指定されたストリームが有効な EMF かどうかを確認します image
type: docs
weight: 90
url: /ja/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid/
---
## IsValid(Stream) {#isvalid}

指定されたストリームが有効な EMF かどうかを確認します image

```csharp
public static bool IsValid(Stream binaryContent)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| binaryContent | Stream | 入力バイト ストリーム。 NULL にすることはできません。読み取りとシークをサポートする必要があります。 |

### 戻り値

指定されたストリームが有効な EMF イメージを保持する場合は true、そうでない場合は false

### 関連項目

* class [EmfImage](../../emfimage)
* 名前空間 [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../emfimage)
* 組み立て [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

指定された base64 でエンコードされた文字列が有効な EMF かどうかを確認します image

```csharp
public static bool IsValid(string contentInBase64)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| contentInBase64 | String | EMF イメージのコンテンツが base64 エンコーディングで格納される入力文字列。 NULL または空にすることはできません。 |

### 戻り値

指定された文字列が有効な EMF イメージを保持している場合は true、そうでない場合は false

### 関連項目

* class [EmfImage](../../emfimage)
* 名前空間 [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../emfimage)
* 組み立て [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
